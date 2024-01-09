# <a id="SQLHandler_ConfiguracionZona"></a> Class ConfiguracionZona

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que alberga la estructura con la configuración de la zona.

```csharp
public class ConfiguracionZona : INotifyPropertyChanged
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ConfiguracionZona](SQLHandler.ConfiguracionZona.md)

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

## Properties

### <a id="SQLHandler_ConfiguracionZona_Activa"></a> Activa

Especifica si la zona está activa o no.

```csharp
public bool Activa { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ConfiguracionZona_Address_Watchdog"></a> Address\_Watchdog

Dirección IP del Watchdog del PLC.

```csharp
public string Address_Watchdog { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_Bascula_MinPeso"></a> Bascula\_MinPeso

Peso mínimo para que la báscula lo reconozca.

```csharp
public int Bascula_MinPeso { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Bascula_PesaEstable"></a> Bascula\_PesaEstable

Especifica si la báscula tiene que pesar cuando está estable o no.

```csharp
public bool Bascula_PesaEstable { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ConfiguracionZona_Bascula_PesaMin"></a> Bascula\_PesaMin

Especifica si la báscula tiene un peso mínimo para funcionar.

```csharp
public bool Bascula_PesaMin { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ConfiguracionZona_DensidadRon"></a> DensidadRon

Especifica la constante de la densidad del ron en cada zona.

```csharp
public float DensidadRon { get; set; }
```

#### Property Value

 [float](https://learn.microsoft.com/dotnet/api/system.single)

### <a id="SQLHandler_ConfiguracionZona_Desc_Zona"></a> Desc\_Zona

Descripción de la zona.

```csharp
public string? Desc_Zona { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="SQLHandler_ConfiguracionZona_EsZonaDeEntrada"></a> EsZonaDeEntrada

Especifica la constante de la densidad del ron en cada zona.

```csharp
public int EsZonaDeEntrada { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_ID_Zona"></a> ID\_Zona

ID númerico de la zona.

```csharp
public int ID_Zona { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_IP_Bascula"></a> IP\_Bascula

Dirección IP de la báscula.

```csharp
public string IP_Bascula { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_IP_PLC"></a> IP\_PLC

Dirección IP del PLC.

```csharp
public string IP_PLC { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_IP_RFID"></a> IP\_RFID

Dirección IP del RFID.

```csharp
public string IP_RFID { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_Log_Prefix_Zona"></a> Log\_Prefix\_Zona

Prefijo del archivo de log de la zona.

```csharp
public string Log_Prefix_Zona { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_PLC_EstadoLinea"></a> PLC\_EstadoLinea

Especifica la variable del PLC donde se leerá el estado de la línea.

```csharp
public string PLC_EstadoLinea { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_PLC_FinalZona"></a> PLC\_FinalZona

Especifica la variable del PLC que nos avisará de presencia en la fotocélula.

```csharp
public string PLC_FinalZona { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_PLC_PesajeOK"></a> PLC\_PesajeOK

Especifica la variable del PLC a la cuál se le mandará la opción de avance.

```csharp
public string PLC_PesajeOK { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_PLC_PesajeRDY"></a> PLC\_PesajeRDY

Especifica la variable que recibe cuando el PLC envía la señal de que la zona está lista para pesar.

```csharp
public string PLC_PesajeRDY { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_PLC_Transfer"></a> PLC\_Transfer

```csharp
public string PLC_Transfer { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_PLC_Transponder_Leido"></a> PLC\_Transponder\_Leido

Esoecifica la variable del PLC a la cuál se enviará el evento de transponder reconocido.

```csharp
public string PLC_Transponder_Leido { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_Pass_PLC"></a> Pass\_PLC

Contraseña del PLC.

```csharp
public string Pass_PLC { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_Port_Bascula"></a> Port\_Bascula

Puerto activo de la báscula.

```csharp
public int Port_Bascula { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Port_RFID"></a> Port\_RFID

Puerto activo del RFID

```csharp
public int Port_RFID { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Puerto_PLC"></a> Puerto\_PLC

Puerto activo del PLC.

```csharp
public int Puerto_PLC { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Rack_PLC"></a> Rack\_PLC

Rack al cuál conectarse del PLC.

```csharp
public int Rack_PLC { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Slot_PLC"></a> Slot\_PLC

Slot al cuál conectarse del PLC.

```csharp
public int Slot_PLC { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Tag_Test_Der"></a> Tag\_Test\_Der

```csharp
public string Tag_Test_Der { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_Tag_Test_Izq"></a> Tag\_Test\_Izq

```csharp
public string Tag_Test_Izq { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_TimeoutBascula"></a> TimeoutBascula

Tiempo en milisegundos de espera de la báscula.

```csharp
public int? TimeoutBascula { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="SQLHandler_ConfiguracionZona_TimeoutPLC"></a> TimeoutPLC

Tiempo en milisegundos de espera del PLC.

```csharp
public int? TimeoutPLC { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="SQLHandler_ConfiguracionZona_TimeoutRFID"></a> TimeoutRFID

Tiempo en milisegundos de espera del RFID.

```csharp
public int? TimeoutRFID { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="SQLHandler_ConfiguracionZona_Timer_Bascula"></a> Timer\_Bascula

Milisegundos del bucle interno de la báscula.

```csharp
public int Timer_Bascula { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Timer_RFID"></a> Timer\_RFID

Milisegundos del bucle interno del RFID.

```csharp
public int Timer_RFID { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Tipo"></a> Tipo

Tipo de la zona.

```csharp
public int Tipo { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_User_PLC"></a> User\_PLC

Usuario del PLC.

```csharp
public string User_PLC { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionZona_Valor_Watchdog_PLC"></a> Valor\_Watchdog\_PLC

Valor que espera el Watchdog.

```csharp
public int Valor_Watchdog_PLC { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Watchdog_Activo"></a> Watchdog\_Activo

Especifica si el Watchdog está activo o no.

```csharp
public bool Watchdog_Activo { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="SQLHandler_ConfiguracionZona_Watchdog_FailMax"></a> Watchdog\_FailMax

Veces que el Watchdog permite el fallo.

```csharp
public int Watchdog_FailMax { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionZona_Watchdog_PLC"></a> Watchdog\_PLC

Tiempo de comprobación del Watchdog del PLC.

```csharp
public int Watchdog_PLC { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="SQLHandler_ConfiguracionZona_NotifyPropertyChanged_System_String_"></a> NotifyPropertyChanged\(string\)

Notifica que una propiedad ha cambiado.

```csharp
public void NotifyPropertyChanged(string propertyName)
```

#### Parameters

`propertyName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nombre de la propiedad que ha cambiado.

### <a id="SQLHandler_ConfiguracionZona_PropertyChanged"></a> PropertyChanged

Evento que se dispara cuando una propiedad cambia.

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

#### Event Type

 [PropertyChangedEventHandler](https://learn.microsoft.com/dotnet/api/system.componentmodel.propertychangedeventhandler)

