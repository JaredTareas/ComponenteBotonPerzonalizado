# ComponenteBotonPerzonalizado
Boton bonito con un diseño agradable y totalmente funcional para proyectos 
Es un componente personalizado de botón en Java Swing que ofrece un diseño atractivo y animacion interactica. Este botón incluye características como iconos personalizables, efectos de hover al pasar el mause, animaciones de clic,degradados y reproducción de sonidos al hacer clic.

Características

Iconos Personalizables: Puedes cambiar el icono del botón utilizando una lista de iconos predefinidos.
Efectos de Hover: El botón cambia de color suavemente cuando el mouse está sobre él.
Animaciones de Clic: El botón tiene una animación de rebote al ser presionado.
Reproducción de Sonidos: Puedes reproducir sonidos personalizados al hacer clic en el botón.
Colores Personalizables: Permite personalizar los colores de fondo y el radio de los bordes.

Instrucciones de Uso
crear un nuevo proyecto 
crear un jframeForm 
![image](https://github.com/user-attachments/assets/5e52a423-26a5-4f94-a1e2-6b737d267c5a)

en la paleta de componentes de nuestro jframeForm dar click derecho y nos vamos a dirigir a palette manager
![image](https://github.com/user-attachments/assets/ea231479-a1b8-4865-9fe5-a9bb006df226)

luego añadimos nuestro archivo .jar que se encuentra en la carpeta dist del proyecto componente el archivo se llama "botonBonito.jar"
![image](https://github.com/user-attachments/assets/c0ae2329-152e-436f-bb82-fe11b7a8e600) y solo le damos next y lo agregamos en el lugar que nos acomodemos mas

Métodos y Propiedades Relevantes
Métodos
cambiarIcono(int indice): Cambia el icono del botón según el índice dado.
cambiarSonido(int indice): Cambia el sonido que se reproduce al hacer clic según el índice dado.
setRutaSonido(String rutaSonido): Establece una ruta de sonido personalizada para la reproducción.
setSonidoActivo(boolean sonidoActivo): Activa o desactiva la reproducción de sonidos.


Propiedades
getColorInicio(): Obtiene el color de inicio del gradiente.
setColorInicio(Color colorInicio): Establece el color de inicio del gradiente.
getColorFin(): Obtiene el color final del gradiente.
setColorFin(Color colorFin): Establece el color final del gradiente.
getColorFinHover(): Obtiene el color final del gradiente al hacer hover.
setColorFinHover(Color colorFinHover): Establece el color final del gradiente al hacer hover.
getRadioBorde(): Obtiene el radio de los bordes redondeados.
setRadioBorde(int radioBorde): Establece el radio de los bordes redondeados.


Requisitos
Java Development Kit (JDK) 8 o superior.
Bibliotecas de Java Swing.


Créditos del equipo
Este componente fue elaborado por el equipo numero 7
en la asignatura de topicos avanzados de programación, dirigida por la profesora - Martinez Nieto Adelina
integrantes del equipo:
García García Luis Jared
Bautista Ramirez Amisadai Zuriel 






