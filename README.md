# 🚁 Base de Conocimientos: Sistema Ontológico de Drones

![Obsidian](https://img.shields.io/badge/Obsidian-483699?style=for-the-badge&logo=obsidian&logoColor=white)
![LM Studio](https://img.shields.io/badge/LM_Studio-000000?style=for-the-badge&logo=openai&logoColor=white)
![Status](https://img.shields.io/badge/Estado-Completado-success?style=for-the-badge)

---

## 📌 Información General

* **Asignatura:** Sistemas Expertos (1er Parcial)
* **Grado y Grupo:** 7° E

### 👥 Integrantes
| Nombre | Registro |
| :--- | :--- |
| **Victor Habib Flores Alfaro** | `23310377` |
| **Erick Oswaldo Ramirez Gonzalez** | `23310402` |

---

## 📖 Introducción

Mediante la integración colaborativa entre **Obsidian** y **LM Studio** (a través de modelos de lenguaje locales), se desarrolló un entorno interactivo para la generación automática y mapeo de **relaciones conceptuales ontológicas** enfocadas en la arquitectura integral de un vehículo aéreo no tripulado (**Drone**).

---

## 🌐 Estructura y Capas del Grafo

El mapa de conocimiento se organiza mediante **tres grupos categóricos primarios** codificados por color en la Vista de Grafo de Obsidian:

### 🟣 Grupo 1: Capa de Hardware, Sensores y Estructura Física
> **Propósito:** Proporcionar la estructura mecánica, el suministro de energía eléctrica, la propulsión y la captura directa de variables físicas del entorno.

* **Descripción:** Agrupa todos los elementos tangibles, módulos de energía, actuadores y componentes mecánicos o electrónicos del vehículo aéreo.
* **Componentes principales:**
  * **Estructura y Energía:** Plataforma Aérea, Batería LiPo.
  * **Propulsión y Etapa de Potencia:** Motor BLDC, ESC (Variador Electrónico).
  * **Procesamiento Base:** Unidad de Control de Vuelo (FCU), Microcontrolador STM32.
  * **Sensores del Sistema:** Unidad de Medida Inercial (IMU), Acelerómetro, Giroscopio, Barómetro, Magnetómetro, GPS, Sensor LiDAR y Cámara de Flujo Óptico.

---

### 🟡 Grupo 2: Capa de Software, Algoritmos y Control de Vuelo
> **Propósito:** Ejecutar la toma de decisiones, la estimación de estados, la estabilización de la actitud y la evasión de colisiones.

* **Descripción:** Representa la inteligencia a bordo encargada de procesar las lecturas sensoriales para calcular la posición real, mantener el equilibrio y ejecutar trayectorias.
* **Componentes principales:**
  * **Firmware / Autopiloto:** PX4 Autopilot, ArduPilot.
  * **Estimación y Control:** Filtro Kalman Extendido (EKF2), Estimador de Estado, Control de Actitud, Controlador PID.
  * **Navegación:** Sistema de Navegación y Localización, Sistema de Detección de Objetos.

---

### 🟢 Grupo 3: Capa de Comunicaciones, Protocolos e Interfaces
> **Propósito:** Permitir el flujo ordenado de datos entre chips (hardware interno), el envío de comandos del piloto y la transmisión de telemetría a tierra.

* **Descripción:** Engloba los buses de datos internos, los enlaces de radiofrecuencia a distancia y los estándares de mensajes utilizados para interconectar el hardware y el software.
* **Componentes principales:**
  * **Radiofrecuencia:** Transmisor RC, Receptor RC, ExpressLRS.
  * **Supervisión Terrestre:** Sistema de Telemetría, Estación de Control Terreno (GCS).
  * **Protocolos y Buses:** MAVLink, DShot600, PWM, UART, SPI e I2C.

## Instrucciones de acceso al grafo en Obsidian
Desde la opción "Administrar Bóvedas" abajo a la izquierda en Obsidian seleccionamos abrir una carpeta como Boveda. Al abrir la carpeta "Prueba" tendremos acceso al grafo.

## 📊 Vista Previa del Grafo
![Grafo](https://github.com/user-attachments/assets/09f3715d-9e36-49ad-b216-272c5566c71f)
