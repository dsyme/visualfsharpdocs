# CompilerServices.TypeProviderTypeAttributes Enumeration (F#)

Indicates the relationship between a compiled entity in a .NET Framework binary and an element in F# source code.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




type TypeProviderAttributes =
| IsErased = 0
| SuppressRelocate = 1


```





## Remarks
The following table shows the possible values and their meaning.



|Value|Description|
|-----|-----------|
|IsErased|Indicates that the type is represented by another type in compiled assemblies and never appears directly.|
|SuppressRelocate|Instructs the compiler not to put generated types as nested types under the user-supplied type abbreviation.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

