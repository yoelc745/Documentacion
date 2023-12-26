# <a id="HavanaApp_TestDataset"></a> Class TestDataset

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Represents a strongly typed in-memory cache of data.

```csharp
[Serializable]
public class TestDataset : DataSet, IComponent, IDisposable, IServiceProvider, IListSource, IXmlSerializable, ISupportInitializeNotification, ISupportInitialize, ISerializable
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[MarshalByValueComponent](https://learn.microsoft.com/dotnet/api/system.componentmodel.marshalbyvaluecomponent) ← 
[DataSet](https://learn.microsoft.com/dotnet/api/system.data.dataset) ← 
[TestDataset](HavanaApp.TestDataset.md)

#### Implements

[IComponent](https://learn.microsoft.com/dotnet/api/system.componentmodel.icomponent), 
[IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable), 
[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider), 
[IListSource](https://learn.microsoft.com/dotnet/api/system.componentmodel.ilistsource), 
[IXmlSerializable](https://learn.microsoft.com/dotnet/api/system.xml.serialization.ixmlserializable), 
[ISupportInitializeNotification](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitializenotification), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable)

<details>
  
<summary>Inherited Members</summary>

[DataSet.IsBinarySerialized\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.isbinaryserialized), 
[DataSet.DetermineSchemaSerializationMode\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.determineschemaserializationmode\#system\-data\-dataset\-determineschemaserializationmode\(system\-runtime\-serialization\-serializationinfo\-system\-runtime\-serialization\-streamingcontext\)), 
[DataSet.DetermineSchemaSerializationMode\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.determineschemaserializationmode\#system\-data\-dataset\-determineschemaserializationmode\(system\-xml\-xmlreader\)), 
[DataSet.GetSerializationData\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getserializationdata), 
[DataSet.GetObjectData\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getobjectdata), 
[DataSet.InitializeDerivedDataSet\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.initializederiveddataset), 
[DataSet.ShouldSerializeRelations\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.shouldserializerelations), 
[DataSet.ShouldSerializeTables\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.shouldserializetables), 
[DataSet.AcceptChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.acceptchanges), 
[DataSet.BeginInit\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.begininit), 
[DataSet.EndInit\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.endinit), 
[DataSet.Clear\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.clear), 
[DataSet.Clone\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.clone), 
[DataSet.Copy\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.copy), 
[DataSet.GetChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getchanges\#system\-data\-dataset\-getchanges), 
[DataSet.GetChanges\(DataRowState\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getchanges\#system\-data\-dataset\-getchanges\(system\-data\-datarowstate\)), 
[DataSet.GetXml\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getxml), 
[DataSet.GetXmlSchema\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getxmlschema), 
[DataSet.HasChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.haschanges\#system\-data\-dataset\-haschanges), 
[DataSet.HasChanges\(DataRowState\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.haschanges\#system\-data\-dataset\-haschanges\(system\-data\-datarowstate\)), 
[DataSet.InferXmlSchema\(XmlReader, string\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.inferxmlschema\#system\-data\-dataset\-inferxmlschema\(system\-xml\-xmlreader\-system\-string\(\)\)), 
[DataSet.InferXmlSchema\(Stream, string\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.inferxmlschema\#system\-data\-dataset\-inferxmlschema\(system\-io\-stream\-system\-string\(\)\)), 
[DataSet.InferXmlSchema\(TextReader, string\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.inferxmlschema\#system\-data\-dataset\-inferxmlschema\(system\-io\-textreader\-system\-string\(\)\)), 
[DataSet.InferXmlSchema\(string, string\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.inferxmlschema\#system\-data\-dataset\-inferxmlschema\(system\-string\-system\-string\(\)\)), 
[DataSet.ReadXmlSchema\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxmlschema\#system\-data\-dataset\-readxmlschema\(system\-xml\-xmlreader\)), 
[DataSet.ReadXmlSchema\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxmlschema\#system\-data\-dataset\-readxmlschema\(system\-io\-stream\)), 
[DataSet.ReadXmlSchema\(TextReader\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxmlschema\#system\-data\-dataset\-readxmlschema\(system\-io\-textreader\)), 
[DataSet.ReadXmlSchema\(string\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxmlschema\#system\-data\-dataset\-readxmlschema\(system\-string\)), 
[DataSet.WriteXmlSchema\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-io\-stream\)), 
[DataSet.WriteXmlSchema\(Stream, Converter<Type, string\>\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-io\-stream\-system\-converter\(\(system\-type\-system\-string\)\)\)), 
[DataSet.WriteXmlSchema\(string\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-string\)), 
[DataSet.WriteXmlSchema\(string, Converter<Type, string\>\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-string\-system\-converter\(\(system\-type\-system\-string\)\)\)), 
[DataSet.WriteXmlSchema\(TextWriter\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-io\-textwriter\)), 
[DataSet.WriteXmlSchema\(TextWriter, Converter<Type, string\>\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-io\-textwriter\-system\-converter\(\(system\-type\-system\-string\)\)\)), 
[DataSet.WriteXmlSchema\(XmlWriter\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-xml\-xmlwriter\)), 
[DataSet.WriteXmlSchema\(XmlWriter, Converter<Type, string\>\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexmlschema\#system\-data\-dataset\-writexmlschema\(system\-xml\-xmlwriter\-system\-converter\(\(system\-type\-system\-string\)\)\)), 
[DataSet.ReadXml\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-xml\-xmlreader\)), 
[DataSet.ReadXml\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-io\-stream\)), 
[DataSet.ReadXml\(TextReader\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-io\-textreader\)), 
[DataSet.ReadXml\(string\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-string\)), 
[DataSet.ReadXml\(XmlReader, XmlReadMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-xml\-xmlreader\-system\-data\-xmlreadmode\)), 
[DataSet.ReadXml\(Stream, XmlReadMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-io\-stream\-system\-data\-xmlreadmode\)), 
[DataSet.ReadXml\(TextReader, XmlReadMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-io\-textreader\-system\-data\-xmlreadmode\)), 
[DataSet.ReadXml\(string, XmlReadMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxml\#system\-data\-dataset\-readxml\(system\-string\-system\-data\-xmlreadmode\)), 
[DataSet.WriteXml\(Stream\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-io\-stream\)), 
[DataSet.WriteXml\(TextWriter\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-io\-textwriter\)), 
[DataSet.WriteXml\(XmlWriter\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-xml\-xmlwriter\)), 
[DataSet.WriteXml\(string\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-string\)), 
[DataSet.WriteXml\(Stream, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-io\-stream\-system\-data\-xmlwritemode\)), 
[DataSet.WriteXml\(TextWriter, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-io\-textwriter\-system\-data\-xmlwritemode\)), 
[DataSet.WriteXml\(XmlWriter, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-xml\-xmlwriter\-system\-data\-xmlwritemode\)), 
[DataSet.WriteXml\(string, XmlWriteMode\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.writexml\#system\-data\-dataset\-writexml\(system\-string\-system\-data\-xmlwritemode\)), 
[DataSet.Merge\(DataSet\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-dataset\)), 
[DataSet.Merge\(DataSet, bool\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-dataset\-system\-boolean\)), 
[DataSet.Merge\(DataSet, bool, MissingSchemaAction\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-dataset\-system\-boolean\-system\-data\-missingschemaaction\)), 
[DataSet.Merge\(DataTable\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-datatable\)), 
[DataSet.Merge\(DataTable, bool, MissingSchemaAction\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-datatable\-system\-boolean\-system\-data\-missingschemaaction\)), 
[DataSet.Merge\(DataRow\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-datarow\(\)\)), 
[DataSet.Merge\(DataRow\[\], bool, MissingSchemaAction\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.merge\#system\-data\-dataset\-merge\(system\-data\-datarow\(\)\-system\-boolean\-system\-data\-missingschemaaction\)), 
[DataSet.OnPropertyChanging\(PropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.onpropertychanging), 
[DataSet.OnRemoveTable\(DataTable\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.onremovetable), 
[DataSet.OnRemoveRelation\(DataRelation\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.onremoverelation), 
[DataSet.RaisePropertyChanging\(string\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.raisepropertychanging), 
[DataSet.RejectChanges\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.rejectchanges), 
[DataSet.Reset\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.reset), 
[DataSet.ReadXmlSerializable\(XmlReader\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.readxmlserializable), 
[DataSet.GetSchemaSerializable\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getschemaserializable), 
[DataSet.GetDataSetSchema\(XmlSchemaSet\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.getdatasetschema), 
[DataSet.Load\(IDataReader, LoadOption, FillErrorEventHandler, params DataTable\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.load\#system\-data\-dataset\-load\(system\-data\-idatareader\-system\-data\-loadoption\-system\-data\-fillerroreventhandler\-system\-data\-datatable\(\)\)), 
[DataSet.Load\(IDataReader, LoadOption, params DataTable\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.load\#system\-data\-dataset\-load\(system\-data\-idatareader\-system\-data\-loadoption\-system\-data\-datatable\(\)\)), 
[DataSet.Load\(IDataReader, LoadOption, params string\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.load\#system\-data\-dataset\-load\(system\-data\-idatareader\-system\-data\-loadoption\-system\-string\(\)\)), 
[DataSet.CreateDataReader\(\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.createdatareader\#system\-data\-dataset\-createdatareader), 
[DataSet.CreateDataReader\(params DataTable\[\]\)](https://learn.microsoft.com/dotnet/api/system.data.dataset.createdatareader\#system\-data\-dataset\-createdatareader\(system\-data\-datatable\(\)\)), 
[DataSet.RemotingFormat](https://learn.microsoft.com/dotnet/api/system.data.dataset.remotingformat), 
[DataSet.SchemaSerializationMode](https://learn.microsoft.com/dotnet/api/system.data.dataset.schemaserializationmode), 
[DataSet.CaseSensitive](https://learn.microsoft.com/dotnet/api/system.data.dataset.casesensitive), 
[DataSet.DefaultViewManager](https://learn.microsoft.com/dotnet/api/system.data.dataset.defaultviewmanager), 
[DataSet.EnforceConstraints](https://learn.microsoft.com/dotnet/api/system.data.dataset.enforceconstraints), 
[DataSet.DataSetName](https://learn.microsoft.com/dotnet/api/system.data.dataset.datasetname), 
[DataSet.Namespace](https://learn.microsoft.com/dotnet/api/system.data.dataset.namespace), 
[DataSet.Prefix](https://learn.microsoft.com/dotnet/api/system.data.dataset.prefix), 
[DataSet.ExtendedProperties](https://learn.microsoft.com/dotnet/api/system.data.dataset.extendedproperties), 
[DataSet.HasErrors](https://learn.microsoft.com/dotnet/api/system.data.dataset.haserrors), 
[DataSet.IsInitialized](https://learn.microsoft.com/dotnet/api/system.data.dataset.isinitialized), 
[DataSet.Locale](https://learn.microsoft.com/dotnet/api/system.data.dataset.locale), 
[DataSet.Site](https://learn.microsoft.com/dotnet/api/system.data.dataset.site), 
[DataSet.Relations](https://learn.microsoft.com/dotnet/api/system.data.dataset.relations), 
[DataSet.Tables](https://learn.microsoft.com/dotnet/api/system.data.dataset.tables), 
[DataSet.MergeFailed](https://learn.microsoft.com/dotnet/api/system.data.dataset.mergefailed), 
[DataSet.Initialized](https://learn.microsoft.com/dotnet/api/system.data.dataset.initialized), 
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
</details>

## Constructors

### <a id="HavanaApp_TestDataset__ctor"></a> TestDataset\(\)

```csharp
public TestDataset()
```

### <a id="HavanaApp_TestDataset__ctor_System_Runtime_Serialization_SerializationInfo_System_Runtime_Serialization_StreamingContext_"></a> TestDataset\(SerializationInfo, StreamingContext\)

```csharp
protected TestDataset(SerializationInfo info, StreamingContext context)
```

#### Parameters

`info` [SerializationInfo](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.serializationinfo)

`context` [StreamingContext](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.streamingcontext)

## Properties

### <a id="HavanaApp_TestDataset_DataTable1"></a> DataTable1

```csharp
[Browsable(false)]
public TestDataset.DataTable1DataTable DataTable1 { get; }
```

#### Property Value

 [TestDataset](HavanaApp.TestDataset.md).[DataTable1DataTable](HavanaApp.TestDataset.DataTable1DataTable.md)

### <a id="HavanaApp_TestDataset_Identificaciones"></a> Identificaciones

```csharp
[Browsable(false)]
public TestDataset.IdentificacionesDataTable Identificaciones { get; }
```

#### Property Value

 [TestDataset](HavanaApp.TestDataset.md).[IdentificacionesDataTable](HavanaApp.TestDataset.IdentificacionesDataTable.md)

### <a id="HavanaApp_TestDataset_Relations"></a> Relations

```csharp
public DataRelationCollection Relations { get; }
```

#### Property Value

 [DataRelationCollection](https://learn.microsoft.com/dotnet/api/system.data.datarelationcollection)

### <a id="HavanaApp_TestDataset_SchemaSerializationMode"></a> SchemaSerializationMode

Gets or sets a <xref href="System.Data.SchemaSerializationMode" data-throw-if-not-resolved="false"></xref> for a <xref href="System.Data.DataSet" data-throw-if-not-resolved="false"></xref>.

```csharp
[Browsable(true)]
public override SchemaSerializationMode SchemaSerializationMode { get; set; }
```

#### Property Value

 [SchemaSerializationMode](https://learn.microsoft.com/dotnet/api/system.data.schemaserializationmode)

### <a id="HavanaApp_TestDataset_Tables"></a> Tables

```csharp
public DataTableCollection Tables { get; }
```

#### Property Value

 [DataTableCollection](https://learn.microsoft.com/dotnet/api/system.data.datatablecollection)

## Methods

### <a id="HavanaApp_TestDataset_Clone"></a> Clone\(\)

Copies the structure of the <xref href="System.Data.DataSet" data-throw-if-not-resolved="false"></xref>, including all <xref href="System.Data.DataTable" data-throw-if-not-resolved="false"></xref> schemas, relations, and constraints. Does not copy any data.

```csharp
public override DataSet Clone()
```

#### Returns

 [DataSet](https://learn.microsoft.com/dotnet/api/system.data.dataset)

A new <xref href="System.Data.DataSet" data-throw-if-not-resolved="false"></xref> with the same schema as the current <xref href="System.Data.DataSet" data-throw-if-not-resolved="false"></xref>, but none of the data.

### <a id="HavanaApp_TestDataset_GetSchemaSerializable"></a> GetSchemaSerializable\(\)

Returns a serializable <xref href="System.Xml.Schema.XmlSchema" data-throw-if-not-resolved="false"></xref> instance.

```csharp
protected override XmlSchema GetSchemaSerializable()
```

#### Returns

 [XmlSchema](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschema)

The <xref href="System.Xml.Schema.XmlSchema" data-throw-if-not-resolved="false"></xref> instance.

### <a id="HavanaApp_TestDataset_GetTypedDataSetSchema_System_Xml_Schema_XmlSchemaSet_"></a> GetTypedDataSetSchema\(XmlSchemaSet\)

```csharp
public static XmlSchemaComplexType GetTypedDataSetSchema(XmlSchemaSet xs)
```

#### Parameters

`xs` [XmlSchemaSet](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschemaset)

#### Returns

 [XmlSchemaComplexType](https://learn.microsoft.com/dotnet/api/system.xml.schema.xmlschemacomplextype)

### <a id="HavanaApp_TestDataset_InitializeDerivedDataSet"></a> InitializeDerivedDataSet\(\)

Deserialize all of the tables data of the DataSet from the binary or XML stream.

```csharp
protected override void InitializeDerivedDataSet()
```

### <a id="HavanaApp_TestDataset_ReadXmlSerializable_System_Xml_XmlReader_"></a> ReadXmlSerializable\(XmlReader\)

Ignores attributes and returns an empty DataSet.

```csharp
protected override void ReadXmlSerializable(XmlReader reader)
```

#### Parameters

`reader` [XmlReader](https://learn.microsoft.com/dotnet/api/system.xml.xmlreader)

The specified XML reader.

### <a id="HavanaApp_TestDataset_ShouldSerializeRelations"></a> ShouldSerializeRelations\(\)

Gets a value indicating whether <xref href="System.Data.DataSet.Relations" data-throw-if-not-resolved="false"></xref> property should be persisted.

```csharp
protected override bool ShouldSerializeRelations()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if the property value has been changed from its default; otherwise, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">false</a>.

### <a id="HavanaApp_TestDataset_ShouldSerializeTables"></a> ShouldSerializeTables\(\)

Gets a value indicating whether <xref href="System.Data.DataSet.Tables" data-throw-if-not-resolved="false"></xref> property should be persisted.

```csharp
protected override bool ShouldSerializeTables()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if the property value has been changed from its default; otherwise, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">false</a>.

