# <a id="SMTPClient_Client"></a> Class Client

Namespace: [SMTPClient](SMTPClient.md)  
Assembly: SMTPClient.dll  

Cliente SMTP que expone las funciones necesarias para el envío de correos

```csharp
public class Client
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Client](SMTPClient.Client.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="SMTPClient_Client__ctor_System_String_System_Int32_System_Boolean_"></a> Client\(string, int, bool\)

Constructor del cliente SMTP

```csharp
public Client(string Host, int Port, bool SSL = false)
```

#### Parameters

`Host` [string](https://learn.microsoft.com/dotnet/api/system.string)

Servidor al cual se conectará el cliente SMTP

`Port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Puerto que usará para la conexión

`SSL` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Especifica si se utilizará SSL para la conexión

## Properties

### <a id="SMTPClient_Client_Status"></a> Status

Especifica si el cliente SMTP está conectado

```csharp
public bool Status { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="SMTPClient_Client_AttachFile_System_String_"></a> AttachFile\(string\)

Añade un archivo al cuerpo del mensaje.

```csharp
public bool AttachFile(string FilePath)
```

#### Parameters

`FilePath` [string](https://learn.microsoft.com/dotnet/api/system.string)

Ruta al archivo a añadir

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SMTPClient_Client_Authenticate_System_String_System_String_"></a> Authenticate\(string, string\)

Autentifica al usuario contra el servidor SMTP

```csharp
public void Authenticate(string Username, string Password)
```

#### Parameters

`Username` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nombre de usuario

`Password` [string](https://learn.microsoft.com/dotnet/api/system.string)

Contraseña

### <a id="SMTPClient_Client_AñadirRemitente_System_String_"></a> AñadirRemitente\(string\)

Especifica el correo remitente

```csharp
public void AñadirRemitente(string To)
```

#### Parameters

`To` [string](https://learn.microsoft.com/dotnet/api/system.string)

Correo al que se enviará

### <a id="SMTPClient_Client_CreateMensaje"></a> CreateMensaje\(\)

Crea un nuevo mensaje para enviar

```csharp
public void CreateMensaje()
```

### <a id="SMTPClient_Client_EnviarEmail"></a> EnviarEmail\(\)

Envía el email.

```csharp
public bool EnviarEmail()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SMTPClient_Client_SetBody_System_String_"></a> SetBody\(string\)

Especifica el cuerpo del mensaje

```csharp
public void SetBody(string Body)
```

#### Parameters

`Body` [string](https://learn.microsoft.com/dotnet/api/system.string)

Cuerpo a escribir del mensaje

### <a id="SMTPClient_Client_SetFrom_System_String_"></a> SetFrom\(string\)

Especifica el correo remite

```csharp
public void SetFrom(string From)
```

#### Parameters

`From` [string](https://learn.microsoft.com/dotnet/api/system.string)

Correo que aparecerá como remite

### <a id="SMTPClient_Client_SetSujeto_System_String_"></a> SetSujeto\(string\)

Especifica el sujeto del mensaje.

```csharp
public void SetSujeto(string Subject)
```

#### Parameters

`Subject` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sujeto a escribir

