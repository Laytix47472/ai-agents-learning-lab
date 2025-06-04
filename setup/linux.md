# 🐧 Setup do Ambiente – Linux (Ubuntu/Debian)

Este guia configura um ambiente Linux para o desenvolvimento de agentes de IA utilizando Python, OpenAI, LangChain, Transformers, RLlib e outros.

---

## 📦 Requisitos

- Python 3.10+
- Git
- pip
- virtualenv (opcional)
- GPU (opcional, mas recomendado para modelos pesados)

---

## 🛠️ Passo a passo

### 1. Atualizar o sistema
```bash
sudo apt update && sudo apt upgrade -y
```
---

### 2. Instalar Python 3.10 e pip
```bash
sudo apt install python3.10 python3.10-venv python3-pip -y
```
---

### 3. Criar e ativar ambiente virtual (opcional)
```bash
python3.10 -m venv venv
source venv/bin/activate
```

### 4. Clonar o repositório
```bash
git clone https://github.com/Emersoft76/ai-agents-learning-lab.git
cd ai-agents-learning-lab
```
---

### 5. Instalar dependências
```bash
pip install -r setup/requirements.txt
```
---

## ✅ Ambiente Linux pronto - OK!
Execute notebooks, scripts de agentes e treinar modelos localmente.
  
---
