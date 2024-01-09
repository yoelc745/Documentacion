# <a id="PLCs_Logger"></a> Class Logger

Namespace: [PLCs](PLCs.md)  
Assembly: PLC.dll  

Clase que proporciona funcionalidades para configurar y gestionar un sistema de registro.

```csharp
public class Logger
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Logger](PLCs.Logger.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Remarks

Permite agregar un dispositivo de registro, configurar opciones de trazado y archivo, y crear instancias de registro.

## Constructors

### <a id="PLCs_Logger__ctor"></a> Logger\(\)

Constructor de la clase Logger.

```csharp
public Logger()
```

#### Remarks

Inicializa una nueva instancia del logger estableciendo el patrón de conversión al patrón predeterminado y activando las opciones del diseño.

## Properties

### <a id="PLCs_Logger_DefaultLayout"></a> DefaultLayout

Diseño predeterminado utilizado para el registro.

```csharp
public PatternLayout DefaultLayout { get; }
```

#### Property Value

 PatternLayout

#### Remarks

Propiedad que devuelve el diseño predeterminado utilizado en el registro de eventos.

### <a id="PLCs_Logger_DefaultPattern"></a> DefaultPattern

Patrón predeterminado utilizado para el registro.

```csharp
public string DefaultPattern { get; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Remarks

Propiedad que devuelve el patrón predeterminado utilizado en el registro de eventos.

## Methods

### <a id="PLCs_Logger_AddAppender_IAppender_"></a> AddAppender\(IAppender\)

Agrega un dispositivo de registro al sistema de registro.

```csharp
public void AddAppender(IAppender appender)
```

#### Parameters

`appender` IAppender

Dispositivo de registro a agregar.

#### Remarks

Método que agrega un dispositivo de registro al sistema de registro actual.

### <a id="PLCs_Logger_Create"></a> Create\(\)

Crea una instancia de registro.

```csharp
public static ILog Create()
```

#### Returns

 ILog

Instancia de registro.

#### Remarks

Método estático que devuelve una instancia de registro con el nombre "PLC_Debug".

