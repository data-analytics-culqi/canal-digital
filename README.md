# canal-digital

# Resumen de Gráficas
## Heatmap de Agentes Activos por Intervalo de 30 Minutos  y 60 minutos
- Representa la cantidad de agentes activos en **bloques de 30 y 60 minutos**.  
- Excluye los periodos de refrigerio de los agentes (usualmente entre las 12h-15h)

## Heatmap de Promedio de Tickets por Semana en Intervalos de 30 y 60 Minutos  
- Muestra la cantidad promedio de tickets creados en el **Canal Digital** 
- Permite identificar **horarios pico** y **días de mayor actividad** de tickets.  


## 3. Heatmap de Nivel de Servicio (%)  
- Indica el porcentaje de tickets respondidos en menos de **90 segundos** por hora y día.  
## Output folder:
  - En el folder el output se está guardando en parquet los archivos de:
    - cantidad_agentes_30m_sin_refrigerio.parquet
    - cantidad_agentes_60m_sin_refrigerio.parquet
    - reporte_30m_tickets_marzo
    - reporte_60m_tickets_marzo
    - ratio_60_tickets_agentes
