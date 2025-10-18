🚀 frontMQTT: Un Cliente MQTT para el Navegador

Un cliente MQTT basado en la web, simple y fácil de usar, para conectar, publicar y suscribirse a tópicos de un broker MQTT.
Toma en cuenta las caracteristicas de tu json para diferir entre modulos IoT, estados y un apartado para enviar y otro para recibir

✨ Características

    Conexión a Broker MQTT: Conéctate a cualquier broker MQTT público o privado.

    Publicación de Mensajes: Envía mensajes a cualquier tópico MQTT.

    Suscripción a Tópicos: Suscríbete a uno o varios tópicos para recibir mensajes en tiempo real.

    Visualización de Mensajes: Visualiza los mensajes entrantes de forma clara y ordenada.

    Interfaz Intuitiva: Una interfaz de usuario limpia y fácil de usar para una experiencia fluida.

    Responsive: Diseño adaptable para funcionar en diferentes tamaños de pantalla.

🏁 Cómo Empezar

Prerrequisitos:

    Tener instalado Node.js y npm.

Sigue estos pasos para tener una copia local del proyecto funcionando.

🛠️ Instalación

  Clona el repositorio:

    git clone https://github.com/DiLe0n/frontMQTT.git

  Navega al directorio del proyecto:

    cd frontMQTT

  Instala las dependencias:

    npm install

  Inicia la aplicación:

    npm start


🚀 Uso

  Abre la aplicación en tu navegador.

  Introduce los detalles de tu broker MQTT:

    Host: La dirección de tu broker (ej. broker.hivemq.com).

    Puerto: El puerto de conexión (ej. 8000 para WebSockets).

    Usuario y Contraseña: (Opcional) Si tu broker requiere autenticación.

  Haz clic en "Conectar". El estado de la conexión se mostrará en la interfaz.

  Para suscribirte a un tópico:

    Introduce el nombre del tópico (ej. casa/sensor/temperatura).

    Haz clic en "Suscribirse".

    Los mensajes que lleguen a ese tópico aparecerán en la sección de "Mensajes".

  Para publicar un mensaje:

    Introduce el tópico al que quieres publicar.

    Escribe el mensaje.

    Haz clic en "Publicar".

🛠️ Construido Con

    MQTT.js - El cliente MQTT para Node.js y el navegador.

    HTML5

    CSS3 - (Opcional: puedes añadir frameworks como Bootstrap, Tailwind, etc.)

    JavaScript
