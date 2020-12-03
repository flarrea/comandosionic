# comandosionic

Algunos comandos básicos de Ionic para iniciar el desarrollo de Apps.
________________________________________________________________________________________________
COMANDOS PARA IONIC

Debes abrir la consola de windows cmd, como administrador.

Recuerda que debes crear un directorio en tu equipo para tus Apps:

C:\ionicApps

Luedo, dentro de ese directorio aplicar los comandos.


1. Instalar ionic:


2. Crear una App

ionic start nombreApp blank --type=angular --cordova


3. Iniciar la App:


ionic serve

ionic lab


4. Crear una página:


ionic generate page pages/home

ionic generate page pages/login

ionic generate page pages/signup


5. Crear un servicio:

ionic g service services/api


6. Instalar plugins:

ionic cordova plugin add cordova-sqlite-storage
npm install @ionic/storage

ionic cordova plugin add cordova-plugin-camera
npm install @ionic-native/camera

ionic cordova plugin add cordova-plugin-telerik-imagepicker
npm install @ionic-native/image-picker

7. Instalar Firebase:


npm install @angular/fire firebase


8. Agregar plataforma Android


ionic cordova platform add android


9. Listar plataforma:


ionic cordova platform list

10. Listar plugins:

ionic cordova plugin list


11. Preparar APK:


ionic cordova build android --release --prod


12. Quitar plataforma:


ionic cordova platform remove android


13. Quitar plugin:


ionic cordova plugin remove cordova-plugin-camera
npm uninstall @ionic-native/camera
