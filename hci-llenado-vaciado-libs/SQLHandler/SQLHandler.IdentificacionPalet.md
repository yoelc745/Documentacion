# <a id="SQLHandler_IdentificacionPalet"></a> Class IdentificacionPalet

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Estructura que recoge los campos de los partes de trabajo.

```csharp
public class IdentificacionPalet
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[IdentificacionPalet](SQLHandler.IdentificacionPalet.md)

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

### <a id="SQLHandler_IdentificacionPalet_Actualizado_Tablet"></a> Actualizado\_Tablet

Indica si el palet ha sido actualizado en la tablet.

```csharp
public int Actualizado_Tablet { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_IdentificacionPalet_CodigoParte"></a> CodigoParte

Código de la parte.

```csharp
public int CodigoParte { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_IdentificacionPalet_DatosTransponder"></a> DatosTransponder

Datos del transponder del palet.

```csharp
public string DatosTransponder { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_IdentificacionPalet_Densidad"></a> Densidad

Densidad del palet.

```csharp
public double Densidad { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_IdentificacionPalet_DiferenciaVolumen"></a> DiferenciaVolumen

Diferencia de volumen del palet.

```csharp
public double DiferenciaVolumen { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_IdentificacionPalet_Fecha"></a> Fecha

Fecha de la identificación del palet.

```csharp
public DateTime Fecha { get; set; }
```

#### Property Value

 [DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)

### <a id="SQLHandler_IdentificacionPalet_Finalizado"></a> Finalizado

Indica si el palet está finalizado.

```csharp
public int Finalizado { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_IdentificacionPalet_ID_Barrica"></a> ID\_Barrica

ID del RFID del palet.

```csharp
public string ID_Barrica { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_IdentificacionPalet_ID_Zona"></a> ID\_Zona

ID de la zona del palet.

```csharp
public int ID_Zona { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_IdentificacionPalet_Id"></a> Id

ID del palet.

```csharp
public int Id { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_IdentificacionPalet_Merma_Peso"></a> Merma\_Peso

Merma de peso del palet.

```csharp
public double Merma_Peso { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_IdentificacionPalet_Observaciones"></a> Observaciones

Observaciones sobre el palet.

```csharp
public string Observaciones { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_IdentificacionPalet_TiempoTrabajo"></a> TiempoTrabajo

Tiempo de trabajo del palet.

```csharp
public int TiempoTrabajo { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_IdentificacionPalet_VolumenAnterior"></a> VolumenAnterior

Volumen anterior del palet.

```csharp
public double VolumenAnterior { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_IdentificacionPalet_VolumenEntrada"></a> VolumenEntrada

Volumen de entrada del palet.

```csharp
public double VolumenEntrada { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_IdentificacionPalet_VolumenSalida"></a> VolumenSalida

Volumen de salida del palet.

```csharp
public double VolumenSalida { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

## Methods

### <a id="SQLHandler_IdentificacionPalet_FinalizarLineaParte_System_Data_SqlClient_SqlConnection_System_String_System_Double_System_Int32_"></a> FinalizarLineaParte\(SqlConnection, string, double, int\)

Finaliza una línea de parte en la base de datos.

```csharp
public bool FinalizarLineaParte(SqlConnection Conn, string Lote, double Peso, int IDZona)
```

#### Parameters

`Conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Lote` [string](https://learn.microsoft.com/dotnet/api/system.string)

`Peso` [double](https://learn.microsoft.com/dotnet/api/system.double)

`IDZona` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_IdentificacionPalet_GuardarLinea_System_Data_SqlClient_SqlConnection_System_String_System_Double_System_Int32_"></a> GuardarLinea\(SqlConnection, string, double, int\)

Guarda una línea en la base de datos.

```csharp
public bool GuardarLinea(SqlConnection Conn, string Lote, double Peso, int IDZona)
```

#### Parameters

`Conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`Lote` [string](https://learn.microsoft.com/dotnet/api/system.string)

`Peso` [double](https://learn.microsoft.com/dotnet/api/system.double)

`IDZona` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_IdentificacionPalet_ObtenerUltimoPesajeFinalizado_System_Data_SqlClient_SqlConnection_System_String_"></a> ObtenerUltimoPesajeFinalizado\(SqlConnection, string\)

Obtiene el último pesaje finalizado para un ID de etiqueta específico.

```csharp
public static IdentificacionPalet ObtenerUltimoPesajeFinalizado(SqlConnection Conn, string TagID)
```

#### Parameters

`Conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`TagID` [string](https://learn.microsoft.com/dotnet/api/system.string)

El ID de la etiqueta RFID.

#### Returns

 [IdentificacionPalet](SQLHandler.IdentificacionPalet.md)

### <a id="SQLHandler_IdentificacionPalet_ObtenerUltimoPesajeSinFinalizar_System_Data_SqlClient_SqlConnection_System_String_"></a> ObtenerUltimoPesajeSinFinalizar\(SqlConnection, string\)

Obtiene el último pesaje sin finalizar para un ID de etiqueta específico.

```csharp
public static IdentificacionPalet ObtenerUltimoPesajeSinFinalizar(SqlConnection Conn, string TagID)
```

#### Parameters

`Conn` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a la base de datos.

`TagID` [string](https://learn.microsoft.com/dotnet/api/system.string)

El ID de la etiqueta RFID.

#### Returns

 [IdentificacionPalet](SQLHandler.IdentificacionPalet.md)

El objeto IdentificacionPalet que representa el último pesaje sin finalizar, o null si no se encontró.

