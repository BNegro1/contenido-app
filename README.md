
## Instalar Ionic

Install my-project with npm

### I) Instalar desde PowerShell: npm install -g @ionic/cli@7

“@version”, en este caso, es la versión “7" 

### II) En caso de “UnauthorizedAccess”:

- ***Powershell con Admin: Set-ExecutionPolicy Unrestricted***
- Desde PowerShell normal: npm install -g @ionic/cli@
- Ionic -v → Verificar instalación

### III) Iniciar proyecto:

- Iniciar PowerShell (shift+ click derecho)
- Luego: ionic start [NOMBRE]

- Elegir un framework:
    
    Se escoge: > Angular | [https://angular.io](https://angular.io/)
    
- Elegir template (En este caso “blank”):
    - blank.
- Build de la aplicación:
    
    1) NgModules
    2) Standalone
    
    Se utilizaría: NgModules
    

## 2) Abrir APP Ionic

Your Ionic app is ready! Follow these next steps:

- cd .\[NOMBRE]
- ionic serve → INICIAR APP
- ionic capacitor → Agregar  un proyecto iOS o de Android usando Capacitor.
- Generate your app icon and splash screens using
- cordova-res --skip-config --copy → Generar icono de la app y splash screen
