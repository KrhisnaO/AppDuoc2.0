# AppDuoc2.0
Es una aplicación móvil híbrida diseñada para sistemas operativos Android. Desarrollada en el Instituto Duoc UC como parte del ramo de programación de aplicaciones móviles, esta aplicación aborda la problemática de la gestión de asistencias e inasistencias de los estudiantes universitarios.

### **Características principales**

La aplicación se destaca por las siguientes características:
* Gestión Integral de Asistencias: Ofrece una solución para el registro y seguimiento de asistencias de los estudiantes.
* Interfaz Intuitiva: Diseñada con una interfaz de usuario intuitiva y amigable para facilitar su uso por parte de estudiantes y personal docente.
* Skills: Angular, Ionic, Capacitor, TypeScript, SCCS, HTML, JavaScript y SQLite.
  
### **Instalación**

Para iniciar el proyecto en tu entorno local, sigue estos sencillos pasos:
1. Instalación de Dependencias:
   
          npm install

3. Iniciar el Proyecto: 
  
          ionic serve
   
6. Activar JSON Server: En otra terminal ejecuta el siguiente comando:

          cd _JSON-SERVER
   
          npx json-server --watch publicaciones.json
   
8. Transferir a Dispositivo Móvil: Para desplegar la aplicación en un dispositivo Android, ejecuta:
  
          ionic capacitor run android
   
### **Credenciales de Acceso**

La app proporciona las siguientes credenciales de acceso para diferentes roles:

**Estudiantes:**

      atorres@duocuc.cl
      Contraseña: 1234
---
      avalenzuela@duocuc.cl
      Contraseña: qwer
---
      cfuentes@duocuc.cl
      Contraseña: asdf
      
**Administrador:**

      admin@duocuc.cl
      Contraseña: Admin
    
### **Pruebas Unitarias y End-to-End**

La aplicación está equipada con pruebas unitarias y pruebas end-to-end para garantizar su fiabilidad y calidad:

* Pruebas Unitarias con Jasmine: Ejecuta el comando **ng test** para realizar pruebas unitarias utilizando Jasmine.
  
* Pruebas End-to-End con Cypress: Ejecuta **npx cypress open** para realizar pruebas end-to-end utilizando Cypress.
