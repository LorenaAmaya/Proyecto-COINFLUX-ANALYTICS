
# Proyecto-COINFLUX-ANALYTICS
Proyecto final de análisis y visualización de datos.
## CONTEXTO
En este proyecto presentamos un analisis a 5 criptomonedas, dichas monedas fueron escogidas segun su estabilidad y cantidad de movimientos 24h antes de tomados los datos desde la API.
Para esto se escogieron las siguientes 5 monedas
- Bitcoin
- Ethereum
- Binancecoin
- Solana
- Tether

 ## OBJETIVO
 Como objetivo principal queremos analizar 5 criptomonedas, para comprender un poco el comportamiento de las criptomonedas y este creciente mercado global.
 Veremos el comportamiento de estas 5 monedas a travez de un periodo de tiempo determinado, examinando los siguientes indicadores:
 - Valor actual de la moneda
 - ATH (All Time High): precio maximo historico
 - ATL: Precio minimo historico
 - Fecha de sus maximos historicos
## EXTRACCION DE DATOS 
Para obtener los datos que fueron utilizados para este proyecto nos conectamos a CoinGeckoAPI, desde aqui obtuvimos los datos historicos de 100 monedas diferentes, a partir de aca creamos un DataFrame con las 5 monedas seleccionadas y con las columnas necesarias para nuestro analisis.

## ANALISIS EXPLORATORIO DE DATOS
En el proceso hacemos uso de las siguientes librerias:
- Pandas
- Matplotlib
- Seasborn
Para realizar este proceso de exploracion utilizamos los siguientes pasos:
1. Conexion con la API: en un primer intento esta conexion cargo datos que no eran relevantes, apartir de aca descargamos un archivo json que nos permitio traer los datos que nos eran utiles para realizar nuestro analisis
2. Limpieza de datos: 
 - Verificacion y eliminacion de valores nulos
 - Eliminacion de columnas irrelevantes
Con esto hecho, descargamos un archivo CSV para proceder con los siguientes pasos.
3. Formulacion de preguntas de negocio
   Apartir de la informacion de nuestra tabla nos planteamos diferentes preguntas que a nuestro criterio ayudarian a un posible comprador de cripto a elegir una moneda para hacer su invesion sin mucho riesgo.
4. Visualizacion:
   Para la visualizacion utilizamos PowerBI, exportando el archivo CSV realizamos las diferentes graficas que daban respuesta a las preguntas que realizamos.
 
