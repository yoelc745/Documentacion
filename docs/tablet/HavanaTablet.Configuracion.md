# <a id="HavanaTablet_Configuracion"></a> Class Configuracion

Namespace: [HavanaTablet](HavanaTablet.md)  
Assembly: HavanaTablet.dll  

Clase que representa una configuración concreta.
Implementa la interfaz INotifyPropertyChanged para notificar cambios en las propiedades.

```csharp
public class Configuracion : INotifyPropertyChanged
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Configuracion](HavanaTablet.Configuracion.md)

#### Implements

[INotifyPropertyChanged](https://learn.microsoft.com/dotnet/api/system.componentmodel.inotifypropertychanged)

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

### <a id="HavanaTablet_Configuracion_Descripcion"></a> Descripcion

Descripción de la configuración.

```csharp
public string Descripcion { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="HavanaTablet_Configuracion_Id"></a> Id

Identificador de la configuración.

```csharp
public int Id { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="HavanaTablet_Configuracion_Nombre"></a> Nombre

Nombre de la configuración.

```csharp
public string Nombre { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="HavanaTablet_Configuracion_Valor"></a> Valor

Valor asociado a la configuración.

```csharp
public string Valor { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="HavanaTablet_Configuracion_NotifyPropertyChanged_System_String_"></a> NotifyPropertyChanged\(string\)

Método para notificar cambios en una propiedad.

```csharp
public void NotifyPropertyChanged(string propertyName)
```

#### Parameters

`propertyName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nombre de la propiedad que ha cambiado.

### <a id="HavanaTablet_Configuracion_PropertyChanged"></a> PropertyChanged

Evento que se dispara cuando una propiedad cambia su valor.

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

#### Event Type

 [PropertyChangedEventHandler](https://learn.microsoft.com/dotnet/api/system.componentmodel.propertychangedeventhandler)

