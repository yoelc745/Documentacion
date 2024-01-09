# <a id="HavanaApp_TestDataset_IdentificacionesDataTable"></a> Class TestDataset.IdentificacionesDataTable

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Represents the strongly named DataTable class.

```csharp
[Serializable]
public class TestDataset.IdentificacionesDataTable : TypedTableBase<TestDataset.IdentificacionesRow>, IComponent, IDisposable, IServiceProvider, IListSource, ISupportInitializeNotification, ISupportInitialize, ISerializable, IXmlSerializable, IEnumerable<TestDataset.IdentificacionesRow>, IEnumerable
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[MarshalByValueComponent](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent) ← 
[DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable) ← 
[TypedTableBase<TestDataset.IdentificacionesRow\>](https://learn.microsoft.com/dotnet/api/system.data.typedtablebase\-1) ← 
[TestDataset.IdentificacionesDataTable](HavanaApp.TestDataset.IdentificacionesDataTable.md)

#### Implements

[IComponent](https://learn.microsoft.com/dotnet/api/system.componentmodel.icomponent), 
[IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable), 
[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider), 
[IListSource](https://learn.microsoft.com/dotnet/api/system.componentmodel.ilistsource), 
[ISupportInitializeNotification](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitializenotification), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), 
[IXmlSerializable](https://learn.microsoft.com/dotnet/api/system.xml.serialization.ixmlserializable), 
[IEnumerable<TestDataset.IdentificacionesRow\>](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1), 
[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.ienumerable)

#### Inherited Members

[TypedTableBase<TestDataset.IdentificacionesRow\>.GetEnumerator\(\)](https://learn.microsoft.com/dotnet/api/system.data.typedtablebase\-1.getenumerator), 
[TypedTableBase<TestDataset.IdentificacionesRow\>.Cast<TResult\>\(\)](https://learn.microsoft.com/dotnet/api/system.data.typedtablebase\-1.cast), 
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

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable__ctor"></a> IdentificacionesDataTable\(\)

```csharp
public IdentificacionesDataTable()
```

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable__ctor_System_Runtime_Serialization_SerializationInfo_System_Runtime_Serialization_StreamingContext_"></a> IdentificacionesDataTable\(SerializationInfo, StreamingContext\)

```csharp
protected IdentificacionesDataTable(SerializationInfo info, StreamingContext context)
```

#### Parameters

`info` [SerializationInfo](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.serializationinfo)

`context` [StreamingContext](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.streamingcontext)

## Properties

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_Codigo_ParteColumn"></a> Codigo\_ParteColumn

```csharp
public DataColumn Codigo_ParteColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_Count"></a> Count

```csharp
[Browsable(false)]
public int Count { get; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_FechaColumn"></a> FechaColumn

```csharp
public DataColumn FechaColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_ID_BarricaColumn"></a> ID\_BarricaColumn

```csharp
public DataColumn ID_BarricaColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_ID_ZonaColumn"></a> ID\_ZonaColumn

```csharp
public DataColumn ID_ZonaColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_PesoColumn"></a> PesoColumn

