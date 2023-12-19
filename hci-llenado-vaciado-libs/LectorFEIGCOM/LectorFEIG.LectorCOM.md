# <a id="LectorFEIG_LectorCOM"></a> Class LectorCOM

Namespace: [LectorFEIG](LectorFEIG.md)  
Assembly: LectorFEIGCOM.dll  

Representa una clase que provee métodos para leer y escribir datos desde y hacia un puerto COM.

```csharp
public class LectorCOM
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LectorCOM](LectorFEIG.LectorCOM.md)

<details open>
  <summary> Methods </summary>

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)
</details>

## Remarks

Esta clase usa la clase System.IO.Ports.SerialPort para comunicarse con el puerto COM.

## Constructors

### <a id="LectorFEIG_LectorCOM__ctor"></a> LectorCOM\(\)

Inicializa una nueva instancia de la clase LectorCOM.

```csharp
public LectorCOM()
```

#### Remarks

Este constructor agrega un manejador de excepciones no controladas al dominio actual de la aplicación y crea un temporizador para verificar el estado de conexión del lector cada segundo.

## Fields

### <a id="LectorFEIG_LectorCOM_IdsRfid"></a> IdsRfid

Almacena los identificadores únicos de las etiquetas RFID que han sido leídas por el lector.

```csharp
public HashSet<string> IdsRfid
```

#### Field Value

 [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="LectorFEIG_LectorCOM_isConnected"></a> isConnected

Indica si el lector está conectado al puerto COM o no.

```csharp
public bool isConnected
```

#### Field Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="LectorFEIG_LectorCOM_reader"></a> reader

Representa una instancia de la clase ReaderModule que provee métodos para interactuar con el lector FEIG.

```csharp
public ReaderModule reader
```

#### Field Value

 ReaderModule

## Methods

### <a id="LectorFEIG_LectorCOM_AsyncClearTransponderData"></a> AsyncClearTransponderData\(\)

Borra los datos del transpondedor RFID que se encuentra en el campo del lector de forma asíncrona.

```csharp
public Task<bool> AsyncClearTransponderData()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Una tarea que representa la operación de borrado y que contiene un valor booleano que indica si el borrado fue exitoso o no.

### <a id="LectorFEIG_LectorCOM_AsyncReadDatosTransponder"></a> AsyncReadDatosTransponder\(\)

Lee los datos del transponder RFID que se encuentra en el campo del lector de forma asíncrona.

```csharp
public Task<string> AsyncReadDatosTransponder()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Una tarea que representa la operación de lectura y que contiene una cadena con los datos del transponder en formato UTF-8.

### <a id="LectorFEIG_LectorCOM_AsyncReadInventory"></a> AsyncReadInventory\(\)

Lee el inventario de los transponders RFID que se encuentran en el campo del lector de forma asíncrona.

```csharp
public Task<HashSet<string>> AsyncReadInventory()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

Una tarea que representa la operación de lectura y que contiene un conjunto de cadenas con los identificadores de los transponders.

### <a id="LectorFEIG_LectorCOM_AsyncWriteDatosTransponder_System_String_"></a> AsyncWriteDatosTransponder\(string\)

Escribe los datos en el transpondedor RFID que se encuentra en el campo del lector de forma asíncrona.

```csharp
public Task<bool> AsyncWriteDatosTransponder(string Message)
```

#### Parameters

`Message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que se escribirá en el transpondedor.

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Una tarea que representa la operación de escritura y que contiene un valor booleano que indica si la escritura fue exitosa o no.

### <a id="LectorFEIG_LectorCOM_ClearTransponderData"></a> ClearTransponderData\(\)

Borra los datos del transpondedor RFID que se encuentra en el campo del lector.

```csharp
public bool ClearTransponderData()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si el borrado fue exitoso o no.

#### Exceptions

 [ErrorWritingTagException](LectorFEIG.ErrorWritingTagException.md)

Se produce si ocurre un error al escribir en el transpondedor.

### <a id="LectorFEIG_LectorCOM_CombineByteArrays_System_Byte___System_Byte___"></a> CombineByteArrays\(byte\[\], byte\[\]\)

Combina dos matrices de bytes en una sola matriz de bytes.

```csharp
public byte[] CombineByteArrays(byte[] First, byte[] Second)
```

#### Parameters

`First` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

La primera matriz de bytes.

`Second` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

La segunda matriz de bytes.

