# <h1 align=center> **Análisis del Mercado de Criptomonedas** </h1>
                                            

<p align="center">
<img src="image/cripto.jpg"  height=500>
</p>


### **Contexto**

En los últimos años, las criptomonedas han experimentado un crecimiento exponencial y adopción global. Desde el inicio del Bitcoin en 2009, se ha creado una variedad de criptomonedas con diferentes tecnologías y usos.

A medida que el interés en las criptomonedas aumenta, inversores y entusiastas buscan entender su comportamiento. Sin embargo, su volatilidad y complejidad presentan desafíos para tomar decisiones informadas.


### **Rol a desarrollar**

El análisis de datos es esencial para obtener información valiosa en este campo. Datos actualizados sobre criptomonedas, como precios, volúmenes y datos históricos, son fundamentales para comprender estos mercados emergentes.

En mi rol como Analista de Datos en una empresa de servicios financieros, he sido encargado de realizar un análisis exhaustivo del mercado de criptomonedas utilizando datos de la **API CoinGecko**. El objetivo de este análisis es comprender mejor el mercado de criptomonedas y presentar hallazgos y recomendaciones en un informe detallado.

Dada la gran cantidad de monedas disponibles en la fuente de información proporcionada (aproximadamente 4000), he decidido acotar mi trabajo a analizar al menos 10 criptomonedas. Mi elección se basó en una combinación de factores como capitalización de mercado, crecimiento reciente y casos innovadores de tecnología o uso.


### **Investigacion**

Las criptomonedas son un tipo de moneda digital que opera de manera descentralizada, lo que significa que no está controlada por ninguna entidad gubernamental o financiera central. Utilizan la criptografía, que es la ciencia de la codificación y decodificación de información, para asegurar las transacciones y garantizar la integridad de la red.

La tecnología subyacente que hace posible el funcionamiento de las criptomonedas se llama blockchain. Un blockchain es esencialmente un registro digital público, inmutable y seguro de todas las transacciones que se realizan con una criptomoneda en particular. Cada transacción se agrega en forma de "bloque" a una cadena continua de bloques anteriores, lo que crea una trazabilidad completa y transparente de todas las transacciones pasadas. Esto garantiza la seguridad y la autenticidad de las transacciones, ya que cualquier intento de alterar un bloque anterior sería evidente y requeriría la modificación de todos los bloques siguientes, lo que resulta prácticamente imposible debido a la naturaleza de la criptografía utilizada.

Una de las características más atractivas de las criptomonedas es su capacidad para permitir transacciones directas y seguras entre dos partes sin intermediarios, como bancos u otras instituciones financieras. Esto reduce los costos y los tiempos de procesamiento, lo que ha impulsado su adopción en diferentes industrias y casos de uso, como las finanzas descentralizadas (DeFi), la tokenización de activos, la gestión de identidad y más.

El auge de las criptomonedas se debe en gran medida a su potencial para revolucionar los sistemas financieros tradicionales, ofrecer mayor inclusión financiera a nivel mundial y brindar nuevas oportunidades para la innovación tecnológica. Sin embargo, también es importante tener en cuenta que el mercado de criptomonedas es altamente volátil y presenta riesgos, por lo que se debe llevar a cabo una investigación cuidadosa antes de invertir o participar en actividades relacionadas con criptomonedas.


### **Eleccion de Criptomonedas**

El criterio empleado para la selección de criptomonedas se centra principalmente en la capitalización de mercado. Esta metodología implica la elección de aquellas criptomonedas que poseen el valor global más alto en el mercado en un instante específico. El cálculo de la capitalización de mercado se realiza al multiplicar el precio de una criptomoneda por la cantidad total en circulación de la misma. Esta elección se fundamenta en la percepción de que estas monedas digitales son las más sólidamente establecidas y ampliamente adoptadas en el mercado, lo que puede incrementar su liquidez y reducir en cierta medida los riesgos asociados con las inversiones en el ámbito de las criptomonedas. **La selección de las 10 criptomonedas se basa en un enfoque totalmente interactivo, lo que implica que mostrará aquellas que ostenten la mayor capitalización en el momento de la actualización del informe.**


### **Kpis**

