# Read class 3

### Java Primitives versus Objects

#### Java Type 
Java has a two-fold type such as int, boolean Every primitive type corresponds to a reference type.

#### Pros and Cons
The decision what object is to be used is based on what application performance we try to achieve, how much available memory we have && amount of available memory && what default values we should handle.

- Single Item Memory Footprint
- Memory Footprint for Arrays
- Performance
- Default Values

#### Usage
current Java language specification doesn't allow usage of primitive types.
Our application needs collections with a big number of elements.

# Exception

> What Is an Exception?
 An exception is an event that occurs during the execution of a program that disrupts the normal flow of instructions.

> The Catch or Specify Requirement.
 This means that code that might throw certain exceptions must be enclosed


> How to Throw Exceptions
 The throw statement requires a single argument: a throwable object. Throwable objects are instances of any subclass of the Throwable class

> The try-with-resources Statement 
 try-with-resources statement is a try statement that declares one or more resources. A resource is an object that must be closed after the program is finished with it. The try-with-resources statement ensures that each resource is closed at the end of the statement. Any object that implements java.lang.AutoCloseable, which includes all objects which implement java.io.Closeable, can be used as a resource


>Advantages of Exceptions
- Separating Error-Handling Code from "Regular" Code
- Propagating Errors Up the Call Stack
- Grouping and Differentiating Error Types
  

> Scanning
Objects of type Scanner are useful for breaking down formatted input into tokens and translating individual tokens according to their data type.A scanner uses white space to separate tokens