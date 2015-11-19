# ExtraTopLevelOperators.dict<'Key,'Value> Function (F#)

Builds a read-only lookup table from a sequence of key/value pairs. The key objects are indexed using generic hashing and equality.

**Namespace/Module Path**: Microsoft.FSharp.Core.ExtraTopLevelOperators

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
dict : seq<'Key * 'Value> -> IDictionary<'Key,'Value> (requires equality)

// Usage:
dict keyValuePairs
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*keyValuePairs*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'Key &#42; 'Value&gt;**



**An object that implements T:System.Collections.Generic.IDictionary&#96;2 that represents the given collection.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **CreateDictionary** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code example shows the use of the dict function.**
**[!CODE [FsCoreLib2#1](../CodeSnippet/VS_Snippets_Fsharp/fscorelib2/FSharp/fs/program.fs#1)]**
**The output is as follows.**
**The dictionary is read only.**
**Value for key 5: 25**
**Key: 1 Value: 1**
**Key: 2 Value: 4**
**Key: 3 Value: 9**
**Key: 4 Value: 16**
**Key: 5 Value: 25**
**Key: 6 Value: 36**
**Key: 7 Value: 49**
**Key: 8 Value: 64**
**Key: 9 Value: 81**
**Key: 10 Value: 100**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.ExtraTopLevelOperators Module &#40;F&#35;&#41;](Core.ExtraTopLevelOperators+Module+28%F%2329%.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+28%F%2329%.md)
