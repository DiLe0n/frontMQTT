# 📡 FrontMQTT - Web Client Dashboard

¡Bienvenido a **FrontMQTT**! Tu interfaz web ligera y profesional para gestionar, monitorear y depurar conexiones MQTT directamente desde el navegador.

Este proyecto actúa como un cliente visual que te permite interactuar con tus dispositivos IoT y Brokers MQTT sin necesidad de instalar software pesado de escritorio. Ideal para desarrolladores y entusiastas de la domótica.

---

## 🚀 Características Principales

* **🔌 Conexión en Tiempo Real:** Conéctate a cualquier Broker MQTT (WebSocket) al instante.
* **📬 Suscripción a Topics:** Escucha múltiples temas simultáneamente para ver el flujo de datos de tus sensores.
* **📝 Publicación de Mensajes:** Envía comandos o datos a tus dispositivos directamente desde la interfaz.
* **📊 Visualización de Logs:** Historial de mensajes recibidos con timestamps para facilitar la depuración.
* **🎨 Interfaz Intuitiva:** Diseño limpio y responsivo para una gestión eficiente.

---

## 🛠️ Tecnologías Utilizadas

Construido con estándares web modernos para garantizar compatibilidad y rendimiento:

* **Frontend:** HTML5, CSS3, JavaScript (ES6+).
* **Protocolo:** MQTT sobre WebSockets (wss:// o ws://).
* **Librería Cliente:** [MQTT.js / Paho MQTT] (El motor de comunicación).
* **UI/UX:** Diseño responsivo adaptable a móviles y escritorio.

---

## 📋 Requisitos Previos

Para usar FrontMQTT, solo necesitas:

1.  Un navegador web moderno (Chrome, Firefox, Edge).
2.  Acceso a un **Broker MQTT** que soporte WebSockets (ej. Mosquitto configurado con websockets, HiveMQ público, etc.).
    * *Nota: Los navegadores no pueden conectarse directamente a puertos TCP puros (como el 1883), deben usar WebSockets (usualmente puerto 8083 o 9001).*

---

## 🔧 Instalación y Uso

Este proyecto es extremadamente fácil de desplegar.

### Opción A: Ejecución Local (Recomendada)
Si tienes Node.js instalado:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/DiLe0n/frontMQTT.git](https://github.com/DiLe0n/frontMQTT.git)
    cd frontMQTT
    ```

2.  **Instala las dependencias (si aplica):**
    ```bash
    npm install
    ```

3.  **Inicia el servidor de desarrollo:**
    ```bash
    npm start
    # O simplemente abre el archivo index.html en tu navegador si es estático
    ```

### Opción B: Despliegue Estático
Puedes alojar este proyecto en cualquier servidor web estático (Apache, Nginx, GitHub Pages) simplemente subiendo los archivos de la carpeta `dist` o `public`.

---

## ⚙️ Configuración de Conexión

Por defecto, la aplicación buscará conectarse a un broker. Asegúrate de configurar los siguientes parámetros en la interfaz:

* **Host:** `tu-broker-mqtt.com` (o `localhost` si corres el broker localmente).
* **Port:** `8083` (o el puerto WebSocket de tu broker).
* **Path:** `/mqtt` (Ruta común para websockets).
* **User/Pass:** (Opcional, si tu broker requiere autenticación).

---

## 📂 Estructura del Proyecto

```text
frontMQTT/
├── src/
│   ├── components/      # Componentes de la UI (Conexión, Logs, Chat)
│   ├── services/        # Lógica de conexión MQTT
│   └── assets/          # Estilos e imágenes
├── public/              # Archivos estáticos
├── package.json         # Dependencias y scripts
└── README.md            # Documentación
```

---


## 🤝 Contribución

### ¡Tu ayuda es bienvenida para hacer este Gateway más robusto!

1. **Haz un Fork del repositorio.**

2. **Crea tu rama (git checkout -b feature/MejoraSeguridad).**

3. **Haz Commit de tus cambios.**

4. **Haz Push a la rama.**

5. **Abre un Pull Request.**

---

## 📝 Licencia

```
Este proyecto está bajo la licencia ISC. Siéntete libre de usarlo y adaptarlo a tu infraestructura.
```

---
