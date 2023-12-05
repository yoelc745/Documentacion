# <a id="SQLHandler_ConectorSQL"></a> Class ConectorSQL

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que alberga las funcionalidades de conexión y comunicación con la base de datos.

```csharp
public class ConectorSQL
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ConectorSQL](SQLHandler.ConectorSQL.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="SQLHandler_ConectorSQL__ctor_System_String_System_String_System_String_System_String_System_Boolean_"></a> ConectorSQL\(string, string, string, string, bool\)

Conecta a la base de datos especificando los datos.

```csharp
public ConectorSQL(string Host, string Username, string Password, string DB, bool DebugMode = false)
```

#### Parameters

`Host` [string](https://learn.microsoft.com/dotnet/api/system.string)

Host donde se encuentra el servidor.

`Username` [string](https://learn.microsoft.com/dotnet/api/system.string)

Usuario de la base de datos.

`Password` [string](https://learn.microsoft.com/dotnet/api/system.string)

Contraseña de la base de datos.

`DB` [string](https://learn.microsoft.com/dotnet/api/system.string)

Base de datos seleccionada por defecto.

`DebugMode` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

#### Exceptions

 [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

### <a id="SQLHandler_ConectorSQL__ctor_System_String_ILog_System_Boolean_"></a> ConectorSQL\(string, ILog, bool\)

Conecta a la base de datos con la cadena de conexión DSN.

```csharp
public ConectorSQL(string DSN, ILog Logger = null, bool DebugMode = false)
```

#### Parameters

`DSN` [string](https://learn.microsoft.com/dotnet/api/system.string)

DSN de conexión

`Logger` ILog

`DebugMode` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

#### Exceptions

 [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

## Fields

### <a id="SQLHandler_ConectorSQL_Connection"></a> Connection

Conexión SQL a la base de datos.

```csharp
protected SqlConnection Connection
```

#### Field Value

 [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

## Methods

### <a id="SQLHandler_ConectorSQL_ActualizarConfiguracionApp_SQLHandler_ConfiguracionApp_"></a> ActualizarConfiguracionApp\(ConfiguracionApp\)

Actualiza la configuración de la aplicación.

```csharp
public void ActualizarConfiguracionApp(ConfiguracionApp item)
```

#### Parameters

`item` [ConfiguracionApp](SQLHandler.ConfiguracionApp.md)

### <a id="SQLHandler_ConectorSQL_ActualizarConfiguracionZona_SQLHandler_ConfiguracionZona_"></a> ActualizarConfiguracionZona\(ConfiguracionZona\)

Actualiza la configuración de la zona especificada.

```csharp
public void ActualizarConfiguracionZona(ConfiguracionZona ConfigZona)
```

#### Parameters

`ConfigZona` [ConfiguracionZona](SQLHandler.ConfiguracionZona.md)

Configuracion de la zona

#### Exceptions

 [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

### <a id="SQLHandler_ConectorSQL_CheckStatus"></a> CheckStatus\(\)

Detecta el estado de la conexión de la base de datos.

```csharp
public bool CheckStatus()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si está conectado, de lo contrario False

### <a id="SQLHandler_ConectorSQL_CheckUpdateParte_System_String_"></a> CheckUpdateParte\(string\)

CheckUpdateParte es una función que toma un parámetro de tipo string, LoteABuscar,
y devuelve un string. Esta función verifica si hay actualizaciones en la tabla EK_OrdenesProd
de la base de datos EKINDATA para un valor de Lote dado. Si se encuentra una actualización,
devuelve el valor de Lote como string. Si no se encuentra ninguna actualización, devuelve null.

```csharp
public string CheckUpdateParte(string LoteABuscar)
```

#### Parameters

