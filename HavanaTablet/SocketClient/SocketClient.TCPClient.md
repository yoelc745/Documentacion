# <a id="SocketClient_TCPClient"></a> Class TCPClient

Namespace: [SocketClient](SocketClient.md)  
Assembly: SocketClient.dll  

Cliente TCP que se conectará a la aplicación de lectura RFID

```csharp
public class TCPClient
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TCPClient](SocketClient.TCPClient.md)

<details open>
  
<summary>Inherited Members</summary>

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)
</details>

## Constructors

### <a id="SocketClient_TCPClient__ctor_System_String_System_Int32_"></a> TCPClient\(string, int\)

Conecta el cliente a la dirección especificada

```csharp
public TCPClient(string Host, int Port)
```

#### Parameters

`Host` [string](https://learn.microsoft.com/dotnet/api/system.string)

IP o servidor al cuál conectarse

`Port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Puerto al cuál conectarse

## Methods

### <a id="SocketClient_TCPClient_Connect"></a> Connect\(\)

Función deprecada, no usar

```csharp
public void Connect()
```

### <a id="SocketClient_TCPClient_Disconnect"></a> Disconnect\(\)

Desconecta el cliente TCP del servidor y libera los recursos asociados.

```csharp
public void Disconnect()
```

### <a id="SocketClient_TCPClient_SendData_System_String_"></a> SendData\(string\)

Envía datos al socket para ser recibidos por el servidor.

```csharp
public bool SendData(string Data)
```

#### Parameters

`Data` [string](https://learn.microsoft.com/dotnet/api/system.string)

Una string con los datos a enviar

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

