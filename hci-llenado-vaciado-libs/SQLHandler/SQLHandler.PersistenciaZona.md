# <a id="SQLHandler_PersistenciaZona"></a> Class PersistenciaZona

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que representa la persistencia de una zona.

```csharp
public class PersistenciaZona : INotifyPropertyChanged
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[PersistenciaZona](SQLHandler.PersistenciaZona.md)

#### Implements

[INotifyPropertyChanged](https://learn.microsoft.com/dotnet/api/system.componentmodel.inotifypropertychanged)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="SQLHandler_PersistenciaZona__ctor_System_Data_SqlClient_SqlConnection_"></a> PersistenciaZona\(SqlConnection\)

Inicializa una nueva instancia de la clase <xref href="SQLHandler.PersistenciaZona" data-throw-if-not-resolved="false"></xref>.

```csharp
public PersistenciaZona(SqlConnection Connection)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a SQL.

## Properties

### <a id="SQLHandler_PersistenciaZona_Estado"></a> Estado

```csharp
public EstadoPersistencia Estado { get; set; }
```

#### Property Value

 [EstadoPersistencia](SQLHandler.EstadoPersistencia.md)

### <a id="SQLHandler_PersistenciaZona_Fecha_Peso"></a> Fecha\_Peso

```csharp
public string Fecha_Peso { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_PersistenciaZona_Fecha_RFID"></a> Fecha\_RFID

```csharp
public string Fecha_RFID { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_PersistenciaZona_Id"></a> Id

```csharp
public int Id { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_PersistenciaZona_Observaciones"></a> Observaciones

```csharp
public string Observaciones { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_PersistenciaZona_Peso"></a> Peso

```csharp
public double Peso { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="SQLHandler_PersistenciaZona_Peso_Enviado"></a> Peso\_Enviado

Obtiene o establece un valor que indica si el peso ha sido enviado.

```csharp
public bool Peso_Enviado { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_PersistenciaZona_RFID"></a> RFID

```csharp
public string RFID { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_PersistenciaZona_RFID_Enviado"></a> RFID\_Enviado

```csharp
public bool RFID_Enviado { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_PersistenciaZona__Estado"></a> \_Estado

Obtiene o establece el estado de persistencia.

```csharp
public EstadoPersistencia _Estado { get; set; }
```

#### Property Value

 [EstadoPersistencia](SQLHandler.EstadoPersistencia.md)

## Methods

### <a id="SQLHandler_PersistenciaZona_ActualizarDatosTabla"></a> ActualizarDatosTabla\(\)

Actualiza los datos de la tabla de persistencia.

```csharp
public void ActualizarDatosTabla()
```

### <a id="SQLHandler_PersistenciaZona_GetPersistenciasZonas_System_Data_SqlClient_SqlConnection_"></a> GetPersistenciasZonas\(SqlConnection\)

Obtiene una lista de persistencias de zonas desde la base de datos.

```csharp
public static List<PersistenciaZona> GetPersistenciasZonas(SqlConnection Connection)
```

#### Parameters

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

La conexión a SQL.

#### Returns

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[PersistenciaZona](SQLHandler.PersistenciaZona.md)\>

Una lista de persistencias de zonas.

### <a id="SQLHandler_PersistenciaZona_PropertyChanged"></a> PropertyChanged

Evento que se produce cuando una propiedad ha cambiado.

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

#### Event Type

 [PropertyChangedEventHandler](https://learn.microsoft.com/dotnet/api/system.componentmodel.propertychangedeventhandler)

