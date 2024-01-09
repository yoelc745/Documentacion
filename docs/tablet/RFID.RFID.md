# <a id="RFID_RFID"></a> Class RFID

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Clase obsoleta con la versión antigua de lector RFID.

```csharp
public class RFID
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[RFID](RFID.RFID.md)

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

## Fields

### <a id="RFID_RFID_SQLConnection"></a> SQLConnection

Obtiene o establece la conexión SQL.

```csharp
public SqlConnection SQLConnection
```

#### Field Value

 [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

### <a id="RFID_RFID_TransponderActual"></a> TransponderActual

Obtiene o establece la etiqueta RFID actual.

```csharp
public TagRFID TransponderActual
```

#### Field Value

 [TagRFID](RFID.TagRFID.md)

## Properties

### <a id="RFID_RFID_IdTransponder"></a> IdTransponder

Obtiene o establece el identificador del transpondedor.

```csharp
public string IdTransponder { get; set; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="RFID_RFID_IsReadingBRM"></a> IsReadingBRM

Obtiene o establece un valor que indica si se está leyendo el BRM.

```csharp
public bool IsReadingBRM { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="RFID_RFID_OnFewTransponders_ObservableHashSet_System_String__"></a> OnFewTransponders\(ObservableHashSet<string\>\)

Genera el evento <xref href="RFID.RFID.FewTransponders" data-throw-if-not-resolved="false"></xref>.

```csharp
protected virtual void OnFewTransponders(ObservableHashSet<string> Transponders)
```

#### Parameters

`Transponders` ObservableHashSet<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Los transpondedores detectados.

### <a id="RFID_RFID_OnTransponderReconocido_ObservableHashSet_System_String__"></a> OnTransponderReconocido\(ObservableHashSet<string\>\)

Genera el evento <xref href="RFID.RFID.TransponderReconocido" data-throw-if-not-resolved="false"></xref>.

```csharp
protected virtual void OnTransponderReconocido(ObservableHashSet<string> Transponder)
```

#### Parameters

`Transponder` ObservableHashSet<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

El transpondedor reconocido.

### <a id="RFID_RFID_FewTransponders"></a> FewTransponders

Evento que se produce cuando se detectan pocos transpondedores.

```csharp
public event EventHandler<ObservableHashSet<string>> FewTransponders
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<ObservableHashSet<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

### <a id="RFID_RFID_TransponderReconocido"></a> TransponderReconocido

Evento que envía el RFID cuando se han reconocido transponders.

```csharp
public event EventHandler<ObservableHashSet<string>> TransponderReconocido
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<ObservableHashSet<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

