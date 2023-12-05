# Documentación del proyecto Havana_Club_International SJ


## 1. INTRODUCCIÓN

### 1.1 Propósito

El propósito de este informe es documentar los aspectos técnicos referidos a las herramientas utilizadas en la implementación de la aplicación  y   registrar los diferentes diagramas que componen el proceso de la línea de llenado y vaciado de barriles de la empresa Havana Club de La Habana. La aplicación desarrollada por el proveedor Ekinsa, tiene como objetivo principal, captar de forma automática en una base de datos la información asociada al pesaje de las paletas que intervienen en el proceso.

## 2. DESARROLLO

### 2.1 Lista de dependencias del sistema

Framework 
.NetFramework 4.8: Es un entorno de ejecución administrado para Windows que proporciona diversos servicios a las aplicaciones en ejecución. Consta de dos componentes principales: Common Language Runtime (CLR), que es el motor de ejecución que controla las aplicaciones en ejecución, y la biblioteca de clases de .NET Framework, que proporciona una biblioteca de código probado y reutilizable al que pueden llamar los desarrolladores desde sus propias aplicaciones. 
Bibliotecas de terceros
DevExpress: Es una herramienta que ofrece a los desarrolladores de aplicaciones una de las suites más completas de componentes de interfaz de usuario (UI) en todas las plataformas . NET tales como Windows Forms, MVC, ASP.NET, Silverlight y Windows XAML.
Nuget.org: Es el administrador de paquetes para . NETO . Permite a los desarrolladores crear, compartir y consumir archivos útiles. Bibliotecas NET. Las herramientas cliente de NuGet brindan la capacidad de producir y consumir estas bibliotecas como "paquetes".

### 2.2 Herramientas Utilizadas

Para la generación de diagramas se utilizó la herramienta Altova UModel Enterprise Edition version 2024.

### 2.3 Diagramas 

**Diagrama de clases:** Este diagrama traza claramente la estructura del sistema al modelar sus clases, atributos, operaciones y relaciones entre objetos.

El diagrama de clases es una herramienta importante en el diseño de software orientado a objetos que ayuda a los desarrolladores a entender la estructura del sistema, definir su estructura, comunicarse de manera efectiva y servir como base para la implementación del sistema.

