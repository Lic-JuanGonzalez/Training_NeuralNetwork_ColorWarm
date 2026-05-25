# Red Neuronal ColorWarm

Red neuronal desde cero que clasifica dos grupos de puntos (círculos concéntricos) y visualiza la frontera de decisión en tiempo real.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Ejecutar

```bash
venv/bin/python3 red_neuronal_colorwarm.py
```

Se abre una ventana gráfica que muestra la frontera de decisión y la curva de loss actualizándose durante el entrenamiento (5000 épocas).
