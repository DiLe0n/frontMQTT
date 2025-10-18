# 🛰️ frontMQTT

> Un cliente MQTT basado en la web (frontend) para conectar, publicar, suscribirse y visualizar mensajes de un broker MQTT desde el navegador.

---

## 📸 Vista previa

*(Aquí una captura de pantalla o gif que muestre la interfaz en acción)*  

---

## 🧭 Tabla de contenido

- [Descripción](#descripción)  
- [Características](#características)  
- [Requisitos](#requisitos)  
- [Instalación](#instalación)  
- [Uso](#uso)  
- [Configuración / Ejemplos JSON](#configuración--ejemplos-json)  
- [Arquitectura / Estructura del proyecto](#arquitectura--estructura-del-proyecto)  
- [Contribuir](#contribuir)  
- [Roadmap](#roadmap)  
- [Créditos](#créditos)  
- [Licencia](#licencia)  
- [Contacto](#contacto)  

---

## 📌 Descripción

**frontMQTT** es un cliente web liviano para interactuar con brokers MQTT desde el navegador.  
Permite conectarse (con o sin autenticación), suscribirse a tópicos, publicar mensajes y ver en tiempo real los que llegan.  
Está pensado para ser sencillo, extensible y fácil de usar.

Además, maneja JSON con lógica para distinguir módulos IoT, estados y separar la sección de enviar/recibir, adaptándose a estructuras comunes en proyectos de IoT.

---

## ✨ Características

- Conexión a cualquier broker MQTT (público o privado)  
- Autenticación (usuario/contraseña)  
- Suscripción a múltiples tópicos  
- Publicación de mensajes en tópicos  
- Visualización clara de los mensajes recibidos  
- Interfaz responsiva (adaptable a móviles y tabletas)  
- Procesamiento de estructuras JSON (módulos, estados, etc.)  
- Basado en **MQTT.js** para compatibilidad con WebSockets  

---

## 🧩 Requisitos

- Node.js >= **XX.X.X**  
- npm >= **X.X.X**  
- Navegador moderno con soporte WebSockets (Chrome, Firefox, Edge, etc.)

---

## 🚀 Instalación

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/DiLe0n/frontMQTT.git
cd frontMQTT