![ClassDiagram1_1](https://github.com/yoelc745/Documentacion/assets/150778531/835c5c7e-0682-4cf5-bf68-d1937edebb77)
#### _Diagramas de clases/ PLC_

![APp](https://github.com/yoelc745/Documentacion/assets/150778531/6a2ca498-fcba-46fb-a0d5-f4afa804d4d9)
#### _Diagramas de clases/ Havana App_

![Zone](https://github.com/yoelc745/Documentacion/assets/150778531/52a39093-a81a-49d9-8a5f-eda0ec5a03c5)
#### _Diagramas de clases/ Zonas_

**Diagrama de flujo:** Es la representación gráfica del proceso, presentando el modo en que los datos fluyen en el sistema. Se representan todos los pasos, las secuencias y las decisiones del proceso o flujo de trabajo.

El diagrama de flujo de un proyecto es una herramienta importante que ayuda a los miembros del equipo a entender las diferentes etapas y actividades que conforman un proyecto, establecer la secuencia de actividades, identificar las dependencias entre ellas y facilitar la planificación y el control del proyecto.

![LogicaEntradaSecuencial_1 1 0-1](https://github.com/yoelc745/Documentacion/assets/150778531/9a7c1cb7-5bb5-46ab-adbc-ccf7193651c4)
#### _Entrada Secuencial_

![DiagramaLogicaSalidaSecuencial1 1 0-1](https://github.com/yoelc745/Documentacion/assets/150778531/6488be83-4636-4ecd-855c-6bf0a531e8cf)
#### _Salida Secuencial_

![DiagramaLogicaTransfer1 0 0-1](https://github.com/yoelc745/Documentacion/assets/150778531/ab6daba3-7bd9-4f20-ad6a-f4eff0193018)
#### _Tranfer_

**Diagrama entidad-relación:** Es un tipo de diagrama de flujo que ilustra cómo las "entidades", se relacionan entre sí dentro del sistema.

El diagrama entidad relación de un proyecto es una herramienta importante que ayuda a los miembros del equipo a entender las diferentes entidades que conforman el sistema, establecer las relaciones entre ellas, identificar las dependencias entre ellas y facilitar la comprensión y la comunicación del proyecto.

![Ekinconfig-ER](https://github.com/yoelc745/Documentacion/assets/150778531/153ccba4-de26-494d-bf58-08e022da8a0a)
#### _EkinConfig_

![EkinData](https://github.com/yoelc745/Documentacion/assets/150778531/bd15138d-9920-4890-a549-443d30857de0)
#### _EkinData_

**Diagrama de componentes:** describe la organización y el cableado de los componentes físicos de un sistema.

En resumen, el diagrama de componentes es una herramienta importante que ayuda a los miembros del equipo a entender los diferentes componentes que conforman el sistema, establecer las relaciones entre ellos, identificar las dependencias entre ellos y facilitar la comprensión y la comunicación del proyecto.

![Coponentes-HCI](https://github.com/yoelc745/Documentacion/assets/150778531/320a111b-8c7e-4cad-aecf-05ac766cca69)
#### _HCI Componentes_

**Diagrama de casos de uso:** Permiten visualizar los diferentes tipos de roles en un sistema y cómo esos roles interactúan con el sistema.

En resumen, el diagrama de casos de uso es una herramienta importante que ayuda a los miembros del equipo a entender quiénes son los usuarios del sistema, qué funcionalidades debe tener el sistema para satisfacer sus necesidades, cómo interactúan los usuarios con el sistema y cómo se relacionan las diferentes funcionalidades del sistema con los usuarios.

![Habana Club](https://github.com/yoelc745/Documentacion/assets/150778531/c005d9b0-1ed8-45b1-bc87-29792dc178a3)
#### _HCI Actores_

**Diagrama de secuencia:** muestra la secuencia de mensajes pasados ​​entre objetos . Los diagramas de secuencia también pueden mostrar las estructuras de control entre objetos.

En resumen, el diagrama de secuencia es una herramienta importante que ayuda a los miembros del equipo a entender la secuencia de eventos, el flujo de datos, los objetos involucrados y cómo se produce la interacción entre ellos en un sistema.

![SequenceDiagram BasculaProcess](https://github.com/yoelc745/Documentacion/assets/150778531/95868814-64dd-4196-8bec-4d83a8b21e8d)
#### _Lógica Báscula_

![SequenceDiagram Consola](https://github.com/yoelc745/Documentacion/assets/150778531/79ace27e-44d4-429f-984d-4befbb958e1e)
#### _Lógica Consola_

![SequenceDiagram ZonaLinea](https://github.com/yoelc745/Documentacion/assets/150778531/1c542039-36ce-4dd4-a537-2355f71417c8)
#### _Lógica Zonas_

![SequenceDiagram WriteVariable](https://github.com/yoelc745/Documentacion/assets/150778531/fc92e63c-9d4f-41da-86a8-5a1bb675d9e3)
#### _Lógica PLC_

**Diagrama de actividades: ** El diagrama de actividades es otra herramienta utilizada en el diseño de software para representar el flujo de actividades en un proceso.

En resumen, el diagrama de actividades es una herramienta importante que ayuda a los miembros del equipo a entender las actividades, el orden en que se realizan, las decisiones que se toman, los recursos necesarios y cómo se puede optimizar el proceso.

![ActivityDiagram1](https://github.com/yoelc745/Documentacion/assets/150778531/9d6848f3-c18e-4350-986a-08ff2d3b697b)
#### _HCI Proceso de Linea_