Los Kpis utilizados son:
- Análisis de Medias Móviles y Cruces: Seguimiento de tendencias mediante medias móviles y señales de cambio cuando estas medias se cruzan.
- Índice de Fuerza Relativa (RSI): Evalúa si una criptomoneda está sobrecomprada (RSI alto) o sobrevendida (RSI bajo), señalando posibles cambios de dirección.
- Volumen: Cantidad de criptomonedas negociadas en un período, indicador de fuerza de tendencia y posible confirmación de movimientos.

Se explican detalladamente en el [EDA](EDA.ipynb)


### **Analisis exploratorio de datos (EDA)**

He extraeido y normalizado la información de la API utilizando un script en Python. Mediante el uso de la biblioteca "Requests", he realizado solicitudes para obtener los datos necesarios. Luego, he aplicado un proceso de normalización para asegurar que los datos estén en un formato coherente y listos para el análisis.

Posteriormente, he llevado a cabo un análisis exploratorio de los datos utilizando la biblioteca "Matplotlib". Esta herramienta me ha permitido crear visualizaciones gráficas que representan de manera efectiva las tendencias y patrones presentes en el mercado de criptomonedas. Estas visualizaciones son esenciales para comprender mejor cómo se comportan las diferentes criptomonedas a lo largo del tiempo.Realizando una conclusión al finalizar el [EDA](EDA.ipynb).


### **Informe**

La herramienta que empleé para visualizar los datos de manera interactiva fue Power BI. Para lograr esto, utilicé scripts de Python para obtener datos y actualizar el informe de manera constante y sencilla. Cargué el informe en Power BI Web, estableciendo un gateway que se conectara con mi entorno de Python. Esta configuración me permitió programar actualizaciones automáticas y mantener el informe siempre actualizado con los datos más recientes.

Como valor añadido, he implementado una integración entre una aplicación desarrollada en Power Apps y Power BI para facilitar un control eficiente de mis inversiones. Esta solución combina la practicidad de una aplicación personalizada con la capacidad analítica de Power BI para ofrecer una visión integral y visualmente atractiva de mi cartera de inversiones.

En la aplicación de Power Apps, he diseñado una interfaz intuitiva que me permite registrar y almacenar información detallada sobre cada inversión. Puedo ingresar datos como el nombre de la inversión, el monto invertido, la fecha de compra y otros detalles relevantes. Esta aplicación me permite mantener un registro organizado y actualizado de mis activos financieros.


## Tecnologia usada
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Seaborn](https://raw.githubusercontent.com/Rickhersd/Rickhersd/e7a293e7309996b0a377e4bd8097aeeca321853b/neobrutalist_icons/neo_seaborn.svg)
![PyCoinGecko API](https://user-images.githubusercontent.com/64792903/112778422-2bffd480-904d-11eb-83ee-edecd6599f1f.png)


## Descargo de Responsabilidad
![](https://bestanimations.com/media/hazards/45886907warning-yellow-blinking-sign-animated-gif-3.gif)

Quiero dejar claro que este proyecto tiene un propósito exclusivamente educativo y refleja un ejercicio personal en un entorno simulado. El objetivo es aplicar y mejorar mis habilidades en análisis de datos y visualización. Los datos utilizados y los resultados obtenidos en este proyecto no deben ser considerados como base para la toma de decisiones reales en ninguna circunstancia.

Es importante subrayar que este proyecto no busca alentar ni recomendar a nadie que tome decisiones basadas en los datos presentados aquí. Toda la información y los resultados aquí expuestos son parte de un ejercicio de aprendizaje y exploración en el campo de la visualización de datos.

Siempre se debe buscar asesoramiento y orientación adecuada de profesionales calificados antes de tomar decisiones importantes que involucren áreas como finanzas, salud, política y otros campos relevantes.

<p align="center">
<img src="image/Analisis general.jpeg"  height=500>
</p>


## Contacto
<a href="https://www.linkedin.com/in/adiegocampos/">
  <img src="https://camo.githubusercontent.com/a80d00f23720d0bc9f55481cfcd77ab79e141606829cf16ec43f8cacc7741e46/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e6b6564496e2d3030373742353f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465" alt="Logo" width="200"/>
</a>

