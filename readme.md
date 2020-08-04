
#####################################################################
## Question: 
      1. What is JVM ? 
## Answer:  
     1. JVM(Java Virtual Machine) acts as a run-time engine to run Java applications. JVM is the one that actually calls the main method present in a java code. JVM is a part of JRE(Java Runtime Environment).

     2. Java applications are called WORA (Write Once Run Anywhere). This means a programmer can develop Java code on one system and can expect it to run on any other Java enabled system without any adjustment. This is all possible because of JVM.

    3. When we compile a .java file, .class files(contains byte-code) with the same class names present in .java file are generated by the Java compiler. This .class file goes into various steps when we run it. 
     2. https://medium.com/@neil.wilston123/why-java-is-platform-independent-1d82c2249a69#:~:text=When%20the%20Java%20program%20runs,RAM%20of%20any%20operating%20system.&text=Hence%20java%20is%20called%20platform%20independent%20language.

#####################################################################
## Questio: JDK,JRE,JVM,JRT compiler
## Answer:  
       1.https://www.geeksforgeeks.org/just-in-time-compiler/#:~:text=The%20JIT%20compiler%20aids%20in,code%2C%20instead%20of%20interpreting%20it.

#####################################################################
## Questio: 9 reasons why used java as by developers. 
## Answer:  
      1. https://medium.com/@neil.wilston123/9-awesome-reasons-why-java-is-popular-f972c41aa9ae

#####################################################################
## Questio: Exception in java 
![alt text](https://static.javatpoint.com/images/throwable.png)
## Pointers:
     1.  checked or compile time exceptions. 
     2.  unchecked exceptions or run time exceptions.
     3.  Errors vs exceptions 
## Answer: 
     1. https://www.javatpoint.com/exception-handling-in-java

#####################################################################
## Questio: string, stringBuilder, stringBuffer.
## Answer: 
      1.  String is immutable. create a new string when we try to append string with the current string. 
      2.  Both StringBuilder,StringBuffer is mutable. 
      3.  StringBuffer is thread safe. If there is multiple threads are running going for StringBuffer is a good option.
      4.  https://www.geeksforgeeks.org/string-vs-stringbuilder-vs-stringbuffer-in-java/

#####################################################################
## Questio: Stack memory space vs heap memory space
## Answer:  


#####################################################################
## Question: ArrayList vs Vector vs LinkedList
![alt text](http://www.programcreek.com/wp-content/uploads/2009/02/java-collection-hierarchy.jpeg)
## Answer:  
     1. ArrayList is implemented as a re-sizable array. It's elements can be accessed directly by 
        using the get and set methods, since ArrayList is essentially an array.
     2.  LinkedList is implemented as a double linked list. Its performance on 
         add and remove is better than Arraylist, but worse on get and set methods.
     3. Vector is similar with ArrayList, but it is synchronized. ArrayList is a
        better choice if your program is thread-safe.
        Vector and ArrayList require space as more elements are added. 
        Vector each time doubles its array size, while ArrayList grow 50% of its size 
        each time. LinkedList, however, also implements Queue interface which adds more
        methods than ArrayList and Vector, such as offer(), peek(), poll(), etc.  

#####################################################################
## Question: Enumeration vs Iterator
## Answer:  
	    1) Enumeration, you can only traverse the Collection object. But using Iterator, you can also remove an element while traversing the Collection. This is the one major difference between Enumeration and Iterator in java. You can say Iterator is some what advanced version of Enumeration. In this post, we will see the differences between Enumeration Vs Iterator In Java. 
	    2) remove() method
		This is the main difference between Enumeration and Iterator interface. Enumeration only traverses the Collection object. You can’t do any modifications to Collection while traversing the Collection using Enumeration. Where as Iterator interface allows us to remove an element while traversing the Collection object. Iterator has remove() method which is not there in the Enumeration interface. Below is the list of Enumeration and Iterator methods.
		Iterator	Enumeration
		hasNext()	hasMoreElements()
		next()	nextElement()
		remove()	(Not Available)
		3) Legacy Interface
		Enumeration is a legacy interface used to traverse only the legacy classes like Vector, HashTable and Stack. Where as Iterator is not a legacy code which is used to traverse most of the classes in the collection framework. For example, ArrayList, LinkedList, HashSet, LinkedHashSet, TreeSet, HashMap, LinkedHashMap, TreeMap etc.
		4) Fail-Fast Vs Fail-Safe
		 
		Iterator is a fail-fast in nature. i.e it throws ConcurrentModificationException if a collection is modified while iterating other than it’s own remove() method. Where as Enumeration is fail-safe in nature. It doesn’t throw any exceptions if a collection is modified while iterating. [See more]
		5) Safe And Secure
		As Iterator is fail-fast in nature and doesn’t allow modification of a collection by other threads while iterating, it is considered as safe and secure than Enumeration.
		6) Which One To Use
		According to Java API Docs, Iterator is always preferred over the Enumeration. Here is the note from the Enumeration Docs.
		NOTE: The functionality of this interface is duplicated by the Iterator interface. In addition, Iterator adds an optional remove operation, and has shorter method names. New implementations should consider using Iterator in preference to Enumeration.
		Enumeration Vs Iterator In Java :
		Enumeration	Iterator
		Using Enumeration, you can only traverse the collection. You can’t do any modifications to collection while traversing it.	Using Iterator, you can remove an element of the collection while traversing it.
		Enumeration is introduced in JDK 1.0	Iterator is introduced from JDK 1.2
		Enumeration is used to traverse the legacy classes like Vector, Stack and HashTable.	Iterator is used to iterate most of the classes in the collection framework like ArrayList, HashSet, HashMap, LinkedList etc.
		Methods : hasMoreElements() and nextElement()	Methods : hasNext(), next() and remove()
		Enumeration is fail-safe in nature.	Iterator is fail-fast in nature.
		Enumeration is not safe and secured due to it’s fail-safe nature.	Iterator is safer and secured than Enumeration.

#####################################################################
## Question: HashMap vs HashTable
## Answer:  

#####################################################################
## Question: Absract class vs Interface
## Answer:  

#####################################################################
## Question: static variable, static class, static methods
## Answer:  

#####################################################################
## Question: inner class vs nested class. 
## Answer:  

#####################################################################
## Question: Songleton class is pattern. 
## Answer:  


#####################################################################
## Question: equals vs == 
## Answer:  

#####################################################################
## Question: Internal Implementation of HashMap 
## Answer: 
      1.Before Java8 they used Arraylist but later the used 
        Balanced binary search tree ( AVL or RedBlack Tree )    

#####################################################################
## Question: Comparable vs Comparator
## Answer:  

#####################################################################
## Question: Thread in Java and write a program run two thread  simultaneously 
## Answer:  

#####################################################################
## Question: ArrayList vs LinkedList
## Answer:  

#####################################################################
## Question: static and Dynamic Polymorphism 
## Answer:  

#####################################################################
## Question:
## Answer:  

#####################################################################
## Question:
## Answer:  

#####################################################################
## Question:
## Answer:  

#####################################################################
## Question:
## Answer:  

