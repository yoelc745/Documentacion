# <a id="SQLHandler_ParametrosApp"></a> Class ParametrosApp

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que guarda la configuración de la aplicación.

```csharp
public class ParametrosApp
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ParametrosApp](SQLHandler.ParametrosApp.md)

<details open>
  <summary> Inherited Members </summary>

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)
</details>

## Properties

### <a id="SQLHandler_ParametrosApp_AutograbadoTags"></a> AutograbadoTags

Indica si se debe realizar el autograbado de tags.

```csharp
public bool AutograbadoTags { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_CopiaSeguridadBD"></a> CopiaSeguridadBD

Indica si se debe hacer una copia de seguridad de las bases de datos cada vez que se inicie la aplicación, por defecto False

```csharp
public bool CopiaSeguridadBD { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_EnviarEmailExcepcion"></a> EnviarEmailExcepcion

Indica si debe enviar un email al detectar una excepción no controlada en la aplicación, por defecto True

```csharp
public bool EnviarEmailExcepcion { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_InicioSesion"></a> InicioSesion

Especifica si se inicia sesión antes de acceder a la aplicación, por defecto True

```csharp
public bool InicioSesion { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_MailEnvioLogs"></a> MailEnvioLogs

Indica el email para el envio de logs de error de la aplicación, por defecto "alex@snt.es"

```csharp
public string MailEnvioLogs { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParametrosApp_Maximizado"></a> Maximizado

Indica si se inicia la aplicación maximizada, por defecto True

```csharp
public bool Maximizado { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_MostrarLogPantalla"></a> MostrarLogPantalla

Indica si se debe mostrar la consola de depuración en la aplicación, por defecto False

```csharp
public bool MostrarLogPantalla { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_PararDobleRFID"></a> PararDobleRFID

Especifica si se para la producción cuando se detectan dos transponders en una línea a la vez, por defecto True

```csharp
public bool PararDobleRFID { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ParametrosApp_PasswordSMB"></a> PasswordSMB

Contraseña SMB para la carpeta compartida.

```csharp
public string PasswordSMB { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParametrosApp_PathCarpetaSMB"></a> PathCarpetaSMB

Carpeta en el recurso compartido donde se almacenarán los archivos.

```csharp
public string PathCarpetaSMB { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParametrosApp_PathCopiaBD"></a> PathCopiaBD

Indica el path donde se copiara el backup con la base de datos.

```csharp
public string PathCopiaBD { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParametrosApp_PuertoAplicacionLector"></a> PuertoAplicacionLector

Indica el puerto donde escuchará la aplicación de recepción de transponders, por defecto 50006

```csharp
public int PuertoAplicacionLector { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParametrosApp_SMTPPort"></a> SMTPPort

Indica el puerto para el envío de correos, por defecto 25

```csharp
public int SMTPPort { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParametrosApp_SMTPServer"></a> SMTPServer

Indica el servidor SMTP para el envío de correos.

```csharp
public string SMTPServer { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParametrosApp_UsernameSMB"></a> UsernameSMB

Usuario SMB para la carpeta compartida

```csharp
public string UsernameSMB { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

