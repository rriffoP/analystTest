# analystTest

Este proyecto es una prueba diseñada para evaluar los conocimientos de los postulantes a Data Analyst, enfocándose en **Python (Nivel Básico)** y **SQL (Nivel Medio)**.

## Descripción de la Prueba

La evaluación consta de **3 preguntas orientadas al área de marketing**. Para responderlas, se deberá revisar y analizar la información contenida en dos bases de datos.

## Requisitos

Para que la prueba sea considerada válida, se deben cumplir los siguientes puntos:

1. **Carga de datos:** Las bases de datos deben cargarse en Python utilizando la librería `sqlite3`.
2. **Extracción de información:** Se debe realizar la extracción de la información necesaria para cada caso mediante consultas en SQL usando la librería mencionada.
3. **Entrega funcional:** Todas las consultas deben quedar en un archivo `.py` que sea funcional y esté listo para ejecutarse.
4. **Análisis complementario:** Aunque la extracción y el ajuste de los datos se deben hacer en SQL, no es obligatorio que el 100% del análisis se realice en Python. Es válido extraer las tablas en SQL y, posteriormente, trabajar los datos en Excel para generar gráficos y resultados que se adjunten en un documento final.

> **Nota:** Las bases de datos contienen datos ficticios y simulados.

## Descripción de las Bases de Datos

### Base 1: Ventas de la Compañía x Cliente

- **id_cliente:** Identificador del cliente que realiza la compra.
- **fecha_compra:** Fecha en la que se efectuó la compra.
- **nro_boleta:** Número de la boleta de la compra.
- **monto_compra:** Monto total de la compra.
- **id_producto:** Identificador del producto.
- **tienda_compra:** Tienda donde se realizó la compra (el valor 30 corresponde a ecommerce).
- **valor_despacho:** Monto del despacho a domicilio.
- **cantidad:** Cantidad de productos comprados.

### Base 2: Ventas por Medio

- **fecha:** Fecha de la venta asociada al medio.
- **medio:** Medio utilizado para la venta.
- **monto_venta:** Monto de la venta asociada a ese medio.

#### Tipos de Medios

- **Directo:** Clientes que ingresan al sitio directamente utilizando la URL.
- **Facebook:** Publicidad pagada en Facebook.
- **Google:** Publicidad pagada en Google.
- **Orgánico:** Clientes que llegan a través del buscador de Google.
- **Otros:** Medios que no encajan en las categorías anteriores.
- **Sitios Ofertas:** Sitios afiliados que promocionan productos y ofertas a cambio de comisiones basadas en las ventas generadas.

## Preguntas

### Pregunta 1

Durante la semana del 10 al 16 de junio se observa un aumento en el presupuesto destinado a medios, a pesar de no existir una campaña específica para esos días. El equipo de marketing requiere analizar:

- ¿Existe realmente un aumento en la inversión?
- ¿Se dispone de información suficiente para confirmarlo?
- En caso afirmativo, ¿a qué se debe este incremento?
- ¿Qué respuesta se le proporcionaría al equipo de marketing?

### Pregunta 2

El gerente de ecommerce ha reportado una caída significativa en las ventas del canal durante la semana del 12 al 18 de agosto. Se solicita determinar:

- ¿Se confirma la caída en las ventas?
- ¿La información disponible es suficiente para un análisis adecuado?
- En caso afirmativo, ¿a qué se puede atribuir esta disminución?
- ¿Qué respuesta se le daría al gerente de ecommerce?

### Pregunta 3

La gerencia plantea establecer una meta de ventas para los meses de enero, febrero y marzo utilizando como referencia el promedio de ventas del año 2024. Se pide:

- ¿Es correcto utilizar el promedio de ventas del año 2024 para fijar esta meta?
- Justifique su respuesta.

### BONO OPCIONAL

1. Estas bases son simuladas ¿te encontraste con datos extraños o incongruentes durante tu trabajo con ellas? ¿Por qué consideras que son extraños?
2. ¿Podrias indicar algo más sobre las ventas de esta compañía?

---

Se recomienda leer detenidamente cada sección y asegurarse de cumplir con todos los requisitos antes de proceder con la resolución de la prueba. ¡Buena suerte!


