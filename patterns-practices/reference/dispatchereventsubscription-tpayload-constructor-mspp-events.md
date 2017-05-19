---
TOCTitle: 'DispatcherEventSubscription(TPayload) Constructor'
Title: 'DispatcherEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.Events.IDispatcherFacade)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683971(v=PandP.50)'
---

# DispatcherEventSubscription&lt;TPayload&gt; Constructor

Creates a new instance of BackgroundEventSubscription.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public DispatcherEventSubscription(
	IDelegateReference actionReference,
	IDelegateReference filterReference,
	IDispatcherFacade dispatcher
)
```


### Parameters

*actionReference*

    Type: IDelegateReference
    A reference to a delegate of type [Action&lt;T&gt;(http://msdn2.microsoft.com/en-us/library/bfcke1bz)].

*filterReference*

    Type: IDelegateReference
    A reference to a delegate of type [Predicate&lt;T&gt;(http://msdn2.microsoft.com/en-us/library/bfcke1bz)].

*dispatcher*

    Type: [Microsoft.Practices.Prism.Events.IDispatcherFacade](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events.idispatcherfacade(v=pandp.50))
    The dispatcher to use when executing the *actionReference* delegate.

## Exceptions

| Exception | Condition                                                                                                                              | [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | When *actionReference* or are **null**a null reference (**Nothing** in Visual Basic).                                                                                                                                                           |
| [System.ArgumentException](http://msdn2.microsoft.com/en-us/library/3w1b3114) | When the target of *actionReference* is not of type [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8), or the target of *filterReference* is not of type [Predicate&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/bfcke1bz). |

## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/gg431416(v=pandp.50))

[DispatcherEventSubscription&lt;TPayload&gt; Members](https://msdn.microsoft.com/en-us/library/gg430769(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

# DispatcherEventSubscription(Of TPayload) Constructor

Creates a new instance of BackgroundEventSubscription.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	actionReference As IDelegateReference,
	filterReference As IDelegateReference,
	dispatcher As IDispatcherFacade
)
```


### Parameters

*actionReference*

    Type: IDelegateReference
    A reference to a delegate of type [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

*filterReference*

    Type: IDelegateReference
    A reference to a delegate of type [Predicate(Of T)](http://msdn2.microsoft.com/en-us/library/bfcke1bz).

*dispatcher*

    Type: [Microsoft.Practices.Prism.Events.IDispatcherFacade](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events.idispatcherfacade(v=pandp.50))
    The dispatcher to use when executing the *actionReference* delegate.

## Exceptions

| Exception | Condition                                                                                                                              | [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | When actionReference or are *Nothinga* null reference (*Nothing* in Visual Basic).
                                 |
| [System.ArgumentException](http://msdn2.microsoft.com/en-us/library/3w1b3114) | When the target of *actionReference* is not of type [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8), or the target of *filterReference* is not of type [Predicate(Of T)](http://msdn2.microsoft.com/en-us/library/bfcke1bz). |

## See Also

[DispatcherEventSubscription(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/gg431416(v=pandp.50))

[DispatcherEventSubscription(Of TPayload) Members](https://msdn.microsoft.com/en-us/library/gg430769(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))