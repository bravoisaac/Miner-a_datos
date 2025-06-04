Visión General
La preparación de los datos es una etapa crítica en el desarrollo de modelos predictivos precisos y fiables. Durante esta fase, se depuran, transforman y seleccionan cuidadosamente los datos, abordando problemas como valores faltantes o inconsistencias. Esto garantiza una mayor calidad e integridad del conjunto de datos, lo cual es esencial para realizar análisis precisos y confiables.

Contexto del Negocio
Una empresa agrícola con sede en Sídney, Australia, opera en un entorno climático altamente variable. Para optimizar la planificación de cultivos y el uso eficiente de recursos, la empresa se apoya en tecnologías avanzadas y expertos en agricultura. La integración de datos meteorológicos precisos en su proceso de toma de decisiones es clave para mejorar la eficiencia operativa y la resiliencia frente a eventos climáticos extremos.

Problema del Negocio
El principal desafío consiste en anticipar y adaptarse a condiciones climáticas adversas —como sequías, inundaciones y ciclones tropicales— que impactan directamente la producción agrícola. La previsión de lluvia, en particular, es esencial para una correcta planificación de siembra, cosecha y gestión hídrica.

Objetivos Clave
Prevención de daños a cultivos:
Anticipar eventos climáticos extremos mediante:

Monitoreo meteorológico continuo

Diversificación de cultivos

Prácticas agrícolas sostenibles

Infraestructura adecuada

Cobertura con seguros agrícolas

Capacitación a agricultores

Estas acciones buscan garantizar la estabilidad de la producción y fortalecer la seguridad alimentaria.

Diccionario de Datos
A continuación se describen las variables del conjunto de datos meteorológicos utilizados.
(* = Variable seleccionada para el análisis)

Variable	Descripción
Date *	Fecha de la observación
Ubicación	Estación meteorológica
MinTemp *	Temperatura mínima (°C)
MaxTemp *	Temperatura máxima (°C)
Lluvia	Precipitación registrada (mm)
Evaporacion	Evaporación en 24h (mm)
Sol	Horas de sol en el día
DirRafaga	Dirección de la ráfaga más fuerte
VelRafaga	Velocidad ráfaga más fuerte (km/h)
Dir9am	Dirección del viento a las 9am
Dir3pm	Dirección del viento a las 3pm
Vel9am	Velocidad del viento a las 9am (km/h)
Vel3pm	Velocidad del viento a las 3pm (km/h)
Hum9am *	Humedad relativa a las 9am (%)
Hum3pm *	Humedad relativa a las 3pm (%)
Pres9am *	Presión atmosférica a las 9am (hPa)
Pre3pm *	Presión atmosférica a las 3pm (hPa)
Nub9am	Nubosidad a las 9am (0-8)
Nub3pm	Nubosidad a las 3pm (0-8)
Temp9am	Temperatura a las 9am (°C)
Temp3pm	Temperatura a las 3pm (°C)
LluviaHoy	Indicador: 1 si llovió en las últimas 24h (>1 mm)
RISK_MM	Medida cuantitativa de riesgo de lluvia
RainToday *	Indicador: 1 si llovió hoy (>1 mm)
LluviaMan	Indicador: 1 si llovió mañana
RainTomorrow *	Indicador: 1 si lloverá mañana (>1 mm)
