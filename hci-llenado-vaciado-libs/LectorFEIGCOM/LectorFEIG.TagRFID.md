# <a id="LectorFEIG_TagRFID"></a> Class TagRFID

Namespace: [LectorFEIG](LectorFEIG.md)  
Assembly: LectorFEIGCOM.dll  

Define una clase que representa una etiqueta RFID que se puede leer y escribir con un dispositivo RFID.

```csharp
public class TagRFID
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TagRFID](LectorFEIG.TagRFID.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="LectorFEIG_TagRFID__ctor_System_String_System_String_TagType_"></a> TagRFID\(string, string, TagType\)

```csharp
public TagRFID(string TagId, string CreationDate, TagType TagType)
```

#### Parameters

`TagId` [string](https://learn.microsoft.com/dotnet/api/system.string)

`CreationDate` [string](https://learn.microsoft.com/dotnet/api/system.string)

`TagType` [TagType](TagType.md)

### <a id="LectorFEIG_TagRFID__ctor"></a> TagRFID\(\)

```csharp
public TagRFID()
```

## Properties

### <a id="LectorFEIG_TagRFID_Creation_Date"></a> Creation\_Date

Obtiene o establece la fecha de creación de la etiqueta RFID.

```csharp
public string Creation_Date { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_Cycles"></a> Cycles

Obtiene o establece el número de ciclos de lectura y escritura que ha realizado la etiqueta RFID.

```csharp
public int Cycles { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="LectorFEIG_TagRFID_Hash_Last_Content"></a> Hash\_Last\_Content

Obtiene o establece el hash del último contenido que se escribió en la etiqueta RFID.

```csharp
public string Hash_Last_Content { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_LastContent"></a> LastContent

Obtiene o establece el último contenido que se escribió en la etiqueta RFID.

```csharp
public string LastContent { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_Removal_Date"></a> Removal\_Date

Obtiene o establece la fecha de retirada de la etiqueta RFID.

```csharp
public string Removal_Date { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_ReplacedWith"></a> ReplacedWith

Obtiene o establece el identificador de la etiqueta RFID que reemplazó a la etiqueta retirada.

```csharp
public string ReplacedWith { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_TagId"></a> TagId

Obtiene o establece el identificador de la etiqueta RFID.

```csharp
public string TagId { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_Type"></a> Type

Obtiene o establece el tipo de la etiqueta RFID.

```csharp
public TagType Type { get; set; }
```

#### Property Value

 [TagType](TagType.md)

### <a id="LectorFEIG_TagRFID_Use"></a> Use

Obtiene o establece el uso que se le da a la etiqueta RFID.

```csharp
public string Use { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_Warning"></a> Warning

Obtiene o establece el nivel de advertencia de la etiqueta RFID.

```csharp
public int Warning { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="LectorFEIG_TagRFID_WarningDate"></a> WarningDate

Obtiene o establece la fecha de la última advertencia de la etiqueta RFID.

```csharp
public string WarningDate { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagRFID_WarningText"></a> WarningText

Obtiene o establece el texto de la última advertencia de la etiqueta RFID.

```csharp
public string WarningText { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="LectorFEIG_TagRFID_AddCycle"></a> AddCycle\(\)

Aumenta el número de ciclos de lectura y escritura que ha realizado la etiqueta RFID en uno y lo devuelve.

```csharp
public int AddCycle()
```

#### Returns

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

El número de ciclos actualizado de la etiqueta RFID.

### <a id="LectorFEIG_TagRFID_SaveChangesToDB_System_Data_SqlClient_SqlConnection_"></a> SaveChangesToDB\(SqlConnection\)

Guarda los datos del Tag en la base de datos.

```csharp
public void SaveChangesToDB(SqlConnection Connection)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

El objeto SqlConnection que representa la conexión con la base de datos.

