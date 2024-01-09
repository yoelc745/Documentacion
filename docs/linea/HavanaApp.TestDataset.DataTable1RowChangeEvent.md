# <a id="HavanaApp_TestDataset_DataTable1RowChangeEvent"></a> Class TestDataset.DataTable1RowChangeEvent

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Row event argument class

```csharp
public class TestDataset.DataTable1RowChangeEvent : EventArgs
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[TestDataset.DataTable1RowChangeEvent](HavanaApp.TestDataset.DataTable1RowChangeEvent.md)

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

### <a id="HavanaApp_TestDataset_DataTable1RowChangeEvent__ctor_HavanaApp_TestDataset_DataTable1Row_System_Data_DataRowAction_"></a> DataTable1RowChangeEvent\(DataTable1Row, DataRowAction\)

```csharp
public DataTable1RowChangeEvent(TestDataset.DataTable1Row row, DataRowAction action)
```

#### Parameters

`row` [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

`action` [DataRowAction](https://learn.microsoft.com/dotnet/api/system.data.datarowaction)

## Properties

### <a id="HavanaApp_TestDataset_DataTable1RowChangeEvent_Action"></a> Action

```csharp
public DataRowAction Action { get; }
```

#### Property Value

 [DataRowAction](https://learn.microsoft.com/dotnet/api/system.data.datarowaction)

### <a id="HavanaApp_TestDataset_DataTable1RowChangeEvent_Row"></a> Row

```csharp
public TestDataset.DataTable1Row Row { get; }
```

#### Property Value

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

