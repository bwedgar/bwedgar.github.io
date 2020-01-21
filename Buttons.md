Buttons is the name of the framework I use to make Web Apps. 
It uses objects to produce a namespace. 
The objects are made using:
```
ObjectName=new function(){
  y=4;
  this.x=2*y;
}
```
Any variable (value or function) prefixed with this is copied to the object and can be accessed using ```ObjectName.variable```
Variables without this are private to the (anonymous) function that creates the object and cannot be accessed from the object
I tried a few different patters such as singletons, modules and factory functions to make the framework but found the way described easiest. 
