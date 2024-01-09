# <a id="CustomControl_ExtendedTextBox"></a> Class ExtendedTextBox

Namespace: [CustomControl](CustomControl.md)  
Assembly: ExtendedTextBox.dll  

Control de caja de texto extendida con validación de datos según el tipo definido.

```csharp
public class ExtendedTextBox : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild
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
[ExtendedTextBox](CustomControl.ExtendedTextBox.md)

#### Implements

[IAnimatable](https://learn.microsoft.com/dotnet/api/system.windows.media.animation.ianimatable), 
[IFrameworkInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iframeworkinputelement), 
[IInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iinputelement), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[IQueryAmbient](https://learn.microsoft.com/dotnet/api/system.windows.markup.iqueryambient), 
[IAddChild](https://learn.microsoft.com/dotnet/api/system.windows.markup.iaddchild)

## Constructors

### <a id="CustomControl_ExtendedTextBox__ctor"></a> ExtendedTextBox\(\)

Constructor de la clase ExtendedTextBox.

```csharp
public ExtendedTextBox()
```

## Properties

### <a id="CustomControl_ExtendedTextBox_HeaderTitle"></a> HeaderTitle

Texto que aparece en la cabecera del control.

```csharp
public string HeaderTitle { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="CustomControl_ExtendedTextBox_PlaceHolder"></a> PlaceHolder

Texto que aparece en la caja sin seleccionar el control.

```csharp
public string PlaceHolder { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="CustomControl_ExtendedTextBox_dataType"></a> dataType

Texto que aparece en la caja sin seleccionar el control.

```csharp
public string dataType { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="CustomControl_ExtendedTextBox_GetContent"></a> GetContent\(\)

Obtiene el contenido actual del cuadro de texto, excluyendo mensajes de error.

```csharp
public string GetContent()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El contenido actual del cuadro de texto si no es un mensaje de error, de lo contrario, una cadena vacía.

### <a id="CustomControl_ExtendedTextBox_GuardarValor_System_String_CustomControl_ExtendedTextBox_DataType_"></a> GuardarValor\(string, DataType\)

Guarda el valor especificado en el textbox y valida su tipo de dato.

```csharp
public void GuardarValor(string Valor, ExtendedTextBox.DataType TipoDato)
```

#### Parameters

`Valor` [string](https://learn.microsoft.com/dotnet/api/system.string)

El valor a ser guardado en el textbox.

`TipoDato` [ExtendedTextBox](CustomControl.ExtendedTextBox.md).[DataType](CustomControl.ExtendedTextBox.DataType.md)

El tipo de dato del valor a ser guardado.

