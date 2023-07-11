# Task-week-1
**#Task-1**

**Lambda Function**
Lambda expression is a new and important feature of Java which was included in Java SE 8. It provides a clear and concise way to represent one method interface using an expression. It is very useful in collection library. It helps to iterate, filter and extract data from collection.
The Lambda expression is used to provide the implementation of an interface which has functional interface. It saves a lot of code. In case of lambda expression, we don't need to define the method again for providing the implementation. Here, we just write the implementation code.
Java lambda expression is treated as a function, so compiler does not create .class file.

**Java lambda expression is consisted of three components.**

1) **Argument-lis**t: It can be empty or non-empty as well.

2) **Arrow-token**: It is used to link arguments-list and body of expression.

3) **Body**: It contains expressions and statements for lambda expression.

**#Task-2** 

**Stream API**
**Stream**
This package consists of classes, interfaces and enum to allows functional-style operations on the elements. You can use stream by importing java.util.stream package.

Stream provides following features:

1. Stream does not store elements. It simply conveys elements from a source such as a data structure, an array, or an I/O channel, through a pipeline of computational operations.
2. Stream is functional in nature. Operations performed on a stream does not modify it's source. For example, filtering a Stream obtained from a collection produces a new 3. Stream without the filtered elements, rather than removing elements from the source collection.
4. Stream is lazy and evaluates code only when required.
5. The elements of a stream are only visited once during the life of a stream. Like an Iterator, a new stream must be generated to revisit the same elements of the source.

**Task-3**

**Exceptation Handling**
The Exception Handling in Java is one of the powerful mechanism to handle the runtime errors so that the normal flow of the application can be maintained.
Exception Handling is a mechanism to handle runtime errors such as ClassNotFoundException, IOException, SQLException, RemoteException, etc.

There are mainly two types of exceptions: checked and unchecked. An error is considered as the unchecked exception. However, according to Oracle, there are three types of exceptions namely:

1.Checked Exception
2.Unchecked Exception
3.Error

**Task-4**

**Collection API**
The collection API is the Application Programming Interface and it provided the reusable functionality for a core set of the algorithms that can be operated with the list collections. It has some util packages and it contains some default classes and interfaces that can be required by the collection framework. The following types are some java collections APIs are:

1. **Collection Interface:** This is the parent root of the collection hierarchy and it implements the methods for creating the application.
2. **Iterator Interface:** Using this interface we can iterate the datas for the loops like “for, while, etc”.
3. **Set Interface**: It is one of the default interfaces and it does not support the duplicate elements in the list.
4. **List Interface:** The list interface is used to store and access the collection datas in the memory. It has some default methods for performing the operations.
5. **Queue Interface:** This interface follows the FIFO(First-In-First-Out) order by the data structure which means that the element which is inserted first will be removed from the first, if we want to add then it will add the new element in the list.
6. **Dequeue Interface:** This deque knew as a double-ended queue and it is the ordered collection of data items which is similar to the queue. Like that it has two ends like front and rear position.
7. **Map Interface:** It is mostly used interface in the collection and using the default methods the values are operated by using the key-value pair items.
8. **List-Iterator Interface:** The list iterator interface allows for traversing the elements in any of the direction and also it obtains the current position in the list.
9. **Sorted-Set Interface:** It is the set interface that will be maintained in the ascending order of the elements. This will be generally used in the ordered sets such as the word lists and other membership areas.
10. **Sorted Map Interface**: This is also the same as Sorted-Set but here the datas ordered will be the key-value pairs.

**Task-4**






