# List.reduce<'T> Function (F#)

Applies a function to each element of the collection, threading an accumulator argument through the computation. This function first applies the function to the first two elements of the list. Then, it passes this result into the function along with the third element and so on. Finally, it returns the final result. If the input function is **f** and the elements are **i0...iN**, then it computes **f (... (f i0 i1) i2 ...) iN**.

**Namespace/Module Path:** Microsoft.FSharp.Collections.List

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
List.reduce : ('T -> 'T -> 'T) -> 'T list -> 'T

// Usage:
List.reduce reduction list


```





#### Parameters
*reduction*
Type: **'T -&gt; 'T -&gt; 'T**


The function to reduce two list elements to a single element.


*list*
Type: **'T**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The input list.



**exceptions tag is not supported!!!!**
**The final reduced value.**
## Remarks
This function is named **Reduce** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code example illustrates the use of List.reduce.**
[!code-fsharp[Main](snippets/fslists/snippet33.fs)]
**Output**
**16**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

