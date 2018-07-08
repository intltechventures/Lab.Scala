
Reading Notes, from Programming in Scala, Third Edition
====

Chapter-1: A Scalable Language
* ```Actor``` class allows passing messages
	* Syntax: {receiving object} ! {message}
	* ```!``` is a method of the Actor class
* ```Traits``` are like Java Interfaces, but can include method implementation details - as well as field definitions.
* Objects are consructed by ```mixin composition```
	* "takes members of a class and adds members of a number of traits to them"
	* Different aspects of classes can be encapsulated in different traits - sort of like multiple inheritance...
* Functional
	* Functions are 1st class values
	* Operations of a program should map input values to output values rather than modify data (i.e. use immutable data structures)
	* Methods should not have side effects ('referentially transparent')
* Strings are treated as high-level sequence of characters, can be queried by ```predicates```
	* ```Function Literal```: A function that takes a character argument (represented by the "_")
* Intersections: to combine types
* Scala Static Type system advantages: 
	* Verbosity avoided through type inference
	* Flexibility gained through pattern matching 
	* New ways to write and compose types 
	* Verified properties of program abstractions
	* Safe refactoring
	* Better documentation 
	
	

