# challegen2-danger-malaga
CUSTOMER CHURN ANALYSIS – TELECOMX LATAM

## RESUMEN EJECUTIVO

---Este proyecto analiza la cancelación de clientes (churn) en una empresa de telecomunicaciones con el objetivo de:
---Identificar los principales drivers de cancelación.
---Detectar segmentos de alto riesgo.
---Estimar el impacto financiero del churn.

Proponer acciones estratégicas de retención.

El análisis se enfoca en métricas de riesgo (% de churn) y no únicamente en volumen de clientes, priorizando una visión de negocio.

#### CONTEXTO DE NEGOCIO

La empresa enfrenta una tasa relevante de cancelación de clientes, afectando directamente los ingresos recurrentes.
El churn impacta:
Ingresos mensuales recurrentes (MRR)
Valor de vida del cliente (LTV)
Costos de adquisición (CAC)
Reducir el churn incluso en pequeños porcentajes puede generar mejoras financieras significativas.

#### PREPARACIÓN DE DATOS

Se realizaron las siguientes acciones:
Limpieza de variables categóricas.
Conversión de variables numéricas.
Creación de variable binaria de churn (1 = Yes, 0 = No).
Estandarización de nombres de columnas.
Se priorizó un dataset limpio y consistente para análisis confiable.

#### PRINCIPALES HALLAZGOS

A. Churn por Tipo de Contrato
Los contratos mensuales presentan la mayor tasa de cancelación.
Los contratos anuales y bianuales muestran menor probabilidad de churn.
***La falta de compromiso contractual aumenta el riesgo.***
Insight estratégico:
Incentivar contratos de mayor duración podría reducir significativamente la cancelación.

### B. Churn por Tipo de Internet

Algunos tipos de servicio presentan mayor tasa de churn.
La calidad percibida y el precio pueden influir en la cancelación.
Insight estratégico:
Revisar experiencia del cliente en los segmentos de mayor riesgo.
#### C. Churn por Método de Pago
Métodos de pago manual muestran mayor churn.
Pago automático presenta menor tasa de cancelación.
Insight estratégico:
Promover la automatización de pagos puede mejorar retención.

*****IMPACTO FINANCIERO ESTIMADO****

Se estimó la pérdida financiera asociada al churn considerando:
Ingreso mensual promedio por cliente.
Número de clientes que cancelan.
Resultado estimado:
Pérdida mensual significativa en ingresos recurrentes.
Impacto anual acumulado considerable.

***Escenario proyectado:***
Una reducción de 5 puntos porcentuales en churn podría recuperar millones en ingresos anuales.
El churn representa no solo pérdida de clientes, sino deterioro estructural del flujo de caja.

***RECOMENDACIONES ESTRATÉGICAS***

Incentivar contratos anuales con descuentos o beneficios.
Promover pago automático mediante incentivos.
Implementar campañas de retención durante los primeros meses.
Monitorear segmentos de alto riesgo con alertas tempranas.
Analizar posibles mejoras en experiencia del cliente en servicios críticos.

#### CONCLUSIÓN

#### El análisis demuestra que el churn no está distribuido de manera uniforme, sino concentrado en segmentos específicos.

Acciones dirigidas sobre:
Tipo de contrato
Método de pago
Segmentos de servicio
podrían reducir significativamente la cancelación y generar impacto financiero directo.
Este proyecto no solo describe datos, sino que traduce hallazgos en decisiones de negocio.

#### ESTRUCTURA DEL REPOSITORIO

README.md
TelecomX_Data.json
TelecomX_LATAM_caso_1_Callegen_2_Danger_Malaga.ipynb

