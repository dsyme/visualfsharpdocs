# Operators.using<'T,'U> Function (F#)

Clean up resources associated with the input object after the completion of the given function. Cleanup occurs even when an exception is raised by the protected code.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
using : 'T -> ('T -> 'U) -> 'U (requires 'T :> IDisposable)

// Usage:
using resource action


```





#### Parameters
*resource*
Type: **'T**


The resource to be disposed after action is called.


*action*
Type: **'T -&gt; 'U**


The action that accepts the resource.



**The resulting value.**
## Remarks
This function is named **Using** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

