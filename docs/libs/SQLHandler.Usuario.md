# <a id="SQLHandler_Usuario"></a> Class Usuario

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

```csharp
public class Usuario
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Usuario](SQLHandler.Usuario.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="SQLHandler_Usuario__ctor_System_String_System_String_SQLHandler_Usuario_NivelAcceso_"></a> Usuario\(string, string, NivelAcceso\)

Inicializa una nueva instancia de la clase Usuario con el nombre de usuario, contraseña y nivel de acceso especificados.

```csharp
public Usuario(string Username, string Password, Usuario.NivelAcceso Nivel)
```

#### Parameters

`Username` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre de usuario del usuario.

`Password` [string](https://learn.microsoft.com/dotnet/api/system.string)

La contraseña del usuario.

`Nivel` [Usuario](SQLHandler.Usuario.md).[NivelAcceso](SQLHandler.Usuario.NivelAcceso.md)

El nivel de acceso del usuario.

## Properties

### <a id="SQLHandler_Usuario_Nivel"></a> Nivel

Obtiene o establece el nivel de acceso del usuario.

```csharp
public Usuario.NivelAcceso Nivel { get; set; }
```

#### Property Value

 [Usuario](SQLHandler.Usuario.md).[NivelAcceso](SQLHandler.Usuario.NivelAcceso.md)

### <a id="SQLHandler_Usuario_Password"></a> Password

Obtiene o establece la contraseña del usuario.

```csharp
public string Password { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_Usuario_Username"></a> Username

Obtiene o establece el nombre de usuario del usuario.

```csharp
public string Username { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="SQLHandler_Usuario_IsAdmin"></a> IsAdmin\(\)

Determina si el usuario tiene acceso de administrador.

```csharp
public bool IsAdmin()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si el usuario tiene acceso de administrador, false en caso contrario.

### <a id="SQLHandler_Usuario_LoginFromDB_System_Data_SqlClient_SqlConnection_System_String_System_String_"></a> LoginFromDB\(SqlConnection, string, string\)

Intenta iniciar sesión de un usuario desde la base de datos utilizando el nombre de usuario y la contraseña proporcionados.

```csharp
public static Usuario LoginFromDB(SqlConnection conn, string Username, string Password)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

El objeto SqlConnection.

`Username` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre de usuario del usuario para iniciar sesión.

`Password` [string](https://learn.microsoft.com/dotnet/api/system.string)

La contraseña del usuario para iniciar sesión.

#### Returns

 [Usuario](SQLHandler.Usuario.md)

Un objeto Usuario que representa al usuario que inició sesión, o null si el inicio de sesión falló.