`LoteABuscar` [string](https://learn.microsoft.com/dotnet/api/system.string)

El valor de Lote a buscar en la tabla.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El valor de Lote como string si se encuentra una actualización, de lo contrario null.

### <a id="SQLHandler_ConectorSQL_Connect"></a> Connect\(\)

Conecta con el destino especificado.

```csharp
public void Connect()
```

### <a id="SQLHandler_ConectorSQL_CrearCopiaSeguridadBD_System_String_System_String_"></a> CrearCopiaSeguridadBD\(string, string\)

Crea una copia de seguridad de la base de datos especificada en el directorio especificado.

```csharp
public bool CrearCopiaSeguridadBD(string Database, string Path)
```

#### Parameters

`Database` [string](https://learn.microsoft.com/dotnet/api/system.string)

`Path` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True si se creó la copia de seguridad correctamente, False en caso contrario.

### <a id="SQLHandler_ConectorSQL_CreateEvent_System_String_System_String_System_Int32_"></a> CreateEvent\(string, string, int\)

Crea un evento con los parámetros dados.

```csharp
public void CreateEvent(string Tipo, string Descripcion, int Tablet = 0)
```

#### Parameters

`Tipo` [string](https://learn.microsoft.com/dotnet/api/system.string)

El tipo de evento.

`Descripcion` [string](https://learn.microsoft.com/dotnet/api/system.string)

La descripción del evento.

`Tablet` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El ID de la tablet asociada con el evento (el valor predeterminado es 0).

### <a id="SQLHandler_ConectorSQL_GetConfigApp"></a> GetConfigApp\(\)

Obtiene la configuración de la aplicación.

```csharp
public ObservableCollection<ConfiguracionApp> GetConfigApp()
```

#### Returns

 [ObservableCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.observablecollection\-1)<[ConfiguracionApp](SQLHandler.ConfiguracionApp.md)\>

Una ObservableCollection de objetos ConfiguracionApp que representan la configuración de la aplicación.

### <a id="SQLHandler_ConectorSQL_GetConfigUIElement_System_String_"></a> GetConfigUIElement\(string\)

Obtiene la configuración del elemento gráfico.

```csharp
public UIElementConfig GetConfigUIElement(string xName)
```

#### Parameters

`xName` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [UIElementConfig](SQLHandler.UIElementConfig.md)

Un objeto UIElementConfig que representa la configuración del elemento gráfico.

### <a id="SQLHandler_ConectorSQL_GetConfigZona_System_Int32_"></a> GetConfigZona\(int\)

Obtenemos la configuración de la zona mediante el número de ID.

```csharp
public ConfiguracionZona GetConfigZona(int ID)
```

#### Parameters

`ID` [int](https://learn.microsoft.com/dotnet/api/system.int32)

ID de la zona

#### Returns

 [ConfiguracionZona](SQLHandler.ConfiguracionZona.md)

Configuración de la zona

### <a id="SQLHandler_ConectorSQL_GetConnection"></a> GetConnection\(\)

Devuelve el objeto de conexión a la base de datos.

```csharp
public SqlConnection GetConnection()
```

#### Returns

 [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

El objeto SqlConnection utilizado para la conexión a la base de datos.

### <a id="SQLHandler_ConectorSQL_GetHistorialTransponder_System_String_"></a> GetHistorialTransponder\(string\)

Obtiene el historial del transponder especificado.

```csharp
public ObservableCollection<RegistroPesaje> GetHistorialTransponder(string Transponder)
```

#### Parameters

`Transponder` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [ObservableCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.observablecollection\-1)<[RegistroPesaje](SQLHandler.RegistroPesaje.md)\>

Una ObservableCollection de objetos RegistroPesaje que representan el historial del transponder.

### <a id="SQLHandler_ConectorSQL_GetIDsPartesAbiertos"></a> GetIDsPartesAbiertos\(\)

Obtiene la lista de IDs con los partes abiertos.

```csharp
public List<ParteTrabajo> GetIDsPartesAbiertos()
```

#### Returns

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[ParteTrabajo](SQLHandler.ParteTrabajo.md)\>

Una lista de objetos ParteTrabajo que representan los partes abiertos.

### <a id="SQLHandler_ConectorSQL_GetLastInsertedID_System_String_"></a> GetLastInsertedID\(string\)

Obtiene la última ID que se ha introducido en la base de datos.

```csharp
public string GetLastInsertedID(string TableName)
```

#### Parameters

`TableName` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConectorSQL_GetLastRegistroByRfid_System_String_"></a> GetLastRegistroByRfid\(string\)

Recupera el objeto RegistroPesaje más reciente asociado con la etiqueta RFID dada.

```csharp
public RegistroPesaje GetLastRegistroByRfid(string RFID)
```

#### Parameters

`RFID` [string](https://learn.microsoft.com/dotnet/api/system.string)

La etiqueta RFID a buscar.

#### Returns

 [RegistroPesaje](SQLHandler.RegistroPesaje.md)

El objeto RegistroPesaje más reciente con la etiqueta RFID coincidente, o null si no se encuentra.

### <a id="SQLHandler_ConectorSQL_GetRegistrosFromParte_System_String_"></a> GetRegistrosFromParte\(string\)

Obtiene una colección de objetos RegistroPesaje desde la base de datos en función del valor de Lote proporcionado.

```csharp
public ObservableCollection<RegistroPesaje> GetRegistrosFromParte(string Lote)
```

#### Parameters

`Lote` [string](https://learn.microsoft.com/dotnet/api/system.string)

El valor de Lote utilizado para filtrar los registros.

#### Returns

 [ObservableCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.observablecollection\-1)<[RegistroPesaje](SQLHandler.RegistroPesaje.md)\>

Una colección ObservableCollection de objetos RegistroPesaje que coinciden con el valor de Lote proporcionado.

#### Exceptions

 [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

Si ocurre un error durante el proceso de obtención.

### <a id="SQLHandler_ConectorSQL_GetRegistryValue_System_String_SQLHandler_RegistryKeyType_"></a> GetRegistryValue\(string, RegistryKeyType\)

Obtiene el valor del registro especificado

```csharp
public static string GetRegistryValue(string Value, RegistryKeyType TipoKey)
```

#### Parameters

`Value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Key del registro a buscar

`TipoKey` [RegistryKeyType](SQLHandler.RegistryKeyType.md)

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Los datos de una clave del registro

#### Exceptions

 [RegistryKeyMissingException](SQLHandler.RegistryKeyMissingException.md)

Si no se encuentra la clave del registro.

### <a id="SQLHandler_ConectorSQL_GuardarConfiguracionZona_SQLHandler_ConfiguracionZona_"></a> GuardarConfiguracionZona\(ConfiguracionZona\)

Inserta la configuración en la base de datos.

```csharp
public void GuardarConfiguracionZona(ConfiguracionZona ConfigZona)
```

#### Parameters

`ConfigZona` [ConfiguracionZona](SQLHandler.ConfiguracionZona.md)

Objeto con la configuración de la zona.

#### Exceptions

 [DuplicateKeyValueException](SQLHandler.DuplicateKeyValueException.md)

### <a id="SQLHandler_ConectorSQL_ObtenerColumnas_System_String_System_String_System_String_System_String_"></a> ObtenerColumnas\(string, string, string, string\)

ObtenerColumnas is a function that retrieves a list of string values from a specified column in a given table of a specified database, with optional conditional statements.

```csharp
public List<string> ObtenerColumnas(string Columna, string Tabla, string BBDD, string Condicionales = "")
```

#### Parameters

`Columna` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the column from which to retrieve values.

`Tabla` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the table from which to retrieve values.

`BBDD` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the database from which to retrieve values.

`Condicionales` [string](https://learn.microsoft.com/dotnet/api/system.string)

(optional) Additional conditional statements to apply to the query.

#### Returns

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

A list of string values retrieved from the specified column.

#### Exceptions

 [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

Thrown when the specified column does not exist.

### <a id="SQLHandler_ConectorSQL_ObtenerConfiguracionZonas"></a> ObtenerConfiguracionZonas\(\)

Obtiene la configuración de las zonas.

```csharp
public ObservableCollection<ConfiguracionZona> ObtenerConfiguracionZonas()
```

#### Returns

 [ObservableCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.observablecollection\-1)<[ConfiguracionZona](SQLHandler.ConfiguracionZona.md)\>

Una ObservableCollection de objetos ConfiguracionZona que representan la configuración de las zonas.

### <a id="SQLHandler_ConectorSQL_SetConfigDB_System_String_"></a> SetConfigDB\(string\)

Especifica la base de datos de configuración de la app.

```csharp
public void SetConfigDB(string DB)
```

#### Parameters

`DB` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConectorSQL_SetDataDB_System_String_"></a> SetDataDB\(string\)

Especifica la base de datos de datos de la app.

```csharp
public void SetDataDB(string DB)
```

#### Parameters

`DB` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConectorSQL_UpdateLoteParte_SQLHandler_ParteTrabajo_System_String_System_String_"></a> UpdateLoteParte\(ParteTrabajo, string, string\)

Actualiza el campo 'Lote' en la tabla 'EK_OrdenesProd' de la base de datos 'EKINDATA'.

```csharp
public void UpdateLoteParte(ParteTrabajo Parte, string LoteViejo, string LoteNuevo)
```

#### Parameters

`Parte` [ParteTrabajo](SQLHandler.ParteTrabajo.md)

El objeto ParteTrabajo que representa la parte a actualizar.

`LoteViejo` [string](https://learn.microsoft.com/dotnet/api/system.string)

El valor antiguo del campo 'Lote' a reemplazar.

`LoteNuevo` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nuevo valor del campo 'Lote' para reemplazar el valor antiguo.

