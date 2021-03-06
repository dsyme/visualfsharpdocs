# Core.RequiresExplicitTypeArgumentsAttribute Class (F#)

Adding this attribute to a type, value or member requires that uses of the construct must explicitly instantiate any generic type parameters.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




[<AttributeUsage(AttributeTargets.Method, AllowMultiple = false)>]
[<Sealed>]
type RequiresExplicitTypeArgumentsAttribute =
class
new RequiresExplicitTypeArgumentsAttribute : unit -> RequiresExplicitTypeArgumentsAttribute
end


```





## Remarks
You can also use the short form of the name, **RequiresExplicitTypeArguments**.


## Constructors


|Member|Description|
|------|-----------|
|[new](http://msdn.microsoft.com/en-us/library/3e361f16-4e93-4492-9233-156f2612a0c6)|Creates an instance of the attribute|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

