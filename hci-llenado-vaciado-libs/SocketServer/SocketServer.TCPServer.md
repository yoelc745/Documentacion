# <a id="SocketServer_TCPServer"></a> Class TCPServer

Namespace: [SocketServer](SocketServer.md)  
Assembly: SocketServer.dll  

Define una clase que representa un servidor TCP que puede aceptar, leer y escribir datos de un cliente.

```csharp
public class TCPServer
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TCPServer](SocketServer.TCPServer.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="SocketServer_TCPServer__ctor_System_String_System_Int32_"></a> TCPServer\(string, int\)

Crea una instancia de un servidor TCP que escucha en una dirección IP y un puerto especificados.

```csharp
public TCPServer(string Host, int Port)
```

#### Parameters

`Host` [string](https://learn.microsoft.com/dotnet/api/system.string)

La dirección IP del servidor en formato de cadena.

`Port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El número de puerto del servidor.

## Properties

### <a id="SocketServer_TCPServer_GUIDConexion"></a> GUIDConexion

Obtiene o establece el identificador único de la conexión con el cliente.

```csharp
public string GUIDConexion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="SocketServer_TCPServer_CheckClientStatus"></a> CheckClientStatus\(\)

Comprueba el estado de conexión del cliente y lo cierra y libera si está desconectado.

```csharp
public bool CheckClientStatus()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Un valor booleano que indica si el cliente está conectado, True si está conectado, False en caso contrario.

### <a id="SocketServer_TCPServer_OnClientConnected_System_Net_Sockets_TcpClient_"></a> OnClientConnected\(TcpClient\)

Invoca el evento ClientConnected con el cliente conectado como argumento.

```csharp
protected virtual void OnClientConnected(TcpClient e)
```

#### Parameters

`e` [TcpClient](https://learn.microsoft.com/dotnet/api/system.net.sockets.tcpclient)

El objeto TcpClient que representa al cliente conectado.

### <a id="SocketServer_TCPServer_OnDataRecieved_System_String_"></a> OnDataRecieved\(string\)

```csharp
protected virtual void OnDataRecieved(string e)
```

#### Parameters

`e` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SocketServer_TCPServer_ReadData"></a> ReadData\(\)

Lee datos del cliente conectado y los devuelve como una cadena de texto.

```csharp
public string ReadData()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena de texto que contiene los datos leídos.

### <a id="SocketServer_TCPServer_StartReadingAsync_System_Int32_"></a> StartReadingAsync\(int\)

Inicia una tarea asincrónica que lee datos del cliente conectado cada cierto intervalo de milisegundos, y lanza el evento OnDataReceived si detecta nuevos datos.

```csharp
public Task StartReadingAsync(int MillisecondsDelay)
```

#### Parameters

`MillisecondsDelay` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El número de milisegundos que se espera entre cada lectura.

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Una tarea que se completa cuando se cierra o se pierde la conexión con el cliente.

### <a id="SocketServer_TCPServer_StopReadingAsync"></a> StopReadingAsync\(\)

Detiene la lectura asíncrona de datos.

```csharp
public void StopReadingAsync()
```

### <a id="SocketServer_TCPServer_WaitForClient"></a> WaitForClient\(\)

Espera de forma asincrónica a que un cliente se conecte al servidor y genera el evento OnClientConnected cuando se conecte.

```csharp
public Task WaitForClient()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Una tarea que se completa cuando se establece la conexión con el cliente.

### <a id="SocketServer_TCPServer_WriteData_System_String_"></a> WriteData\(string\)

Escribe datos en el flujo de datos del cliente conectado.

```csharp
public void WriteData(string Data)
```

#### Parameters

`Data` [string](https://learn.microsoft.com/dotnet/api/system.string)

Los datos que se quieren enviar al cliente.

### <a id="SocketServer_TCPServer_ClientConnected"></a> ClientConnected

Evento generado cuando se conecta un cliente en el socket.

```csharp
public event EventHandler<TcpClient> ClientConnected
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[TcpClient](https://learn.microsoft.com/dotnet/api/system.net.sockets.tcpclient)\>

### <a id="SocketServer_TCPServer_DataRecieved"></a> DataRecieved

Evento generado cuando se obtienen nuevos datos en el socket.

```csharp
public event EventHandler<string> DataRecieved
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

