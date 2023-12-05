# <a id="SQLHandler_ParteTrabajo"></a> Class ParteTrabajo

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Estructura que representa el parte de trabajo de producción.

```csharp
public class ParteTrabajo
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ParteTrabajo](SQLHandler.ParteTrabajo.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Fields

### <a id="SQLHandler_ParteTrabajo_Adapter"></a> Adapter

Adaptador para la manipulación de datos.

```csharp
public SqlDataAdapter Adapter
```

#### Field Value

 [SqlDataAdapter](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqldataadapter)

### <a id="SQLHandler_ParteTrabajo_TablaDB"></a> TablaDB

Tabla de datos para almacenar los resultados.

```csharp
public DataTable TablaDB
```

#### Field Value

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

## Properties

### <a id="SQLHandler_ParteTrabajo_Actualizado_Tablet"></a> Actualizado\_Tablet

Indicador de si el parte de trabajo fue actualizado en la tablet.

```csharp
public int Actualizado_Tablet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_CodAlmacen_Destino"></a> CodAlmacen\_Destino

Código del almacén de destino.

```csharp
public int CodAlmacen_Destino { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_CodAlmacen_Origen"></a> CodAlmacen\_Origen

Código del almacén de origen.

```csharp
public int CodAlmacen_Origen { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_CodigoArticulo"></a> CodigoArticulo

Código del artículo.

```csharp
public int CodigoArticulo { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_CodigoError"></a> CodigoError

Código de error del parte de trabajo.

```csharp
public int CodigoError { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_Densidad"></a> Densidad

Densidad del parte de trabajo.

```csharp
public double Densidad { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_ParteTrabajo_Descripcion"></a> Descripcion

Descripción del parte de trabajo.

```csharp
public string Descripcion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_Estado"></a> Estado

Estado del parte de trabajo.

```csharp
public int Estado { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_Fecha_Fin"></a> Fecha\_Fin

Fecha de fin del parte de trabajo.

```csharp
public string Fecha_Fin { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_Fecha_Inicio"></a> Fecha\_Inicio

Fecha de inicio del parte de trabajo.

```csharp
public string Fecha_Inicio { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_Lote"></a> Lote

Lote del parte de trabajo.

```csharp
public string Lote { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_NumeroOP"></a> NumeroOP

Número de OP.

```csharp
public int NumeroOP { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_Observaciones"></a> Observaciones

Observaciones del parte de trabajo.

```csharp
public string Observaciones { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_Tipo"></a> Tipo

Tipo del parte de trabajo.

```csharp
public string Tipo { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_TipoBarril"></a> TipoBarril

Tipo de barril del parte de trabajo.

```csharp
public int TipoBarril { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_TipoPalet"></a> TipoPalet

Tipo de palet del parte de trabajo.

```csharp
public int TipoPalet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ParteTrabajo_Usuario"></a> Usuario

Usuario del parte de trabajo.

```csharp
public string Usuario { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ParteTrabajo_Volumen_Total"></a> Volumen\_Total

Volumen total del parte de trabajo.

```csharp
public double Volumen_Total { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

## Methods

### <a id="SQLHandler_ParteTrabajo_CerrarParte_System_Data_SqlClient_SqlConnection_System_Int32_"></a> CerrarParte\(SqlConnection, int\)

Cierra el parte en la base de datos.

```csharp
public void CerrarParte(SqlConnection conn, int IDParte)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

Conexión activa a la base de datos.

`IDParte` [int](https://learn.microsoft.com/dotnet/api/system.int32)

ID del parte.

### <a id="SQLHandler_ParteTrabajo_GetDataTable_System_Data_SqlClient_SqlConnection_"></a> GetDataTable\(SqlConnection\)

Obtiene un DataTable a partir de una conexión SqlConnection.

```csharp
public DataTable GetDataTable(SqlConnection conn)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión SqlConnection.

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

El DataTable obtenido.

### <a id="SQLHandler_ParteTrabajo_GuardarParte_System_Data_SqlClient_SqlConnection_"></a> GuardarParte\(SqlConnection\)

Guarda el parte de trabajo en la base de datos.

```csharp
public void GuardarParte(SqlConnection conn)
```

#### Parameters

`conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

Conexión activa a la base de datos.

