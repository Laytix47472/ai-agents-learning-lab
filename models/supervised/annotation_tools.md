# 🧠 Aprendizado Supervisionado – Anotação de Dados e Treinamento

O aprendizado supervisionado é baseado em **dados rotulados por humanos**, como pares entrada/saída. É usado amplamente em agentes classificadores, NERs, detecção de sentimentos, entre outros.

---

## 📌 Exemplo de tarefa: Classificação de Intenção de Usuário

| Entrada                       | Rótulo (Intenção)  |
|------------------------------|--------------------|
| "Quero reservar um voo"      | reservar_voo       |
| "Qual o clima em Lisboa?"    | buscar_clima       |
| "Toque uma música animada"   | tocar_musica       |

---

## 🔧 Ferramentas de Anotação

| Ferramenta       | Link                                     |
|------------------|------------------------------------------|
| Label Studio     | https://labelstud.io/                    |
| Prodigy (pago)   | https://prodi.gy                         |
| Doccano          | https://github.com/doccano/doccano       |

---

## ⚙️ Pipeline típico (com scikit-learn)

```python
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LogisticRegression

X = ["quero reservar um voo", "qual o clima em lisboa"]
y = ["reservar_voo", "buscar_clima"]

vec = TfidfVectorizer()
X_vec = vec.fit_transform(X)

model = LogisticRegression()
model.fit(X_vec, y)
```
---

## 📁 Dataset de exemplo
```txt
data/supervised/intent_dataset.csv
```
Inclua exemplos rotulados para treinar o modelo de classificação.

---

## 🧪 Uso em Agente

Modelos supervisionados podem ser usados como subcomponentes de decisão em agentes maiores.

---
