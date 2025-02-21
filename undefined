```scala
class MyClass {
  private var internalValue: Int = 0

  def updateValue(newValue: Int): Unit = {
    internalValue = newValue 
  }

  def getValue(): Int = {
    internalValue
  }
}

 object Main extends App {
  val myObject = new MyClass
  myObject.updateValue(10)
  println(myObject.getValue()) // Prints 10

  // Creating another instance, which will have its own independent internalValue
  val anotherObject = new MyClass
  println(anotherObject.getValue()) //Prints 0, as expected. Note that this is different from myObject
 }
```