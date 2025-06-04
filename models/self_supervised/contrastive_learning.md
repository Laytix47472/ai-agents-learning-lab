# 🔍 Aprendizado Auto-supervisionado – Contrastive Learning

Este paradigma não exige rótulos humanos: os dados “ensinam a si mesmos” por meio de tarefas pretextuais. É usado no pré-treinamento de LLMs e embeddings de texto/imagem.

---

## 🧠 Exemplo: BERT Masked Language Modeling (MLM)

- Frase original: "A inteligência artificial está avançando rápido"
- Frase com máscara: "A inteligência artificial está [MASK] rápido"
- O modelo tenta prever "avançando"

---

## 📌 Outro exemplo: Contrastive Learning (Siamese Networks)

- Dados pareados positivos (ex: mesma pergunta com sinônimos)
- Dados pareados negativos (ex: perguntas sem relação)

---

## 🔧 Ferramentas

| Framework       | Descrição                            |
|------------------|--------------------------------------|
| HuggingFace Transformers | Pré-treinamento de LLMs             |
| SimCSE            | Contrastive Learning para embeddings |
| DINOv2 (Meta AI)  | Aprendizado auto-supervisionado visual  |

---

## 🧪 Exemplo com `transformers`

```python
from transformers import BertTokenizer, BertForMaskedLM
import torch

tokenizer = BertTokenizer.from_pretrained("bert-base-uncased")
model = BertForMaskedLM.from_pretrained("bert-base-uncased")

inputs = tokenizer("The sky is [MASK].", return_tensors="pt")
with torch.no_grad():
    outputs = model(**inputs).logits
```
---

## 📁 Aplicação

Auto-supervisão é base fundamental para agentes LLM, pois permite escalar treinamento sem custo de anotação.

---
