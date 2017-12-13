# Polymorphism & Composition Homework - Quiz

# Polymorphism (IS A)

1. What does the ___word___ 'polymorphism' mean?

It means to take on many forms (poly = many, morph = form).*

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means that an object can take on many forms. i.e. when creating a class:

public class Dog extends Pet implements IActions{}

  the dog in this instance is a:
  1. Dog
  2. Pet
  3. IActions
  4. Object


3. What can we use to implement polymorphism in Java?

inheritance (abstract classes, super classes) and interfaces - as demonstrated above.

4. How many 'forms' can an object take when using polymorphism?

It can take the form of itself and an object, and as many more as it has superclasses and interfaces.

5. Give an example of when you could use polymorphism.

When you need to use different items at different time that are not necessarily the same object but fulfil the same method within the class.
When grouping many objects that have the same behaviours.
It makes the class flexible and extendable.


# Composition (HAS A)

6. What do we mean by 'composition' in reference to object-oriented programming?

It is when a object is created by combining(composing) several different objects with their own specific behaviours.
Composition is when a class references a group or family of behaviours.

7. When would you use composition? Provide a simple example in Java.

i.e. a car has an Array List of Wheels Objects, a body Object, An Array List of door Objects.
a car could have an Engine (perhaps a superclass and you could use polymorphism to change the engine (!))

8. What is/are the advantage(s) of using composition?

It is much less code and keeps your program DRY...
It also allows greater flexibilty and the option to add further objects to a program without having to re-factor
It also helps keep classes Single Responsibility.
allows you to swap at runtime when combining this with polymorphism.

9. What happens to the behaviours when the object composed of them is destroyed?

Those behaviours are also destroyed
