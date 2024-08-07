# Reverb Realtime Chat ![Laravel](https://img.shields.io/badge/Laravel-11-red) ![Realtime](https://img.shields.io/badge/Realtime-Enabled-blue)

Reverb Realtime Chat es una aplicación de chat en tiempo real construida con Laravel 11. Permite a los usuarios ver una lista de otros usuarios, iniciar conversaciones, y chatear en tiempo real utilizando Laravel Echo, Pusher y Laravel Reverb.

## Tecnologías Utilizadas

- **Laravel 11** ![Laravel](https://img.shields.io/badge/Laravel-11-red): Framework de PHP para el desarrollo de la aplicación.
- **Laravel Reverb** ![Laravel Reverb](https://img.shields.io/badge/Laravel%20Reverb-Active-yellow): Servicio de broadcasting utilizado para la comunicación en tiempo real.
- **Pusher** ![Pusher](https://img.shields.io/badge/Pusher-Enabled-lightblue): Servicio para la gestión de canales en tiempo real.
- **Laravel Echo** ![Laravel Echo](https://img.shields.io/badge/Laravel%20Echo-Active-green): Biblioteca para escuchar eventos de WebSocket.
- **JavaScript con AJAX** ![JavaScript](https://img.shields.io/badge/JavaScript-AJAX-yellowgreen): Para actualizaciones dinámicas sin recargar la página.
- **Blade** ![Blade](https://img.shields.io/badge/Blade-Templates-lightgray): Motor de plantillas de Laravel para las vistas.

## Características

- **Lista de Usuarios** ![Users](https://img.shields.io/badge/Users-List-orange): Visualiza una lista de usuarios disponibles para iniciar una conversación.
- **Lista de Conversaciones** ![Conversations](https://img.shields.io/badge/Conversations-List-purple): Consulta la lista de conversaciones actuales.
- **Mensajería en Tiempo Real** ![Chat](https://img.shields.io/badge/Realtime%20Chat-Enabled-blue): Envía y recibe mensajes en tiempo real con otros usuarios.

## Instalación y Configuración

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. **Clonar el Repositorio** ![Clone](https://img.shields.io/badge/Clone-Git%20Repo-blueviolet)

    ```bash
    git clone https://github.com/tu-usuario/reverb-realtime-chat.git
    cd reverb-realtime-chat
    ```

2. **Actualizar Dependencias** ![Update](https://img.shields.io/badge/Update-Dependencies-brightgreen)

    - **Composer** ![Composer](https://img.shields.io/badge/Composer-Update-blue)

      ```bash
      composer update
      ```

    - **NPM** ![NPM](https://img.shields.io/badge/NPM-Update-yellow)

      ```bash
      npm update
      ```

3. **Configurar el Entorno** ![Environment](https://img.shields.io/badge/Setup-Environment-orange)

    Copia el archivo de ejemplo de configuración:

    ```bash
    cp .env.example .env
    ```

    Luego, edita el archivo `.env` para configurar tus credenciales de base de datos y servicios de broadcasting.

4. **Generar Clave de Aplicación** ![Key](https://img.shields.io/badge/Generate-Key-blue)

    ```bash
    php artisan key:generate
    ```

5. **Migrar la Base de Datos y Cargar Semillas** ![Migrate](https://img.shields.io/badge/Migrate--Seed-brightgreen)

    ```bash
    php artisan migrate --seed
    ```

6. **Iniciar los Servidores de Desarrollo** ![Start](https://img.shields.io/badge/Start-Servers-yellowgreen)

    - **Mantener NPM en Ejecución** ![NPM Run](https://img.shields.io/badge/NPM%20Run%20Dev-blueviolet)

      ```bash
      npm run dev
      ```

    - **Iniciar el Servicio de Broadcasting** ![Broadcasting](https://img.shields.io/badge/Start%20Broadcasting-yellow)

      ```bash
      php artisan reverb:start
      ```

## Uso

- Accede a la aplicación en tu navegador local en `http://localhost`.
- Navega a la lista de usuarios para iniciar nuevas conversaciones.
- Revisa y participa en conversaciones existentes desde la vista de lista de conversaciones.


## Contacto

Si tienes preguntas o necesitas ayuda, no dudes en ponerte en contacto con [ulloadeifheltsteven@gmail.com](mailto:ulloadeifheltsteven@gmail.com).

