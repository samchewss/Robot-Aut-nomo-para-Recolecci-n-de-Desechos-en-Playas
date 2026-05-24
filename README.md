# 🤖 Robot Recolector de Residuos para Playas

Proyecto mecatrónico orientado al diseño, construcción e implementación de un robot compacto para la recolección de residuos sólidos en playas mediante un sistema móvil de bajo costo basado en ESP32.

El objetivo principal del proyecto es desarrollar una solución tecnológica capaz de contribuir a la limpieza de entornos costeros, facilitando la recolección de pequeños residuos presentes en la arena y promoviendo el uso de tecnologías aplicadas a problemáticas ambientales.

---

## 📌 Características principales

✔ Sistema de tracción mediante orugas  
✔ Control remoto mediante comunicación infrarroja (IR)  
✔ Movimiento multidireccional:
- Avance
- Reversa
- Giro a la derecha
- Giro a la izquierda

✔ Accionamiento de pala frontal para recolección

✔ Paro de emergencia mediante final de carrera

✔ Control basado en ESP32

✔ Generación de señales PWM para control de velocidad de motores

---

## ⚙️ Hardware utilizado

El prototipo integra los siguientes componentes:

- ESP32-WROOM
- Motores DC
- Drivers para motores
- Receptor infrarrojo (IR)
- Control remoto infrarrojo
- Final de carrera
- Sistema de tracción por orugas
- Sistema mecánico de pala frontal
- Batería de alimentación
- Estructura impresa en 3D

---

## 📂 Estructura del repositorio

```text
Robot_Recolector_Playas/
│
├── Codigos_Pruebas/
│   │
│   ├── Prueba_Control_Infrarrojo/
│   ├── Prueba_Avance_Reversa/
│   └── Prueba_Movimiento_Completo/
│
├── Codigo_Final_Robot/
│   │
│   └── Robot_Recolector_Final/
│
├── Diagramas/
│   │
│   ├── Esquematico_Electronico
│   ├── Conexion_ESP32
│   └── CAD_Robot
│
└── Documentacion/
```

---

## 🧪 Descripción de pruebas realizadas

### Prueba 1: Validación de receptor infrarrojo
Se realizó la identificación y lectura de códigos provenientes del control remoto infrarrojo para validar la comunicación con la ESP32.

### Prueba 2: Movimiento básico
Se implementó el control de avance y reversa utilizando motores DC mediante PWM.

### Prueba 3: Movimiento completo
Se añadieron movimientos laterales para mejorar la maniobrabilidad del robot.

### Prueba 4: Integración final
Se integró el sistema de movilidad y el mecanismo de accionamiento de la pala frontal en un único sistema funcional.

---

## 🔧 Librerías utilizadas

### IRremote
Utilizada para la recepción y procesamiento de señales provenientes del control infrarrojo.

Instalación:

Arduino IDE → Library Manager → Buscar:

```text
IRremote
```

Autor recomendado:

```text
Armin Joachimsmeyer
```

---

## 🚀 Funcionamiento general

El usuario envía comandos mediante un control remoto infrarrojo hacia el receptor conectado a la ESP32. Posteriormente, el microcontrolador interpreta dichos comandos y genera señales PWM para controlar la velocidad y dirección de los motores de tracción y del mecanismo de accionamiento de la pala.

---

## 👥 Integrantes

Proyecto desarrollado dentro de la asignatura:

**Proyectos Mecatrónicos**

Centro Universitario de Ciencias Exactas e Ingenierías (CUCEI)

---

## 🌎 Objetivo ambiental

Este proyecto busca demostrar cómo la integración de mecánica, electrónica y programación puede utilizarse para desarrollar soluciones tecnológicas enfocadas a la reducción del impacto ambiental y al fortalecimiento de prácticas sostenibles.
