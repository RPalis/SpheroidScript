//[Spheroid Script](../index.md)/[spheroid](index.md)/[check](check.md)



# check  
 
Throws an [IllegalStateException](-illegal-state-exception/index.md) if the [value]() is false.  
  
  
fun [check](check.md)(value: [Boolean](-boolean/index.md)): [Unit](-unit/index.md)  


 
Throws an [IllegalStateException](-illegal-state-exception/index.md) with the result of calling [lazyMessage]() if the [value]() is false.  
  
  
fun [check](check.md)(value: [Boolean](-boolean/index.md), lazyMessage: () -> [Any](-any/index.md))  



