# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value type whereas Classes are reference type. Structs are stored on the stack whereas Classes are stored on the heap.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Instantiation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
To allow the method to be overridden
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Internal, Protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only a member in the same class
```