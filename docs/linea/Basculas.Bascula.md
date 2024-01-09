# <a id="Basculas_Bascula"></a> Class Bascula

Namespace: [Basculas](Basculas.md)  
Assembly: Bascula.dll  

Clase que representa una báscula con funcionalidades de conexión y comunicación.

```csharp
public class Bascula
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Bascula](Basculas.Bascula.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="Basculas_Bascula__ctor_System_String_System_Int32_ILog_"></a> Bascula\(string, int, ILog\)

Conecta con la báscula y expone las funcionalidades básicas.

```csharp
public Bascula(string IP, int Port, ILog logger = null)
```

#### Parameters

`IP` [string](https://learn.microsoft.com/dotnet/api/system.string)

IP en la cual se encuentra la báscula

`Port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Puerto en el cual se encuentra la báscula

`logger` ILog

Log handler de log4net

## Properties

### <a id="Basculas_Bascula_Debug"></a> Debug

Especifica si devuelve datos de debug. (por defecto false)

```csharp
public bool Debug { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="Basculas_Bascula_DelayLectura"></a> DelayLectura

Especifica el tiempo de retraso en milisegundos en leer los datos recibidos. (por defecto 100ms)

```csharp
public int DelayLectura { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="Basculas_Bascula_Estable"></a> Estable

Especifica si la báscula está estable.

```csharp
public bool Estable { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="Basculas_Bascula_ComprobarConexion_System_Boolean_"></a> ComprobarConexion\(bool\)

Comprueba si la báscula está conectada correctamente y la reconecta si se especifica.

```csharp
public bool ComprobarConexion(bool Reconnect)
```

#### Parameters

`Reconnect` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Booleano

### <a id="Basculas_Bascula_ComprobarEstabilidad"></a> ComprobarEstabilidad\(\)

Verifica si la balanza está en un estado estable.

```csharp
public bool ComprobarEstabilidad()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Booleano que indica si la balanza está estable.

### <a id="Basculas_Bascula_ConectarBascula"></a> ConectarBascula\(\)

Intenta establecer una conexión con la balanza.

```csharp
public void ConectarBascula()
```

#### Remarks

Si la conexión tiene éxito, establece el estado de conexión a verdadero.
Si falla, establece el estado de conexión a falso y registra un error en el logger si está disponible.

### <a id="Basculas_Bascula_Disconnect"></a> Disconnect\(\)

Desconecta y libera los recursos asociados al socket de la balanza.

```csharp
public void Disconnect()
```

### <a id="Basculas_Bascula_EnviarComando_System_Byte___"></a> EnviarComando\(byte\[\]\)

Envía el comando especificado a la báscula.

```csharp
public Task<string> EnviarComando(byte[] Comando)
```

#### Parameters

`Comando` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

Comando de la báscula

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

String con la respuesta

### <a id="Basculas_Bascula_OnPesajeEstable_System_Int32_"></a> OnPesajeEstable\(int\)

```csharp
protected virtual void OnPesajeEstable(int peso)
```

#### Parameters

`peso` [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="Basculas_Bascula_OnPeso_System_Int32_"></a> OnPeso\(int\)

```csharp
protected virtual void OnPeso(int peso)
```

#### Parameters

`peso` [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="Basculas_Bascula_OnSalidaPeso_System_Boolean_"></a> OnSalidaPeso\(bool\)

```csharp
protected virtual void OnSalidaPeso(bool SalidaPeso)
```

#### Parameters

`SalidaPeso` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="Basculas_Bascula_ReconectarBascula"></a> ReconectarBascula\(\)

Intenta reconectar la balanza de manera continua.

```csharp
public Task ReconectarBascula()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Tarea asincrónica de la reconexión.

#### Remarks

Si no puede conectar, continuará reintentando cada segundo.

### <a id="Basculas_Bascula_DetectadoPeso"></a> DetectadoPeso

Devuelve el valor de la báscula cuando se ha detectado peso.

```csharp
public event EventHandler<int> DetectadoPeso
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="Basculas_Bascula_PesajeEstable"></a> PesajeEstable

Devuelve el valor de la báscula después de estabilizarse pesando.

```csharp
public event EventHandler<int> PesajeEstable
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="Basculas_Bascula_SalidaPeso"></a> SalidaPeso

Evento lanzado cuando el peso sale de la báscula.

```csharp
public event EventHandler<bool> SalidaPeso
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

