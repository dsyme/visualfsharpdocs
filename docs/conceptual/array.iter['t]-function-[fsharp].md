# Array.iter<'T> Function (F#)

Applies the given function to each element of the array.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
Array.iter : ('T -> unit) -> 'T [] -> unit

// Usage:
Array.iter action array


```





#### Parameters
*action*
Type: **'T -&gt;**[unit](http://msdn.microsoft.com/en-us/library/00b837c2-6c8a-483a-87d3-0479c64037a7)


The function to apply.


*array*
Type: **'T**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The input array.




## Remarks
This function is named **Iterate** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code demonstrates the use of Array.iter.**
[!code-fsharp[Main](snippets/fssamples101/snippet1002.fs)]
**Array.iter: (1, 1) (2, 4) (3, 9) (4, 16) (5, 25)**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

