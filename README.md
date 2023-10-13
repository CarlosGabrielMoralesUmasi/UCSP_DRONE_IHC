# Proyecto Drone UCSP

Este proyecto es una aplicación Android que integra funcionalidades de DJI SDK para control de drones. Permite interactuar con drones DJI y realizar diversas operaciones de control de vuelo y grabación de datos.

## Requisitos

Asegúrate de tener los siguientes requisitos instalados:

1. **Java 11:** Descarga e instala [Java 11](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html).

2. **Paquetes del Proyecto:**

   - **Package Name:** `com.dji.sdk.sample`
   - **Google Services:** Asegúrate de tener el archivo `google-services.json` configurado para tu proyecto.

   ```json
   # google-services.json
   {
     "project_info": {
       "project_number": "115206810105",
       "firebase_url": "https://dronucsp-default-rtdb.firebaseio.com",
       "project_id": "dronucsp",
       "storage_bucket": "dronucsp.appspot.com"
     },
     "client": [
       {
         "client_info": {
           "mobilesdk_app_id": "1:115206810105:android:a466133d7878a2fefff528",
           "android_client_info": {
             "package_name": "com.dji.sdk.sample"
           }
         },
         "oauth_client": [],
         "api_key": [
           {
             "current_key": "YOUR_API_KEY_HERE"
           }
         ],
         "services": {
           "appinvite_service": {
             "other_platform_oauth_client": []
           }
         }
       }
     ],
     "configuration_version": "1"
   }
- Reemplaza "YOUR_API_KEY_HERE" con tu clave API personal de tu proyecto de FIREBASE.
- Reemplaza "YOUR_API_KEY_HERE" con tu clave API personal obtenida en la página [DJI Developers](https://developer.dji.com/user/apps/#all).

   **APP INFORMATION**
   - **SDK Type:** Mobile SDK
   - **App Name:** ucsp_dron
   - **Software Platform:** Android
   - **Package Name:** **com.dji.sdk.sample**
   - **App Key:** 3b22aa_tiene_esta_forma_e8d5c
   - **Category:** Film shooting
   - **Description:** Proyecto donde se debe tener el paquete con el nombre "com.dji.sdk.sample" obligatorio para tener las herramientas completas del código y el APP KEY "personal key", el cual debe ser creado únicamente para una cuenta de DJI DEVELOPERS.


## Instrucciones de Ejecución
1. Clona este repositorio en tu entorno de desarrollo.

2. Abre el proyecto en Android Studio.

3. Ejecuta la aplicación en un emulador o dispositivo Android.
   
## NOTAS
No se recomienda actualizar la versión de Gradle a 8.0 debido a problemas aún desconocidos. Mantén la versión que se especifica en el archivo build.gradle.

## Contacto
Yerson Sanchez Y. (Head del proyecto)
//Carlos Morales U.
//Cristhian Ocola P.

Este `README.md` proporciona información sobre el proyecto, requisitos, instrucciones de ejecución y contacto para posibles consultas. Asegúrate de personalizarlo según las necesidades específicas de tu proyecto.
