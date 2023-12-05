# <a id="LectorFEIG_LectorTCP"></a> Class LectorTCP

Namespace: [LectorFEIG](LectorFEIG.md)  
Assembly: LectorFEIGCOM.dll  

Representa una clase que provee métodos para leer y escribir datos desde y hacia un puerto TCP.

```csharp
public class LectorTCP
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LectorTCP](LectorFEIG.LectorTCP.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="LectorFEIG_LectorTCP__ctor"></a> LectorTCP\(\)

```csharp
public LectorTCP()
```

### <a id="LectorFEIG_LectorTCP__ctor_System_Boolean_"></a> LectorTCP\(bool\)

Inicializa una nueva instancia de la clase LectorTCP con la opción de mantener la conexión activa.

```csharp
public LectorTCP(bool WithKeepAlive)
```

#### Parameters

`WithKeepAlive` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si se enviará un comando de keep alive al lector cada segundo.

#### Remarks

Este constructor crea una instancia de la clase ReaderModule y asigna un manejador de eventos al temporizador KeepAlive.

## Fields

### <a id="LectorFEIG_LectorTCP_AntennaAddress"></a> AntennaAddress

La dirección de la antena que se usará para la comunicación con el lector.

```csharp
public byte AntennaAddress
```

#### Field Value

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)

### <a id="LectorFEIG_LectorTCP_DelayAntennas"></a> DelayAntennas

El tiempo de espera en milisegundos entre el cambio de antenas.

```csharp
public int DelayAntennas
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="LectorFEIG_LectorTCP_InventarioAntenaDos"></a> InventarioAntenaDos

Almacena los identificadores de los transpondedores que han sido leídos por la antena dos del lector.

```csharp
public HashSet<string> InventarioAntenaDos
```

