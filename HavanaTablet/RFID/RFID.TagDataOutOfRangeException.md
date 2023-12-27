# <a id="RFID_TagDataOutOfRangeException"></a> Class TagDataOutOfRangeException

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Excepción que se lanza cuando los datos de la etiqueta están fuera del rango.

```csharp
public class TagDataOutOfRangeException : Exception, ISerializable, _Exception
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[TagDataOutOfRangeException](RFID.TagDataOutOfRangeException.md)

#### Implements

[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), 
[\_Exception](https://learn.microsoft.com/dotnet/api/system.runtime.interopservices.\_exception)

<details open>
  
<summary>Inherited Members</summary>

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

### <a id="RFID_TagDataOutOfRangeException__ctor"></a> TagDataOutOfRangeException\(\)

Inicializa una nueva instancia de la clase <xref href="RFID.TagDataOutOfRangeException" data-throw-if-not-resolved="false"></xref>.

```csharp
public TagDataOutOfRangeException()
```

### <a id="RFID_TagDataOutOfRangeException__ctor_System_String_"></a> TagDataOutOfRangeException\(string\)

Inicializa una nueva instancia de la clase <xref href="RFID.TagDataOutOfRangeException" data-throw-if-not-resolved="false"></xref> con un mensaje de error especificado.

```csharp
public TagDataOutOfRangeException(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

### <a id="RFID_TagDataOutOfRangeException__ctor_System_String_System_Exception_"></a> TagDataOutOfRangeException\(string, Exception\)

Inicializa una nueva instancia de la clase <xref href="RFID.TagDataOutOfRangeException" data-throw-if-not-resolved="false"></xref> con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

```csharp
public TagDataOutOfRangeException(string message, Exception inner)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

`inner` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

La excepción que es la causa de la excepción actual.

