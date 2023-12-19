# <a id="LectorFEIG_TagUpdateError"></a> Class TagUpdateError

Namespace: [LectorFEIG](LectorFEIG.md)  
Assembly: LectorFEIGCOM.dll  

Define una clase que representa una excepción personalizada que se produce cuando hay un error al actualizar los datos de una etiqueta RFID.

```csharp
public class TagUpdateError : Exception, ISerializable, _Exception
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[TagUpdateError](LectorFEIG.TagUpdateError.md)

#### Implements

[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), 
[\_Exception](https://learn.microsoft.com/dotnet/api/system.runtime.interopservices.\_exception)

<details open>
  <summary> Inherited Members </summary>

[Exception.GetBaseException\(\)](https://learn.microsoft.com/dotnet/api/system.exception.getbaseexception), 
[Exception.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.exception.tostring), 
[Exception.GetObjectData\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.exception.getobjectdata), 
[Exception.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.exception.gettype), 
[Exception.Message](https://learn.microsoft.com/dotnet/api/system.exception.message), 
[Exception.Data](https://learn.microsoft.com/dotnet/api/system.exception.data), 
[Exception.InnerException](https://learn.microsoft.com/dotnet/api/system.exception.innerexception), 
[Exception.TargetSite](https://learn.microsoft.com/dotnet/api/system.exception.targetsite), 
[Exception.StackTrace](https://learn.microsoft.com/dotnet/api/system.exception.stacktrace), 
[Exception.HelpLink](https://learn.microsoft.com/dotnet/api/system.exception.helplink), 
[Exception.Source](https://learn.microsoft.com/dotnet/api/system.exception.source), 
[Exception.HResult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), 
[Exception.SerializeObjectState](https://learn.microsoft.com/dotnet/api/system.exception.serializeobjectstate), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)
</details>

## Constructors

### <a id="LectorFEIG_TagUpdateError__ctor"></a> TagUpdateError\(\)

Inicializa una nueva instancia de la clase TagUpdateError sin especificar un mensaje de error.

```csharp
public TagUpdateError()
```

### <a id="LectorFEIG_TagUpdateError__ctor_System_String_"></a> TagUpdateError\(string\)

Inicializa una nueva instancia de la clase TagUpdateError con un mensaje de error especificado.

```csharp
public TagUpdateError(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

### <a id="LectorFEIG_TagUpdateError__ctor_System_String_System_Exception_"></a> TagUpdateError\(string, Exception\)

Inicializa una nueva instancia de la clase TagUpdateError con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

```csharp
public TagUpdateError(string message, Exception inner)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

`inner` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

La excepción que es la causa de la excepción actual, o una referencia nula si no se especifica ninguna excepción interna.

