<h1 align="center"><img src="https://camo.githubusercontent.com/62da68eb62b1e5f175f7d1f0191dd89a653d7908feb22d37d4a0ab07365d6791/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4d3967624264396e6244724f5475314d71782f67697068792e676966" alt="Canuto_Desarrollo_Web" width="220px" height="220px" align="center" border="2px solid blue">

## Sobre mí

Hola, soy Jhozmer Ramírez! 👋, les presento el desafío 1 (Robot Trading) propuesto por Alura Latam en el BootCamp "Data Science and Machine Learning".

## Habilidades en este proyecto

 Python : Numpy, Pandas, Matplotlib, yfinance, BeautifulSoap

## Título del Proyecto
<h1 align="center" color="#7778c2"><em><b>Robot Trading<b/></em></h1>
<p align="left" color="#7778c2"> Propuesto por <em>Alura Latam y ORACLE</em> "ONE OracleNextEducation"</p> 
<br>
<p align="center"><img src="https://github.com/Alejarp78/Alejarp78/blob/main/Imagenes/Imagen%20Perro%20Pitbull%20con%20las%20patas%20sobre%20el%20teclado%20programando_Canuto-Developer.PNG" alt="Canuto_Desarrollo_Web" max-width="290px" height="270px" align="center"  border="3px solid blue"></p>
<p align="center"><strong>Canuto-Developer</strong></p> 
<p>Copyright ©Octubre 2023 - Jhozmer Ramírez</p>

<p align="left">GitHub:  issues: <img src="https://img.shields.io/github/issues/Alejarp78/Alejarp78.github.io" alt="alejarp78"> 
   forks: <img src="https://img.shields.io/github/forks/Alejarp78/Alejarp78.github.io" alt="alejarp78">    stars: <img src="https://img.shields.io/github/stars/Alejarp78/Alejarp78.github.io" alt="alejarp78">    License: <img src="https://img.shields.io/github/license/Alejarp78/Alejarp78.github.io" alt="alejarp78"></p>

