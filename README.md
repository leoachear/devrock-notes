# PWA - devrock-notes
Implementación de una Progressive Web App con Polymer y Firebase

## Instalación y dependencias:

### Bower:
```sh
npm install -g bower
```

### Firebase CLI:
```sh
npm install -g firebase-tools
```

¿Problemas para instalar? Por ahí tenés que [cambiar los permisos de NPM](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

#### Verificamos la version del cliente de Firebase
```sh
firebase version
```

Debería decir 3.x.x, si es una version menor tenemos que cambiar los paths.

```sh
alias firebase="'npm config get prefix'/bin/firebase"
```

### Crear App en Firebase!

Vamos a ir a la [consola de Firebase](https://console.firebase.google.com/?pli=1) y vamos a crear una nueva App, le ponemos un lindo nombre y la localización.

### Conectarse a Firebase:
```sh
firebase login
```

### Por ultimo iniciamos el cliente de Firebase:
```sh
firebase init
```

Y lo configuramos, como este repositorio ya tiene configurado Firebase le vamos a dar siguiente siguiente siguiente, hasta que tengamos que seleccionar la base de datos con la que vamos a trabajar. Despues nos vamos a encargar del resto.

### Por suerte para nosotros Firebase tiene un servidor web incorporado <3
```sh
firebase serve
```
