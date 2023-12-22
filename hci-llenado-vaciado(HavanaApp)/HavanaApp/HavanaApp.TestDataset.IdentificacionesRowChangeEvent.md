# <a id="HavanaApp_TestDataset_IdentificacionesRowChangeEvent"></a> Class TestDataset.IdentificacionesRowChangeEvent

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Row event argument class

```csharp
public class TestDataset.IdentificacionesRowChangeEvent : EventArgs
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[TestDataset.IdentificacionesRowChangeEvent](HavanaApp.TestDataset.IdentificacionesRowChangeEvent.md)

#### Inherited Members

[EventArgs.Empty](https://learn.microsoft.com/dotnet/api/system.eventargs.empty), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="HavanaApp_TestDataset_IdentificacionesRowChangeEvent__ctor_HavanaApp_TestDataset_IdentificacionesRow_System_Data_DataRowAction_"></a> IdentificacionesRowChangeEvent\(IdentificacionesRow, DataRowAction\)

```csharp
public IdentificacionesRowChangeEvent(TestDataset.IdentificacionesRow row, DataRowAction action)
```

#### Parameters

`row` [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

`action` [DataRowAction](https://learn.microsoft.com/dotnet/api/system.data.datarowaction)

## Properties

### <a id="HavanaApp_TestDataset_IdentificacionesRowChangeEvent_Action"></a> Action

```csharp
public DataRowAction Action { get; }
```

#### Property Value

 [DataRowAction](https://learn.microsoft.com/dotnet/api/system.data.datarowaction)

### <a id="HavanaApp_TestDataset_IdentificacionesRowChangeEvent_Row"></a> Row

```csharp
public TestDataset.IdentificacionesRow Row { get; }
```

#### Property Value

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

