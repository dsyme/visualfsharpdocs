# Operators.string<^T> Function (F#)

Converts the argument to a string using **M:System.Object.ToString**.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
string : ^T -> string

// Usage:
string value


```





#### Parameters
*value*
Type: **^T**


The input value.



**The converted string.**
## Remarks
For standard integer and floating point values the **M:System.Object.ToString** conversion uses **P:System.Globalization.CultureInfo.InvariantCulture**.

This function is named **ToString** in compiled assembly. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

