### Java_Primera_Entrega
## Primera Entrega del proyecto del 2º Cuatrimestre

# Estructura general del proyecto

A.    El proyecto debe contener tres carpetas: src, data y doc.

B.    La carpeta data debe incluir el fichero CSV del dataset seleccionado.

C.    La carpeta src debe incluir el código fuente, organizado en paquetes. Crear un paquete fp. Crear dentro de él un paquete utiles para las clases de utilidad, un paquete common para los tipos auxiliares, y un paquete para los tipos del dominio de trabajo (p.ej. música, cine…). Por último, crear un paquete test dentro del paquete de los tipos.

D.    El proyecto debe contener un fichero README.md donde se describirán los datos y los tipos implementados.

# Entrega  

Elegir un tipo, que deberá tener como mínimo 8 propiedades entre básicas y derivadas, y deberán ser de tipos variados (integer, float/double, String, boolean, fecha y hora, enumerado). Además, deberá tener una propiedad de un tipo auxiliar implementada mediante un record y otra, obligatoriamente, de tipo lista o conjunto.
Crear la estructura básica del proyecto.
Implementar el tipo base, que debe cumplir los siguientes requisitos:

•    Tener al menos dos constructores.

•    Tener al menos una propiedad derivada.

•    Tener definida una representación como cadena.

•    Tener definido un criterio de igualdad.

•    Tener definido un criterio de orden natural.

•    Tener definidas al menos dos restricciones sobre las propiedades de tipos diferentes: limitación de fechas, propiedades numéricas entre valores, cadenas de caracteres con un prefijo o con un separador, etc.

Realizar un test del tipo en el que se comprueben los resultados de cada uno de los métodos.

La entrega debe incluir la implementación y prueba del tipo, así como la documentación del tipo, tanto en el fichero README.md como en el propio código mediante comentarios de documentación.

Para el tipo auxiliar (record) puede usar atributos que guarden pares de valores: intervalo de fecha de inicio y fin, resultados deportivos, coordenadas geográficas, ciudad y nación, dos contadores como el de pasajeros y tripulación, conciertos al aire libre o en local cerrado, etc.
