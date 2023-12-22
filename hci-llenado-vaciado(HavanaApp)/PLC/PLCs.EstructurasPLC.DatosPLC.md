# <a id="PLCs_EstructurasPLC_DatosPLC"></a> Struct EstructurasPLC.DatosPLC

Namespace: [PLCs](PLCs.md)  
Assembly: PLC.dll  

Estructura que representa los datos del PLC.

```csharp
public struct EstructurasPLC.DatosPLC
```

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype)

## Remarks

Contiene propiedades para la zona, la dirección, el tipo de operación, el valor y la fecha asociados a los datos del PLC.

## Properties

### <a id="PLCs_EstructurasPLC_DatosPLC_Address"></a> Address

Dirección asociada a los datos del PLC.

```csharp
public string Address { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Remarks

Propiedad que representa la dirección en la estructura de datos del PLC.

### <a id="PLCs_EstructurasPLC_DatosPLC_Date"></a> Date

Fecha asociada a los datos del PLC.

```csharp
public string Date { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Remarks

Propiedad que representa la fecha en la estructura de datos del PLC.

### <a id="PLCs_EstructurasPLC_DatosPLC_TipoOperacion"></a> TipoOperacion

Tipo de operación asociada a los datos del PLC.

```csharp
public EstructurasPLC.TipoOperacion TipoOperacion { get; set; }
```

#### Property Value

 [EstructurasPLC](PLCs.EstructurasPLC.md).[TipoOperacion](PLCs.EstructurasPLC.TipoOperacion.md)

#### Remarks

Propiedad que representa el tipo de operación en la estructura de datos del PLC.

### <a id="PLCs_EstructurasPLC_DatosPLC_Value"></a> Value

Valor asociado a los datos del PLC.

```csharp
public int Value { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Remarks

Propiedad que representa el valor en la estructura de datos del PLC.

### <a id="PLCs_EstructurasPLC_DatosPLC_Zona"></a> Zona

Número de la zona asociada a los datos del PLC.

```csharp
public int Zona { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Remarks

Propiedad que representa el número de la zona en la estructura de datos del PLC.

