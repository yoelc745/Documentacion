# <a id="RFID_TagRFID"></a> Class TagRFID

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Clase que representa una etiqueta RFID.

```csharp
public class TagRFID
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TagRFID](RFID.TagRFID.md)

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

### <a id="RFID_TagRFID__ctor_System_String_System_String_RFID_TagType_"></a> TagRFID\(string, string, TagType\)

Constructor de la clase TagRFID.

```csharp
public TagRFID(string TagId, string CreationDate, TagType TagType)
```

#### Parameters

`TagId` [string](https://learn.microsoft.com/dotnet/api/system.string)

Identificador de la etiqueta.

`CreationDate` [string](https://learn.microsoft.com/dotnet/api/system.string)

Fecha de creación de la etiqueta.

`TagType` [TagType](RFID.TagType.md)

Tipo de la etiqueta.

### <a id="RFID_TagRFID__ctor"></a> TagRFID\(\)

Constructor vacío de la clase TagRFID.

```csharp
public TagRFID()
```

## Properties

### <a id="RFID_TagRFID_Creation_Date"></a> Creation\_Date

Obtiene o establece la fecha de creación de la etiqueta.

```csharp
public string Creation_Date { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_Cycles"></a> Cycles

Obtiene o establece el número de ciclos de la etiqueta.

```csharp
public int Cycles { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="RFID_TagRFID_Hash_Last_Content"></a> Hash\_Last\_Content

Obtiene o establece el hash del último contenido de la etiqueta.

```csharp
public string Hash_Last_Content { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_LastContent"></a> LastContent

Obtiene o establece el último contenido de la etiqueta.

```csharp
public string LastContent { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_Removal_Date"></a> Removal\_Date

Obtiene o establece la fecha de eliminación de la etiqueta.

```csharp
public string Removal_Date { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_ReplacedWith"></a> ReplacedWith

Obtiene o establece el identificador de la etiqueta que la reemplaza.

```csharp
public string ReplacedWith { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_TagId"></a> TagId

Obtiene o establece el identificador de la etiqueta.

```csharp
public string TagId { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_Type"></a> Type

Obtiene o establece el tipo de la etiqueta.

```csharp
public TagType Type { get; set; }
```

#### Property Value

 [TagType](RFID.TagType.md)

### <a id="RFID_TagRFID_Use"></a> Use

Obtiene o establece el uso de la etiqueta.

```csharp
public string Use { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_Warning"></a> Warning

Obtiene o establece el nivel de advertencia de la etiqueta.

```csharp
public int Warning { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="RFID_TagRFID_WarningDate"></a> WarningDate

Obtiene o establece la fecha de la advertencia de la etiqueta.

```csharp
public string WarningDate { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagRFID_WarningText"></a> WarningText

Obtiene o establece el texto de la advertencia de la etiqueta.

```csharp
public string WarningText { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="RFID_TagRFID_AddCycle"></a> AddCycle\(\)

Añade un ciclo de lectura/escritura al tag.

```csharp
public int AddCycle()
```

#### Returns

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

El número de ciclos que tiene el tag

### <a id="RFID_TagRFID_SaveChangesToDB_System_Data_SqlClient_SqlConnection_"></a> SaveChangesToDB\(SqlConnection\)

Guarda los datos del Tag en la base de datos.

```csharp
public void SaveChangesToDB(SqlConnection Connection)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

