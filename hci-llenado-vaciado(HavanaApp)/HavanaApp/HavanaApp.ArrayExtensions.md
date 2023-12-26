# <a id="HavanaApp_ArrayExtensions"></a> Class ArrayExtensions

Namespace: [HavanaApp](HavanaApp.md)  
Assembly: HavanaApp.dll  

Clase estática que proporciona métodos de extensión para la desestructuración de arrays en C#.

```csharp
public static class ArrayExtensions
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ArrayExtensions](HavanaApp.ArrayExtensions.md)

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

## Methods

### <a id="HavanaApp_ArrayExtensions_Deconstruct__1___0_____0____0____"></a> Deconstruct<T\>\(T\[\], out T, out T\[\]\)

Descompone un array en su primer elemento y el resto de los elementos en un nuevo array.

```csharp
public static void Deconstruct<T>(this T[] array, out T first, out T[] rest)
```

#### Parameters

`array` T\[\]

El array a descomponer.

`first` T

El primer elemento del array, o el valor predeterminado de T si el array está vacío.

`rest` T\[\]

Un nuevo array que contiene el resto de los elementos después del primero.

#### Type Parameters

`T` 

El tipo de elementos del array.

### <a id="HavanaApp_ArrayExtensions_Deconstruct__1___0_____0____0____0____"></a> Deconstruct<T\>\(T\[\], out T, out T, out T\[\]\)

Descompone un array en sus dos primeros elementos y el resto de los elementos en un nuevo array.

```csharp
public static void Deconstruct<T>(this T[] array, out T first, out T second, out T[] rest)
```

#### Parameters

`array` T\[\]

El array a descomponer.

`first` T

El primer elemento del array.

`second` T

El segundo elemento del array.

`rest` T\[\]

Un nuevo array que contiene el resto de los elementos después del segundo.

#### Type Parameters

`T` 

El tipo de elementos del array.

### <a id="HavanaApp_ArrayExtensions_Deconstruct__1___0_____0____0____0____0____"></a> Deconstruct<T\>\(T\[\], out T, out T, out T, out T\[\]\)

Descompone un array en sus tres primeros elementos y el resto de los elementos en un nuevo array.

```csharp
public static void Deconstruct<T>(this T[] array, out T first, out T second, out T third, out T[] rest)
```

#### Parameters

`array` T\[\]

El array a descomponer.

`first` T

El primer elemento del array.

`second` T

El segundo elemento del array.

`third` T

El tercer elemento del array.

`rest` T\[\]

Un nuevo array que contiene el resto de los elementos después del tercer elemento.

#### Type Parameters

`T` 

El tipo de elementos del array.

### <a id="HavanaApp_ArrayExtensions_Deconstruct__1___0_____0____0____0____0____0____"></a> Deconstruct<T\>\(T\[\], out T, out T, out T, out T, out T\[\]\)

Descompone un array en sus cuatro primeros elementos y el resto de los elementos en un nuevo array.

```csharp
public static void Deconstruct<T>(this T[] array, out T first, out T second, out T third, out T fourth, out T[] rest)
```

#### Parameters

`array` T\[\]

El array a descomponer.

`first` T

El primer elemento del array.

`second` T

El segundo elemento del array.

`third` T

El tercer elemento del array.

`fourth` T

El cuarto elemento del array.

`rest` T\[\]

Un nuevo array que contiene el resto de los elementos después del cuarto elemento.

#### Type Parameters

`T` 

El tipo de elementos del array.

### <a id="HavanaApp_ArrayExtensions_Deconstruct__1___0_____0____0____0____0____0____0____"></a> Deconstruct<T\>\(T\[\], out T, out T, out T, out T, out T, out T\[\]\)

Descompone un array en sus cinco primeros elementos y el resto de los elementos en un nuevo array.

```csharp
public static void Deconstruct<T>(this T[] array, out T first, out T second, out T third, out T fourth, out T fifth, out T[] rest)
```

#### Parameters

`array` T\[\]

El array a descomponer.

`first` T

El primer elemento del array.

`second` T

El segundo elemento del array.

`third` T

El tercer elemento del array.

`fourth` T

El cuarto elemento del array.

`fifth` T

El quinto elemento del array.

`rest` T\[\]

Un nuevo array que contiene el resto de los elementos después del quinto elemento.

#### Type Parameters

`T` 

El tipo de elementos del array.

