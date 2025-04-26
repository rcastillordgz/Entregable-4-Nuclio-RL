# 🧊 FrozenLake — Reinforcement Learning

## Descripción

Este proyecto resuelve el problema **FrozenLake** de OpenAI Gym utilizando técnicas de **Reinforcement Learning**, concretamente el algoritmo **Q-Learning**.

El entorno consiste en una cuadrícula 4x4 donde un agente debe aprender a llegar desde el punto de inicio (`S`) hasta la meta (`G`), evitando caer en agujeros (`H`).

## Objetivos

- Moverse aleatoriamente para entender el entorno.
- Entrenar un agente usando **Q-Learning**.
- Ajustar hiperparámetros para mejorar el desempeño del agente.
- Evaluar y comparar resultados antes y después de la mejora.

## Tecnologías usadas

- Python 3
- OpenAI Gym
- NumPy

## Estructura del proyecto

- **Primer intento:** Entrenamiento y evaluación inicial del agente.
- **Análisis:** Diagnóstico de problemas y propuesta de mejoras.
- **Segundo intento:** Reentrenamiento con mejores hiperparámetros y evaluación final.

## Resultados

Tras los ajustes, el agente alcanza el objetivo en **el 100% de los episodios de prueba**.

---

## 🚀 Instrucciones rápidas

1. Clonar el repositorio.
2. Ejecutar el notebook en Google Colab o localmente.
3. Instalar dependencias si es necesario:

```bash
pip install gym numpy
