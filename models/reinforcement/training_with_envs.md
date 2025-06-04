# 🔁 Aprendizado por Reforço – Treinamento com Ambientes (OpenAI Gym)

Agentes por reforço aprendem com tentativa e erro, recebendo **recompensas** com base no desempenho em um ambiente simulado.

---

## 🔧 Frameworks usados

| Framework | Função                              |
|-----------|-------------------------------------|
| Gym       | Ambientes de simulação padrão       |
| Ray RLlib | Treinamento distribuído de RL       |
| PettingZoo | Multiagentes para RL               |

---

## 🧪 Exemplo: CartPole com Gym + RLlib

```python
import gym
from ray.rllib.algorithms.ppo import PPO

env = gym.make("CartPole-v1")
algo = PPO(env="CartPole-v1")
results = algo.train()
```
---

## 🎯 Recompensas

O agente aprende através de feedback (positivo ou negativo), por exemplo:

- +1 se mantém o poste em pé
- -1 se ele cai
---

## 📁 Código
```txt
models/reinforcement/cartpole_ppo.py
```
---

## 🤖 Uso em Agentes

Agentes treinados por reforço são usados em:

- Decisão tática e estratégica
- Navegação autônoma
- Aprendizado por reforço com feedback humano (RLHF)

---
