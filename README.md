# Wizard Chess 馃獎鈾燂笍

### Descripci贸n: 
Wizard Chess es un ajedrez en realidad virtual por control de voz cuyo objetivo principal es incentivar a personas que han tenido poco contacto con el ajedrez a jugarlo de una manera m谩s entretenida. Para ello se cre贸 un juego multijugador cooperativo en el cual el usuario puede comandar las fichas por medio de su voz en un escenario con un ambiente m谩gico.

![imagen](https://user-images.githubusercontent.com/53950535/205774857-7ce345ff-964d-4128-8205-65379b1c9b34.png)




> 馃摵 Ver Trailer: https://www.youtube.com/watch?v=2rnAn1-6BMY

---

## Prerrequisitos, descarga y ejecuci贸n:

A continuaci贸n, se describen los prerequisitos, las instrucciones y consideraciones adicionales para poder correr Wizard Chess en tu propia maquina.

### Prerrequisitos
Hardware:
- [x] Meta Quest 2
- [x] Un computador desde el cual se instalar谩 el juego. Este debe tener minimo un procesador de +2.0GHz y 2GB de RAM.
- [x] Cable USB C compatible con el Meta Quest 2

Software:
- [x] One Drive
- [x] Unity Hub (De preferencia 3.x.x)
- [x] Unity 2021.3.8f1 
- [x] Android SDK
- [x] Aplicaci贸n Oculus Escritorio
- [x] Aplicaci贸n Oculus Dispositivo M贸vil 


### Instrucciones para configurar ambiente de trabajo: 

1. **Unity Hub**: Para instalar Unity, se debe dirigir a la p谩gina de Unity e instalar [Unity Hub](https://unity.com/download). Asegurese de elegir el archivo correspondiente a su sistema operativo.

2. **Unity 2021.3.8f1**: Una vez tenga instalado Unity Hub en su computador, dirijase a [esta pagina](https://unity.com/releases/editor/archive) y seleccione la version solicitada de unity, en este caso la 2021.3.8. Haga click en la opci贸n de Unity Hub para instalar.
![imagen](https://user-images.githubusercontent.com/53950535/205778534-3322b416-9c5f-4c03-93f2-db4ac49ccf45.png)

3. **Android SDK**: Al seleccionar la opci贸n de Unity Hub en el 煤ltimo paso, se abrir谩 su aplicaci贸n de Unity Hub con m谩s detalles y opciones para instalar la versi贸n solicitada de Unity. En esta pesta帽a, seleccione las opciones de *Android Build Support* como se muestra en la imagen de abajo y de click en continuar.
![imagen](https://user-images.githubusercontent.com/53950535/205779138-c3c68cf4-cb0a-4c8b-aeaa-e33dd536ce56.png)

4. **Oculus Escritorio**: Descargue e instale la aplicaci贸n de [Oculus para escritorio](https://www.meta.com/quest/setup/). Una vez iniciada la aplicaci贸n, verifique que la conexi贸n entre su dispositivo Quest 2 y escritorio funcionan al conectar estos y verificar la secci贸n de dispositivos. En esta se deber铆a mostrar el dispositivo y el estado "conectado".

5. En caso de que no tenga una cuenta de desarrollador y no pertenezca a ninguna organizaci贸n, dirijase a https://dashboard.oculus.com/organizations/create/ y diligencie la informaci贸n necesaria para crear una organizaci贸n. 

6. **Oculus M贸vil**: Descargue e instale la aplicaci贸n de Oculus en su dispositivo m贸vil. Siga las instrucciones en el dispositivo para iniciar sesi贸n con su cuenta de desarrollador de Oculus. En el apartado de configuraciones, active el modo de desarrollador.

**Una vez se sigan estos pasos de configuraci贸n, se puede seguir a descargar e importar el proyecto en Unity**

### Instrucciones para descargar e importar el proyecto de Wizard Chess en Unity:

1. Descargue el proyecto del link de [One Drive](https://uniandes-my.sharepoint.com/:u:/g/personal/ne_calero_uniandes_edu_co/ESZ88uLHwVFEsLfimzPOjNcBll7ghLD3oF44k1GRF6342w?e=DxTGxP)
2. Descromprima el proyecto en la carpeta que desea utilizar
3. Desde Unity Hub, seleccione la opci贸n de abrir un nuevo proyecto y seleccione el directorio donde descarg贸 el proyecto.
![imagen](https://user-images.githubusercontent.com/53950535/205788029-d310abf7-adf6-45e6-a950-a93717fb9a86.png)

### Instrucciones para ejecutar el proyecto de Wizard Chess desde Unity:

1. Conecte el dispositivo Quest 2 a su computador y verifique la conexi贸n de este mediante la aplicaci贸n de Oculus de escritorio. 

2. Abra el proyecto en Unity

3. Abra *File* -> *Build and Run* 

4. Verifique que la configuraci贸n de las escenas es igual a la que se muestra a continuaci贸n:
 
![imagen](https://user-images.githubusercontent.com/53950535/205791449-e1e15898-dbe8-4065-b0e8-4e0831dd252f.png)

6. Verifique que la configuraci贸n adicional es igual a la que se muestra a continuaci贸n:
![imagen](https://user-images.githubusercontent.com/53950535/205793196-0eb5f32f-09e7-4fef-aa5b-c27e4ca7479e.png)

7. Finalmente, de click en el bot贸n Build and Run para construir el APK y ejecutarlo desde su dispositivo. 

### Instalar con APK
Para instalar el APK, se debe tener instalado [SIDEQUEST](https://sidequestvr.com/) en el computador donde se encuentra el APK de Wizard Chess. Una vez se tenga configurado SIDEQUEST, se debe conectar el casco de realidad virtual Quest 2 al computador y verificar su conexi贸n en la aplicaci贸n SIDEQUEST. Luego, se debe seleccionar la opci贸n de 鈥淚nstalar archivo APK desde computador鈥? y seleccionar el APK de Wizard Chess. Al finalizar, la aplicaci贸n se puede encontrar en la secci贸n de 鈥淔uentes desconocidas鈥? del Quest 2. 

### Instrucciones de juego

- Para iniciar la partida, haga click en el bot贸n A

- Para moverse por las distintas zonas del tablero, haga click en el bot贸n X 

- Para activar la funcionalidad de movimiento de fichas por medio de comandos de voz, se debe oprimir y mantener el bot贸n *Right Grip* hasta que termine de dictar el movimiento. El comando de voz debe seguir la estructura: 

  (Ficha) (Posici贸n actual) (Posici贸n deseada)
  
  Un ejemplo de esto ser铆a decir el comando 鈥淧e贸n B2 B3鈥? para mover el pe贸n de la posici贸n inicial B2 a la posici贸n deseada B3 y as铆 iniciar la partida
  
- Para mover manualmente una ficha, mantenga oprimido el bot贸n A mientras apunta a una ficha con su control derecho. Mueva la ficha hasta la posici贸n deseada y suelte el bot贸n A para confirmar su movimiento




