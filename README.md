# Entrega 1

## Documentación de dominios y sub-dominios

### El alumno identificó y documentó correctamente todos los dominios y sub-dominios usando el DSL de ContextMapper [10pt]

SaludTech de los Alpes (STA) es una compañía
colombiana constituida en 2021 que se desenvuelve
en la industria del Vertical AI. 

Su enfoque principal es recaudar, procesar y distribuir imágenes médicas y diagnósticos anonimizados a compañías de IA y desarrolladores. Dichas imágenes y metadatos sirven como fuente de entrenamiento para modelos de IA. 

Lo primero a identificar son los dominios de negocio.

Pensando ampliamente podemos pensar en dos dominios que son:

**(a) Recaudar imagenes:** Es la posibilidad de que los proveedores de salud pueden proveer datos anonimizados a STA y obtener un pago por ello. En este caso lo que se propone es un pago acuerdo al nivel de uso de los datos. 

**(b) procesar y distribuir imágenes médicas y diagnósticos anonimizados:** STA cuenta con 3 diferentes productos diseñados para servir como datos de entrenamiento de modelos de IA. 

No obstante, consideramos que hay un vinculo muy grande entre procesar y distribuir las imagenes y diagnosticos anonimizados y la recaudacion de las imagenes. Sin imagenes no se pueden procesar y mucho menos distribuir los datos por lo que (b) depende de (a)

Siendo este el caso, se tomo la decisión de trabajar con un único dominio de negocio: **Recaudación, procesamiento y distribución de imagenes médicas y diagnosticos anonimizados**
