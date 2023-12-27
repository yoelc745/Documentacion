# <a id="HavanaTablet_ConfiguracionSQL"></a> Class ConfiguracionSQL

Namespace: [HavanaTablet](HavanaTablet.md)  
Assembly: HavanaTablet.dll  

Clase que contiene la configuración para la conexión a una base de datos SQL.

```csharp
public class ConfiguracionSQL
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ConfiguracionSQL](HavanaTablet.ConfiguracionSQL.md)

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

## Properties

### <a id="HavanaTablet_ConfiguracionSQL_Database"></a> Database

Nombre de la base de datos a la que se va a conectar.

```csharp
public string Database { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="HavanaTablet_ConfiguracionSQL_Host"></a> Host

Dirección IP o nombre de host del servidor SQL.

```csharp
public string Host { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="HavanaTablet_ConfiguracionSQL_Instance"></a> Instance

Nombre de la instancia del servidor SQL.

```csharp
public string Instance { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="HavanaTablet_ConfiguracionSQL_Password"></a> Password

Contraseña para la conexión a la base de datos.

```csharp
public string Password { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="HavanaTablet_ConfiguracionSQL_Port"></a> Port

Puerto para la conexión al servidor SQL.

```csharp
public int Port { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="HavanaTablet_ConfiguracionSQL_Username"></a> Username

Nombre de usuario para la conexión a la base de datos.

```csharp
public string Username { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="HavanaTablet_ConfiguracionSQL_GetDSN"></a> GetDSN\(\)

Obtiene el DSN (Data Source Name) para la conexión a la base de datos.

```csharp
public string GetDSN()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

DSN para la conexión a la base de datos.

