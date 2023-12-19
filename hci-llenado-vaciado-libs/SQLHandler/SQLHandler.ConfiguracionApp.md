# <a id="SQLHandler_ConfiguracionApp"></a> Class ConfiguracionApp

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que alberga la estructura de los campos de configuración de la app.

```csharp
public class ConfiguracionApp : INotifyPropertyChanged
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ConfiguracionApp](SQLHandler.ConfiguracionApp.md)

#### Implements

[INotifyPropertyChanged](https://learn.microsoft.com/dotnet/api/system.componentmodel.inotifypropertychanged)

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

### <a id="SQLHandler_ConfiguracionApp_Ayuda"></a> Ayuda

Ayuda descriptiva del campo.

```csharp
public string Ayuda { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionApp_ID"></a> ID

Id del campo.

```csharp
public int ID { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_ConfiguracionApp_Nombre"></a> Nombre

Descripción del campo.

```csharp
public string Nombre { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_ConfiguracionApp_Valor"></a> Valor

Valor que alberga el campo.

```csharp
public string Valor { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="SQLHandler_ConfiguracionApp_NotifyPropertyChanged_System_String_"></a> NotifyPropertyChanged\(string\)

Notifica que una propiedad ha cambiado.

```csharp
public void NotifyPropertyChanged(string propertyName)
```

#### Parameters

`propertyName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nombre de la propiedad que ha cambiado.

### <a id="SQLHandler_ConfiguracionApp_PropertyChanged"></a> PropertyChanged

Evento que se dispara cuando una propiedad cambia.

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

#### Event Type

 [PropertyChangedEventHandler](https://learn.microsoft.com/dotnet/api/system.componentmodel.propertychangedeventhandler)

