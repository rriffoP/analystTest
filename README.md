# analystTest
Esto es una prueba para evaluar los conocimientos de los postulantes a Data Analyst.
Python: Básico
SQL: Medio

La prueba consta de 3 preguntas orientadas al área de marketing. Se requiere revisar 2 bases de datos y obtener la información necesaria para contestar. 
Para considerar la prueba como valida se requiere que se cumplan los siguientes puntos:
1.- Que las bases se carguen en python utilizando la librería sqlite3
2.- Si bien puedes revisar las bases de varias formas, el objetivo es que hagas una extraxión de la información necesaria para cada caso con lenguaje SQL usando la librería indicada.
3.- Todas las consultas deben quedar en un documento .py que debe ser funcional y entregado.
4.- Lo relevante es que la extraxión y ajuste de los datos requeridos para cada pregunta sea en SQL, pero no es necesario que el 100% de los análisis se hagan en python, eso queda a criterio del postulante, una opción valida es extraer tablas que se requieran en SQL y trabajarlas dentro de un excel para posteriormente entregar este documento con gráficos y resultados.

*Son bases con datos ficticios simulados.

Base 1: Ventas de la compañía x cliente

id_cliente: Identificador del cliente que compra
fecha_compra: fecha de la compra
nro_boleta: Número de la boleta de la compra
monto_compra: Monto de la compra
id_producto: Identificador del producto
tienda_compra: Tienda donde se ejecutó la compra (30 es ecommerce)
valor_despacho: Monto del despacho a domicilio.
cantidad: Cantidad de los productos comprados

Base 2: Ventas x medio

fecha: fecha de la venta asociada al medio
medio: Indica el medio utilizada
monto_venta: Monto de la venta asociada a ese medio

Medios:
-Directo - Clientes que ingresan al sitio usando la url del sitio.
-Facebook - Publicidad pagada en Facebook.
-Google - Publicidad pagada en Google.
-Organico - Clientes que llegan por el buscador de google.
-Otros - Medios no considerados.
-Sitios ofertas - Sitios afiliados que promocionan productos y ofertas a cambio de comisiones en base a la venta generada.

Pregunta 1
En los análisis de la semana se ve un aumento en el presupuesto de medios en la semana del 10 al 16 de junio a pesar de que no hay una campaña especifica para esos días . Se le solicita por parte del equipo de marketing revisar que produjo ese aumento de consumo de presupuesto en la inversión enfocada a rentabilidad (Estos medios consumen en base a la cantidad de compras online).
¿Hay un aumento de inversión? ¿Tienes información suficiente?
¿De existir, a que se debe?
¿Qué le contestarias al equipo de marketing?

Pregunta 2
El gerente de ecommerce levanta al área que hay una caída importante en la venta del canal en la semana del 12 al 18 de agosto. Se le solicita revisar que pudo producir esta caída en la venta.
¿Hay una caída en la venta? ¿Tienes información suficiente?
¿De existir, a que se debe?
¿Qué le contestarias al gerente de ecommerce?

Pregunta 3
La gerencia quiere poner una meta de venta para los meses de enero, febrero y marzo e indican que lo más apropiado es usar el promedio de venta del año 2024.
¿Es correcto poner esta meta? Justifique la respuesta.

