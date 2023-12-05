# <a id="SQLHandler_ConectorSQL_FuncionesAuxiliares"></a> Class ConectorSQL.FuncionesAuxiliares

Namespace: [SQLHandler](SQLHandler.md)  
Assembly: SQLHandler.dll  

Clase que contiene funciones auxiliares para el manejo de la base de datos.

```csharp
public static class ConectorSQL.FuncionesAuxiliares
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ConectorSQL.FuncionesAuxiliares](SQLHandler.ConectorSQL.FuncionesAuxiliares.md)

#### Inherited Members

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Methods

### <a id="SQLHandler_ConectorSQL_FuncionesAuxiliares_ObtenerHistorialParte_System_Int32_System_Data_SqlClient_SqlConnection_"></a> ObtenerHistorialParte\(int, SqlConnection\)

Obtiene los registros históricos de una parte específica de la base de datos.

```csharp
public static List<RegistroBarrica> ObtenerHistorialParte(int IdParte, SqlConnection Connection)
```

#### Parameters

`IdParte` [int](https://learn.microsoft.com/dotnet/api/system.int32)

El ID de la parte para la cual se van a obtener los registros históricos.

`Connection` [SqlConnection](https://learn.microsoft.com/dotnet/api/system.data.sqlclient.sqlconnection)

El objeto SqlConnection utilizado para conectarse a la base de datos.

#### Returns

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[RegistroBarrica](SQLHandler.RegistroBarrica.md)\>

Una lista de objetos RegistroBarrica que representan los registros históricos de la parte.

