# <a id="SQLHandler_Parte"></a> Class Parte

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

```csharp
public class Parte
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Parte](SQLHandler.Parte.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="SQLHandler_Parte__ctor_SQLHandler_Parte_TipoParte_"></a> Parte\(TipoParte\)

Inicia un nuevo parte de trabajo.

```csharp
public Parte(Parte.TipoParte tipoParte)
```

#### Parameters

`tipoParte` [Parte](SQLHandler.Parte.md).[TipoParte](SQLHandler.Parte.TipoParte.md)

Tipo de parte definido.

## Methods

### <a id="SQLHandler_Parte_GetFechaCreacion"></a> GetFechaCreacion\(\)

Obtiene la fecha en la cuál se ha creado el parte de trabajo.

```csharp
public string GetFechaCreacion()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

string

### <a id="SQLHandler_Parte_GetTipo"></a> GetTipo\(\)

Obtiene el codigo de tipo de parte de trabajo actual.

```csharp
public string GetTipo()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

TipoParte

### <a id="SQLHandler_Parte_GetTipoString"></a> GetTipoString\(\)

Obtiene el tipo de parte en formato descriptivo.

```csharp
public string GetTipoString()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_Parte_GetTypeOfParte_System_String_"></a> GetTypeOfParte\(string\)

Obtiene el tipo de parte especificando el tipo de código de parte.

```csharp
public static Parte.TipoParte GetTypeOfParte(string CodigoParte)
```

#### Parameters

`CodigoParte` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [Parte](SQLHandler.Parte.md).[TipoParte](SQLHandler.Parte.TipoParte.md)

