# FuncConvert.FuncFromTupled<'T1,'T2,'T3,'U> Method (F#)

A utility function to convert function values from tupled to curried form.

**Namespace/Module Path**: Microsoft.FSharp.Core

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
static member FuncFromTupled : ('T1 * 'T2 * 'T3 -> 'U) -> 'T1 -> 'T2 -> 'T3 -> 'U

// Usage:
FuncConvert.FuncFromTupled (func)


```





#### Parameters
*func*
Type: **'T1 &#42; 'T2 &#42; 'T3 -&gt; 'U**


The input function that has tupled arguments.



**The output curried function.**
## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.FuncConvert Class &#40;F&#35;&#41;](Core.FuncConvert-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

