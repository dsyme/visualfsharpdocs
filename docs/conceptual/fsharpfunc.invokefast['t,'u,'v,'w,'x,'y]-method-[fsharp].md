# FSharpFunc.InvokeFast<'T,'U,'V,'W,'X,'Y> Method (F#)

Invoke an F# first class function value with five curried arguments. In some cases this will result in a more efficient application than applying the arguments successively.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
static member InvokeFast : FSharpFunc<'T,('U -> 'V -> 'W -> 'X -> 'Y)> * 'T * 'U * 'V * 'W * 'X -> 'Y

// Usage:
FSharpFunc.InvokeFast (func, arg1, arg2, arg3, arg4, arg5)


```





#### Parameters
*func*
Type: [FSharpFunc](http://msdn.microsoft.com/en-us/library/6fbc582c-a36a-4154-9bfe-296de5ecba53)**&lt;'T,('U -&gt; 'V -&gt;'W -&gt; 'X -&gt; 'Y)&gt;**


The input function.


*arg1*
Type: **'T**


The first arg.


*arg2*
Type: **'U**


The second arg.


*arg3*
Type: **'V**


The third arg.


*arg4*
Type: **'W**


The fourth arg.


*arg5*
Type: **'X**


The fifth arg.



**The function result.**
## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.FSharpFunc&#60;'T,'U&#62; Class &#40;F&#35;&#41;](Core.FSharpFunc%5B%27T%2C%27U%5D-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

