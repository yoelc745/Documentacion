# <a id="HavanaApp_TestDataset_DataTable1DataTable"></a> Class TestDataset.DataTable1DataTable

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Represents the strongly named DataTable class.

```csharp
[Serializable]
public class TestDataset.DataTable1DataTable : TypedTableBase<TestDataset.DataTable1Row>, IComponent, IDisposable, IServiceProvider, IListSource, ISupportInitializeNotification, ISupportInitialize, ISerializable, IXmlSerializable, IEnumerable<TestDataset.DataTable1Row>, IEnumerable
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[MarshalByValueComponent](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent) ← 
[DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable) ← 
[TypedTableBase<TestDataset.DataTable1Row\>](https://learn.microsoft.com/dotnet/api/system.data.typedtablebase\-1) ← 
[TestDataset.DataTable1DataTable](HavanaApp.TestDataset.DataTable1DataTable.md)

#### Implements

[IComponent](https://learn.microsoft.com/dotnet/api/system.componentmodel.icomponent), 
[IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable), 
[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider), 
[IListSource](https://learn.microsoft.com/dotnet/api/system.componentmodel.ilistsource), 
[ISupportInitializeNotification](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitializenotification), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), 
[IXmlSerializable](https://learn.microsoft.com/dotnet/api/system.xml.serialization.ixmlserializable), 
[IEnumerable<TestDataset.DataTable1Row\>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1), 
[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

#### Inherited Members

[TypedTableBase<TestDataset.DataTable1Row\>.GetEnumerator\(\)](https://learn.microsoft.com/dotnet/api/system.data.typedtablebase\-1.getenumerator), 
[TypedTableBase<TestDataset.DataTable1Row\>.Cast<TResult\>\(\)](https://learn.microsoft.com/dotnet/api/system.data.typedtablebase\-1.cast), 
[DataTable.fInitInProgress](https://learn.microsoft.com/dotnet/api/system.data.datatable.finitinprogress), 
[DataTable.GetObjectData\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.getobjectdata), 
[DataTable.BeginInit\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.begininit), 
[DataTable.EndInit\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.endinit), 
[DataTable.AcceptChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.acceptchanges), 
[DataTable.CreateInstance\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.createinstance), 
[DataTable.Clone\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.clone), 
[DataTable.Copy\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.copy), 
[DataTable.Clear\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.clear), 
[DataTable.Compute\(string, string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.compute), 
[DataTable.GetChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.getchanges\#system\-data\-datatable\-getchanges), 
[DataTable.GetChanges\(DataRowState\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.getchanges\#system\-data\-datatable\-getchanges\(system\-data\-datarowstate\)), 
[DataTable.GetErrors\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.geterrors), 
[DataTable.ImportRow\(DataRow\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.importrow), 
[DataTable.NewRow\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.newrow), 
[DataTable.NewRowFromBuilder\(DataRowBuilder\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.newrowfrombuilder), 
[DataTable.GetRowType\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.getrowtype), 
[DataTable.NewRowArray\(int\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.newrowarray), 
[DataTable.OnColumnChanging\(DataColumnChangeEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.oncolumnchanging), 
[DataTable.OnColumnChanged\(DataColumnChangeEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.oncolumnchanged), 
[DataTable.OnPropertyChanging\(PropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.onpropertychanging), 
[DataTable.OnRemoveColumn\(DataColumn\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.onremovecolumn), 
[DataTable.OnRowChanged\(DataRowChangeEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.onrowchanged), 
[DataTable.OnRowChanging\(DataRowChangeEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.onrowchanging), 
[DataTable.OnRowDeleting\(DataRowChangeEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.onrowdeleting), 
[DataTable.OnRowDeleted\(DataRowChangeEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.onrowdeleted), 
[DataTable.OnTableCleared\(DataTableClearEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.ontablecleared), 
[DataTable.OnTableClearing\(DataTableClearEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.ontableclearing), 
[DataTable.OnTableNewRow\(DataTableNewRowEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.ontablenewrow), 
[DataTable.RejectChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.rejectchanges), 
[DataTable.Reset\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.reset), 
[DataTable.Select\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.select\#system\-data\-datatable\-select), 
[DataTable.Select\(string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.select\#system\-data\-datatable\-select\(system\-string\)), 
[DataTable.Select\(string, string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.select\#system\-data\-datatable\-select\(system\-string\-system\-string\)), 
[DataTable.Select\(string, string, DataViewRowState\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.select\#system\-data\-datatable\-select\(system\-string\-system\-string\-system\-data\-dataviewrowstate\)), 
[DataTable.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.tostring), 
[DataTable.BeginLoadData\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.beginloaddata), 
[DataTable.EndLoadData\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.endloaddata), 
[DataTable.LoadDataRow\(object\[\], bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.loaddatarow\#system\-data\-datatable\-loaddatarow\(system\-object\(\)\-system\-boolean\)), 
[DataTable.LoadDataRow\(object\[\], LoadOption\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.loaddatarow\#system\-data\-datatable\-loaddatarow\(system\-object\(\)\-system\-data\-loadoption\)), 
[DataTable.Merge\(DataTable\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.merge\#system\-data\-datatable\-merge\(system\-data\-datatable\)), 
[DataTable.Merge\(DataTable, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.merge\#system\-data\-datatable\-merge\(system\-data\-datatable\-system\-boolean\)), 
[DataTable.Merge\(DataTable, bool, MissingSchemaAction\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.merge\#system\-data\-datatable\-merge\(system\-data\-datatable\-system\-boolean\-system\-data\-missingschemaaction\)), 
[DataTable.Load\(IDataReader\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.load\#system\-data\-datatable\-load\(system\-data\-idatareader\)), 
[DataTable.Load\(IDataReader, LoadOption\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.load\#system\-data\-datatable\-load\(system\-data\-idatareader\-system\-data\-loadoption\)), 
[DataTable.Load\(IDataReader, LoadOption, FillErrorEventHandler\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.load\#system\-data\-datatable\-load\(system\-data\-idatareader\-system\-data\-loadoption\-system\-data\-fillerroreventhandler\)), 
[DataTable.CreateDataReader\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.createdatareader), 
[DataTable.WriteXml\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-stream\)), 
[DataTable.WriteXml\(Stream, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-stream\-system\-boolean\)), 
[DataTable.WriteXml\(TextWriter\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-textwriter\)), 
[DataTable.WriteXml\(TextWriter, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-textwriter\-system\-boolean\)), 
[DataTable.WriteXml\(XmlWriter\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-xml\-xmlwriter\)), 
[DataTable.WriteXml\(XmlWriter, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-xml\-xmlwriter\-system\-boolean\)), 
[DataTable.WriteXml\(string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-string\)), 
[DataTable.WriteXml\(string, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-string\-system\-boolean\)), 
[DataTable.WriteXml\(Stream, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-stream\-system\-data\-xmlwritemode\)), 
[DataTable.WriteXml\(Stream, XmlWriteMode, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-stream\-system\-data\-xmlwritemode\-system\-boolean\)), 
[DataTable.WriteXml\(TextWriter, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-textwriter\-system\-data\-xmlwritemode\)), 
[DataTable.WriteXml\(TextWriter, XmlWriteMode, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-io\-textwriter\-system\-data\-xmlwritemode\-system\-boolean\)), 
[DataTable.WriteXml\(XmlWriter, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-xml\-xmlwriter\-system\-data\-xmlwritemode\)), 
[DataTable.WriteXml\(XmlWriter, XmlWriteMode, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-xml\-xmlwriter\-system\-data\-xmlwritemode\-system\-boolean\)), 
[DataTable.WriteXml\(string, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-string\-system\-data\-xmlwritemode\)), 
[DataTable.WriteXml\(string, XmlWriteMode, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexml\#system\-data\-datatable\-writexml\(system\-string\-system\-data\-xmlwritemode\-system\-boolean\)), 
[DataTable.WriteXmlSchema\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-io\-stream\)), 
[DataTable.WriteXmlSchema\(Stream, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-io\-stream\-system\-boolean\)), 
[DataTable.WriteXmlSchema\(TextWriter\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-io\-textwriter\)), 
[DataTable.WriteXmlSchema\(TextWriter, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-io\-textwriter\-system\-boolean\)), 
[DataTable.WriteXmlSchema\(XmlWriter\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-xml\-xmlwriter\)), 
[DataTable.WriteXmlSchema\(XmlWriter, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-xml\-xmlwriter\-system\-boolean\)), 
[DataTable.WriteXmlSchema\(string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-string\)), 
[DataTable.WriteXmlSchema\(string, bool\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.writexmlschema\#system\-data\-datatable\-writexmlschema\(system\-string\-system\-boolean\)), 
[DataTable.ReadXml\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxml\#system\-data\-datatable\-readxml\(system\-io\-stream\)), 
[DataTable.ReadXml\(TextReader\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxml\#system\-data\-datatable\-readxml\(system\-io\-textreader\)), 
[DataTable.ReadXml\(string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxml\#system\-data\-datatable\-readxml\(system\-string\)), 
[DataTable.ReadXml\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxml\#system\-data\-datatable\-readxml\(system\-xml\-xmlreader\)), 
[DataTable.ReadXmlSchema\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxmlschema\#system\-data\-datatable\-readxmlschema\(system\-io\-stream\)), 
[DataTable.ReadXmlSchema\(TextReader\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxmlschema\#system\-data\-datatable\-readxmlschema\(system\-io\-textreader\)), 
[DataTable.ReadXmlSchema\(string\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxmlschema\#system\-data\-datatable\-readxmlschema\(system\-string\)), 
[DataTable.ReadXmlSchema\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxmlschema\#system\-data\-datatable\-readxmlschema\(system\-xml\-xmlreader\)), 
[DataTable.GetDataTableSchema\(XmlSchemaSet\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.getdatatableschema), 
[DataTable.GetSchema\(\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.getschema), 
[DataTable.ReadXmlSerializable\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.datatable.readxmlserializable), 
[DataTable.CaseSensitive](https://learn.microsoft.com/dotnet/api/system.data.datatable.casesensitive), 
[DataTable.IsInitialized](https://learn.microsoft.com/dotnet/api/system.data.datatable.isinitialized), 
[DataTable.RemotingFormat](https://learn.microsoft.com/dotnet/api/system.data.datatable.remotingformat), 
[DataTable.ChildRelations](https://learn.microsoft.com/dotnet/api/system.data.datatable.childrelations), 
[DataTable.Columns](https://learn.microsoft.com/dotnet/api/system.data.datatable.columns), 
[DataTable.Constraints](https://learn.microsoft.com/dotnet/api/system.data.datatable.constraints), 
[DataTable.DataSet](https://learn.microsoft.com/dotnet/api/system.data.datatable.dataset), 
[DataTable.DefaultView](https://learn.microsoft.com/dotnet/api/system.data.datatable.defaultview), 
[DataTable.DisplayExpression](https://learn.microsoft.com/dotnet/api/system.data.datatable.displayexpression), 
[DataTable.ExtendedProperties](https://learn.microsoft.com/dotnet/api/system.data.datatable.extendedproperties), 
[DataTable.HasErrors](https://learn.microsoft.com/dotnet/api/system.data.datatable.haserrors), 
[DataTable.Locale](https://learn.microsoft.com/dotnet/api/system.data.datatable.locale), 
[DataTable.MinimumCapacity](https://learn.microsoft.com/dotnet/api/system.data.datatable.minimumcapacity), 
[DataTable.ParentRelations](https://learn.microsoft.com/dotnet/api/system.data.datatable.parentrelations), 
[DataTable.PrimaryKey](https://learn.microsoft.com/dotnet/api/system.data.datatable.primarykey), 
[DataTable.Rows](https://learn.microsoft.com/dotnet/api/system.data.datatable.rows), 
[DataTable.TableName](https://learn.microsoft.com/dotnet/api/system.data.datatable.tablename), 
[DataTable.Namespace](https://learn.microsoft.com/dotnet/api/system.data.datatable.namespace), 
[DataTable.Prefix](https://learn.microsoft.com/dotnet/api/system.data.datatable.prefix), 
[DataTable.Site](https://learn.microsoft.com/dotnet/api/system.data.datatable.site), 
[DataTable.ColumnChanging](https://learn.microsoft.com/dotnet/api/system.data.datatable.columnchanging), 
[DataTable.ColumnChanged](https://learn.microsoft.com/dotnet/api/system.data.datatable.columnchanged), 
[DataTable.Initialized](https://learn.microsoft.com/dotnet/api/system.data.datatable.initialized), 
[DataTable.RowChanged](https://learn.microsoft.com/dotnet/api/system.data.datatable.rowchanged), 
[DataTable.RowChanging](https://learn.microsoft.com/dotnet/api/system.data.datatable.rowchanging), 
[DataTable.RowDeleting](https://learn.microsoft.com/dotnet/api/system.data.datatable.rowdeleting), 
[DataTable.RowDeleted](https://learn.microsoft.com/dotnet/api/system.data.datatable.rowdeleted), 
[DataTable.TableClearing](https://learn.microsoft.com/dotnet/api/system.data.datatable.tableclearing), 
[DataTable.TableCleared](https://learn.microsoft.com/dotnet/api/system.data.datatable.tablecleared), 
[DataTable.TableNewRow](https://learn.microsoft.com/dotnet/api/system.data.datatable.tablenewrow), 
[MarshalByValueComponent.Dispose\(\)](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.dispose\#system\-componentmodel\-marshalbyvaluecomponent\-dispose), 
[MarshalByValueComponent.Dispose\(bool\)](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.dispose\#system\-componentmodel\-marshalbyvaluecomponent\-dispose\(system\-boolean\)), 
[MarshalByValueComponent.GetService\(Type\)](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.getservice), 
[MarshalByValueComponent.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.tostring), 
[MarshalByValueComponent.Events](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.events), 
[MarshalByValueComponent.Site](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.site), 
[MarshalByValueComponent.Container](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.container), 
[MarshalByValueComponent.DesignMode](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.designmode), 
[MarshalByValueComponent.Disposed](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent.disposed), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Constructors

### <a id="HavanaApp_TestDataset_DataTable1DataTable__ctor"></a> DataTable1DataTable\(\)

```csharp
public DataTable1DataTable()
```

### <a id="HavanaApp_TestDataset_DataTable1DataTable__ctor_System_Runtime_Serialization_SerializationInfo_System_Runtime_Serialization_StreamingContext_"></a> DataTable1DataTable\(SerializationInfo, StreamingContext\)

```csharp
protected DataTable1DataTable(SerializationInfo info, StreamingContext context)
```

#### Parameters

`info` [SerializationInfo](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.serializationinfo)

`context` [StreamingContext](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.streamingcontext)

## Properties

### <a id="HavanaApp_TestDataset_DataTable1DataTable_Count"></a> Count

```csharp
[Browsable(false)]
public int Count { get; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_EmailColumn"></a> EmailColumn

```csharp
public DataColumn EmailColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_IsAdminColumn"></a> IsAdminColumn

```csharp
public DataColumn IsAdminColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_NombreColumn"></a> NombreColumn

```csharp
public DataColumn NombreColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_Item_System_Int32_"></a> this\[int\]

```csharp
public TestDataset.DataTable1Row this[int index] { get; }
```

#### Property Value

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

## Methods

### <a id="HavanaApp_TestDataset_DataTable1DataTable_AddDataTable1Row_HavanaApp_TestDataset_DataTable1Row_"></a> AddDataTable1Row\(DataTable1Row\)

```csharp
public void AddDataTable1Row(TestDataset.DataTable1Row row)
```

#### Parameters

`row` [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_AddDataTable1Row_System_String_System_String_System_Boolean_"></a> AddDataTable1Row\(string, string, bool\)

```csharp
public TestDataset.DataTable1Row AddDataTable1Row(string Nombre, string Email, bool IsAdmin)
```

#### Parameters

`Nombre` [string](https://learn.microsoft.com/dotnet/api/system.string)

`Email` [string](https://learn.microsoft.com/dotnet/api/system.string)

`IsAdmin` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

#### Returns

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_Clone"></a> Clone\(\)

Clones the structure of the <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref>, including all <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref> schemas and constraints.

```csharp
public override DataTable Clone()
```

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

A new <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref> with the same schema as the current <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref>.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_CreateInstance"></a> CreateInstance\(\)

Creates a new instance of <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref>.

```csharp
protected override DataTable CreateInstance()
```

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

The new expression.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_GetRowType"></a> GetRowType\(\)

Gets the row type.

```csharp
protected override Type GetRowType()
```

#### Returns

 [Type](https://learn.microsoft.com/dotnet/api/system.type)

The type of the <xref href="System.Data.DataRow" data-throw-if-not-resolved="false"></xref>.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_GetTypedTableSchema_System_Xml_Schema_XmlSchemaSet_"></a> GetTypedTableSchema\(XmlSchemaSet\)

```csharp
public static XmlSchemaComplexType GetTypedTableSchema(XmlSchemaSet xs)
```

#### Parameters

`xs` [XmlSchemaSet](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschemaset)

#### Returns

 [XmlSchemaComplexType](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschemacomplextype)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_NewDataTable1Row"></a> NewDataTable1Row\(\)

```csharp
public TestDataset.DataTable1Row NewDataTable1Row()
```

#### Returns

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_NewRowFromBuilder_System_Data_DataRowBuilder_"></a> NewRowFromBuilder\(DataRowBuilder\)

Creates a new row from an existing row.

```csharp
protected override DataRow NewRowFromBuilder(DataRowBuilder builder)
```

#### Parameters

`builder` [DataRowBuilder](https://learn.microsoft.com/dotnet/api/system.data.datarowbuilder)

A <xref href="System.Data.DataRowBuilder" data-throw-if-not-resolved="false"></xref> object.

#### Returns

 [DataRow](https://learn.microsoft.com/dotnet/api/system.data.datarow)

A <xref href="System.Data.DataRow" data-throw-if-not-resolved="false"></xref> derived class.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_OnRowChanged_System_Data_DataRowChangeEventArgs_"></a> OnRowChanged\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowChanged" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowChanged(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_OnRowChanging_System_Data_DataRowChangeEventArgs_"></a> OnRowChanging\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowChanging" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowChanging(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_OnRowDeleted_System_Data_DataRowChangeEventArgs_"></a> OnRowDeleted\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowDeleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowDeleted(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_OnRowDeleting_System_Data_DataRowChangeEventArgs_"></a> OnRowDeleting\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowDeleting" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowDeleting(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_DataTable1DataTable_RemoveDataTable1Row_HavanaApp_TestDataset_DataTable1Row_"></a> RemoveDataTable1Row\(DataTable1Row\)

```csharp
public void RemoveDataTable1Row(TestDataset.DataTable1Row row)
```

#### Parameters

`row` [TestDataset](HavanaApp.TestDataset.md).[DataTable1Row](HavanaApp.TestDataset.DataTable1Row.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_DataTable1RowChanged"></a> DataTable1RowChanged

```csharp
public event TestDataset.DataTable1RowChangeEventHandler DataTable1RowChanged
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1RowChangeEventHandler](HavanaApp.TestDataset.DataTable1RowChangeEventHandler.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_DataTable1RowChanging"></a> DataTable1RowChanging

```csharp
public event TestDataset.DataTable1RowChangeEventHandler DataTable1RowChanging
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1RowChangeEventHandler](HavanaApp.TestDataset.DataTable1RowChangeEventHandler.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_DataTable1RowDeleted"></a> DataTable1RowDeleted

```csharp
public event TestDataset.DataTable1RowChangeEventHandler DataTable1RowDeleted
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1RowChangeEventHandler](HavanaApp.TestDataset.DataTable1RowChangeEventHandler.md)

### <a id="HavanaApp_TestDataset_DataTable1DataTable_DataTable1RowDeleting"></a> DataTable1RowDeleting

```csharp
public event TestDataset.DataTable1RowChangeEventHandler DataTable1RowDeleting
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1RowChangeEventHandler](HavanaApp.TestDataset.DataTable1RowChangeEventHandler.md)

