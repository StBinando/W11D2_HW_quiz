# Polymorphism & Composition Homework - Quiz

# Polymorphism

####1. What does the ___word___ 'polymorphism' mean?
- literally "many shapes"; it means that can be used in many ways;

####3. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
- a class can use interfaces and inheritance in order to allow a class to select and use different objects depending on the circumstances;
We can have a super Class of output devices, and children classes of specific ones. And a computer Class able to select which one to use using a generic interface with a method useOutputDevice; 

####4. What can we use to implement polymorphism in Java?
- interfaces, super classes (abstract or not), composition and aggregation;

####5. How many 'forms' can an object take when using polymorphism?
- unlimited

####6. Give an example of when you could use polymorphism.
- when a class can contain different classes and behave differently depending on which class is used;



# Composition and Aggregation

####6. What do we mean by 'composition' in reference to object-oriented programming?
- composition means that we have a Class made up of other classes that are created within itself, so when the Class object is discarded, so are the classes it contains. It follows the principle "is part of".

####8. When would you use composition? Provide a simple example in Java.
- A house is "composed" on many parts, as Roof, Chimney... but they cannot exist outwith the context of the House;

####10. Give a difference between composition and aggregation?
- classes within a composition cannot exist outwith the main class (Roof within a house);
classe within an aggregation can exist independently (engine within a car)

####11. What is/are the advantage(s) of using composition/aggregation?
- the individual pieces/classes that are used in composition/aggregation can be customised for different Classes, maintaining single responsibility, and allowing those classes to change behavior at runtime 

####12. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
-they are also destroyed;

####13. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
- they are kept alive, as created outwith the object being destroyed.