# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): Amazon, sector de comercio electrónico y logística.
- Problema a resolver: Optimizar el inventario y evitar pérdidas de ventas o exceso de stock. 
- Objetivo de negocio (rentabilidad): Aumentar ventas mediante personalización y reducir costes logísticos con prediiciones de la demanda

## 2) Big Data: recogida masiva de datos
 Amazon se considera Big Data debido a que maneja grandes volúmenes de datos, como son sus usuarios, a gran velocidad ya que son en tiempo real
 y con variedad, mediante textos, imágenes, clics...
 
- Fuente 1: Historial de navegación y compras
- Fuente 2: Interacciones con alexa y dispositivos inteligentes
- Fuente 3: Reseñas y valoraciones de productos
- Volumen/velocidad (estimación): Millones de transaccioens y eventos por segundo a nivel global. 
- Formatos: textos, reviews, clics, imagenes, series de ventas. 

- https://aws.amazon.com/big-data/
- https://developer.amazon.com/en-US/alexa
- https://www.amazon.science/tag/recommendation-systems

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada: 
 Los datos de usuario se capturan en tiempo real, posteriormente en el paso 2 se limpian, transforman y almacenan en la nube para poder utilizarlos 
 y por último se preparan variables y se usan modelos de IA para recomendar y predecir la demanda. 

- Ingesta (captura/eventos): Captura de eventos en tiempo real (Amazon kinesis)
- Limpieza/normalización: Procesos ETL con AWS Glue 
- Almacenamiento (data lake/warehouse): Data Lake en Amazon S3 y Data Werehouse en RedShift
- Preparación de variables (features): Ingeniería de características en SageMaker
- Análisis/BI (opcional): Visualización con QuickSight 

- https://aws.amazon.com/kinesis/
- https://aws.amazon.com/s3/
- https://aws.amazon.com/sagemaker/

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...):
- Entrada del modelo (qué datos usa):
- Salida del modelo (qué produce):
- Decisión que habilita (qué hace la empresa con esa salida):

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 2:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 3:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

## 6) Diagrama del pipeline (ASCII o Mermaid)
(Pega aquí el diagrama)

## 7) Riesgos y mitigación
Riesgo 1:
- Mitigación 1:

Riesgo 2:
- Mitigación 2:

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy):
- Importancia futura (3–5 años):
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo):
- Conclusión razonada:

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
