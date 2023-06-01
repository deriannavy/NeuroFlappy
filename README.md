# Neuro flappy bird game
[![finalizada](https://img.shields.io/badge/Finalizada-greendark?style=flat)](https://github.com/deriannavy)

Repositorio con scripts necesarios para recrear el juego flappy, implementando parámetros aleatoriamente del tipo NEAT.

## Funciones

- Crea generaciones dependiendo los parámetros del último flappy en colisionar.
- Ajusta con aletoriedad algunos parámetros para propiciar mutaciones.
- Después de ciertas generaciones aprende a llevar los obstáculos.
- No requiere de tantas generaciones para llegar el objetivo.


## Tecnologías & Arquitectura

Juego desarrollado en pygame con entidades que aprenden a evitar los obstáculos.

- Bash
- Python

## Instalación

NeuroFlapy requires python2.7 o python3 para correr, de preferencia en un entorno virtual.

```bash
pip install -r requeriments.txt
```

Una vez instaladas las liberías necesarias para ejecutar la versión básica:

```bash
python main.py 
```

Para ejercutar la versión avanzada donde aprende más rápido:
```bash
python main_better.py
```


## Pantallas

<p align="center">
  <a href="https://github.com/deriannavy">
    <img width="300" src="https://raw.githubusercontent.com/deriannavy/images/main/flappy/1.png" />
  </a>
  <a href="https://github.com/deriannavy">
    <img width="300" src="https://raw.githubusercontent.com/deriannavy/images/main/flappy/2.png" />
  </a>
  <a href="https://github.com/deriannavy">
    <img width="300" src="https://raw.githubusercontent.com/deriannavy/images/main/flappy/3.png" />
  </a>
</p>
