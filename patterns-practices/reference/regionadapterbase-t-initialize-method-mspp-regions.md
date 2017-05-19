---
TOCTitle: Initialize Method
Title: 'RegionAdapterBase(T).Initialize Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.Initialize(\`0,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418936(v=PandP.50)'
---

Prism Class Library

RegionAdapterBase&lt;T&gt;.Initialize Method
===============================================================

Adapts an object and binds it to a new [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)


## Syntax

```C#
public IRegion Initialize( T regionTarget, string regionName )
```
```VB
'Declaration
Public Function Initialize ( regionTarget As T, regionName As String ) As IRegion
```


### Parameters

*regionTarget*  
Type: [T](https://msdn.microsoft.com/en-us/library/gg431546(v=pandp.50))

The object to adapt.

*regionName*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

The name of the region to be created.

### Return Value

Type: [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50))

The new instance of [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) that the *regionTarget* is bound to.

See Also
--------


[RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;) Class](https://msdn.microsoft.com/en-us/library/gg431546(v=pandp.50))

[RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;) Members](https://msdn.microsoft.com/en-us/library/gg405501(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))