#### Returns

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

Una matriz de bytes que contiene los elementos de las dos matrices de bytes originales.

### <a id="LectorFEIG_LectorCOM_Connect_System_String_System_String_System_Int32_"></a> Connect\(string, string, int\)

Conecta el lector al puerto COM especificado con el marco y la velocidad de transmisión dados.

```csharp
[HandleProcessCorruptedStateExceptions]
public void Connect(string COMPort, string Frame, int BaudRate = 115200)
```

#### Parameters

`COMPort` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre del puerto COM al que se conectará el lector.

`Frame` [string](https://learn.microsoft.com/dotnet/api/system.string)

El marco de datos que se usará para la comunicación.

`BaudRate` [int](https://learn.microsoft.com/dotnet/api/system.int32)

La velocidad de transmisión en bits por segundo. El valor predeterminado es 115200.

#### Exceptions

 [ErrorConnectingException](LectorFEIG.ErrorConnectingException.md)

Se produce si no se puede conectar al lector después de cinco intentos.

### <a id="LectorFEIG_LectorCOM_Disconnect"></a> Disconnect\(\)

Desconecta el lector del puerto COM.

```csharp
public void Disconnect()
```

### <a id="LectorFEIG_LectorCOM_GetError"></a> GetError\(\)

Devuelve el último texto de estado de error del lector.

```csharp
public string GetError()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene el último texto de estado de error del lector.

### <a id="LectorFEIG_LectorCOM_GetInfo"></a> GetInfo\(\)

Devuelve el ID del dispositivo del lector en formato hexadecimal.

```csharp
public string GetInfo()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene el ID del dispositivo del lector en formato hexadecimal.

### <a id="LectorFEIG_LectorCOM_GetStatus"></a> GetStatus\(\)

Devuelve el último texto de estado del lector.

```csharp
public string GetStatus()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene el último texto de estado del lector.

### <a id="LectorFEIG_LectorCOM_IsConnected"></a> IsConnected\(\)

Indica si el lector está conectado al puerto COM o no.

```csharp
public bool IsConnected()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica el estado de conexión del lector.

### <a id="LectorFEIG_LectorCOM_LeerDatosTransponder"></a> LeerDatosTransponder\(\)

Lee los datos del transponder RFID que se encuentra en el campo del lector.

```csharp
public string LeerDatosTransponder()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene los datos del transponder en formato UTF-8.

### <a id="LectorFEIG_LectorCOM_LogFeig_System_String_System_String_"></a> LogFeig\(string, string\)

Registra un mensaje en un archivo con una marca de tiempo y un prefijo.

```csharp
public static void LogFeig(string FileName, string Message)
```

#### Parameters

`FileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre del archivo al que se agregará el mensaje.

`Message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje a registrar.

### <a id="LectorFEIG_LectorCOM_RFReset"></a> RFReset\(\)

Reinicia el módulo de radiofrecuencia del lector.

```csharp
public void RFReset()
```

### <a id="LectorFEIG_LectorCOM_ReadInventory"></a> ReadInventory\(\)

Lee el inventario de los transponders RFID que se encuentran en el campo del lector.

```csharp
public HashSet<string> ReadInventory()
```

#### Returns

 [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Un conjunto de cadenas que contienen los identificadores de los transponders.

### <a id="LectorFEIG_LectorCOM_ReadInventoryLegacy"></a> ReadInventoryLegacy\(\)

Lee el inventario de los transpondedores RFID que se encuentran en el campo del lector usando el método legacy.

```csharp
public void ReadInventoryLegacy()
```

### <a id="LectorFEIG_LectorCOM_StringToByteArray_System_String_"></a> StringToByteArray\(string\)

Convierte una cadena hexadecimal en una matriz de bytes.

```csharp
public static byte[] StringToByteArray(string hex)
```

#### Parameters

`hex` [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena hexadecimal que se convertirá.

#### Returns

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

Una matriz de bytes que contiene los valores de los caracteres hexadecimales.

### <a id="LectorFEIG_LectorCOM_WriteDatosTransponder_System_String_"></a> WriteDatosTransponder\(string\)

Escribe los datos en el transpondedor RFID que se encuentra en el campo del lector.

```csharp
public bool WriteDatosTransponder(string Message)
```

#### Parameters

`Message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que se escribirá en el transpondedor.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si la escritura fue exitosa o no.

