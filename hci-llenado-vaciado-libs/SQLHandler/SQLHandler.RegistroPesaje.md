# <a id="SQLHandler_RegistroPesaje"></a> Class RegistroPesaje

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Representa un registro de pesaje.

```csharp
public class RegistroPesaje : INotifyPropertyChanged
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[RegistroPesaje](SQLHandler.RegistroPesaje.md)

#### Implements

[INotifyPropertyChanged](https://learn.microsoft.com/dotnet/api/system.componentmodel.inotifypropertychanged)

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

### <a id="SQLHandler_RegistroPesaje_Fecha"></a> Fecha

Obtiene o establece la fecha del registro.

```csharp
public DateTime Fecha { get; set; }
```

#### Property Value

 [DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)

### <a id="SQLHandler_RegistroPesaje_Id_Zona"></a> Id\_Zona

Obtiene o establece el ID de la zona del registro.

```csharp
public int Id_Zona { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_RegistroPesaje_Numero_Lote"></a> Numero\_Lote

Obtiene o establece el número de lote del registro.

```csharp
public string Numero_Lote { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_RegistroPesaje_Peso"></a> Peso

Obtiene o establece el peso del registro.

```csharp
public int Peso { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_RegistroPesaje_Tag"></a> Tag

Obtiene o establece el tag del registro.

```csharp
public string Tag { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_RegistroPesaje_Uuid"></a> Uuid

Obtiene o establece el UUID del registro.

```csharp
public string Uuid { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="SQLHandler_RegistroPesaje_ComprobarExistenciaRegistro_System_Data_SqlClient_SqlConnection_SQLHandler_RegistroPesaje_"></a> ComprobarExistenciaRegistro\(SqlConnection, RegistroPesaje\)

Comprueba si existe un registro de pesaje para un determinado tag en la base de datos.

```csharp
public static bool ComprobarExistenciaRegistro(SqlConnection dbconn, RegistroPesaje RegistroAComprobar)
```

#### Parameters

`dbconn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`RegistroAComprobar` [RegistroPesaje](SQLHandler.RegistroPesaje.md)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si existe un registro de pesaje asociado al tag especificado, False de lo contrario.

### <a id="SQLHandler_RegistroPesaje_GuardarRegistroBd_System_Data_SqlClient_SqlConnection_"></a> GuardarRegistroBd\(SqlConnection\)

Guarda un registro de pesaje en la base de datos.

```csharp
public bool GuardarRegistroBd(SqlConnection Conn)
```

#### Parameters

`Conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si el registro se guarda exitosamente, False en caso contrario.

### <a id="SQLHandler_RegistroPesaje_ObtenerRegistroByUuid_System_Data_SqlClient_SqlConnection_System_String_"></a> ObtenerRegistroByUuid\(SqlConnection, string\)

Obtiene un registro de pesaje por su UUID desde la base de datos.

```csharp
public static RegistroPesaje ObtenerRegistroByUuid(SqlConnection dbconn, string Uuid)
```

#### Parameters

`dbconn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Uuid` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [RegistroPesaje](SQLHandler.RegistroPesaje.md)

El registro de pesaje asociado al UUID especificado, o null si no se encontró ningún registro.

### <a id="SQLHandler_RegistroPesaje_ObtenerRegistrosFromTag_System_Data_SqlClient_SqlConnection_System_String_"></a> ObtenerRegistrosFromTag\(SqlConnection, string\)

Obtiene el último registro de pesaje para un determinado tag desde la base de datos.

```csharp
public static RegistroPesaje ObtenerRegistrosFromTag(SqlConnection dbconn, string Tag)
```

#### Parameters

`dbconn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Tag` [string](https://learn.microsoft.com/dotnet/api/system.string)

El tag para el cual se obtendrá el registro.

#### Returns

 [RegistroPesaje](SQLHandler.RegistroPesaje.md)

El último registro de pesaje asociado al tag especificado, o null si no se encontró ningún registro.

### <a id="SQLHandler_RegistroPesaje_ObtenerUltimosRegistrosFromTag_System_Data_SqlClient_SqlConnection_System_String_"></a> ObtenerUltimosRegistrosFromTag\(SqlConnection, string\)

Obtiene los últimos registros de pesaje para un determinado tag desde la base de datos.

```csharp
public static List<RegistroPesaje> ObtenerUltimosRegistrosFromTag(SqlConnection dbconn, string Tag)
```

#### Parameters

`dbconn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Tag` [string](https://learn.microsoft.com/dotnet/api/system.string)

El tag para el cual se obtendrán los registros.

#### Returns

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[RegistroPesaje](SQLHandler.RegistroPesaje.md)\>

Una lista de los últimos registros de pesaje asociados al tag especificado.

### <a id="SQLHandler_RegistroPesaje_ObtenerUltimosXRegistros_System_Data_SqlClient_SqlConnection_System_Int32_"></a> ObtenerUltimosXRegistros\(SqlConnection, int\)

Obtiene los últimos X registros de pesaje desde la base de datos.

```csharp
public static List<RegistroPesaje> ObtenerUltimosXRegistros(SqlConnection dbconn, int Count)
```

#### Parameters

`dbconn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Count` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[RegistroPesaje](SQLHandler.RegistroPesaje.md)\>

Una lista de los últimos X registros de pesaje.

### <a id="SQLHandler_RegistroPesaje_OnPropertyChanged_System_String_"></a> OnPropertyChanged\(string\)

Llama al evento PropertyChanged cuando cambia una propiedad de la clase.

```csharp
protected void OnPropertyChanged(string PropertyName)
```

#### Parameters

`PropertyName` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre de la propiedad que ha cambiado.

### <a id="SQLHandler_RegistroPesaje_ToString"></a> ToString\(\)

Retorna una representación en forma de cadena de este objeto.

```csharp
public override string ToString()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que representa el objeto actual.

### <a id="SQLHandler_RegistroPesaje_PropertyChanged"></a> PropertyChanged

Se produce cuando cambia una propiedad de la clase.

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

#### Event Type

 [PropertyChangedEventHandler](https://learn.microsoft.com/dotnet/api/system.componentmodel.propertychangedeventhandler)

