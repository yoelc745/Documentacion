# Introducción
---------------------------

## Lista de dependencias del sistema

Framework 

- .NetFramework 4.8: Es un entorno de ejecución administrado para Windows que proporciona diversos servicios a las aplicaciones en ejecución. Consta de dos componentes principales: Common Language Runtime (CLR), que es el motor de ejecución que controla las aplicaciones en ejecución, y la biblioteca de clases de .NET Framework, que proporciona una biblioteca de código probado y reutilizable al que pueden llamar los desarrolladores desde sus propias aplicaciones. 

Bibliotecas de terceros

- DevExpress: Es una herramienta que ofrece a los desarrolladores de aplicaciones una de las suites más completas de componentes de interfaz de usuario (UI) en todas las plataformas. NET tales como Windows Forms, MVC, ASP.NET, Silverlight y Windows XAML.

- Nuget.org: Es el administrador de paquetes para .NET. Permite a los desarrolladores crear, compartir y consumir archivos útiles. Bibliotecas NET. Las herramientas cliente de NuGet brindan la capacidad de producir y consumir estas bibliotecas como "paquetes".

| Biblioteca | Versión utilizada | Proyecto en el que se utiliza |
| :--------: | :---------------: | :---------------------------: |
| DbDataReaderMapper| 1.1.0    |   SQLHandler |
| DevExpress.Wpf  | 22.1.5   |   Zonas |
| log4net | 22.0.12   |   HavanaApp, PLC, SQLHandler, Zonas, Utiles |
| MaiKit  | 2.11.1   |   SMTPClient |
| MimeKit  | 2.11.0   |   SMTPClient |
| OxyPlot.Core  | 2.0.0   |   Zonas |
| OxyPlot.WPF  | 2.0.0   |   Zonas |
| Portable.BouncyCastle | 1.8.10   |   SMTPClient |
| S7netplus | 0.13.0  |   PLC |
| Sharp7 | 1.1.75   |   PLC |
| SonarAnalyzer.CSharp | 8.55.0.65544   |   Lector FEIGCOM, ControlConsola |
| BrotliSharpLib | 0.3.3  |   Lector FEIGCOM |
| SqlDataReaderMapper | 1.0.5  |   SQLHandler |

## Herramientas Utilizadas

### Edición y revisión de código

Para la edición e identificación del código se utilizó Visual Studio 2022.
Las principales características de Visual Studio son su multiplataforma, lenguajes de programación, integración con herramientas de desarrollo, depuración avanzada, diseño visual, pruebas automatizadas e integración con la nube.

### Modelado de datos

Para la generación de diagramas se utilizaron herramientas como Altova UModel Enterprise Edition versión 2024, Visual Studio Ultimate 2022, Visual Parading versión web, Draw.io versión colaborativa.

En resumen, el objetivo principal de las herramientas de diseño UML es proporcionar una forma estandarizada y visualmente clara de representar modelos de software, lo que ayuda a los equipos de desarrollo a trabajar en conjunto, acelerar el proceso de desarrollo, reducir errores y diseñar software fácil de entender, mantener y modificar en el futuro.

## Diagramas 

**Diagrama de clases:** El objetivo principal de los diagramas de clase es representar la estructura estática de un sistema orientado a objetos. Estos diagramas muestran las clases que componen el sistema, sus atributos, métodos y las relaciones entre ellas. El objetivo es proporcionar una visión general del sistema y ayudar a los desarrolladores a comprender cómo las diferentes clases interactúan entre sí. Además, los diagramas de clase también pueden ser utilizados para documentar el diseño del sistema y para comunicar ideas entre los miembros del equipo de desarrollo.

