# 📑 Cheatsheet – Ferramentas e Bibliotecas

## 🔗 Bibliotecas

| Biblioteca      | Função                                   |
|-----------------|-------------------------------------------|
| `langchain`     | Criação de agentes e cadeias de prompts   |
| `openai`        | Acesso à API da OpenAI                    |
| `transformers`  | Modelos de linguagem prontos              |
| `gym`           | Simulações e ambientes de reforço         |
| `rllib`         | Treinamento escalável de RL               |

---

## 🛠️ Comandos úteis

### Criação de venv

```bash
python -m venv venv
source venv/bin/activate  # Linux
.\venv\Scripts\activate   # Windows
```

Instalação com requirements.txt
```bash
pip install -r setup/requirements.txt
```

Execução de agente
```bash
python agents/langchain_agents/tool_agent_math_search.py
```

---

