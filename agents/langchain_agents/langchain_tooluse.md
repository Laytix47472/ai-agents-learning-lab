# 🧰 LangChain Agents com Tools – Raciocínio e Execução

> Agentes que utilizam LLMs como cérebro e ferramentas externas como braços. Raciocinam passo a passo, chamam funções, APIs, calculadoras, e retornam resultados.

---

## 🧠 Descrição

LangChain permite criar agentes que:

- Recebem perguntas complexas
- Decidem quais ferramentas usar
- Executam chamadas passo a passo
- Raciocinam em cadeia

---

## 🧪 Exemplo

```python
from langchain.agents import load_tools, initialize_agent
from langchain.llms import OpenAI

llm = OpenAI(temperature=0)
tools = load_tools(["serpapi", "llm-math"], llm=llm)

agent = initialize_agent(tools, llm, agent="zero-shot-react-description", verbose=True)
agent.run("Qual a raiz quadrada de 289 dividida pela idade de Obama?")
```
Resultado: o agente usa llm-math e serpapi para resolver.

---

## ⚙️ Ferramentas úteis

- Calculadora (llm-math)
- API Web Search (SerpAPI)
- Weather API
- Zapier
- Banco de dados

---

## 📁 Exemplo real
```txt
agents/langchain_agents/tool_agent_math_search.py
```
---

## 📌 Uso prático

- Agentes de atendimento
- Assistentes com raciocínio simbólico + recuperação de informações

---

