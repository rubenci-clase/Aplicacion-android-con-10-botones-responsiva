# Aplicacion-android-con-10-botones-responsiva
App creada para **Android 7.0** o posteriores, que utiliza un GridLayout para organizar una serie de botones numerados del 1 al 9 y el 0. Este diseño es flexible, permitiendo que los botones se distribuyan uniformemente en la pantalla del dispositivo.

La aplicación ha sido comprobada en varios formatos tal como se muestra al final del documento (Smartphone, Tablet y Escritorio).

## Características
- **Es responsiva** Se ajustan automáticamente al tamaño de la pantalla, manteniendo una distribución uniforme en diferentes dispositivos.
- **Funciona en modo noche** La interfaz es totalmente funcional en modo noche.
- **Diseño limpio** Cada botón tiene márgenes definidos para dar espacio entre ellos, ofreciendo una interfaz clara y fácil de usar.
- **Fácil de reutilizar** Cada botón tiene un ID único, lo que facilita su acceso y configuración en el código para manejar eventos de clic.

![image](https://github.com/user-attachments/assets/59c5c4eb-efcb-4862-91a8-555392e15a67)

## Tecnologías Utilizadas
- **Android Studio** Entorno de desarrollo
- **Android SDK (Software Development Kit)** 
- **XML** para diseñar la interfaz
- **Gradle** Herramienta de automatización de compilación

## Requisitos Previos para el desarrollo
- **Android Studio**
  * el IDE oficial para el desarrollo de aplicaciones Android.
    
- **JDK (Java Development Kit)**
  * Java Development Kit, versión 8 o superior, necesario para compilar el código en Java.
    
- **Android SDK**
  * Instalación de la SDK de Android, especialmente la API 24 (Android 7.0 - Nougat) o superior, ya que la app está orientada a esta versión mínima.
    
- **Conexión a Internet**
  * Necesaria para descargar dependencias, herramientas y actualizaciones de Android Studio y el SDK.
    
- **Dispositivo de Prueba (Emulador o Físico)**
  * Un emulador de Android o un dispositivo físico con Android 7.0 o superior para probar y depurar la app.

## Instrucciones para clonar y ejecutar el proyecto en Android Studio
### 1. Clona el repositorio:
Abre la terminal o línea de comandos y clona el repositorio en tu máquina local:
   ```bash
   https://github.com/rubenci-clase/Aplicacion-android-con-10-botones-responsiva.git
```
### 2.Abre el proyecto en Android Studio
* Abre Android Studio.
* En la pantalla de bienvenida, selecciona Open o Open an existing project.
* Navega hasta la carpeta donde clonaste el repositorio y selecciónala.
* Haz clic en OK para abrir el proyecto.

### 3.Sincroniza el proyecto con Gradle
Una vez que el proyecto esté abierto, Android Studio debería detectar automáticamente los archivos 'build.gradle'.
* Si aparece una notificación para sincronizar el proyecto, haz clic en Sync Now.
* Si no ves esta opción, puedes forzar la sincronización yendo a File > Sync Project with Gradle Files.

### 4.Configura un dispositivo de prueba
* Conecta un dispositivo físico con Depuración USB habilitada o utiliza un Emulador de Android.
* Para configurar un emulador, ve a Device Manager y selecciona o crea un emulador adecuado.

### 5.Compila y ejecuta la aplicación
* Asegúrate de seleccionar el dispositivo de destino (emulador o dispositivo físico) en la barra superior.
* Haz clic en el botón Run (o el ícono de reproducción ▶️) en la barra de herramientas, o utiliza el atajo de teclado Shift + F10.

### 6.¡Listo!
Android Studio compilará y ejecutará la aplicación en el dispositivo seleccionado. Una vez completado, podrás ver la aplicación en funcionamiento en tu emulador o dispositivo físico.

## Funcionamiento en diferentes dispositivos:
### **Smartphone**
![image](https://github.com/user-attachments/assets/96e4c809-fa8f-468c-adfd-a087c6661f71)

### **Tablet**
![image](https://github.com/user-attachments/assets/aea60296-4cd9-4dc2-b4a9-760cfd780977)

### **Escritorio**
![image](https://github.com/user-attachments/assets/645ae9fa-7c93-4d94-8ca0-fb90ff030a0e)

### **Smartphone Plegable**
![image](https://github.com/user-attachments/assets/8ea01290-b8b5-4806-b1b3-774832feb28c)
