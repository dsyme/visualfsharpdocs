# Core.CompilationMappingAttribute Class (F#)

This attribute is inserted automatically by the F# compiler to tag types and methods in the generated Common Language Infrastructure (CLI) code with flags indicating the correspondence with original source constructs. It is used by the functions in the [Microsoft.FSharp.Reflection](http://msdn.microsoft.com/en-us/library/353a36b1-af8f-49de-a92f-73a8e881a4c5) namespace to reverse-map compiled constructs to their original forms. It is not intended for use from user code.

**Namespace/Module Path**: Microsoft.FSharp.Core

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




[<AttributeUsage(AttributeTargets.All, AllowMultiple = false)>]
[<Sealed>]
type CompilationMappingAttribute =
class
new CompilationMappingAttribute : SourceConstructFlags * int * int -> CompilationMappingAttribute
new CompilationMappingAttribute : SourceConstructFlags * int -> CompilationMappingAttribute
new CompilationMappingAttribute : SourceConstructFlags -> CompilationMappingAttribute
member this.SequenceNumber :  int
member this.SourceConstructFlags :  SourceConstructFlags
member this.VariantNumber :  int
end


```





## Remarks
You can also use the short form of the name, **CompilationMapping**.


## Constructors


|Member|Description|
|------|-----------|
|[new](http://msdn.microsoft.com/en-us/library/979300ad-606c-48b0-b6f1-aa31fcca2600)|Creates an instance of the attribute.|

## Instance Members


|Member|Description|
|------|-----------|
|[SequenceNumber](http://msdn.microsoft.com/en-us/library/d9847912-169e-483c-8755-4eab85354529)|Indicates the sequence number of the entity, if any, in a linear sequence of elements with F# source code.|
|[SourceConstructFlags](http://msdn.microsoft.com/en-us/library/d4ac2a55-1c0b-4f1e-b586-524838e23ae2)|Indicates the relationship between the compiled entity and F# source code.|
|[VariantNumber](http://msdn.microsoft.com/en-us/library/3a27a825-5667-4d23-a896-b31d6f129d15)|Indicates the variant number of the entity, if any, in a linear sequence of elements with F# source code.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