#### Field Value

 [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="LectorFEIG_LectorTCP_InventarioAntenaUno"></a> InventarioAntenaUno

Almacena los identificadores de los transpondedores que han sido leídos por la antena uno del lector.

```csharp
public HashSet<string> InventarioAntenaUno
```

#### Field Value

 [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="LectorFEIG_LectorTCP_InventoryTags"></a> InventoryTags

Almacena los identificadores de los transpondedores que han sido leídos por el lector.

```csharp
public HashSet<string> InventoryTags
```

#### Field Value

 [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="LectorFEIG_LectorTCP_NumberOfAntennas"></a> NumberOfAntennas

El número de antenas que tiene el lector.

```csharp
public int NumberOfAntennas
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="LectorFEIG_LectorTCP_PayloadAntenaDos"></a> PayloadAntenaDos

La carga útil en bytes para activar la antena dos del lector.

```csharp
public byte[] PayloadAntenaDos
```

#### Field Value

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

### <a id="LectorFEIG_LectorTCP_PayloadAntenaUno"></a> PayloadAntenaUno

La carga útil en bytes para activar la antena uno del lector.

```csharp
public byte[] PayloadAntenaUno
```

#### Field Value

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

### <a id="LectorFEIG_LectorTCP_TagBlockSize"></a> TagBlockSize

El tamaño de bloque en bytes para leer y escribir datos en los transpondedores.

```csharp
public ulong TagBlockSize
```

#### Field Value

 [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="LectorFEIG_LectorTCP_reader"></a> reader

Representa una instancia de la clase ReaderModule que provee métodos para interactuar con el lector TCP.

```csharp
public ReaderModule reader
```

#### Field Value

 ReaderModule

## Methods

### <a id="LectorFEIG_LectorTCP_AsyncBRMMode"></a> AsyncBRMMode\(\)

Lee el inventario de los transpondedores RFID que se encuentran en el campo del lector usando el modo BRM (Buffer Read Mode) de forma asíncrona.

```csharp
public Task AsyncBRMMode()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Una tarea que representa la operación de lectura.

### <a id="LectorFEIG_LectorTCP_AsyncReadDataFromTag"></a> AsyncReadDataFromTag\(\)

Lee los datos del transpondedor RFID que se encuentra en el campo del lector de forma asíncrona.

```csharp
public Task<string> AsyncReadDataFromTag()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Una tarea que representa la operación de lectura y que contiene una cadena con los datos del transpondedor.

### <a id="LectorFEIG_LectorTCP_AsyncReadInventory"></a> AsyncReadInventory\(\)

Lee el inventario de los transpondedores RFID que se encuentran en el campo del lector de forma asíncrona.

```csharp
public Task AsyncReadInventory()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Una tarea que representa la operación de lectura.

### <a id="LectorFEIG_LectorTCP_AsyncWriteToTag_System_String_"></a> AsyncWriteToTag\(string\)

Escribe los datos en el transpondedor RFID que se encuentra en el campo del lector de forma asíncrona.

```csharp
public Task<bool> AsyncWriteToTag(string Message)
```

#### Parameters

`Message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que se escribirá en el transpondedor.

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Una tarea que representa la operación de escritura y que contiene un valor booleano que indica si la escritura fue exitosa o no.

#### Exceptions

 [TagIntegrityErrorException](LectorFEIG.TagIntegrityErrorException.md)

Se produce si se intenta escribir más de 112 bytes en el transpondedor.

 [ErrorWritingTagException](LectorFEIG.ErrorWritingTagException.md)

Se produce si ocurre un error al escribir en el transpondedor.

### <a id="LectorFEIG_LectorTCP_CheckAndDisconnect"></a> CheckAndDisconnect\(\)

Verifica si el lector está conectado al puerto TCP y lo desconecta en caso de que lo esté.

```csharp
public bool CheckAndDisconnect()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si el lector fue desconectado o no.

### <a id="LectorFEIG_LectorTCP_CheckAndReconnectIfDisconnected"></a> CheckAndReconnectIfDisconnected\(\)

Verifica si el lector está conectado al puerto TCP y lo reconecta en caso de que no lo esté.

```csharp
public bool CheckAndReconnectIfDisconnected()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si el lector está conectado o no.

### <a id="LectorFEIG_LectorTCP_ClearMUXBuffer"></a> ClearMUXBuffer\(\)

Limpia el búfer del multiplexor de antenas del lector.

```csharp
public void ClearMUXBuffer()
```

### <a id="LectorFEIG_LectorTCP_ClearTag"></a> ClearTag\(\)

Borra los datos del transpondedor RFID que se encuentra en el campo del lector de forma asíncrona.

```csharp
public Task ClearTag()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Una tarea que representa la operación de borrado.

#### Exceptions

 [TagIntegrityErrorException](LectorFEIG.TagIntegrityErrorException.md)

Se produce si se intenta escribir más de 112 bytes en el transpondedor.

 [ErrorWritingTagException](LectorFEIG.ErrorWritingTagException.md)

Se produce si ocurre un error al escribir en el transpondedor.

### <a id="LectorFEIG_LectorTCP_CombineByteArrays_System_Byte___System_Byte___"></a> CombineByteArrays\(byte\[\], byte\[\]\)

Combina dos matrices de bytes en una sola matriz de bytes.

```csharp
public static byte[] CombineByteArrays(byte[] First, byte[] Second)
```

#### Parameters

`First` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

La primera matriz de bytes.

`Second` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

La segunda matriz de bytes.

#### Returns

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

Una matriz de bytes que contiene los elementos de las dos matrices de bytes originales.

### <a id="LectorFEIG_LectorTCP_Connect_System_String_System_Int32_"></a> Connect\(string, int\)

Conecta el lector al puerto TCP especificado.

```csharp
public bool Connect(string IP, int Port)
```

#### Parameters

`IP` [string](https://learn.microsoft.com/dotnet/api/system.string)

La dirección IP del lector.

`Port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El puerto TCP del lector.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si la conexión fue exitosa o no.

### <a id="LectorFEIG_LectorTCP_Disconnect"></a> Disconnect\(\)

Desconecta el lector del puerto TCP.

```csharp
public void Disconnect()
```

### <a id="LectorFEIG_LectorTCP_EnableMUXMode_System_Int32_System_Int32_"></a> EnableMUXMode\(int, int\)

Habilita el modo multiplexor de antenas para el lector.

```csharp
public void EnableMUXMode(int AntennasNumber, int DelayBetweenAntennas)
```

#### Parameters

`AntennasNumber` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El número de antenas que tiene el lector.

`DelayBetweenAntennas` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El tiempo de espera en milisegundos entre el cambio de antenas.

### <a id="LectorFEIG_LectorTCP_GetDataFromTag_System_String_"></a> GetDataFromTag\(string\)

Obtiene los datos del transpondedor RFID que tiene el identificador dado.

```csharp
public string GetDataFromTag(string IDD)
```

#### Parameters

`IDD` [string](https://learn.microsoft.com/dotnet/api/system.string)

El identificador del transpondedor.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene los datos del transpondedor.

### <a id="LectorFEIG_LectorTCP_GetErrorCode"></a> GetErrorCode\(\)

Devuelve el último texto de estado de error del lector.

```csharp
public string GetErrorCode()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene el último texto de estado de error del lector.

### <a id="LectorFEIG_LectorTCP_GetStatus"></a> GetStatus\(\)

Devuelve el último texto de estado del lector.

```csharp
public string GetStatus()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que contiene el último texto de estado del lector.

### <a id="LectorFEIG_LectorTCP_IsConnected"></a> IsConnected\(\)

Indica si el lector está conectado al puerto TCP o no.

```csharp
public bool IsConnected()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica el estado de conexión del lector.

### <a id="LectorFEIG_LectorTCP_OnAntenaReconectada_System_Boolean_"></a> OnAntenaReconectada\(bool\)

```csharp
protected virtual void OnAntenaReconectada(bool Reconectada)
```

#### Parameters

`Reconectada` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="LectorFEIG_LectorTCP_OnTransponderReconocido_System_Collections_Generic_HashSet_System_String__"></a> OnTransponderReconocido\(HashSet<string\>\)

```csharp
protected virtual void OnTransponderReconocido(HashSet<string> Transponder)
```

#### Parameters

`Transponder` [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="LectorFEIG_LectorTCP_ReadInventory_System_Boolean_"></a> ReadInventory\(bool\)

Lee el inventario de los transpondedores RFID que se encuentran en el campo del lector y devuelve un conjunto de cadenas con los identificadores de los transpondedores.

```csharp
public HashSet<string> ReadInventory(bool Return)
```

#### Parameters

`Return` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si se devolverá el conjunto de cadenas o no.

#### Returns

 [HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Un conjunto de cadenas que contienen los identificadores de los transpondedores.

### <a id="LectorFEIG_LectorTCP_ReadInventory"></a> ReadInventory\(\)

Lee el inventario de los transpondedores RFID que se encuentran en el campo del lector y almacena los identificadores de los transpondedores en la propiedad InventoryTags.

```csharp
public void ReadInventory()
```

### <a id="LectorFEIG_LectorTCP_ReadMUX"></a> ReadMUX\(\)

Lee el inventario de los transpondedores RFID que se encuentran en el campo del lector usando el multiplexor de antenas.

```csharp
public Task<HashSet<string>> ReadMUX()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

Una tarea que representa la operación de lectura y que contiene un conjunto de cadenas con los identificadores de los transpondedores.

### <a id="LectorFEIG_LectorTCP_ReconnectReader"></a> ReconnectReader\(\)

Reconecta el lector al puerto TCP.

```csharp
public void ReconnectReader()
```

### <a id="LectorFEIG_LectorTCP_StopBRMMode"></a> StopBRMMode\(\)

Detiene el modo BRM del lector y limpia el búfer y la cola de lectura.

```csharp
public void StopBRMMode()
```

### <a id="LectorFEIG_LectorTCP_StringToByteArray_System_String_"></a> StringToByteArray\(string\)

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

### <a id="LectorFEIG_LectorTCP_WriteToTag_System_String_"></a> WriteToTag\(string\)

Escribe los datos en el transpondedor RFID que se encuentra en el campo del lector.

```csharp
[HandleProcessCorruptedStateExceptions]
public (bool Estado, string Error) WriteToTag(string Message)
```

#### Parameters

`Message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que se escribirá en el transpondedor.

#### Returns

 \([bool](https://learn.microsoft.com/dotnet/api/system.boolean) [Estado](https://learn.microsoft.com/dotnet/api/system.valuetuple\-system.boolean,system.string\-.estado), [string](https://learn.microsoft.com/dotnet/api/system.string) [Error](https://learn.microsoft.com/dotnet/api/system.valuetuple\-system.boolean,system.string\-.error)\)

Una tupla que contiene un valor booleano que indica si la escritura fue exitosa o no, y una cadena que contiene el texto de error en caso de que haya ocurrido alguno.

#### Exceptions

 [TagIntegrityErrorException](LectorFEIG.TagIntegrityErrorException.md)

Se produce si se intenta escribir más de 112 bytes en el transpondedor.

### <a id="LectorFEIG_LectorTCP_AntenaReconectada"></a> AntenaReconectada

Evento que envía el RFID cuando se ha reconectado.

```csharp
public event EventHandler<bool> AntenaReconectada
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="LectorFEIG_LectorTCP_TransponderReconocido"></a> TransponderReconocido

Evento que envía el RFID cuando se han reconocido transponders.

```csharp
public event EventHandler<HashSet<string>> TransponderReconocido
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[HashSet](https://learn.microsoft.com/dotnet/api/system.collections.generic.hashset\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

