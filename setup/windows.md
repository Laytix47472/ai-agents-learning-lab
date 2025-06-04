# 🪟 Setup do Ambiente – Windows

Este guia configura um ambiente de desenvolvimento para agentes de IA no Windows com Python 3.10+, via terminal PowerShell ou Git Bash.

---

## 📦 Requisitos

- [Python 3.10+](https://www.python.org/downloads/windows/)
- [Git for Windows](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- (opcional) [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) para uso com GPU

---

## 🛠️ Passo a passo

### 1. Verifique o Python
```powershell
python --version
pip --version
```
Caso não tenha, instale do site oficial com a opção “Add Python to PATH” marcada.

---

### 2. Clonar o repositório
```powershell
git clone https://github.com/seu-usuario/ai-agents-learning-lab.git
cd ai-agents-learning-lab
```
---

### 3. Criar ambiente virtual
```powershell
python -m venv venv
.\venv\Scripts\activate
```
---

### 4. Instalar as dependências
```powershell
pip install -r setup/requirements.txt
```
---

✅ Ambiente Windows pronto - OK!
Rode notebooks, LangChain, agentes autônomos e experimentos com GPTs localmente.

---
