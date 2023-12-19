# <a id="SQLHandler_UIElementConfig"></a> Class UIElementConfig

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Estructura que recoge la configuración XAML de un elemento UI.

```csharp
public class UIElementConfig : INotifyPropertyChanged
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[UIElementConfig](SQLHandler.UIElementConfig.md)

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

## Fields

### <a id="SQLHandler_UIElementConfig_FontSize"></a> FontSize

Tamaño del texto.

```csharp
public int FontSize
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_Height"></a> Height

Altura del elemento.

```csharp
public int Height
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_HexColorBackground"></a> HexColorBackground

Color del fondo en Hexadecimal

```csharp
public string HexColorBackground
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_UIElementConfig_ID"></a> ID

ID del elemento.

```csharp
public int ID
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_Name"></a> Name

x:Name del elemento.

```csharp
public string Name
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="SQLHandler_UIElementConfig_PosBottom"></a> PosBottom

Posición relativa abajo.

```csharp
public int PosBottom
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_PosLeft"></a> PosLeft

Posición relativa a la izquierda.

```csharp
public int PosLeft
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_PosRight"></a> PosRight

Posición relativa a la derecha.

```csharp
public int PosRight
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_PosTop"></a> PosTop

Posición relativa arriba.

```csharp
public int PosTop
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="SQLHandler_UIElementConfig_Width"></a> Width

Anchura del elemento.

```csharp
public int Width
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="SQLHandler_UIElementConfig_NotifyPropertyChanged_System_String_"></a> NotifyPropertyChanged\(string\)

Notifica a los suscriptores que una propiedad ha cambiado.

```csharp
public void NotifyPropertyChanged(string propertyName)
```

#### Parameters

`propertyName` [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre de la propiedad que ha cambiado.

### <a id="SQLHandler_UIElementConfig_PropertyChanged"></a> PropertyChanged

```csharp
public event PropertyChangedEventHandler PropertyChanged
```

#### Event Type

 [PropertyChangedEventHandler](https://learn.microsoft.com/dotnet/api/system.componentmodel.propertychangedeventhandler)

