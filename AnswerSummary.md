# Java Basic Objects Practice

## Object test
 1.What is the knowledge point of the test? Where is the official document to the knowledge point?
- [Object class](https://docs.oracle.com/javase/8/docs/api/java/util/Objects.html)
- [Java is Pass by Value](https://www.journaldev.com/3884/java-is-pass-by-value-and-not-pass-by-reference)
- [Object internal state](https://www.javacodegeeks.com/2011/10/testing-objects-internal-state-with.html)
- [Overloading Methods](https://docs.oracle.com/javase/tutorial/java/javaOO/methods.html)
- [Execution of Initialization blocks and Constructors in Java](https://www.geeksforgeeks.org/order-execution-initialization-blocks-constructors-java/)
- [Instance Initialization Block (IIB) in Java](https://www.geeksforgeeks.org/instance-initialization-block-iib-java/)
- [Constructors in Java](https://www.geeksforgeeks.org/constructors-in-java/)
- [Variable Arguments (Varargs) in Java](https://www.geeksforgeeks.org/variable-arguments-varargs-in-java/)

## Inheritance Test
- [Subclasses, Superclasses, and Inheritance](http://journals.ecs.soton.ac.uk/java/tutorial/java/javaOO/subclasses.html)
- [Super Keyword in Java](https://www.geeksforgeeks.org/super-keyword/)
- [Arrays Types](https://docs.oracle.com/javase/specs/jls/se7/html/jls-10.html)
- [Java instanceof](https://www.javatpoint.com/downcasting-with-instanceof-operator)
- [Working With hashcode() and equals()](https://dzone.com/articles/working-with-hashcode-and-equals-in-java)

## Exception Test
-[Get the class name in a static method](https://www.rgagnon.com/javadetails/java-0402.html)
-[Exceptions in Java](https://stackify.com/specify-handle-exceptions-java/)
-[Flow control in try catch finally in Java](https://www.geeksforgeeks.org/flow-control-in-try-catch-finally-in-java/)

2.Why the test failed at first?
- It's because the expected result is originally set to 0 or some pre-fixed value while "assertEquals()/assertThrows()" compare the expected and the actual result and output a Boolean as the comparison result. 

3.Why you corrected the test that way?
- So that the expected result should be matched to the actual result which is stated in each unit test

4.Do you have further questions on this knowledge point?
 - Should be okay
