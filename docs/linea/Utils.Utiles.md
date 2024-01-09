# <a id="Utils_Utiles"></a> Class Utiles

Namespace: [Utils](Utils.md)  
Assembly: Utiles.dll  

Clase que proporciona métodos útiles para operaciones comunes, como hash de datos y manipulación de fechas.

```csharp
public class Utiles
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Utiles](Utils.Utiles.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Methods

### <a id="Utils_Utiles_GetCurrentDate"></a> GetCurrentDate\(\)

Obtiene la fecha y hora actuales en formato de cadena "yyyyMMdd HH:mm:ss".

```csharp
public static string GetCurrentDate()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

La fecha y hora actuales en formato de cadena.

#### Remarks

Visualmente este es el formato ('2020-01-20 03:23:20')

### <a id="Utils_Utiles_Hash256String_System_String_"></a> Hash256String\(string\)

Genera un hash SHA256 de la cadena especificada y devuelve el resultado como una cadena hexadecimal.

```csharp
public static string Hash256String(string value)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

La cadena para la cual se generará el hash.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El hash SHA256 generado como una cadena en formato hexadecimal.

### <a id="Utils_Utiles_Hash512_System_String_System_String_"></a> Hash512\(string, string\)

Genera un hash SHA512 de la cadena especificada junto con la sal proporcionada (opcional).

```csharp
public static string Hash512(string str, string salt = "")
```

#### Parameters

`str` [string](https://learn.microsoft.com/dotnet/api/system.string)

Cadena a hashear.

`salt` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sal utilizada para el hash (opcional).

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El hash generado como una cadena.

