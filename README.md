# Documentación para la implementación de un monitor de material particulado móvil

_Proyecto coparticipativo con la Secretaría de Ambiente de la provincia de Córdoba y la Facultad de Ciencias Exactas, físicas y Naturales de la Universidad Nacional de Córdoba._

![alt text](https://github.com/ezerosso/ProyectoIntegrador/blob/main/images/dispositivoFinal.jpg)

(Después pondremos una foto con el plot bien termiando.)

## Guía práctica para la implementación del proyecto

A continuación se explicará la estructura del presente repositorio y los pasos a seguir. 

### En la carpeta Hardware se encuentra:
* Los componentes electrónicos necesarias para el dispositivo y dónde conseguirlos
* Implementación del circuito impreso PCB
* Implementación del Gabinete

### Instalación de software necesario:

* [Visual Studio Code](https://code.visualstudio.com/download) - Editor de código fuente donde se podrá visualizar el proyecto en su totalidad.

* [Extensión PlatformIo](https://platformio.org/install/ide?install=vscode) - Entorno de desarrollo Integrado (IDE) desde donde se podrá cargar el programa a la placa de desarollo.

* [Git Bash](https://gitforwindows.org/) - Software de control de versiones, necesario para [clonar el repositorio de GitHub](https://docs.github.com/es/repositories/creating-and-managing-repositories/cloning-a-repository) en nuestra PC. 

Una vez hecho esto, desde el VSC, se debe abrir el proyecto _(Archivo -> Abrir carpeta -> Buscamos en la carpeta donde se clonó el repositorio)._

A continuación se debe conectar mediante un cable USB la placa NodeMCU a cualquier puerto USB de nuestra PC. Luego cargamos el código a la placa:

![alt text](https://github.com/ezerosso/ProyectoIntegrador/blob/main/images/cargarPrograma.png)

Por último insertamos la Placa en los conectores de nuestra PCB como se indica en la carpeta Hardware.

Si se desea realizar una prueba preliminar, previo al montaje final, se puede realizar conexionando el circuito en una [protoboard](http://www.circuitoselectronicos.org/2007/10/el-protoboard-tableta-de-experimentacin.html) siguiendo el esquemático mostrado el el archivo esquematico.pdf que se encuentra en la carpeta KiCad (_Hardware -> Circuito impreso -> KiCad_).

![alt text](https://github.com/ezerosso/ProyectoIntegrador/blob/main/images/circuitoProtoboard.jpg)

<!-- *_Referencias_*

- https://programarfacil.com/blog/arduino-blog/platformio/

 -->


 # Manual de uso

 ### Acceso externo: Carga, Encendido y Extracción de microSD

Una vez se tenga el equipo implementado, en su parte inferior se tendrá acceso al switch on-off, a la extracción de la memoria microSD y al pin de carga:

![alt text](https://github.com/ezerosso/ProyectoIntegrador/blob/main/images/accesoExternoMonitor.jpg)

 Los datos son guardados en archivos .csv que pueden ser visualizados en planillas de cálculo como el programa libre office, acomodados por día y agrupados en la carpeta Monitor PM.

 ![alt text](https://github.com/ezerosso/ProyectoIntegrador/blob/main/images/visualizacionDatosPlanilla.png)

(mostrar como se guardan los datos, como extraerlos y qué hacer con ellos)
(CONSULTAR A LA VIVI QUE HACER CON LOS DATOS)

 ### Pantallas y significados


