# Grupo Hotusa - Data Analysis Test

Tarea para candidatos que aplican a un puesto de Data Analyst en Grupo Hotusa.

## Descripción de la tarea

El dataset a trabajar contiene las siguientes columnas:
- *res_id*: Id de Reserva
- *date_gen*: Fecha en la que se realizó la reserva
- *date_checkin*: Fecha de entrada de la reserva
- *nights*: Número de noches de la reserva
- *ori_id*: Origen de la reserva
- *agency_id*: Agencia a partir de la cual entró la reserva
- *mean_price_per_night*: Precio medio por noche de la reserva
- *status*: Status de la reserva (Cancelada o Confirmada)

Debes crear un report reproducible contestando las siguientes preguntas:
1. Representa gráficamente el número de **cancelaciones y reservas confirmadas** para cada fecha de **check in** (date_checkin). 
2. Número de **reservas confirmadas y cancelaciones** para cada **agencia** (agengy_id). Selecciona únicamente el top 10 en cuanto a volumen total de reservas.
3. Evolución del **precio mínimo**, **precio medio**, **precio máximo** y **revenue** para cada fecha de **check in** (date_checkin) (Nótese: revenue = mean_price_per_night * nights)
	- Se puede extraer alguna conclusión al comparar la evolución entre los precios y el revenue. ¿Hay fechas mal vendidas?  
4. Las reservas entran con una antelación. La antelación se calcula como: date_eval - date_checkin. El objetivo de esta pregunta es observar
**como afecta la antelación a la cancelación y confirmación de las reservas**. (Si es posible agrupa las antelaciones en intervalos: [0,3),[3,7),[7,30),[30,90),[90,120] días)
5. Elabora **2 análisis** por tu parte:
	- Algunas sugerencias: Diferencias entre precio de venta de reservas canceladas y confirmadas, cómo afecta el número de noches al precio medio de la reserva, cómo afecta el 
	número de guests, ratio de cancelación por origen (origen_id), análisis del precio de venta por mes...

## Entrega

Entrega tus resultados en notebook o en un link al repo en GitHub a: carlos.perez@eurostarshotelcompany.com 
