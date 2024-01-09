# <a id="SQLHandler_TipoBarril"></a> Class TipoBarril

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que representa el tipo de barril.

```csharp
public class TipoBarril
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TipoBarril](SQLHandler.TipoBarril.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Properties

### <a id="SQLHandler_TipoBarril_Actualizado_Tablet"></a> Actualizado\_Tablet

Gets or sets the flag indicating whether the TipoBarril was updated from a tablet.

```csharp
public int Actualizado_Tablet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_TipoBarril_Descripcion"></a> Descripcion

Gets or sets the description of the TipoBarril.

```csharp
public string Descripcion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_TipoBarril_EstimadoLleno"></a> EstimadoLleno

Gets or sets the estimated volume when the TipoBarril is full.

```csharp
public double EstimadoLleno { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_TipoBarril_EstimadoVacio"></a> EstimadoVacio

Gets or sets the estimated volume when the TipoBarril is empty.

```csharp
public double EstimadoVacio { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_TipoBarril_Id"></a> Id

Gets or sets the ID of the TipoBarril.

```csharp
public int Id { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_TipoBarril_Margen"></a> Margen

Gets or sets the margin of the TipoBarril.

```csharp
public double Margen { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_TipoBarril_TablaDB"></a> TablaDB

Gets or sets the DataTable object used for storing data.

```csharp
public DataTable TablaDB { get; set; }
```

#### Property Value

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

### <a id="SQLHandler_TipoBarril_Volumen"></a> Volumen

Gets or sets the volume of the TipoBarril.

```csharp
public double Volumen { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_TipoBarril_VolumenConjunto"></a> VolumenConjunto

Gets or sets the combined volume of the TipoBarril.

```csharp
public double VolumenConjunto { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

## Methods

### <a id="SQLHandler_TipoBarril_BindDataTable_System_Data_DataTable_"></a> BindDataTable\(DataTable\)

Binds the provided DataTable to the class property.

```csharp
public void BindDataTable(DataTable Table)
```

#### Parameters

`Table` [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

The DataTable to bind.

### <a id="SQLHandler_TipoBarril_ConfirmDataTableChanges"></a> ConfirmDataTableChanges\(\)

Confirms the changes made to the DataTable.

```csharp
public void ConfirmDataTableChanges()
```

### <a id="SQLHandler_TipoBarril_GetDatosBarril_System_Data_SqlClient_SqlConnection_System_Int32_"></a> GetDatosBarril\(SqlConnection, int\)

Retrieves data for a TipoBarril from the database.

```csharp
public static TipoBarril GetDatosBarril(SqlConnection connection, int Id)
```

#### Parameters

`connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

The SqlConnection object.

`Id` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The ID of the TipoBarril to retrieve.

#### Returns

 [TipoBarril](SQLHandler.TipoBarril.md)

A TipoBarril object with the retrieved data.

### <a id="SQLHandler_TipoBarril_GetRecordsInDataTable_System_Data_SqlClient_SqlConnection_"></a> GetRecordsInDataTable\(SqlConnection\)

Retrieves records from the database and returns them in a DataTable.

```csharp
public DataTable GetRecordsInDataTable(SqlConnection conn)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

The SqlConnection object.

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

A DataTable containing the retrieved records.

### <a id="SQLHandler_TipoBarril_SaveChangesToDB_System_Data_SqlClient_SqlConnection_System_Int32_"></a> SaveChangesToDB\(SqlConnection, int\)

Saves the changes made to the database.

```csharp
public bool SaveChangesToDB(SqlConnection conn, int ActualizadoTablet = 0)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

`ActualizadoTablet` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True if the changes were saved successfully, false otherwise.

### <a id="SQLHandler_TipoBarril_UpdateFromDatatable_System_Data_SqlClient_SqlConnection_System_Int32_"></a> UpdateFromDatatable\(SqlConnection, int\)

Updates the database from the DataTable.

```csharp
public bool UpdateFromDatatable(SqlConnection conn, int Tablet = 0)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

`Tablet` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True if the update was successful, false otherwise.

