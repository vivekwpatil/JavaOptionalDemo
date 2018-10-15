# Java Optional Demo

1. Why Optional?

![Screenshot](src/main/resources/NullpointerExceptioncartoon.png)

- How many times in our development career, we have troubles with "NullpointerException"?
- To avoid this we end up adding lot of boiler plate code checking each and every variable in nested object.
- To make this clean, Java Optional can be used effectively.

2 . Java 8 optional
 different methods available on Optional object:
  - get
  - isPresent
  - filter:If a value is present, and the value matches the given predicate, return an Optional describing the value, otherwise return an empty Optional
  - map 
  - orElse
  - orElseGet
  - orElseThrow

3 . Java 9 Optional new methods
- stream
- ifPresentOrElse
- or



