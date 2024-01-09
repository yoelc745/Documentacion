# <a id="RFID_SQLsRFID"></a> Class SQLsRFID

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Clase abstracta que contiene las consultas SQL utilizadas para interactuar con la base de datos.

```csharp
public abstract class SQLsRFID
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SQLsRFID](RFID.SQLsRFID.md)

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

## Fields

### <a id="RFID_SQLsRFID_SQLClearHash"></a> SQLClearHash

Consulta SQL para borrar el hash y el último contenido de una etiqueta en la base de datos.

```csharp
public static readonly string SQLClearHash
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_SQLsRFID_SQLInsertTag"></a> SQLInsertTag

Consulta SQL para insertar una nueva etiqueta en la base de datos.

```csharp
public static readonly string SQLInsertTag
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_SQLsRFID_SQLReplaceTag"></a> SQLReplaceTag

Consulta SQL para reemplazar una etiqueta por otra en la base de datos.

```csharp
public static readonly string SQLReplaceTag
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_SQLsRFID_SQLSelectTag"></a> SQLSelectTag

Consulta SQL para seleccionar una etiqueta de la base de datos.

```csharp
public static readonly string SQLSelectTag
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_SQLsRFID_SQLUpdateTag"></a> SQLUpdateTag

Consulta SQL para actualizar los datos de una etiqueta en la base de datos.

```csharp
public static readonly string SQLUpdateTag
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

