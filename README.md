# 📊 Análisis de Rendimiento de Tiendas

Este proyecto analiza el rendimiento de **cuatro tiendas** del Sr. Juan utilizando **Python**, **Pandas** y **Matplotlib** en Google Colab.  
El objetivo es determinar qué tienda presenta el menor desempeño general para considerar su venta.

---

## 🚀 Características del proyecto
- Cálculo de **ingresos totales** por tienda.
- Análisis de **categorías de productos** más y menos vendidas.
- Evaluación de **calificaciones promedio de clientes**.
- Identificación de **productos más y menos vendidos**.
- Cálculo del **costo de envío promedio**.
- Generación de **gráficos visuales** para facilitar la interpretación de datos.
- Informe final con **recomendación** de la tienda a vender.

---

## 📂 Estructura del repositorio
├── ChallengeAluraStore.ipynb
└── README.md


---

## 📦 Requisitos y dependencias

El proyecto se ejecuta en **Google Colab**, por lo que no requiere instalación local.  
Si quieres ejecutarlo localmente, necesitarás instalar las siguientes librerías:

```bash
pip install pandas matplotlib

## 🔗 Conexión con los datos

Los datos se obtienen directamente desde un repositorio en GitHub mediante enlaces CSV:

import pandas as pd

url = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv"
url2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv"
url3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv"
url4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"
