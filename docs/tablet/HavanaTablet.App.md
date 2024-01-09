# <a id="HavanaTablet_App"></a> Class App

Namespace: [HavanaTablet](HavanaTablet.md)  
Assembly: HavanaTablet.dll  

Clase de aplicación principal que gestiona la lógica global de la aplicación.

```csharp
public class App : Application, IQueryAmbient
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DispatcherObject](https://learn.microsoft.com/dotnet/api/system.windows.threading.dispatcherobject) ← 
[Application](https://learn.microsoft.com/dotnet/api/system.windows.application) ← 
[App](HavanaTablet.App.md)

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

### <a id="HavanaTablet_App__ctor"></a> App\(\)

Constructor de la clase App.

```csharp
public App()
```

## Fields

### <a id="HavanaTablet_App_ConfigActual"></a> ConfigActual

Lista que contiene la configuración actual de la aplicación.

```csharp
public static List<Configuracion> ConfigActual
```

#### Field Value

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[Configuracion](HavanaTablet.Configuracion.md)\>

### <a id="HavanaTablet_App_DatosDBOffline"></a> DatosDBOffline

Datos de configuración de la base de datos en modo fuera de línea.

```csharp
public static ConfiguracionSQL DatosDBOffline
```

#### Field Value

 [ConfiguracionSQL](HavanaTablet.ConfiguracionSQL.md)

### <a id="HavanaTablet_App_DatosDBOnline"></a> DatosDBOnline

Datos de configuración de la base de datos en modo en línea.

```csharp
public static ConfiguracionSQL DatosDBOnline
```

#### Field Value

 [ConfiguracionSQL](HavanaTablet.ConfiguracionSQL.md)

## Properties

### <a id="HavanaTablet_App_AntenaRFID"></a> AntenaRFID

Dispositivo de antena RFID para la lectura.

```csharp
public static LectorCOM AntenaRFID { get; set; }
```

#### Property Value

 LectorCOM

### <a id="HavanaTablet_App_IsOfflineMode"></a> IsOfflineMode

Indica si la aplicación está en modo fuera de línea.

```csharp
public static bool IsOfflineMode { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="HavanaTablet_App_SQLDataset"></a> SQLDataset

Conjunto de datos SQL para la gestión de datos.

```csharp
public static DataSet SQLDataset { get; set; }
```

#### Property Value

 [DataSet](https://learn.microsoft.com/dotnet/api/system.data.dataset)

### <a id="HavanaTablet_App_SQLHandler"></a> SQLHandler

Manejador SQL para la conexión y manipulación de la base de datos.

```csharp
public static ConectorSQL SQLHandler { get; set; }
```

#### Property Value

 ConectorSQL

### <a id="HavanaTablet_App_SqlAdapterOnline"></a> SqlAdapterOnline

Manejador de adaptadores de SQL para la conexión en línea.

```csharp
public static SqlDataAdapter SqlAdapterOnline { get; set; }
```

#### Property Value

 [SqlDataAdapter](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqldataadapter)

## Methods

### <a id="HavanaTablet_App_ConectarSQL_System_Boolean_"></a> ConectarSQL\(bool\)

Conecta la aplicación con la base de datos SQL Server.

```csharp
public object ConectarSQL(bool Online)
```

#### Parameters

`Online` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Booleano que indica si la conexión es en línea.

#### Returns

 [object](https://learn.microsoft.com/dotnet/api/system.object)

Un objeto con el handler de la base de datos, si no puede conectarse, null.

### <a id="HavanaTablet_App_GetValueFromConfigKey_System_String_"></a> GetValueFromConfigKey\(string\)

Obtiene el valor de configuración para el nombre especificado.

```csharp
public static string GetValueFromConfigKey(string Nombre)
```

#### Parameters

`Nombre` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nombre de la configuración deseada.

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El valor de configuración correspondiente al nombre especificado.

### <a id="HavanaTablet_App_IsInternetAvailable_System_String_"></a> IsInternetAvailable\(string\)

Verifica la disponibilidad de conexión a Internet.

```csharp
public static bool IsInternetAvailable(string Host)
```

#### Parameters

`Host` [string](https://learn.microsoft.com/dotnet/api/system.string)

El host al que se realiza el ping.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Booleano que indica la disponibilidad de conexión.

### <a id="HavanaTablet_App_LoadConfiguracion_System_Collections_Generic_Dictionary_System_String_System_String__"></a> LoadConfiguracion\(Dictionary<string, string\>\)

Carga la configuración inicial de la aplicación desde el archivo .ini.

```csharp
public void LoadConfiguracion(Dictionary<string, string> ConfigData)
```

#### Parameters

`ConfigData` [Dictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.dictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Diccionario que contiene los datos de configuración.

