# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

*It means to take on many forms (poly = many, morph = form).*

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

*It means that an object can take on many forms. i.e. when creating a class:

# public class Dog extends Pet implements IActions{}

  the dog in this instance is a:
  1. Dog
  2. Pet
  3. IActions
  4. Object*


3. What can we use to implement polymorphism in Java?

*super classes and interfaces - as demonstrated above.*

4. How many 'forms' can an object take when using polymorphism?

*It can take the form of itself and an object, and as many more as it has superclasses and interfaces.*

5. Give an example of when you could use polymorphism.

*When you need to use different items at different time that are not necessarily the same object but fulfil the same method within the class*


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
*Composition is when we use an Interface to reference a particular group of behaviours, and then use that interface to pass into a class.  This means that at run time, we can attribute that particular instance of the Interface to any object that implements that Interface, and this can change at each runtime.*

*It is when a object is created by combining(composing) several different objects with their own specific behaviours.*

7. When would you use composition? Provide a simple example in Java.
*...* *i.e. a car has an Array List of Wheels Objects, a body Object, An Array List of door Objects*

8. What is/are the advantage(s) of using composition?
*It is much less code and keeps your program DRY...
It also allows greater flexibilty and the option to add further objects to a program without having to re-factor
It also helps keep classes Single Responsibility.*

9. What happens to the behaviours when the object composed of them is destroyed?
*Those behaviours are also destroyed*
