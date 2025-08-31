# 🌌 Origin Space – Simulador Astrobiológico (Unity + Python)

Este repositorio contiene el desarrollo de un **MVP de simulación virtual astrobiológica** en **Unity**, con un prototipo de ROVer controlado mediante **inputs físicos** y un puente de integración con **Python POO**.

---

## 🚀 Objetivos del proyecto
- Simular entornos 3D realistas de Marte basados en investigaciones de astrobiología.
- Implementar un prototipo de ROVer que se mueva con física básica.
- Integrar Unity (C#) con Python (POO) mediante sockets o middleware.
- Documentar avances y compartir resultados con fines académicos y divulgativos.

---

## 📂 Estructura del repositorio

origin-space-astro-simulator/

│── /unity_project/ # Proyecto principal de Unity

│── /python_bridge/ # Scripts Python OOP para control y comunicación

│── /docs/ # Documentación y manuales

│── /assets/ # Modelos 3D, texturas, referencias

│── README.md # Descripción general

│── .gitignore # Archivos ignorados

***

## 🔧 Instalación y uso

1. **Clonar repositorio**
   ```bash
   git clone https://github.com/origin-space/origin-space-astro-simulator.git
   cd origin-space-astro-simulator
   
Configurar Unity:
> Versión recomendada: Unity 2022.3 LTS

> Abrir carpeta /unity_project/ desde Unity Hub.

> Configurar Python

> Version recomenda: Python 3.10+

> Instalar dependencias:

> pip install -r requirements.txt

***
Flujo de trabajo en GitHub
> main: versión estable.

> dev-unity: desarrollo del entorno y físicas.

> dev-python: integración de scripts en Python.

> feature-*: ramas para nuevas características.
