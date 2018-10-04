
# Practice with Instance Methods

## Introduction
In the last lesson, we talked about instance methods -- what are they and how to define them. In this lab, we are going to put our new skills to the test and start writing our own instance methods on our classes.

## Objectives

* Practice defining classes and instantiating instances of those classes
* Practice defining instance methods and calling them

## Defining Classes and Instance Methods

In this section, define two classes, `Driver`, `Passenger`. 

In the `Driver` class, define the instance method `greeting` that returns the string `"Hey, how are you?"`. Then define the method `ask_for_destination`, which returns the string `"Where would you like to go today?"`. 

In the `Passenger` class, define the instance method `reply_greeting` that returns the string `"I am doing well! Thanks for picking me up today!"`. Then define the method `in_a_hurry`, which returns the string `"Punch it! They're on our tail!"`. 

Define these classes and instance methods in the cells below
    
> **Remember:** *as we learned in the previous lesson, we need to define our instance methods with at least one argument (`self`) in order to call them on an instance object. Don't worry, we will learn more about this argument in a later lesson.*


```python
# Define Driver class here
class Driver(object):
    
    def greeting(self):
        return "Hey, how are you?"
    
    def ask_for_destination(self):
        return "Where would you like to go today?"
```


```python
# Define Passenger class here 
class Passenger(object):
    
    def reply_greeting(self):
        return "I am doing well! Thanks for picking me up today!"
    
    def in_a_hurry(self):
        return "Punch it! They're on our tail!"
```

## Instantiate Instances and Practice Using Instance Methods
Great! We've defined our classes and our instance methods. Now, in this section we are going to actually use them!

Start by instantiating two drivers and two passengers. Assign the drivers to the variables `daniel` and `meryl` and assign the passengers to `niky` and `terrance`.


```python
daniel = Driver() # driver
meryl = Driver() # driver
niky = Passenger() # passenger
terrance = Passenger() # passenger
```

Alright, we have our passengers and drivers! Now we need to put those instance methods to use. Try them out and assign the return values to the variables below. Let's have `daniel` greet his passenger, who is going to be `niky`. Assign the greeting to the variable, `polite_greeting`. Have `niky` respond by calling `in_a_hurry`, and assign the return value to the variable, `no_time_to_talk`.


```python
polite_greeting = daniel.greeting()
print(polite_greeting)
```

    Hey, how are you?
    


```python
no_time_to_talk = niky.in_a_hurry()
print(no_time_to_talk)
```

    Punch it! They're on our tail!
    

## Extra Practice

Now, let's have some extra practice creating classes, instantiating objects, and using instance methods. 

In the cells below, you'll create three different classes that represent animals in a zoo--lions, tigers, and elephants.  Each animal should have a method, `speak`, which returns a string containing the sound they make (feel free have some fun with this--we don't know how to spell the sound an elephant makes any better than you do!). 


```python
# create Lion class
class Lion(object):
    
    def speak(self):
        return "Roar"
```


```python
class Tiger(object):
    
    def speak(self):
        return "Meow"
```


```python
class Elephant(object):
    
    def speak(self):
        return "woo-I'm-an-elephant!"
```

Now, in the cell below, create an instance of each animal. 


```python
simba = Lion()
tony = Tiger()
dumbo = Elephant()
```

Now, append each of them into the array `zoo` in the cell below.


```python
zoo = []
zoo.append(simba)
zoo.append(tony)
zoo.append(dumbo)
```

Now, loop through the `zoo` array and call print out the `.speak()` method for every animal in the zoo. 


```python
for animal in zoo:
    print(animal.speak())
```

    Roar
    Meow
    woo-I'm-an-elephant!
    

## Summary
In this lab, we practiced defining classes and instance methods. We then instantiated instances of our classes and used them to practice calling our instance methods. 
