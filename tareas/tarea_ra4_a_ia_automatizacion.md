1) Describe el proceso “ANTES” (sin IA)

Gestion de facturas y recibos de manera manual. 

Normalmente una persona se encarga de recibir todas las facturas y recibos, las revisa una por una para verificar que sean correctas 
despues las registra en un sistema contable u hoja de calculo, las clasifica y finalmente aprueba los pagos. 


¿Quién lo hace? (rol/equipo)

Todo eso lo hace un contable, administrativo o asistente de oficina. 

¿Qué pasos tiene? (5–7 pasos)

1- Recibe las facturas por correo o de forma física
2- Revisa manualmente cada factura: datos, importe, fechas, impuestos...
3- Clasificar las facturas por proveedor
4- Registra las facturas en el sistema contable 
5- Prepara la factura para su pago 
6- Archiva el comprobante y actualiza el pago


¿Cuánto tarda? (estimación)

El tiempo estimado depende de la complejidad de las facturas pero suele comprender unos 10 min por factura. 

¿Qué errores o cuellos de botella hay?

Puede haber errores humanos al rellenar datos como por ejemplo el numero de factura 
Se pueden perder facturas o clasificarlas mal 
Y los pagos o el proceso puede retrasarse por una revisión lenta


2) Propón la automatización con IA (DESPUÉS)

¿Qué parte automatiza la IA? (clasificación, predicción, extracción, generación, etc.)

La extraccion de datos de facturas (proveedor, importe) 
Clasificacion de facturas por proveedro
Registro en el sistema contable

¿Qué queda para humanos? (validación, excepciones, decisiones críticas)

Validación de facturas con datos conflictivos 
Decision final sobre aprovacion de pagos 
Supervisión periodica del trabajo con IA 

¿Qué datos necesitaría la IA? (sin datos sensibles; menciona tipos: logs, texto, imágenes…)

Facturas en PDF  o imagenes escaneadas
HIstorial de facturas y pagos 
Listado de proveedores y categoria de contables

3) Explica la OPTIMIZACIÓN (mejora medible)

Define 3 métricas y estima la mejora (aunque sea aproximada, debe ser coherente).

En funcion de los ejemplos de moodle: w
Tiempo por factua: Antes 10 minutos, con la IA 1-2 minutos (80% de mejora) 
Coste humano: Antes: Horas de contable, mientras que con ia menos horas de revision (60% de mejora de tiempo)
Calidad: Antes: errores de regitro y clasificacion, mientras que con ia son datos consistentes (Reduccion del 90% de errores)

4)Optimizacion 

Tiempo por factua: 80% de mejora con la ia
Coste humano: (60% de mejora de tiempo)
Calidad: (Reduccion del 90% de errores)


5) Diagrama de flujo (Mermaind) 

    A (Factura recibida) --> B (AI extrae datos
    B --> C (Clasificacion automática por proveedores) 
    B --> D (Sugerencia de registro en sistema contable)
    C --> E (Validación humana en caos conflictivo)
    D --> E 
    E --> F(Factura registrada y archivada) 
    
    
6) Riesgos y mitigación (obligatorio)

Incluye 2 riesgos (sesgo, alucinaciones, privacidad, dependencia, seguridad, costes…).
La IA puede extraer datos incorrectos si la factura tiene formato inusual.	
Dependencia excesiva sin revision humana constante pueden pasar errores desapercibido

Propón 2 mitigaciones (humano en el bucle, validación, auditoría, límites, trazabilidad…).
En el bucle de trabajo con ia aparecen constantemente las revisiones humanas para revisar el trabajo


7) FUente oficial 

	Microsoft AI Builder: Invoice Processing
  explica cómo la IA puede extraer datos de facturas y automatizar procesos contables.



