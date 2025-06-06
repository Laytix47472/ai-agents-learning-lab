# 🤖 AI Agents Learning Lab – Autonomous Intelligence from Scratch

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green?logo=openai)](https://platform.openai.com/)
[![LangChain](https://img.shields.io/badge/LangChain-Agents-purple)](https://www.langchain.com/)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-orange?logo=huggingface)](https://huggingface.co/)
[![Ray RLlib](https://img.shields.io/badge/Ray-RLlib-lightgrey)](https://docs.ray.io/en/latest/rllib/index.html)
[![Ubuntu](https://img.shields.io/badge/Linux-Ubuntu-yellow?logo=ubuntu)](https://ubuntu.com/)
[![Windows](https://img.shields.io/badge/Windows-OS-blue?logo=windows)](https://microsoft.com/)

---

> **PT-BR 🇧🇷**  
> Laboratório técnico e educativo para aprendizado sobre Agentes de IA — supervisionados, por reforço, auto-supervisionados e autônomos — com foco na formulação e perseguição de objetivos, execução de tarefas e raciocínio em múltiplas etapas.

> **EN 🇺🇸**  
> Technical and educational lab for building AI Agents — supervised, reinforcement-based, self-supervised and fully autonomous — focused on goal-setting, task execution and multi-step reasoning.

---

> ⭐ **Curtiu o projeto? Deixe uma estrela para apoiar!**  
> If you find this project useful, please give it a ⭐ star to support the work.

[![Stars](https://img.shields.io/github/stars/Emersoft76/ai-agents-learning-lab?style=social)](https://github.com/Emersoft76/nome-do-repositorio/stargazers)

---

## 📚 Índice · Table of Contents

1. [📁 Estrutura do Repositório · Repo Structure](#-estrutura-do-repositório--repo-structure)
2. [🛠️ Instalação · Environment Setup](#️-instalação--environment-setup)
3. [🧠 Modelos de Aprendizado · Learning Models](#-modelos-de-aprendizado--learning-models)
4. [🤖 Agentes Autônomos · Autonomous Agents](#-agentes-autônomos--autonomous-agents)
5. [📨 Exemplos de Prompts · Prompt Examples](#-exemplos-de-prompts--prompt-examples)
6. [📊 Diagramas e Fluxos · Diagrams & Flows](#-diagramas-e-fluxos--diagrams--flows)
7. [📎 Documentação Auxiliar · Docs](#-documentação-auxiliar--docs)
8. [🌐 Traduções · Translations](#-traduções--translations)
9. [📄 Licença · License](#-licença--license)

---

## 📁 Estrutura do Repositório · Repo Structure

| Caminho                                | Descrição · Description                                                    |
|----------------------------------------|-----------------------------------------------------------------------------|
| [`README.md`](./README.md)             | Principal (bilingue) · Main bilingual documentation                        |
| [`setup/`](./setup/)                   | Setup de ambiente (Linux e Windows) · Environment setup                    |
| [`models/supervised/`](./models/supervised/)           | Aprendizado supervisionado · Supervised Learning                          |
| [`models/reinforcement/`](./models/reinforcement/)     | Aprendizado por reforço · Reinforcement Learning                          |
| [`models/self_supervised/`](./models/self_supervised/) | Aprendizado auto-supervisionado · Self-Supervised Learning                |
| [`agents/planning_agents/`](./agents/planning_agents/) | Agentes de planejamento (BabyAGI, etc) · Planning Agents                  |
| [`agents/langchain_agents/`](./agents/langchain_agents/)| Agentes com LangChain e ferramentas · Tool-using Agents                   |
| [`agents/openai_autonomous/`](./agents/openai_autonomous/) | Agentes com GPTs e APIs OpenAI · Autonomous GPT Agents              |
| [`prompts/`](./prompts/)               | Prompts originais e templates                                              |
| [`diagrams/`](./diagrams/)             | Diagramas e fluxos de decisão                                              |
| [`docs/`](./docs/)                     | Glossário, cheatsheets, links úteis                                       |
| [`translations/`](./translations/)     | Versões completas em Português e Inglês                                    |

---

## 🛠️ Instalação · Environment Setup

- [Linux Setup](./setup/linux.md)
- [Windows Setup](./setup/windows.md)
- [`requirements.txt`](./setup/requirements.txt)

Inclui:
- Python 3.10+
- Transformers
- LangChain
- OpenAI
- Gym, Ray, RLlib
- VS Code extensions

---

## 🧠 Modelos de Aprendizado · Learning Models

| Tipo · Type                   | Caminho                                                   |
|------------------------------|-----------------------------------------------------------|
| Supervisionado · Supervised  | [`models/supervised/`](./models/supervised/)             |
| Por Reforço · Reinforcement  | [`models/reinforcement/`](./models/reinforcement/)       |
| Auto-supervisionado          | [`models/self_supervised/`](./models/self_supervised/)   |

---

## 🤖 Agentes Autônomos · Autonomous Agents

| Agente                         | Caminho                                                        |
|--------------------------------|-----------------------------------------------------------------|
| BabyAGI, AutoGPT               | [`agents/planning_agents/`](./agents/planning_agents/)         |
| LangChain + Tool Use           | [`agents/langchain_agents/`](./agents/langchain_agents/)       |
| GPT Agents (ReAct, OpenAI)     | [`agents/openai_autonomous/`](./agents/openai_autonomous/)     |

---

## 📨 Exemplos de Prompts · Prompt Examples

| Idioma · Language        | Caminho                                           |
|--------------------------|----------------------------------------------------|
| Português                | [`prompts/prompt_examples_pt.md`](./prompts/prompt_examples_pt.md) |
| English                  | [`prompts/prompt_examples_en.md`](./prompts/prompt_examples_en.md) |
| Templates JSON           | [`prompts/prompt_templates.json`](./prompts/prompt_templates.json) |

---

## 📊 Diagramas e Fluxo

### 🔁 Fluxo de Treinamento de Agentes de IA

O diagrama abaixo mostra como os três principais paradigmas de aprendizado alimentam um modelo base, que se torna a fundação para agentes capazes de planejar, agir e interagir com ferramentas, objetivos, memória e ambiente.

![Fluxo de Treinamento de Agentes](./diagrams/agent_training_flow.png)

---

## 📎 Documentação Auxiliar · Docs

| Item                      | Caminho                                  |
|---------------------------|------------------------------------------|
| Glossário PT/EN           | [`docs/glossary_pt_en.md`](./docs/glossary_pt_en.md) |
| Cheatsheets               | [`docs/cheatsheets.md`](./docs/cheatsheets.md)       |
| Links úteis               | [`docs/links.md`](./docs/links.md)                   |

---

## 🌐 Traduções · Translations

- [`README_pt.md`](./translations/README_pt.md)
- [`README_en.md`](./translations/README_en.md)

---

---

## 📄 Licença

Este projeto é distribuído sob a [Licença MIT Bilíngue](./LICENSE), com autoria declarada por **Emerson Maciel** ([@Emersoft76](https://github.com/Emersoft76)), profissional graduado em Gestão de Redes (UNIP – Brasília/DF), e atuante em soluções modernas de Redes, Sistemas, Computação em Nuvem e IA.

This repository is licensed under the [Bilingual MIT License](./LICENSE), authored by **Emerson Maciel**, professional graduated in Network Management (UNIP – Brasília/DF), and active in modern Network, Systems, Cloud Computing and AI solutions.

---
