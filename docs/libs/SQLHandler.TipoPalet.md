# <a id="SQLHandler_TipoPalet"></a> Class TipoPalet

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que representa el tipo de palet.

```csharp
public class TipoPalet
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TipoPalet](SQLHandler.TipoPalet.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Properties

### <a id="SQLHandler_TipoPalet_Actualizado_Tablet"></a> Actualizado\_Tablet

Indicador de si el tipo de palet fue actualizado en la tablet.

```csharp
public int Actualizado_Tablet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_TipoPalet_Descripcion"></a> Descripcion

Descripción del tipo de palet.

```csharp
public string Descripcion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_TipoPalet_Id"></a> Id

ID del tipo de palet.

```csharp
public int Id { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_TipoPalet_TablaDB"></a> TablaDB

Tabla de datos para almacenar los resultados.

```csharp
public DataTable TablaDB { get; set; }
```

#### Property Value

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

## Methods

### <a id="SQLHandler_TipoPalet_BindDataTable_System_Data_DataTable_"></a> BindDataTable\(DataTable\)

Asocia una tabla de datos a la propiedad `TablaDB`.

```csharp
public void BindDataTable(DataTable Table)
```

#### Parameters

`Table` [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

La tabla de datos a asociar.

### <a id="SQLHandler_TipoPalet_ConfirmDataTableChanges"></a> ConfirmDataTableChanges\(\)

Confirma los cambios realizados en la tabla de datos `TablaDB`.

```csharp
public void ConfirmDataTableChanges()
```

### <a id="SQLHandler_TipoPalet_GetRecordsInDataTable_System_Data_SqlClient_SqlConnection_"></a> GetRecordsInDataTable\(SqlConnection\)

Obtiene los registros de la base de datos y los almacena en la tabla de datos `TablaDB`.

```csharp
public DataTable GetRecordsInDataTable(SqlConnection conn)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

La tabla de datos con los registros obtenidos.

### <a id="SQLHandler_TipoPalet_UpdateFromDatatable_System_Data_SqlClient_SqlConnection_System_Int32_"></a> UpdateFromDatatable\(SqlConnection, int\)

Actualiza los datos en la base de datos a partir de la tabla de datos `TablaDB`.

```csharp
public bool UpdateFromDatatable(SqlConnection conn, int Tablet = 0)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Tablet` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El indicador de si la actualización se realiza desde una tablet.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si la actualización se realizó correctamente, False en caso contrario.

