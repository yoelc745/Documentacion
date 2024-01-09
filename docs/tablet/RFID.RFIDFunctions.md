# <a id="RFID_RFIDFunctions"></a> Class RFIDFunctions

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Funciones externas asociadas al RFID, no necesita ser instanciado.

```csharp
public static class RFIDFunctions
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[RFIDFunctions](RFID.RFIDFunctions.md)

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

## Methods

### <a id="RFID_RFIDFunctions_ClearDBDataFromTag_System_Data_SqlClient_SqlConnection_System_String_System_Boolean_"></a> ClearDBDataFromTag\(SqlConnection, string, bool\)

Borra los datos de la base de datos asociados a una etiqueta.

```csharp
public static bool ClearDBDataFromTag(SqlConnection Connection, string IDTag, bool FromTablet = false)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

Conexión a la base de datos.

`IDTag` [string](https://learn.microsoft.com/dotnet/api/system.string)

Identificador de la etiqueta.

`FromTablet` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Indica si la eliminación se realizó desde una tableta.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Verdadero si se eliminaron los datos correctamente, falso en caso contrario.

### <a id="RFID_RFIDFunctions_EncodeData_System_String_"></a> EncodeData\(string\)

Codifica los datos en Brotli para introducirlos en el transponder.

```csharp
public static string EncodeData(string Data)
```

#### Parameters

`Data` [string](https://learn.microsoft.com/dotnet/api/system.string)

String a codificar.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Representacion en Base64 de la cadena codificada en Brotli

### <a id="RFID_RFIDFunctions_Hash256String_System_String_"></a> Hash256String\(string\)

Calcula el hash SHA256 de una cadena de texto.

```csharp
public static string Hash256String(string value)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Cadena de texto a la que se le calculará el hash.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El hash SHA256 de la cadena de texto.

### <a id="RFID_RFIDFunctions_LoadTagFromDB_System_Data_SqlClient_SqlConnection_System_String_"></a> LoadTagFromDB\(SqlConnection, string\)

Obtiene la información del tag especificado desde la base de datos.

```csharp
public static TagRFID LoadTagFromDB(SqlConnection Connection, string IDTag)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

`IDTag` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [TagRFID](RFID.TagRFID.md)

Un objeto <code>Tag</code> o <code>null</code> si no existe.

#### Exceptions

 [DuplicatedTagException](RFID.DuplicatedTagException.md)

Si existe más de un tag

### <a id="RFID_RFIDFunctions_SubstituteTagData_System_Data_SqlClient_SqlConnection_System_String_System_String_System_Boolean_"></a> SubstituteTagData\(SqlConnection, string, string, bool\)

Reemplaza los datos de una etiqueta por los de otra en la base de datos.

```csharp
public static bool SubstituteTagData(SqlConnection Connection, string OldTag, string NewTag, bool FromTablet = false)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

Conexión a la base de datos.

`OldTag` [string](https://learn.microsoft.com/dotnet/api/system.string)

Identificador de la etiqueta a reemplazar.

`NewTag` [string](https://learn.microsoft.com/dotnet/api/system.string)

Identificador de la nueva etiqueta.

`FromTablet` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Indica si el reemplazo se realizó desde una tableta.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Verdadero si se reemplazaron los datos correctamente, falso en caso contrario.