## Índice :bookmark:
* [Sobre mí](#Sobre-mí)
* [Habilidades en este proyecto](#Habilidades-en-este-proyecto)
* [Título del Proyecto](#Título-del-Proyecto)
* [Descripción](#Descripción)
* [Vídeo](#Vídeo)
* [Pre-requisitos](#Pre-requisitos)
* [Construido con](#Construido-con)
* [Colaboradores](#Colaboradores)
* [Versionado](#Versionado)
* [Mejoras](#Mejoras)
* [Autor](#Autor)
* [Gracias por visitar mi repositorio](#Gracias-por-visitar-mi-repositorio)

## Descripción

<span>_Este proyecto contiene un código en Python que lleva por nombre "Robot Trading", que es capaz de tomar decisiones de compra y venta de Bitcoin en tiempo real, lo que implica tomar datos de una de las páginas web más comunes de visualización de seguimiento de precios para criptoactivos.

Para lograr este cometido es necesario entrar a una API que proporcione datos históricos de Bitcoins en formato JSON. Una vez en la página se realiza "Web Scraping" en un site de noticias para obtener el precio actual y algunos indicadores de tendencia del Bitcoin. Con los datos históricos se procede a cargarlos en DataFrame de Pandas para poder manipularlos y analizarlos, de esa manera identificar y eliminar los "outliers", además de tratar cualquier valor "nulo" o "duplicado" en la base. Finalmente con la base limpia, se calcula el precio promedio del Bitcoin.

Después de obtenido el precio promedio del Bitcoin, se compara con el precio actual y la tendencia del BTC que previamente se obtuvo con el Web Scraping. Si el precio actual es mayor/igual que la media y la tendencia es de baja, entonces se debe vender, pero si el precio actual es menor que la media y la tendencia es de alta, entonces se debe comprar.

Se utiliza la librería Matplotlib para crear un gráfico donde se muestra la evolución del precio del Bitcoin durante el periodo seleccionado, y una línea recta que pase sobre el precio medio. Por último, se muestra un mensaje en el gráfico que indique “Vender”, “Comprar” o “Esperar” según sea la decisión del algoritmo.

Finalmente, con el algoritmo de decisión, se automatizó el proceso. Utilizando la librería de Python "time" para ejecutar el algoritmo de decisión cada 5 minutos y actualizar el gráfico.

Este es un proyecto básico pero ambicioso que requiere una cantidad importante de tiempo y esfuerzo, así como una comprensión básica de Python y lo más importante, mucha creatividad. 

Imagen del resultado de las gráficos del Histórico del BTC ($)

![Histórico_datos_BTC_original_tratados_Alta_velocidadAlta](https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/93983f67-06f6-4730-9607-679bec38bc7e)

![Histórico_datos_BTC_tratado_Alta_velocidadAlta](https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/427e6249-ec35-4b55-8973-e3d9f5ad61ab)

Imagen del resultado de las gráficos del BoxPlot los datos tratados del Histórico del BTC ($)

![BoxPlot_Datos_Tratados](https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/458cb9df-2a30-463a-a981-e5b94a586367)

![BoxPlot_Robot_Trading](https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/f80f2162-1e87-4ada-b891-ce295b089816)

![Histórico_datos_BTC_tratado_Comprar_Tendencia](https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/e4648d69-5755-4b28-8956-2d63a5af5d7d)

Imagen del DataFrame de los datos tratados:

![DataFrame corregido](https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/ccef2f66-ea97-4140-a6c1-fe8e49e0c2cc)

Se dejan en este repositorio imagenes del DataFrame corregido y de cada una de las gráficas obtenidas.

</span>

## Vídeo

<p>Robot Trading MP4</p>
https://github.com/Alejarp78/Robot_Trading_Basico/blob/main/Robot_Trading_v1.mp4

## Pre-requisitos

- Python 3.0 o superior
- Datos en este cuaderno (Notebook Colab Jupyter)

## Construido con

* Numpy
* Pandas
* Matplotlib
* yfinance
* BeautifulSoap
* lxml
* Boxplot

## Colaboradores

[Alejarp78](https://https://github.com/Alejarp78)

## Versionado

Versión Final 1.0

## Mejoras

El Robot Trading posee indicadores de precio promedio y mediana, con Boxplot se pueden identificar los cuartiles, apoyados con colores, de la misma manera que las gráficas "Plot" están diferenciadas con varios colores para los valores: original (tal como se encuantra en la página de criptoactivos), con datos tratados o limpios (corrección de la gráfica eliminando valores nulos y duplicados). Posee una línea de tendencia, que permite observar su inclinación en función a la horizontal, para entender la velocidad de inversión según el volúmen.

## Insignias

<h1 align="center"><img src="https://github.com/Alejarp78/Robot_Trading_Basico/assets/88687677/413ddef4-a7b3-44c6-946f-25a6961ebb5a" alt="Canuto_Desarrollo_Web" width="220px" height="220px" align="center" border="2px solid blue">

## Autor
- | [Jhozmer Ramírez (@Alejarp78)] |
- [<img src="https://avatars.githubusercontent.com/u/88687677?s=400&u=c3e15a75772d3ffed5d55c17123fae2e51ce81a4&v=4" width=115><br><sub>Jhozmer Ramírez</sub>](https://github.com/Alejarp78) |
  
## Gracias por visitar mi repositorio

* Comenta a otros sobre este proyecto 📢
* Deja tu opinión abajo 🤓.
* Si te gusta sigue mi cuenta. 📌

---
<span> Copyright © 2023 [Alejarp78](https://https://github.com/Alejarp78) </span>
<p>Página generada el 24 de octubre del 2023 por Jhozmer A. Ramírez P. Versión 1.0, Mérida-Venezuela.</p>
 

