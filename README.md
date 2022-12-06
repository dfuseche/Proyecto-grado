# Wizard Chess 🪄♟️

### Descripción: 
Wizard Chess es un ajedrez en realidad virtual por control de voz cuyo objetivo principal es incentivar a personas que han tenido poco contacto con el ajedrez a jugarlo de una manera más entretenida. Para ello se creó un juego multijugador cooperativo en el cual el usuario puede comandar las fichas por medio de su voz en un escenario con un ambiente mágico.

![imagen](https://user-images.githubusercontent.com/53950535/205774857-7ce345ff-964d-4128-8205-65379b1c9b34.png)




> 📺 Ver Trailer: https://www.youtube.com/watch?v=2rnAn1-6BMY

---

## Prerrequisitos, descarga y ejecución:

A continuación, se describen los prerequisitos, las instrucciones y consideraciones adicionales para poder correr Wizard Chess en tu propia maquina.

### Prerrequisitos
Hardware:
- [x] Meta Quest 2
- [x] Un computador desde el cual se instalará el juego. Este debe tener minimo un procesador de +2.0GHz y 2GB de RAM.
- [x] Cable USB C compatible con el Meta Quest 2

Software:
- [x] Git Bash
- [x] Unity Hub (De preferencia 3.x.x)
- [x] Unity 2021.3.8f1 
- [x] Android SDK
- [x] Aplicación Oculus Escritorio
- [x] Aplicación Oculus Dispositivo Móvil 


### Instrucciones para configurar ambiente de trabajo: 

1. **Plastic SCM**: Para instalar Git Plastic, dirijase a la siguiente página https://www.plasticscm.com/download y seleccione la versión correspondiente a su sistema operativo. Siga las instrucciones que se presentan en el instalador hasta terminar la instalación.

2. **Unity Hub**: Para instalar Unity, se debe dirigir a la página de Unity e instalar [Unity Hub](https://unity.com/download). Asegurese de elegir el archivo correspondiente a su sistema operativo.

3. **Unity 2021.3.8f1**: Una vez tenga instalado Unity Hub en su computador, dirijase a [esta pagina](https://unity.com/releases/editor/archive) y seleccione la version solicitada de unity, en este caso la 2021.3.8. Haga click en la opción de Unity Hub para instalar.
![imagen](https://user-images.githubusercontent.com/53950535/205778534-3322b416-9c5f-4c03-93f2-db4ac49ccf45.png)

4. **Android SDK**: Al seleccionar la opción de Unity Hub en el último paso, se abrirá su aplicación de Unity Hub con más detalles y opciones para instalar la versión solicitada de Unity. En esta pestaña, seleccione las opciones de *Android Build Support* como se muestra en la imagen de abajo y de click en continuar.
![imagen](https://user-images.githubusercontent.com/53950535/205779138-c3c68cf4-cb0a-4c8b-aeaa-e33dd536ce56.png)

5. **Oculus Escritorio**: Descargue e instale la aplicación de [Oculus para escritorio](https://www.meta.com/quest/setup/). Una vez iniciada la aplicación, verifique que la conexión entre su dispositivo Quest 2 y escritorio funcionan al conectar estos y verificar la sección de dispositivos. En esta se debería mostrar el dispositivo y el estado "conectado".

6. En caso de que no tenga una cuenta de desarrollador y no pertenezca a ninguna organización, dirijase a https://dashboard.oculus.com/organizations/create/ y diligencie la información necesaria para crear una organización. 

7. **Oculus Móvil**: Descargue e instale la aplicación de Oculus en su dispositivo móvil. Siga las instrucciones en el dispositivo para iniciar sesión con su cuenta de desarrollador de Oculus. En el apartado de configuraciones, active el modo de desarrollador.

**Una vez se sigan estos pasos de configuración, se puede seguir a descargar e importar el proyecto en Unity**

### Instrucciones para descargar e importar el proyecto de Wizard Chess en Unity:

1. Abra la carpeta donde desea ubicar el proyecto
2. Corra Git Bash desde esta carpeta, como se muestra a continuacion:
![imagen](https://user-images.githubusercontent.com/53950535/205787401-fb045dca-1d04-4396-af2c-c17719aeb05b.png)

3. Clone el proyecto en la carpeta deseada, ejecutando el siguiente comando desde la ventana que se abrió de Git Bash
```git
git clone https://github.com/necalero/WizardChess
```
4. Desde Unity Hub, seleccione la opción de abrir un nuevo proyecto y seleccione el directorio donde clonó el proyecto.
![imagen](https://user-images.githubusercontent.com/53950535/205788029-d310abf7-adf6-45e6-a950-a93717fb9a86.png)

### Instrucciones para ejecutar el proyecto de Wizard Chess desde Unity:

1. Conecte el dispositivo Quest 2 a su computador y verifique la conexión de este mediante la aplicación de Oculus de escritorio. 

2. Abra el proyecto en Unity

3. Abra *File* -> *Build and Run* 

4. Verifique que la configuración de las escenas es igual a la que se muestra a continuación:
 
![imagen](https://user-images.githubusercontent.com/53950535/205791449-e1e15898-dbe8-4065-b0e8-4e0831dd252f.png)

6. Verifique que la configuración adicional es igual a la que se muestra a continuación:
![imagen](https://user-images.githubusercontent.com/53950535/205793196-0eb5f32f-09e7-4fef-aa5b-c27e4ca7479e.png)

7. Finalmente, de click en el botón Build and Run para construir el APK y ejecutarlo desde su dispositivo. 

### Instrucciones de juego

- Para iniciar la partida, haga click en el botón A

- Para moverse por las distintas zonas del tablero, haga click en el botón X 

- Para activar la funcionalidad de movimiento de fichas por medio de comandos de voz, se debe oprimir y mantener el botón *Right Grip* hasta que termine de dictar el movimiento. El comando de voz debe seguir la estructura: 

  (Ficha) (Posición actual) (Posición deseada)
  
  Un ejemplo de esto sería decir el comando “Peón B2 B3” para mover el peón de la posición inicial B2 a la posición deseada B3 y así iniciar la partida
  
- Para mover manualmente una ficha, mantenga oprimido el botón A mientras apunta a una ficha con su control derecho. Mueva la ficha hasta la posición deseada y suelte el botón A para confirmar su movimiento




