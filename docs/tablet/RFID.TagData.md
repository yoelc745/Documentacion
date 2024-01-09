# <a id="RFID_TagData"></a> Class TagData

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Clase que representa los datos de una etiqueta.

```csharp
public class TagData
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TagData](RFID.TagData.md)

<details open>
  
<summary>Inherited Members</summary>

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)
</details>

## Properties

### <a id="RFID_TagData_CodigoBarril"></a> CodigoBarril

Obtiene o establece el código de barril.

```csharp
public string CodigoBarril { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_CodigoPalet"></a> CodigoPalet

Obtiene o establece el código de palet.

```csharp
public string CodigoPalet { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_Densidad"></a> Densidad

Obtiene o establece la densidad.

```csharp
public string Densidad { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_Fecha"></a> Fecha

Obtiene o establece la fecha.

```csharp
public string Fecha { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_GradoAlcoholico"></a> GradoAlcoholico

Obtiene o establece el grado alcohólico.

```csharp
public string GradoAlcoholico { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_Localizacion"></a> Localizacion

Obtiene o establece la localización.

```csharp
public string Localizacion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_Lote"></a> Lote

Obtiene o establece el lote.

```csharp
public string Lote { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_TipoBase"></a> TipoBase

Obtiene o establece el tipo de base.

```csharp
public string TipoBase { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_TagData_Volumen"></a> Volumen

Obtiene o establece el volumen.

```csharp
public string Volumen { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="RFID_TagData_DestructureToString"></a> DestructureToString\(\)

Devuelve una cadena que representa los datos de la etiqueta.

```csharp
public string DestructureToString()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

Una cadena que representa los datos de la etiqueta.

### <a id="RFID_TagData_GetFromString_System_String_"></a> GetFromString\(string\)

Devuelve una instancia de <xref href="RFID.TagData" data-throw-if-not-resolved="false"></xref> a partir de una cadena.

```csharp
public static TagData GetFromString(string Data)
```

#### Parameters

`Data` [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena que contiene los datos de la etiqueta.

#### Returns

 [TagData](RFID.TagData.md)

Una instancia de <xref href="RFID.TagData" data-throw-if-not-resolved="false"></xref>.

