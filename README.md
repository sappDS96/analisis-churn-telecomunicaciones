# Analisis de Churn en Clientes de Telecomunicaciones

Proyecto de analisis de datos orientado a identificar patrones de abandono de clientes (churn) en una empresa de telecomunicaciones, segmentar perfiles de riesgo y estimar el impacto economico asociado a la perdida de clientes.

## Vista del analisis

- [Ver notebook limpio](analisis_churn_telecomunicaciones.md): version ligera para revisar el codigo en GitHub.
- [Ver analisis completo en HTML](analisis_churn_telecomunicaciones.html): version exportada con codigo, texto y graficos.

## Objetivo del proyecto

Construir un analisis visual y ejecutivo que permita:

- medir la tasa de churn sobre la base total de clientes
- identificar segmentos con mayor riesgo de abandono
- detectar variables asociadas al churn, como contrato, antiguedad y metodo de pago
- estimar el ingreso mensual asociado a clientes que abandonaron
- priorizar clientes y segmentos de mayor impacto para acciones de retencion

## Origen de los datos

Conjunto de datos relacional de una empresa de telecomunicaciones, compuesto por cuatro tablas: contratos, datos personales de clientes, servicios de internet y servicios de telefonia.

Las tablas fueron integradas, depuradas y transformadas para construir un dataset analitico enfocado en churn.

## Herramientas utilizadas

- Python
- Pandas
- Power BI
- DAX
- Power Query

## Flujo de trabajo

1. Integracion de datos relacionales
2. Limpieza y transformacion de variables
3. Construccion del dataset analitico
4. Definicion de KPIs y medidas DAX
5. Diseno del dashboard interactivo en Power BI
6. Analisis de patrones, segmentacion y priorizacion de riesgo

## Principales hallazgos

- Los contratos mensuales presentan la mayor tasa de churn frente a contratos de mayor permanencia.
- El abandono se concentra especialmente en clientes con baja antiguedad.
- El metodo de pago E-Check muestra una asociacion relevante con mayores tasas de churn.
- El cruce entre tipo de contrato y rango de antiguedad permite identificar segmentos de riesgo mas precisos.
- El dashboard permite estimar el ingreso mensual en riesgo asociado al abandono de clientes.

## Dashboard

El dashboard incluye:

- clientes totales
- clientes churn
- tasa de churn
- ingreso mensual
- ingreso en riesgo
- churn por tipo de contrato
- churn por antiguedad
- churn por metodo de pago
- matriz de churn por combinacion de variables
- top 10 clientes en riesgo

## Archivos recomendados del repositorio

- `analisis_churn_telecomunicaciones.md`: notebook limpio para revision del codigo.
- `analisis_churn_telecomunicaciones.html`: analisis completo exportado con graficos.
- `df_Churn.csv`: CSV analitico final.
- Capturas del dashboard.

## Autor

**Sergio Perez**  
Data Analytics / Impact

GitHub: [sappDS96](https://github.com/sappDS96)  
LinkedIn: [sergioperezp](https://www.linkedin.com/in/sergioperezp/)
