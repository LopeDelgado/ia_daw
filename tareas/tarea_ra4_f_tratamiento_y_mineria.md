# Práctica IA (RA4 · f)(Lope Delgado Suárez)

## 1) Caso de uso
- Tipo de aplicación: Tienda online (Plataforma web de recomendacion de contenido), como por ejemplo Amazon, 
- Problema: Hay demasiadas opciones en la tienda y no ofrece claridad para los usuarios
- Usuario: Usuarios registrados en la plataforma

## 2) Datos
- Datos: Historial de compra, Historial de visualización, Productos guardados, Tiempo invertido en cada producto, Valoraciones, Búsquedas, Preferencias de usuario.. .
- Tipo minería: Mineria de datos predictiva, analiza patrones en los datos de la plataforma 

## 3) Pipeline
- Recogida: La aplicacion web recoge datos de los usuarios y los guarda en la base de datos 
- Limpieza: Se eliminan datos incorrectos o duplicados
- Transformación: Los datos se convierten a formato numerico para Machine Learning
- Entrenamiento: Se entrena el modelo con machine learning usando herramientas de IA
- Predicción: El modelo predice que productos podrían interesarle al usuario
- Uso: La aplicacion web muestra recomendaciones personalizadas 

- https://www.tensorflow.org/resources/recommendation-systems?utm_source

## 4) Integración
- Backend: Servidor en Java, PHP, o Python que conecta la IA con la base de dato 
- Frontend: Interfaz web hecha con HTML, CSS y JavaScript 
- Flujo: 1. Usuario entra en la web
	 2. El Interfaz web (HTML, CSS y JavaScript) envía datos al servidor (Java, PHP o Phyton)
	 3. El servidor envía datos al modelo de IA
	 4. La IA hace la predicción
	 5. El servidor recibe la predicción
	 6- Por ultimo el interfaz web muestra recomendaciones
Este modelo se usa en Apps como Amazon o Netflix: 
- https://help.netflix.com/es/node/100639?utm_source


## 5) Valor
- Mejora: Personalizacion, mas ventas, mejor  experiencia de usuario
- Sin IA: Sin IA solo se mostrarian productos aleatorios o los más vendidos 
- Rentabilidad: Aumentan las ventas y el tiempo que el usuario permanece en la web

## 6) Diagrama

Usuario --> Frontend (Web)
   
Frontend (Web) --> Backend (Servidor)
   
Backend (Servidor) --> Base de Datos
   
Base de Datos --> Modelo IA / Machine Learning
   
Modelo IA / Machine Learning --> Predicción
   
Predicción --> Backend
   
Backend --> Frontend
   
Frontend --> Usuario recibe recomendaciones


## 7) Riesgos
- Riesgo 1: Uso de datos personales ( riesgo en la privacidad)
- Mitigación 1: Cumplir RGPD y anonimizar datos
- Riesgo 2: Predicciones incorrectas
- Mitigación 2: Entrenar el modelo de IA y mejorar lo datos

## 8) Fuente

- Sistemas de recomendacion 
- Netflix Help Center 
- https://www.tensorflow.org/resources/recommendation-systems?utm_source 
