# <a id="LectorINI_Reader"></a> Class Reader

Namespace: [LectorINI](LectorINI.md)  
Assembly: LectorINI.dll  

Clase que alberga el lector de archivos de configuración.

```csharp
public class Reader
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Reader](LectorINI.Reader.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="LectorINI_Reader__ctor_System_String_"></a> Reader\(string\)

Crea el lector de configuración del archivo especificado.

```csharp
public Reader(string FilePath)
```

#### Parameters

`FilePath` [string](https://learn.microsoft.com/dotnet/api/system.string)

Ruta al archivo de configuración.

#### Exceptions

 [INIFileNotFound](LectorINI.INIFileNotFound.md)

 [InvalidFileException](LectorINI.InvalidFileException.md)

## Fields

### <a id="LectorINI_Reader_DiccionarioValores"></a> DiccionarioValores

Array que alberga las líneas del archivo de configuración.

```csharp
public List<(string Key, string Value)> DiccionarioValores
```

#### Field Value

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<\([string](https://learn.microsoft.com/dotnet/api/system.string) [Key](https://learn.microsoft.com/dotnet/api/system.valuetuple\-system.string,system.string\-.key), [string](https://learn.microsoft.com/dotnet/api/system.string) [Value](https://learn.microsoft.com/dotnet/api/system.valuetuple\-system.string,system.string\-.value)\)\>

## Methods

### <a id="LectorINI_Reader_ConvertFileToDictionary"></a> ConvertFileToDictionary\(\)

Convierte un archivo en un diccionario de pares clave-valor.

```csharp
public Dictionary<string, string> ConvertFileToDictionary()
```

#### Returns

 [Dictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.dictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Un diccionario con claves de tipo string y valores de tipo string.

### <a id="LectorINI_Reader_GetParameter_System_String_"></a> GetParameter\(string\)

Obtiene el parámetro especificado del archivo de configuración.

```csharp
public string GetParameter(string Parameter)
```

#### Parameters

`Parameter` [string](https://learn.microsoft.com/dotnet/api/system.string)

Parámetro a buscar.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Exceptions

 [ParameterNotFound](LectorINI.ParameterNotFound.md)

### <a id="LectorINI_Reader_WriteParameter_System_String_System_String_"></a> WriteParameter\(string, string\)

Escribe el parámetro especificado en el archivo de configuración.

```csharp
public void WriteParameter(string Parameter, string Value)
```

#### Parameters

`Parameter` [string](https://learn.microsoft.com/dotnet/api/system.string)

Parámetro a escribir

`Value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Valor a escribir

