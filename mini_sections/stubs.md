## Stubs

Stubs are methods which are defined, but not yet implemented.
They can be very helpful to keep track of what's still to be done and allow to compile and test projects 
before the implementation is complete.

In the following example, stubbing the method `calculatePi()` allows you to use and test the method `plus()`
that you have already implemented.

```java
public class Subclass extends SimpleMathDefinition{
    
    @Override 
    public int plus(int x, int y){
        return x + y;
    }  

    @Override 
    public double calculatePi(){
        // TODO Method Stub. Not yet implemented.
        return 0;
    }
}
```

Assume now that you run out of time or you don't know how to implement `calculatePi()`.
You may want to submit something like this (and mention it in your README.md):

```java
public class Subclass extends SimpleMathDefinition{
    
    @Override 
    public int plus(int x, int y){
        return x + y;
    }  

    @Override 
    public double calculatePi(){
        // TODO I did not find the time to implement this method. I thus hardcoded a mock return value of 3
        return 3;
    }
}
```

#### Practical Note on Mock Return Value
Note that while this is a quick-and-dirty way to help you getting partial points for your other code in a programming assignment,
this is not a reasonable approach in real life production code. 
There, you'd probably prefer to throw an exception instead of returning a mock value (making sure the unimplemented method is never used)
and use proper mock dependencies for testing.

