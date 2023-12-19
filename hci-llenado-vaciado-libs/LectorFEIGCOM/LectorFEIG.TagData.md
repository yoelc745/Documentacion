# <a id="LectorFEIG_TagData"></a> Class TagData

Namespace: [LectorFEIG](LectorFEIG.md)  
Assembly: LectorFEIGCOM.dll  

```csharp
public class TagData
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TagData](LectorFEIG.TagData.md)

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

### <a id="LectorFEIG_TagData_CodigoBarril"></a> CodigoBarril

Obtiene o establece el código del barril.

```csharp
public string CodigoBarril { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_CodigoPalet"></a> CodigoPalet

Obtiene o establece el código del palet al que pertenece el barril.

```csharp
public string CodigoPalet { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_Densidad"></a> Densidad

Obtiene o establece la densidad del alcohol del barril en gramos por mililitro.

```csharp
public string Densidad { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_Fecha"></a> Fecha

Obtiene o establece la fecha de producción del barril.

```csharp
public string Fecha { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_GradoAlcoholico"></a> GradoAlcoholico

Obtiene o establece el grado alcohólico del barril.

```csharp
public string GradoAlcoholico { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_Localizacion"></a> Localizacion

Obtiene o establece la localización del barril en el almacén.

```csharp
public string Localizacion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_Lote"></a> Lote

Obtiene o establece el lote al que pertenece el barril.

```csharp
public string Lote { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_TipoBase"></a> TipoBase

Obtiene o establece el tipo de base del alcohol del barril.

```csharp
public string TipoBase { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorFEIG_TagData_Volumen"></a> Volumen

Obtiene o establece el volumen del barril en litros.

```csharp
public string Volumen { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="LectorFEIG_TagData_DecodeDataFromTag_System_String_"></a> DecodeDataFromTag\(string\)

Decodifica los datos de la etiqueta a partir de una cadena de texto en formato Base64 usando el algoritmo de descompresión Brotli.

```csharp
public static string DecodeDataFromTag(string EncodedData)
```

#### Parameters

`EncodedData` [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena de texto codificada en Base64.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena de texto que contiene los datos de la etiqueta.

### <a id="LectorFEIG_TagData_DestructureToString"></a> DestructureToString\(\)

Convierte los datos de la etiqueta en una cadena de texto separada por el carácter '#'.

```csharp
public string DestructureToString()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena de texto que contiene los datos de la etiqueta.

### <a id="LectorFEIG_TagData_EncodeDataForTag_System_String_"></a> EncodeDataForTag\(string\)

Codifica los datos de la etiqueta en una cadena de texto en formato Base64.

```csharp
public static string EncodeDataForTag(string Data)
```

#### Parameters

`Data` [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena de texto que contiene los datos de la etiqueta.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena de texto codificada en Base64.

### <a id="LectorFEIG_TagData_GetFromString_System_String_"></a> GetFromString\(string\)

Obtiene los datos de la etiqueta a partir de una cadena de texto separada por el carácter '#'.

```csharp
public static TagData GetFromString(string Data)
```

#### Parameters

`Data` [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena de texto que contiene los datos de la etiqueta.

#### Returns

 [TagData](LectorFEIG.TagData.md)

Un objeto de la clase TagData con los datos de la etiqueta.

