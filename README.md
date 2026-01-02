---
title: "Práctica final - Visualización de datos - Análisis de telemetría F1"
author: "Alejandro Barea Novillo"
---

## Descripción del proyecto

Este proyecto analiza y compara la telemetría de las vueltas rápidas de  
**Max Verstappen (VER)** y **Fernando Alonso (ALO)** durante la sesión de  
**Clasificación del GP de Mónaco 2023** para analizar en que punto de la vuelta
consiguió ganar Max Verstappen la pole position.

Se utilizan datos oficiales obtenidos mediante la librería **FastF1**, y se
realizan distintas visualizaciones para estudiar:

- Velocidad a lo largo de la vuelta
- Uso del acelerador y freno
- Heatmap de velocidad sobre el trazado
- Delta de tiempo acumulado
- Trayectoria en el circuito

---

## Requisitos previos

- Python **>= 3.12**
- Acceso a internet (para descarga inicial de datos FastF1)
- `uv` instalado  

Instalación de `uv`:
- Abrir terminal (CTRL+ñ en caso de VScode)

`pip install uv`

Para crear el entorno virtual usado ejecutamos el siguiente mandato en terminal:

`uv venv --python 3.12 "nombre_del_entorno"`

Este entorno es el que usaremos como Kernel en el notebook

para ejecutar el entorno escribimos por terminal:

`"nombre_del_entorno"\Scripts\activate`

Una vez hemos ejecutado el entorno instalamos las librerias necesarias con el archivo requirements.txt. En consola:

`uv pip install -r requirements.txt`

Finalmente, podemos abrir el notebook y ejecutar todas las celdas para comprobar los resultados(seleccionando previamente el kernel creado). Es posible que os pida instalar ipykernel
si el aviso no salta, la forma de instalarlo es:

`uv pip install ipykernel`
