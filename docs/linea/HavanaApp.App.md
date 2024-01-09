# <a id="HavanaApp_App"></a> Class App

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Lógica de inicio de la aplicación.

```csharp
public class App : Application, IQueryAmbient
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DispatcherObject](https://learn.microsoft.com/dotnet/api/system.windows.threading.dispatcherobject) ← 
[Application](https://learn.microsoft.com/dotnet/api/system.windows.application) ← 
[App](HavanaApp.App.md)

#### Implements

[IQueryAmbient](https://learn.microsoft.com/dotnet/api/system.windows.markup.iqueryambient)

#### Inherited Members

[Application.Run\(\)](https://learn.microsoft.com/dotnet/api/system.windows.application.run\#system\-windows\-application\-run), 
[Application.Run\(Window\)](https://learn.microsoft.com/dotnet/api/system.windows.application.run\#system\-windows\-application\-run\(system\-windows\-window\)), 
[Application.Shutdown\(\)](https://learn.microsoft.com/dotnet/api/system.windows.application.shutdown\#system\-windows\-application\-shutdown), 
[Application.Shutdown\(int\)](https://learn.microsoft.com/dotnet/api/system.windows.application.shutdown\#system\-windows\-application\-shutdown\(system\-int32\)), 
[Application.FindResource\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.application.findresource), 
[Application.TryFindResource\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.application.tryfindresource), 
[Application.LoadComponent\(object, Uri\)](https://learn.microsoft.com/dotnet/api/system.windows.application.loadcomponent\#system\-windows\-application\-loadcomponent\(system\-object\-system\-uri\)), 
[Application.LoadComponent\(Uri\)](https://learn.microsoft.com/dotnet/api/system.windows.application.loadcomponent\#system\-windows\-application\-loadcomponent\(system\-uri\)), 
[Application.GetResourceStream\(Uri\)](https://learn.microsoft.com/dotnet/api/system.windows.application.getresourcestream), 
[Application.GetContentStream\(Uri\)](https://learn.microsoft.com/dotnet/api/system.windows.application.getcontentstream), 
[Application.GetRemoteStream\(Uri\)](https://learn.microsoft.com/dotnet/api/system.windows.application.getremotestream), 
[Application.GetCookie\(Uri\)](https://learn.microsoft.com/dotnet/api/system.windows.application.getcookie), 
[Application.SetCookie\(Uri, string\)](https://learn.microsoft.com/dotnet/api/system.windows.application.setcookie), 
[Application.OnStartup\(StartupEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onstartup), 
[Application.OnExit\(ExitEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onexit), 
[Application.OnActivated\(EventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onactivated), 
[Application.OnDeactivated\(EventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.ondeactivated), 
[Application.OnSessionEnding\(SessionEndingCancelEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onsessionending), 
[Application.OnNavigating\(NavigatingCancelEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onnavigating), 
[Application.OnNavigated\(NavigationEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onnavigated), 
[Application.OnNavigationProgress\(NavigationProgressEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onnavigationprogress), 
[Application.OnNavigationFailed\(NavigationFailedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onnavigationfailed), 
[Application.OnLoadCompleted\(NavigationEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onloadcompleted), 
[Application.OnNavigationStopped\(NavigationEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onnavigationstopped), 
[Application.OnFragmentNavigation\(FragmentNavigationEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.application.onfragmentnavigation), 
[Application.Current](https://learn.microsoft.com/dotnet/api/system.windows.application.current), 
[Application.Windows](https://learn.microsoft.com/dotnet/api/system.windows.application.windows), 
[Application.MainWindow](https://learn.microsoft.com/dotnet/api/system.windows.application.mainwindow), 
[Application.ShutdownMode](https://learn.microsoft.com/dotnet/api/system.windows.application.shutdownmode), 
[Application.Resources](https://learn.microsoft.com/dotnet/api/system.windows.application.resources), 
[Application.StartupUri](https://learn.microsoft.com/dotnet/api/system.windows.application.startupuri), 
[Application.Properties](https://learn.microsoft.com/dotnet/api/system.windows.application.properties), 
[Application.ResourceAssembly](https://learn.microsoft.com/dotnet/api/system.windows.application.resourceassembly), 
[Application.Startup](https://learn.microsoft.com/dotnet/api/system.windows.application.startup), 
[Application.Exit](https://learn.microsoft.com/dotnet/api/system.windows.application.exit), 
[Application.Activated](https://learn.microsoft.com/dotnet/api/system.windows.application.activated), 
[Application.Deactivated](https://learn.microsoft.com/dotnet/api/system.windows.application.deactivated), 
[Application.SessionEnding](https://learn.microsoft.com/dotnet/api/system.windows.application.sessionending), 
[Application.DispatcherUnhandledException](https://learn.microsoft.com/dotnet/api/system.windows.application.dispatcherunhandledexception), 
[Application.Navigating](https://learn.microsoft.com/dotnet/api/system.windows.application.navigating), 
[Application.Navigated](https://learn.microsoft.com/dotnet/api/system.windows.application.navigated), 
[Application.NavigationProgress](https://learn.microsoft.com/dotnet/api/system.windows.application.navigationprogress), 
[Application.NavigationFailed](https://learn.microsoft.com/dotnet/api/system.windows.application.navigationfailed), 
[Application.LoadCompleted](https://learn.microsoft.com/dotnet/api/system.windows.application.loadcompleted), 
[Application.NavigationStopped](https://learn.microsoft.com/dotnet/api/system.windows.application.navigationstopped), 
[Application.FragmentNavigation](https://learn.microsoft.com/dotnet/api/system.windows.application.fragmentnavigation), 
[DispatcherObject.Dispatcher](https://learn.microsoft.com/dotnet/api/system.windows.threading.dispatcherobject.dispatcher), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="HavanaApp_App__ctor"></a> App\(\)

Constructor que inicia la aplicación.

```csharp
public App()
```

## Fields

### <a id="HavanaApp_App_ParametrosAppActuales"></a> ParametrosAppActuales

Objeto que guarda la configuración de la aplicación.

```csharp
public ParametrosApp ParametrosAppActuales
```

#### Field Value

 ParametrosApp

### <a id="HavanaApp_App_db"></a> db

Objeto que guarda la conexión a la base de datos.

```csharp
public ConectorSQL db
```

#### Field Value

 ConectorSQL

