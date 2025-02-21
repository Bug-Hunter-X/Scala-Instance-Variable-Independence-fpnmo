# Scala Instance Variable Independence

This example illustrates a point that may be confusing to beginners in Scala: instance variables are specific to each object instance.

## The Code

The `MyClass` class has a private instance variable `internalValue`. The `Main` object creates two instances of `MyClass`, demonstrates how updating `internalValue` for one instance does not affect the other. This is in contrast to static variables, that are shared among all instances.

## How to run

Save the code as `MyClass.scala` and compile/run using the Scala compiler:
```bash
scala MyClass.scala
```

## Discussion

This is fundamental to object-oriented programming.  Understanding that instance variables are unique to each object is crucial for avoiding unexpected behavior in more complex programs.