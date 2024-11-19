# Guía para Instalar y Configurar el Plugin Zoom Meeting en Moodle

En esta guía te explico cómo instalar y configurar el plugin **Zoom Meeting** en Moodle para integrar reuniones de Zoom directamente en tus cursos. 

## Pasos para la instalación

### 1. Ingresar a la página oficial de Moodle
   Lo primero es entrar a la página oficial de Moodle: [https://moodle.org](https://moodle.org).
![Screenshot from 2024-11-18 21-35-52](https://github.com/user-attachments/assets/87e8c699-667f-431b-83c5-70d73410063c)

### 2. Buscar el plugin Zoom Meeting
   - En el buscador de la página, escribí **"Zoom Meeting"**.
   - Seleccioná el plugin **Zoom Meeting** de la lista de resultados.
![Screenshot from 2024-11-18 21-36-14](https://github.com/user-attachments/assets/88bb5dab-8266-4af1-9c2f-f91b8e7ef24b)

### 3. Descargar el plugin
   - Hacé clic en el botón **"Download"** para descargar el archivo `.zip` del plugin.

### 4. Levantar Moodle en tu entorno local
   - Para levantar Moodle en tu máquina, podés seguir el video explicativo en el siguiente enlace:  
     [Video explicativo de cómo levantar Moodle en local](https://www.youtube.com/watch?v=0folHDpIFqM).
   - Asegurate de configurar Moodle en el puerto que prefieras. Por defecto, se usa el puerto 80.

### 5. Ingresar como administrador en Moodle
   - Una vez que Moodle esté corriendo en tu máquina local, ingresá con una cuenta de administrador.
![Screenshot from 2024-11-18 21-43-08](https://github.com/user-attachments/assets/69ea5c86-bf5f-4740-8f05-0152757bb2ee)

### 6. Navegar a la sección de administración
   - En el menú de administración, andá a **"Administración del sitio"** > **"Extensiones"** > **"Instalar complementos"**.
![Screenshot from 2024-11-18 21-43-26](https://github.com/user-attachments/assets/2b409e22-706c-473d-a1c2-7a74897b952f)
![Screenshot from 2024-11-18 21-43-32](https://github.com/user-attachments/assets/e0f522da-9d0e-42ff-abbf-bce16d904b59)

### 7. Instalar el plugin
   - Arrastrá el archivo `.zip` del plugin que descargaste antes y hacé clic en **"Instalar plugin desde el archivo ZIP"**.
![Screenshot from 2024-11-18 21-43-42](https://github.com/user-attachments/assets/c5497d4f-e23f-4818-8dcc-54c8913bac70)

### 8. Configuración de las claves de Zoom
   - Después de instalar el plugin, se va a abrir una página donde vas a tener que poner las claves de la API de Zoom para que el plugin funcione.
   - Los campos que tenés que completar son:
     - **Zoom Account ID**
     - **Zoom Client ID**
     - **Zoom Client Secret**
   - Para obtener estas claves, tenés que crear una app en el [sitio de desarrolladores de Zoom](https://marketplace.zoom.us/).
![Screenshot from 2024-11-18 21-45-11](https://github.com/user-attachments/assets/3b862966-d6b4-435d-866b-13bf86f172b6)

### 9. Acceder al curso
   - Ahora, entrá al curso donde querés usar el plugin de Zoom.
   - Asegurate de estar en **modo edición**.

### 10. Agregar una nueva actividad
   - Hacé clic en el botón **"Agregar una nueva actividad o recurso"** dentro del curso.
   - Seleccioná la opción **"Zoom Meeting"**.

### 11. Configurar la actividad de Zoom
   - Poné un **nombre** a la actividad de Zoom.
   - Hacé clic en **"Guardar y regresar al curso"**.

## Configuración adicional (opcional)

Si querés personalizar aún más la integración con Zoom, podés modificar varias opciones desde la página de configuración de la actividad, como:

- **Duración de la reunión**.
- **Configuración de grabación**.
- **Configuración de cámara y micrófono predeterminados**.
- **Sincronización con el calendario de Moodle**.

Estas opciones se pueden ajustar según lo que necesites para tu curso.

## Consideraciones finales

- El plugin **Zoom Meeting** te permite crear y gestionar reuniones de Zoom directamente desde tu plataforma Moodle, lo que facilita la interacción en línea dentro de los cursos.
- Asegurate de que la cuenta de Zoom que uses tenga los permisos necesarios para crear reuniones.

Con estos pasos, ya deberías poder integrar las reuniones de Zoom en tu plataforma Moodle local.

