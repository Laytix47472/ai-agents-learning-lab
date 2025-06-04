# 🤖 BabyAGI – Planejamento e Execução Baseado em Objetivos

> Um agente que usa LLMs para gerar, priorizar, executar e replanejar tarefas, com base em um objetivo final.

---

## 🎯 Descrição

BabyAGI é um agente iterativo. Ele:

1. Recebe um objetivo
2. Gera tarefas relevantes
3. Executa uma tarefa por vez (usando LLMs)
4. Reavalia o progresso
5. Gera novas tarefas se necessário

---

## ⚙️ Stack usada

| Tecnologia  | Uso                                      |
|-------------|-------------------------------------------|
| LangChain   | Cadeia de prompts, ferramentas e memória  |
| OpenAI GPT  | Processamento de tarefas                  |
| ChromaDB    | Memória vetorial (opcional)              |

---

## 🧪 Exemplo de uso

```bash
Objective: "Planejar uma viagem para Tóquio com orçamento limitado"

- Gerar lista de tarefas
- Buscar passagens
- Buscar hospedagem
- Otimizar roteiro
- Verificar clima
```
Cada passo é executado por um LLM via ferramenta (tool), e o progresso é monitorado.

---

## 📁 Exemplo real
```txt
agents/planning_agents/babyagi_langchain.py
```
---

## 📌 Uso prático

BabyAGI é útil para:

- Agentes autônomos com múltiplos passos
- Delegação de tarefas
- Planejamento em ambiente desconhecido

---
