# LanguagePrimitives.GenericComparisonWithComparer<'T> Function (F#)

Compare two values. May be called as a recursive case from an implementation of **T:System.IComparable&#96;1** to ensure consistent NaN comparison semantics.

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
GenericComparisonWithComparer : IComparer -> 'T -> 'T -> int (requires comparison)

// Usage:
GenericComparisonWithComparer comp e1 e2
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*comp*
Type: **T:System.Collections.IComparer**


The function to compare the values.


*e1*
Type: **'T**


The first value.


*e2*
Type: **'T**


The second value.



**The result of the comparison.**
## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives+Module+%28FSharp%29.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+%28FSharp%29.md)
