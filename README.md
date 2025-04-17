![Ajolote money](images/billete.jpeg)


Los seres humanos no solo adquieren deudas para cubrir necesidades básicas. Los países también pueden endeudarse como una forma de gestionar su economía. Por ejemplo, invertir en infraestructura representa un gasto elevado, pero es fundamental para garantizar una buena calidad de vida a los ciudadanos. El Banco Mundial es una de las instituciones que otorgan préstamos a los países.

En este proyecto, vas a analizar datos sobre deuda internacional recopilados por el Banco Mundial. El conjunto de datos incluye información sobre la cantidad de deuda (en dólares estadounidenses) que deben los países en desarrollo, clasificada en varias categorías. Tu tarea será responder las siguientes preguntas:

- ¿Cuántos países diferentes aparecen en la base de datos?
- ¿Qué país tiene la mayor cantidad de deuda?
- ¿Qué país ha realizado los pagos más bajos?

A continuación, se describe la tabla con la que vas a trabajar:

## Tabla `international_debt`

| Columna         | Descripción                                                       | Tipo de dato |
|-----------------|-------------------------------------------------------------------|--------------|
| country_name     | Nombre del país                                                   | `varchar`    |
| country_code     | Código que representa al país                                     | `varchar`    |
| indicator_name   | Descripción del indicador de deuda                                | `varchar`    |
| indicator_code   | Código que representa el indicador de deuda                       | `varchar`    |
| debt             | Valor del indicador de deuda para el país (en dólares actuales)  | `float`      |

Deberás realizar consultas SQL para responder las tres preguntas mencionadas.
