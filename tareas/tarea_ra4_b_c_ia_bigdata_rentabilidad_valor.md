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
Explica el flujo de forma ordenada: a
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
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...): Sistemas de recomendación y predicción de demanda.
- Entrada del modelo (qué datos usa): Historial de compras, clics, búsquedas, valoraciones
- Salida del modelo (qué produce): Productos recomendados y previsión de demanda futura
- Decisión que habilita (qué hace la empresa con esa salida): 	Ajuste dinámico de inventario y personalización de la web en tiempo real

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia): Ratio de conversion 
- Antes: Recomendaciones genéricas
- Después: REcomendaciones personalizadas
- Por qué mejora la rentabilidad: Más compras por usuario

KPI 2: Costes de almacenamiento
- Antes: Exceso o falta de stock
- Después: Predicción ajustada de demanda
- Por qué mejora la rentabilidad:Menos inventario inmovilizado

KPI 3: Tiempo medio de entrega 
- Antes: Planificación menos pesada
- Después: Logística optimizada con IA 
- Por qué mejora la rentabilidad: mayor satisfacción de clientes y aumento de la fidelidad de los mismos

## 6) Diagrama del pipeline (ASCII o Mermaid)
Usuarios → Captura de eventos (Kinesis) → limpieza y transformación → almacenamiento en Data Lake y Data Warehouse (Redshift) → preparación de variables → modelo IA → recomendaciones y predicción de demanda → optimización de inventario y ventas
## 7) Riesgos y mitigación
Riesgo 1: Sesgo algorítmico
- Mitigación 1: MOnitorización continua de modelos

Riesgo 2: Privacidad de datos
- Mitigación 2: Encriptación y cumplimiento normativo (RGPD) 

- https://aws.amazon.com/compliance/gdpr-center/

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy): La IA es el núcleo que permite personalizzción masiva y logística, convirtiendo amazon en un catálogo mas predictivo.
- Importancia futura (3–5 años): Mayor automatización en almacenes, modelos mas precisos de prevision y uso creciente de IA para atender clientes. 
- Condiciones/limitacione: Dependencia de datos de calidad, altos costes de infraestructura cloud, regulación creciente y riesgos estéticos
- Conclusión razonada: La IA no es un complemento en Amazon y su implementacion podria marcar la diferencia frente a otras empresas del e-commerce

- https://aws.amazon.com/machine-learning/
- https://aws.amazon.com/ai/

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial): -https://aws.amazon.com/big-data/
- IA/técnica/modelo (enlace oficial): - https://aws.amazon.com/machine-learning/