```csharp
public DataColumn PesoColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_Tiempo_TrabajoColumn"></a> Tiempo\_TrabajoColumn

```csharp
public DataColumn Tiempo_TrabajoColumn { get; }
```

#### Property Value

 [DataColumn](https://learn.microsoft.com/dotnet/api/system.data.datacolumn)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_Item_System_Int32_"></a> this\[int\]

```csharp
public TestDataset.IdentificacionesRow this[int index] { get; }
```

#### Property Value

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

## Methods

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_AddIdentificacionesRow_HavanaApp_TestDataset_IdentificacionesRow_"></a> AddIdentificacionesRow\(IdentificacionesRow\)

```csharp
public void AddIdentificacionesRow(TestDataset.IdentificacionesRow row)
```

#### Parameters

`row` [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_AddIdentificacionesRow_System_DateTime_System_Int64_System_String_System_Int64_System_Int64_System_Int64_"></a> AddIdentificacionesRow\(DateTime, long, string, long, long, long\)

```csharp
public TestDataset.IdentificacionesRow AddIdentificacionesRow(DateTime Fecha, long Peso, string ID_Barrica, long ID_Zona, long Tiempo_Trabajo, long Codigo_Parte)
```

#### Parameters

`Fecha` [DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)

`Peso` [long](https://learn.microsoft.com/dotnet/api/system.int64)

`ID_Barrica` [string](https://learn.microsoft.com/dotnet/api/system.string)

`ID_Zona` [long](https://learn.microsoft.com/dotnet/api/system.int64)

`Tiempo_Trabajo` [long](https://learn.microsoft.com/dotnet/api/system.int64)

`Codigo_Parte` [long](https://learn.microsoft.com/dotnet/api/system.int64)

#### Returns

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_Clone"></a> Clone\(\)

Clones the structure of the <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref>, including all <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref> schemas and constraints.

```csharp
public override DataTable Clone()
```

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

A new <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref> with the same schema as the current <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref>.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_CreateInstance"></a> CreateInstance\(\)

Creates a new instance of <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref>.

```csharp
protected override DataTable CreateInstance()
```

#### Returns

 [DataTable](https://learn.microsoft.com/dotnet/api/system.data.datatable)

The new expression.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_GetRowType"></a> GetRowType\(\)

Gets the row type.

```csharp
protected override Type GetRowType()
```

#### Returns

 [Type](https://learn.microsoft.com/dotnet/api/system.type)

The type of the <xref href="System.Data.DataRow" data-throw-if-not-resolved="false"></xref>.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_GetTypedTableSchema_System_Xml_Schema_XmlSchemaSet_"></a> GetTypedTableSchema\(XmlSchemaSet\)

```csharp
public static XmlSchemaComplexType GetTypedTableSchema(XmlSchemaSet xs)
```

#### Parameters

`xs` [XmlSchemaSet](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschemaset)

#### Returns

 [XmlSchemaComplexType](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschemacomplextype)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_NewIdentificacionesRow"></a> NewIdentificacionesRow\(\)

```csharp
public TestDataset.IdentificacionesRow NewIdentificacionesRow()
```

#### Returns

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_NewRowFromBuilder_System_Data_DataRowBuilder_"></a> NewRowFromBuilder\(DataRowBuilder\)

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

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_OnRowChanged_System_Data_DataRowChangeEventArgs_"></a> OnRowChanged\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowChanged" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowChanged(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_OnRowChanging_System_Data_DataRowChangeEventArgs_"></a> OnRowChanging\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowChanging" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowChanging(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_OnRowDeleted_System_Data_DataRowChangeEventArgs_"></a> OnRowDeleted\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowDeleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowDeleted(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_OnRowDeleting_System_Data_DataRowChangeEventArgs_"></a> OnRowDeleting\(DataRowChangeEventArgs\)

Raises the <xref href="System.Data.DataTable.RowDeleting" data-throw-if-not-resolved="false"></xref> event.

```csharp
protected override void OnRowDeleting(DataRowChangeEventArgs e)
```

#### Parameters

`e` [DataRowChangeEventArgs](https://learn.microsoft.com/dotnet/api/system.data.datarowchangeeventargs)

A <xref href="System.Data.DataRowChangeEventArgs" data-throw-if-not-resolved="false"></xref> that contains the event data.

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_RemoveIdentificacionesRow_HavanaApp_TestDataset_IdentificacionesRow_"></a> RemoveIdentificacionesRow\(IdentificacionesRow\)

```csharp
public void RemoveIdentificacionesRow(TestDataset.IdentificacionesRow row)
```

#### Parameters

`row` [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRow](HavanaApp.TestDataset.IdentificacionesRow.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_IdentificacionesRowChanged"></a> IdentificacionesRowChanged

```csharp
public event TestDataset.IdentificacionesRowChangeEventHandler IdentificacionesRowChanged
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRowChangeEventHandler](HavanaApp.TestDataset.IdentificacionesRowChangeEventHandler.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_IdentificacionesRowChanging"></a> IdentificacionesRowChanging

```csharp
public event TestDataset.IdentificacionesRowChangeEventHandler IdentificacionesRowChanging
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRowChangeEventHandler](HavanaApp.TestDataset.IdentificacionesRowChangeEventHandler.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_IdentificacionesRowDeleted"></a> IdentificacionesRowDeleted

```csharp
public event TestDataset.IdentificacionesRowChangeEventHandler IdentificacionesRowDeleted
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRowChangeEventHandler](HavanaApp.TestDataset.IdentificacionesRowChangeEventHandler.md)

### <a id="HavanaApp_TestDataset_IdentificacionesDataTable_IdentificacionesRowDeleting"></a> IdentificacionesRowDeleting

```csharp
public event TestDataset.IdentificacionesRowChangeEventHandler IdentificacionesRowDeleting
```

#### Event Type

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesRowChangeEventHandler](HavanaApp.TestDataset.IdentificacionesRowChangeEventHandler.md)

