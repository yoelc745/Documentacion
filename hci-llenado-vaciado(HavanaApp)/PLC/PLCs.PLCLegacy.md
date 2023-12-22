# <a id="PLCs_PLCLegacy"></a> Class PLCLegacy

Namespace: [PLCs](PLCs.md)  
Assembly: PLC.dll  

Gestiona la comunicación con un PLC legado.

```csharp
public class PLCLegacy
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[PLCLegacy](PLCs.PLCLegacy.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="PLCs_PLCLegacy__ctor_System_String_System_Int16_System_Int16_"></a> PLCLegacy\(string, short, short\)

Inicializa una nueva instancia de la clase PLCLegacy y establece una conexión con el PLC utilizando la dirección IP, el Rack y el Slot especificados.

```csharp
public PLCLegacy(string IP, short Rack, short Slot)
```

#### Parameters

`IP` [string](https://learn.microsoft.com/dotnet/api/system.string)

Dirección IP del PLC.

`Rack` [short](https://learn.microsoft.com/dotnet/api/system.int16)

Número de rack del PLC.

`Slot` [short](https://learn.microsoft.com/dotnet/api/system.int16)

Número de slot del PLC.

## Fields

### <a id="PLCs_PLCLegacy_BufferPLC"></a> BufferPLC

Lista que contiene datos del PLC en el buffer.

```csharp
public List<EstructurasPLC.DatosPLC> BufferPLC
```

#### Field Value

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[EstructurasPLC](PLCs.EstructurasPLC.md).[DatosPLC](PLCs.EstructurasPLC.DatosPLC.md)\>

### <a id="PLCs_PLCLegacy_IsWorkingBuffer"></a> IsWorkingBuffer

Indicador del estado del búfer de trabajo.

```csharp
public bool IsWorkingBuffer
```

#### Field Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="PLCs_PLCLegacy_Log"></a> Log

Logger para registrar información.

```csharp
public ILog Log
```

#### Field Value

 ILog

### <a id="PLCs_PLCLegacy_plc"></a> plc

Controlador PLC.

```csharp
public Plc plc
```

#### Field Value

 Plc

## Methods

### <a id="PLCs_PLCLegacy_Disconnect"></a> Disconnect\(\)

Intenta desconectar el PLC si está actualmente conectado.

```csharp
public bool Disconnect()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Devuelve verdadero si se desconecta correctamente, de lo contrario, falso.

### <a id="PLCs_PLCLegacy_IsConnected"></a> IsConnected\(\)

Verifica si la conexión con el PLC está activa.

