# 🎯 Agentes com GPT + ReAct – Objetivo e Execução

> Agente que pensa, age e observa, com base no modelo ReAct: **"Reasoning + Acting"**.

---

## 📚 O que é ReAct?

ReAct é uma estratégia onde o agente:

1. **Raciocina** sobre o problema
2. **Executa** uma ação (ex: usar API, ferramenta)
3. **Observa** o resultado
4. Recomeça

---

## 🔁 Ciclo

```text
Pergunta → Pensamento → Ação → Observação → Pensamento → Resposta
```
---

## 🧪 Exemplo com LangChain ReAct
```python
agent.run("Quantos anos tinha Einstein quando publicou a teoria da relatividade?")
```
O agente:

- Busca quando nasceu Einstein
- Calcula a diferença até 1905
- Retorna a resposta com raciocínio completo

---

## 📁 Exemplo real
```txt
agents/openai_autonomous/react_agent_reasoning.py
```

---

## 📌 Uso prático

- Agentes que respondem com transparência do raciocínio
- Ferramentas de resolução de tarefas complexas
- Análise + execução combinada

---
---
