# Investigacion_comportamiento_usuario
## Objetivo: Investigar el comportamiento del usuario para la aplicación de la empresa. Primero, estudiar el embudo de ventas y luego, observa y analizar los resultados de un test A/A/B.

## Paso 1:  
Importamos las librerías que vamos a necesitar en el transcurso del análisis.
Observamos los datos del archivo y leemos su información general.

## Paso 2:
Se comprobó que no hay valores ausentes y los valores repetidos representan un porcentaje demasiado pequeño para el total de datos, por lo tanto de eliminaron. 
Se corrigió el tipo de formato de la columna 'full_date' y se crearon dos columnas nuevas que contienen la fecha y la hora por separado.


## Paso 3.
Estudié y comprobé los datos, el total de registros y usuarios por evento.
Realicé un histograma para visualizar las fechas con los datos registrados y concluir en qué fechas tenemos datos relevantes y las demás excluirlas, creando un nuevo DataFrame filtrado con los datos relevantes para el análisis.

## Paso 4.
Realicé el análisis de embudo de eventos, creando un gráfico para su visualización. 
Lo cual concluí que en el transito de etapas donde se pierden más clientes es de la pantalla principal a la página de las ofertas (Se debe de hacer un análisis más exaustivo con otros departamentos de este punto para encontrar una posible mejora). También es bueno saber que un 48% de los clientes que inician sesión llega hasta el final del embudo que es el pago del pedido, es un tasa de retención final muy buena.