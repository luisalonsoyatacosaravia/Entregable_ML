# 🧠 Proyecto ENTREGABLE_ML

## 📘 Descripción general

Este proyecto tiene como objetivo **demostrar el uso de modelos de Machine Learning directamente en el navegador web**, utilizando librerías como **TensorFlow.js**, **ml5.js** y **p5.js**.  
A través de tres ejercicios interactivos, se aplican diferentes técnicas de **reconocimiento de imágenes, dibujos y objetos en tiempo real**
---

## 🧩 Problemática

En la actualidad, los sistemas informáticos requieren soluciones que permitan **reconocer e identificar objetos o dibujos de forma rápida y precisa**.  
Esto es esencial en áreas como la educación, la seguridad y la automatización.  

---

## 💡 Propuesta de solución

Se desarrolló una aplicación web dividida en tres ejercicios, cada uno enfocado en un tipo distinto de reconocimiento visual:

### 🔹 Ejercicio A – Clasificación de imágenes con MobileNet
Permite subir una imagen desde el dispositivo y el modelo **MobileNet** predice el nombre del objeto y su nivel de confianza.

**Tecnologías utilizadas:**
- TensorFlow.js  
- MobileNet  
- HTML, CSS y JavaScript  

---

### 🔹 Ejercicio B – Reconocimiento de dibujos y validación por login
El usuario inicia sesión con su nombre y contraseña, luego dibuja en un lienzo.  
El modelo **DoodleNet** reconoce el dibujo y lo compara con un código asignado a cada usuario, validando si coincide.

**Tecnologías utilizadas:**
- ml5.js  
- p5.js  
- HTML, CSS y JavaScript  

---

### 🔹 Ejercicio C – Detección de objetos en tiempo real con cámara web
Utiliza un modelo personalizado entrenado con imágenes de objetos reales como **celular, billetera, cargador, llaves y tomatodo**.  
El sistema reconoce los objetos mediante la cámara y pronuncia su nombre con voz sintetizada.

**Tecnologías utilizadas:**
- ml5.js  
- TensorFlow.js  
- Reconocimiento de voz con `speechSynthesis`  
- p5.js para visualización  

---


