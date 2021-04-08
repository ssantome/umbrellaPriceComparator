# UmbrellaPriceComparator

UmbrellaPriceComparator es un web scraper orientado a recolectar información sobre el precio de los paraguas en diferentes sitios web de compra online como pueden ser Amazon y Ebay.


## 1. Contexto

En los tiempos que corren existe tanta oferta de productos online que se vuelve prácticamente imposible hacer una búsqueda de los mejores precios de forma manual. 

De este problema nace este web scraper, capaz de comparar los precios de todas las ofertas de **Amazon** y **Ebay** para un producto previamente especificado, en este caso: el paraguas.

Hemos querido escoger las 3 principales plataformas de venta online de referencia a nivel mundial: Aliexpress, Amazon y Ebay. Hay que tener en cuenta que representan los 3 grandes mercados que nos podemos encontrar en el basto internet hoy en día, el mercado: **Chino**, **Europeo** y **Norte Americano**. La plataforma de venta online **Aliexpress** finalmente no la hemos incluido porque no permite realizar scraping.

Se eligen los paraguas como artículo para ejemplificar el funcionamiento del web scraper ya que se trata de un artículo básico, barato y del cual podemos encontrar multitud de ofertas en cada una de las plataformas mencionadas anteriormente.


## Instalación


## Modo de empleo


## Resultado

Como resultado de la ejecución de este web scraper obtendremos un archivo en formato .csv que contendrá toda la información recopilada de cada una de las webs analizadas.

### 2. Denominación dataset
Vamos a tener dos dataset, uno por cada web:
- Denominación de la recopilación de Amazon: Amazon
- Denomicación de la recopilación de Ebay: Ebay

## 3. Descripción del dataset
Tanto el dataset de Amazon como el de Ebay muestra el comportamiento de precios de los primeros 58 productos. 

## 4. Representaciones graficas de ejemplo(graficas con sus respectivas explicaciones, indicando que significado tiene cada eje, dato, columna, linea, etc)

## 5. Contenido
  La estructura de ambos dataset es la misma, estan compuestos por dos campos: nombre_artículo y precio_artículo.
  La variable "nombre_artículo" es de tipo: "character".
  La variable "precio_artículo" es de tipo: "numeric".
  A cada campo, se le añade las 3 letras iniciales de cada plataforma de venta online, siendo:
    - Amazon: Ama
    - Ebay: Eba
  La recogida de información corresponde al día 7 de abril de 2021 y se ha llevado a cabo a través del lenguaje de programación R.

## 6. Agradecimientos

## 7. Inspiración
  Los códigos formulados permiten recopilar en un instante los conceptos y precios de dos de las principales plataformas de venta online en España. Esto es un gran avance ya que el internet cada día esta más cerca de llegar a los que los economistas denominan "**competencia perfecta**". La competencia perfecta es cuando en los mercados se encuentran productos estandarizados y hay plena transparencia sobre los precios y los productos. Justamente con los codigos empleados estamos más cerca de llegar a lo que denominamos competencia perfecta ya que podemos recopilar los conceptos y precios de los diferentes productos. No solo conseguimos que sea útil para el consumidor ya que permite ver donde se encuentran los mejores precios y productos, sino además da la posibilidad de que cualquier empresa que venda algún tipo de producto, pueda conocer con facilidad como se encuentran los precios del mercado y así marcar ciertas estrategias que le ayuden con sus objetivos. 

## 8. Licencia: CC BY-SA 4.0
  La licencia por la que optamos es licencia CC by SA 4.0. Esta decisión se sustenta en 3 pilares:
  - **Uso comercial**: Como esta orientada hacia el comercio creemos que sería recomendable que se hiciera un uso comercial porque así podria mejorarse y adaptarse para un mayor número de personas.
  - **Emplear bajo misma licencia**: Tantos las remezclas, transformaciones y creaciones que partan de este material debera difundirse bajo la misma licencia.
  - **Autoría**: Al hacer uso del material hay que indicar la autoría, mostrar el enlace a la licencia e indicar los cambios efectuados.

## Funcionamiento del web excraper
explicación de los metodos empleados para la recolección de la información


## Explicacion de la licencia elegida


#### **Si vemos que algún aspartado de estos se vuelve muy extenso siempre se puede mover para la wiki y enlazarlo aqui en el readme principal**
