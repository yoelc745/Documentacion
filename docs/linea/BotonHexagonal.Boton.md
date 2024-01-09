# <a id="BotonHexagonal_Boton"></a> Class Boton

Namespace: [BotonHexagonal](BotonHexagonal.md)  
Assembly: BotonHexagonal.dll  

Control de usuario que representa un botón personalizado con propiedades de texto y color configurables.

```csharp
public class Boton : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DispatcherObject](https://learn.microsoft.com/dotnet/api/system.windows.threading.dispatcherobject) ← 
[DependencyObject](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject) ← 
[Visual](https://learn.microsoft.com/dotnet/api/system.windows.media.visual) ← 
[UIElement](https://learn.microsoft.com/dotnet/api/system.windows.uielement) ← 
[FrameworkElement](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement) ← 
[Control](https://learn.microsoft.com/dotnet/api/system.windows.controls.control) ← 
[ContentControl](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol) ← 
[UserControl](https://learn.microsoft.com/dotnet/api/system.windows.controls.usercontrol) ← 
[Boton](BotonHexagonal.Boton.md)

#### Implements

[IAnimatable](https://learn.microsoft.com/dotnet/api/system.windows.media.animation.ianimatable), 
[IFrameworkInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iframeworkinputelement), 
[IInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iinputelement), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[IQueryAmbient](https://learn.microsoft.com/dotnet/api/system.windows.markup.iqueryambient), 
[IAddChild](https://learn.microsoft.com/dotnet/api/system.windows.markup.iaddchild)

## Remarks

Las propiedades disponibles incluyen texto, color de fondo y color del borde del botón.

## Constructors

### <a id="BotonHexagonal_Boton__ctor"></a> Boton\(\)

Constructor de la clase Boton.

```csharp
public Boton()
```

#### Remarks

Inicializa una nueva instancia del botón.

## Properties

### <a id="BotonHexagonal_Boton_ColorBorde"></a> ColorBorde

Color del borde del botón.

```csharp
public SolidColorBrush ColorBorde { get; set; }
```

#### Property Value

 [SolidColorBrush](https://learn.microsoft.com/dotnet/api/system.windows.media.solidcolorbrush)

#### Remarks

Propiedad que define el color del borde del botón.

### <a id="BotonHexagonal_Boton_ColorFondo"></a> ColorFondo

Color de fondo del botón.

```csharp
public SolidColorBrush ColorFondo { get; set; }
```

#### Property Value

 [SolidColorBrush](https://learn.microsoft.com/dotnet/api/system.windows.media.solidcolorbrush)

#### Remarks

Propiedad que define el color de fondo del botón.

### <a id="BotonHexagonal_Boton_Texto"></a> Texto

Texto mostrado en el botón.

```csharp
public string Texto { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Remarks

Propiedad que define el texto visible en el botón.

## Methods

### <a id="BotonHexagonal_Boton_BindOnClickEvent_System_Windows_Input_MouseButtonEventHandler_"></a> BindOnClickEvent\(MouseButtonEventHandler\)

Vincula un evento de clic al botón.

```csharp
public void BindOnClickEvent(MouseButtonEventHandler e)
```

#### Parameters

`e` [MouseButtonEventHandler](https://learn.microsoft.com/dotnet/api/system.windows.input.mousebuttoneventhandler)

Controlador de eventos para el clic del botón.

#### Remarks

Establece un evento de clic para el botón al manipulador proporcionado.

