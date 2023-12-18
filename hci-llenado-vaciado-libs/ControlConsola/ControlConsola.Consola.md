# <a id="ControlConsola_Consola"></a> Class Consola

Namespace: [ControlConsola](ControlConsola.md)  
Assembly: ControlConsola.dll  

Componente que crea la consola para ir mostrando mensajes de estado.

```csharp
public class Consola : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild
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
[Consola](ControlConsola.Consola.md)

#### Implements

[IAnimatable](https://learn.microsoft.com/dotnet/api/system.windows.media.animation.ianimatable), 
[IFrameworkInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iframeworkinputelement), 
[IInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iinputelement), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[IQueryAmbient](https://learn.microsoft.com/dotnet/api/system.windows.markup.iqueryambient), 
[IAddChild](https://learn.microsoft.com/dotnet/api/system.windows.markup.iaddchild)



## Constructors

### <a id="ControlConsola_Consola__ctor"></a> Consola\(\)

Constructor de la consola.

```csharp
public Consola()
```

## Methods

### <a id="ControlConsola_Consola_AddLogMessage_System_String_"></a> AddLogMessage\(string\)

Añade un nuevo mensaje al pool para mostrar.

```csharp
public void AddLogMessage(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Mensaje para añadir al pool.

### <a id="ControlConsola_Consola_ClearConsole"></a> ClearConsole\(\)

Limpia la consola eliminando todos los elementos del control GridConsola y actualizándolo.

```csharp
public void ClearConsole()
```

### <a id="ControlConsola_Consola_SetDarkMode"></a> SetDarkMode\(\)

Cambia la consola a modo oscuro.

```csharp
public void SetDarkMode()
```

### <a id="ControlConsola_Consola_StartConsola"></a> StartConsola\(\)

Empieza a mostrar mensajes en la consola.

```csharp
public void StartConsola()
```

