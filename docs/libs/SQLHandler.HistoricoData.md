# <a id="SQLHandler_HistoricoData"></a> Class HistoricoData

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Representa los datos históricos de un registro en la base de datos.

```csharp
public class HistoricoData
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[HistoricoData](SQLHandler.HistoricoData.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Properties

### <a id="SQLHandler_HistoricoData_Densidad"></a> Densidad

Obtiene o establece la densidad.

```csharp
public double Densidad { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_HistoricoData_DiferenciaPeso"></a> DiferenciaPeso

Obtiene o establece la diferencia de peso.

```csharp
public double DiferenciaPeso { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_HistoricoData_Fecha"></a> Fecha

Obtiene o establece la fecha.

```csharp
public string Fecha { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_HistoricoData_GradoAlcoholico"></a> GradoAlcoholico

Obtiene o establece el grado alcohólico.

```csharp
public double GradoAlcoholico { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_HistoricoData_NumeroLote"></a> NumeroLote

Obtiene o establece el número de lote.

```csharp
public int NumeroLote { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_HistoricoData_NumeroPalet"></a> NumeroPalet

Obtiene o establece el número de paleta.

```csharp
public int NumeroPalet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_HistoricoData_PesoLleno"></a> PesoLleno

Obtiene o establece el peso lleno.

```csharp
public double PesoLleno { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_HistoricoData_PesoVacio"></a> PesoVacio

Obtiene o establece el peso vacío.

```csharp
public double PesoVacio { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_HistoricoData_TipoBarril"></a> TipoBarril

Obtiene o establece el tipo de barril.

```csharp
public int TipoBarril { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_HistoricoData_TipoBase"></a> TipoBase

Obtiene o establece el tipo de base.

```csharp
public string TipoBase { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_HistoricoData_TipoPalet"></a> TipoPalet

Obtiene o establece el tipo de palet.

```csharp
public int TipoPalet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_HistoricoData_Volumen"></a> Volumen

Obtiene o establece el volumen.

```csharp
public double Volumen { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

## Methods

### <a id="SQLHandler_HistoricoData_MarcarRegistroMigrado_System_Data_SqlClient_SqlConnection_SQLHandler_HistoricoData_"></a> MarcarRegistroMigrado\(SqlConnection, HistoricoData\)

Marca un registro como migrado en la base de datos.

```csharp
public static bool MarcarRegistroMigrado(SqlConnection dbconn, HistoricoData data)
```

#### Parameters

`dbconn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

`data` [HistoricoData](SQLHandler.HistoricoData.md)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si el registro se marcó correctamente; de lo contrario, False.