```csharp
public bool IsConnected()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Booleano que indica si la conexión está activa (true) o no (false).

### <a id="PLCs_PLCLegacy_OnBufferProcesado_PLCs_EstructurasPLC_DatosPLC_"></a> OnBufferProcesado\(DatosPLC\)

```csharp
protected virtual void OnBufferProcesado(EstructurasPLC.DatosPLC Data)
```

#### Parameters

`Data` [EstructurasPLC](PLCs.EstructurasPLC.md).[DatosPLC](PLCs.EstructurasPLC.DatosPLC.md)

### <a id="PLCs_PLCLegacy_ReadAllVars_SQLHandler_ConfiguracionZona_"></a> ReadAllVars\(ConfiguracionZona\)

Lee todas las variables del PLC especificadas en la configuración de la zona y devuelve un objeto PLCData con los valores obtenidos.

```csharp
public PLCLegacy.PLCData ReadAllVars(ConfiguracionZona ConfigZona)
```

#### Parameters

`ConfigZona` ConfiguracionZona

Configuración de la zona que contiene las direcciones de memoria a leer.

#### Returns

 [PLCLegacy](PLCs.PLCLegacy.md).[PLCData](PLCs.PLCLegacy.PLCData.md)

Objeto PLCData con los valores leídos del PLC.

### <a id="PLCs_PLCLegacy_ReadVariable_System_String_PLCs_PLCLegacy_TipoDato_"></a> ReadVariable\(string, TipoDato\)

Lee el valor de la variable especificada del PLC y devuelve un objeto del tipo especificado por 'Tipo'.

```csharp
public object ReadVariable(string Variable, PLCLegacy.TipoDato Tipo)
```

#### Parameters

`Variable` [string](https://learn.microsoft.com/dotnet/api/system.string)

Variable a leer en el formato 'VarType.Address'.

`Tipo` [PLCLegacy](PLCs.PLCLegacy.md).[TipoDato](PLCs.PLCLegacy.TipoDato.md)

Tipo de dato que se espera obtener de la lectura (Bit, Byte, DWord, Real).

#### Returns

 [object](https://learn.microsoft.com/dotnet/api/system.object)

Objeto con el valor leído del PLC según el tipo especificado.

#### Exceptions

 [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

Se lanza una excepción si hay un error al leer la variable del PLC.

### <a id="PLCs_PLCLegacy_ReadVars_System_String_"></a> ReadVars\(string\)

Lee las variables especificadas en una cadena separada por ';' del PLC y devuelve un objeto PLCData con los valores obtenidos.

```csharp
public PLCLegacy.PLCData ReadVars(string Vars)
```

#### Parameters

`Vars` [string](https://learn.microsoft.com/dotnet/api/system.string)

Cadena de variables a leer en formato 'VarType.Address' separadas por ';'.

#### Returns

 [PLCLegacy](PLCs.PLCLegacy.md).[PLCData](PLCs.PLCLegacy.PLCData.md)

Objeto PLCData con los valores leídos del PLC.

### <a id="PLCs_PLCLegacy_SetBufferMode_System_Boolean_"></a> SetBufferMode\(bool\)

Establece el modo del buffer para el PLC.

```csharp
public void SetBufferMode(bool Status)
```

#### Parameters

`Status` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Estado que indica si el modo de buffer está activado (true) o desactivado (false).

### <a id="PLCs_PLCLegacy_StartBufferMode"></a> StartBufferMode\(\)

Inicia el modo buffer del PLC para la lectura/escritura infinita de variables

```csharp
public void StartBufferMode()
```

#### Remarks

Este método utiliza un bucle para procesar los elementos del buffer PLC, escribiendo o leyendo valores según la operación definida.

#### See Also

[PLCLegacy](PLCs.PLCLegacy.md).[SetBufferMode](PLCs.PLCLegacy.md\#PLCs\_PLCLegacy\_SetBufferMode\_System\_Boolean\_)\([bool](https://learn.microsoft.com/dotnet/api/system.boolean)\), 
[PLCLegacy](PLCs.PLCLegacy.md).[WriteVariable](PLCs.PLCLegacy.md\#PLCs\_PLCLegacy\_WriteVariable\_System\_String\_System\_Object\_)\([string](https://learn.microsoft.com/dotnet/api/system.string), [object](https://learn.microsoft.com/dotnet/api/system.object)\), 
[PLCLegacy](PLCs.PLCLegacy.md).[ReadVariable](PLCs.PLCLegacy.md\#PLCs\_PLCLegacy\_ReadVariable\_System\_String\_PLCs\_PLCLegacy\_TipoDato\_)\([string](https://learn.microsoft.com/dotnet/api/system.string), [PLCLegacy](PLCs.PLCLegacy.md).[TipoDato](PLCs.PLCLegacy.TipoDato.md)\)

### <a id="PLCs_PLCLegacy_WaitForAddressChange_System_String_System_Boolean_"></a> WaitForAddressChange\(string, bool\)

Espera a que una dirección de memoria cambie para continuar con el código.

```csharp
public Task WaitForAddressChange(string Variable, bool Value)
```

#### Parameters

`Variable` [string](https://learn.microsoft.com/dotnet/api/system.string)

Variable que estará escuchando el PLC (ej: M157.0).

`Value` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Valor que espera para continuar con el código.

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="PLCs_PLCLegacy_WriteVariable_System_String_System_Object_"></a> WriteVariable\(string, object\)

Escribe el valor especificado en la variable especificada.

```csharp
public void WriteVariable(string Variable, object value)
```

#### Parameters

`Variable` [string](https://learn.microsoft.com/dotnet/api/system.string)

Variable especificada (ej: M157.0)

`value` [object](https://learn.microsoft.com/dotnet/api/system.object)

Valor a escribir en el PLC.

### <a id="PLCs_PLCLegacy_BufferProcesado"></a> BufferProcesado

Evento que se activa cuando se procesa un buffer.

```csharp
public event EventHandler<EstructurasPLC.DatosPLC> BufferProcesado
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[EstructurasPLC](PLCs.EstructurasPLC.md).[DatosPLC](PLCs.EstructurasPLC.DatosPLC.md)\>