![APp](https://github.com/yoelc745/Documentacion/assets/150778531/6772099d-4977-46f8-9e6c-af9535704e2f)
_Diagramas de clases/ Havana App_

![Zona](https://github.com/yoelc745/Documentacion/assets/150778531/33eda5e8-0989-4f37-85f0-c8351d8995d4)
_Diagramas de clases/ Zonas_

![Visor](https://github.com/yoelc745/Documentacion/assets/150778531/1144f0b9-c5a4-4555-b1ae-ade47e3387cd)

_Diagramas de clases/ Visor_


**Diagrama de flujo:** El objetivo principal de los diagramas de flujo es representar gráficamente el flujo de un proceso o procedimiento. Estos diagramas se utilizan para modelar la secuencia de pasos en un proceso, desde el inicio hasta el fin. Los diagramas de flujo permiten identificar los diferentes pasos que se deben seguir en un proceso, así como los posibles caminos alternativos y las decisiones que se deben tomar en cada etapa. Además, los diagramas de flujo también pueden ser utilizados para documentar un proceso y para comunicar ideas entre los miembros del equipo de trabajo. En resumen, el objetivo principal de los diagramas de flujo es proporcionar una vista clara y detallada del proceso y su secuencia de pasos, lo que ayuda a los usuarios a entender cómo funciona el proceso y cómo se deben realizar las diferentes tareas.

![LogicaEntradaSecuencial_1 1 0-1](https://github.com/yoelc745/Documentacion/assets/150778531/9a7c1cb7-5bb5-46ab-adbc-ccf7193651c4)
_Entrada Secuencial_

![DiagramaLogicaSalidaSecuencial1 1 0-1](https://github.com/yoelc745/Documentacion/assets/150778531/6488be83-4636-4ecd-855c-6bf0a531e8cf)
_Salida Secuencial_

![DiagramaLogicaTransfer1 0 0-1](https://github.com/yoelc745/Documentacion/assets/150778531/ab6daba3-7bd9-4f20-ad6a-f4eff0193018)
_Tranfer_

**Diagrama entidad-relación:** El objetivo principal de los diagramas entidad-relación (ER) es representar la estructura de datos de un sistema en términos de entidades, atributos y relaciones entre ellas. Estos diagramas son utilizados para modelar la información que se almacena en una base de datos y para definir las reglas de negocio que rigen el comportamiento del sistema. Los diagramas ER permiten identificar las entidades clave en el sistema, así como las relaciones entre ellas, lo que ayuda a los desarrolladores a comprender cómo los datos se relacionan entre sí y cómo se deben almacenar en la base de datos. Además, los diagramas ER también pueden ser utilizados para documentar el diseño del sistema y para comunicar ideas entre los miembros del equipo de desarrollo.

![ER](https://github.com/yoelc745/Documentacion/assets/150778531/2aa9762a-d7de-4a35-894a-b0234718e959)
_Diagramas/ Entidad Relación_

**Diagrama de componentes:** El objetivo principal de los diagramas de componentes es representar la estructura y las relaciones entre los componentes de un sistema. Estos diagramas son utilizados para modelar la arquitectura de software de un sistema y para describir cómo los componentes se comunican entre sí y con otros sistemas. Los diagramas de componentes permiten identificar los diferentes módulos o componentes que conforman el sistema, así como las interfaces y dependencias entre ellos. Además, los diagramas de componentes también pueden ser utilizados para documentar el diseño del sistema y para comunicar ideas entre los miembros del equipo de desarrollo. 
En resumen, el objetivo principal de los diagramas de componentes es proporcionar una vista clara y detallada de la estructura del sistema y sus componentes, lo que ayuda a los desarrolladores a entender cómo funciona el sistema y cómo se deben implementar los diferentes componentes.

![Coponentes drawio](https://github.com/yoelc745/Documentacion/assets/150778531/08c63023-d53f-4685-8357-57bec727f70a)
_HCI Componentes_

**Diagrama de casos de uso:** El objetivo principal de los diagramas de casos de uso es representar gráficamente los diferentes actores que interactúan con un sistema y los diferentes escenarios de uso que se pueden presentar. Estos diagramas se utilizan para modelar la funcionalidad del sistema desde el punto de vista del usuario, es decir, para identificar las diferentes tareas que se pueden realizar con el sistema y cómo se relacionan entre sí. Los diagramas de casos de uso permiten definir los requisitos funcionales del sistema y establecer una base para el diseño y la implementación del mismo. Además, los diagramas de casos de uso también pueden ser utilizados para documentar el comportamiento del sistema y para comunicar ideas entre los miembros del equipo de trabajo. 
En resumen, el objetivo principal de los diagramas de casos de uso es proporcionar una vista clara y detallada de la funcionalidad del sistema y cómo se relaciona con los usuarios, lo que ayuda a los usuarios a entender cómo utilizar el sistema y cómo se deben realizar las diferentes tareas.

![Habana Club](https://github.com/yoelc745/Documentacion/assets/150778531/c005d9b0-1ed8-45b1-bc87-29792dc178a3)
_HCI Actores_

**Diagrama de secuencia:** El objetivo principal de los diagramas de secuencia es representar gráficamente la interacción entre diferentes objetos o componentes de un sistema en un escenario específico de uso. Estos diagramas se utilizan para modelar el comportamiento del sistema desde el punto de vista de los objetos o componentes que participan en una determinada tarea. Los diagramas de secuencia permiten definir la secuencia de eventos que ocurren durante la ejecución de una tarea, incluyendo la interacción entre los objetos o componentes y los mensajes que se intercambian entre ellos. Además, los diagramas de secuencia también pueden ser utilizados para identificar posibles errores o problemas en la interacción entre los objetos o componentes del sistema, lo que ayuda a mejorar la calidad y eficiencia del mismo. 
En resumen, el objetivo principal de los diagramas de secuencia es proporcionar una vista detallada y clara de cómo interactúan los diferentes objetos o componentes de un sistema en un escenario específico de uso, lo que ayuda a entender mejor el comportamiento del sistema y a identificar posibles mejoras o problemas en su diseño y funcionamiento.

![SequenceDiagram BasculaProcess](https://github.com/yoelc745/Documentacion/assets/150778531/95868814-64dd-4196-8bec-4d83a8b21e8d)


### _Lógica Báscula_

![SequenceDiagram Consola](https://github.com/yoelc745/Documentacion/assets/150778531/79ace27e-44d4-429f-984d-4befbb958e1e)
_Lógica Consola_

![SequenceDiagram ZonaLinea](https://github.com/yoelc745/Documentacion/assets/150778531/1c542039-36ce-4dd4-a537-2355f71417c8)
_Lógica Zonas_

![SequenceDiagram WriteVariable](https://github.com/yoelc745/Documentacion/assets/150778531/fc92e63c-9d4f-41da-86a8-5a1bb675d9e3)
_Lógica PLC_

**Diagrama de actividades:** El objetivo principal de los diagramas de actividades es representar gráficamente el flujo de trabajo o procesos de un sistema, mostrando las actividades y acciones que se realizan en un orden secuencial. Estos diagramas se utilizan para modelar el comportamiento del sistema desde una perspectiva de alto nivel, mostrando cómo se llevan a cabo las actividades y cómo se relacionan entre sí. 

Los diagramas de actividades permiten definir la secuencia de acciones que se llevan a cabo en un proceso, incluyendo las decisiones que se toman y las condiciones que deben cumplirse para avanzar en el flujo de trabajo. Además, los diagramas de actividades también pueden ser utilizados para identificar posibles cuellos de botella o problemas en el proceso, lo que ayuda a mejorar la eficiencia y calidad del mismo. 

En resumen, el objetivo principal de los diagramas de actividades es proporcionar una vista detallada y clara del flujo de trabajo o procesos de un sistema, lo que ayuda a entender mejor su funcionamiento y a identificar posibles mejoras o problemas en su diseño y ejecución.

![Activity-HCI](https://github.com/yoelc745/Documentacion/assets/150778531/68a6f091-16a5-40b3-b73b-53225935e0b1)
_HCI Proceso de Línea_


