# Stock Methods
 

The <a href="1df39166-cdbc-ea41-0f5d-56de5e09158b">Stock</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="090965dd-a373-63b1-08c1-bc38738ea2ad">RemoteGetter</a></td><td>
Universal getter method without reference to the instance. Please use direct getter as much as possible. Remote setter is designed for generic computation methods.
 (Inherited from <a href="bce605e3-e729-258a-0e66-9bfb6e48c607">MathObject</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="f27fefd1-791f-1bb1-3e1e-c8d33f566812">RemoteLink</a></td><td>
Universal abstraction for inner relationship between two properties in this instance. This method build up a function that can help you get a new value of the dependent variable when you change the value of the independent variable. Input value should always be <a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a> and return types is also <a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a>. Remote link is designed for generic computation methods.
 (Inherited from <a href="bce605e3-e729-258a-0e66-9bfb6e48c607">MathObject</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="9549b6b3-3f98-bc2d-f2fe-10355f8d5464">RemoteSetter</a></td><td>
Universal setter method without reference to the instance. To set value, input must be <a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a>. Please use direct setters as much as possible. Remote setter is designed for generic computation methods.
 (Inherited from <a href="bce605e3-e729-258a-0e66-9bfb6e48c607">MathObject</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="da420a04-08e1-4ec7-b29f-b8446ae7263d">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="bce605e3-e729-258a-0e66-9bfb6e48c607">MathObject</a>.)</td></tr></table>&nbsp;
<a href="#stock-methods">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="718ec2ab-e890-7d30-f161-f5a9ecf2f0b3">To(T)</a></td><td>
Shortcut to cast a obj from one type to another. Be careful of if these types can cast directly.
 (Defined by <a href="f8375fff-6215-8a0d-083f-b42a5658e465">MathClassHelper</a>.)</td></tr></table>&nbsp;
<a href="#stock-methods">Back to Top</a>

## See Also


#### Reference
<a href="1df39166-cdbc-ea41-0f5d-56de5e09158b">Stock Class</a><br /><a href="d9e4b2f9-9258-2f31-ca55-43e6b838bbc3">MathFuncConsole.MathObjects.Applications Namespace</a><br />