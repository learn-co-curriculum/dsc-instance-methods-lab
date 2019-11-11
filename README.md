
# Instance Methods - Lab

## Introduction
In the last lesson, you learned about instance methods -- what they are and how to define them. In this lab, you are going to flesh out the `Driver` and `Passenger` classes by writing your own instance methods for these classes.

## Objectives

In this lab you will: 

* Create an instance of a class 
* Define and call an instance method


## Define classes and instance methods

You will now define classes and associated instance methods in the cell below: 
    
> **Remember:** *as we learned in the previous lesson, we need to define our instance methods with at least one argument (`self`) in order to call them on an instance object.*

Define a class `Driver` with two instance methods: 

- `greeting`: this should return the string `"Hey, how are you?"` 
- `ask_for_destination`: this should return the string `"Where would you like to go today?"` 


```python
# Define Driver class here
```

Define a class `Passenger` with two instance methods: 

- `reply_greeting`: this should return the string `"I am doing well!"` 
- `in_a_hurry`: this should return the string `"Punch it! They're on our tail!"`


```python
# Define Passenger class here 
```

## Instantiate classes and methods

Great! You've now defined classes and the associated instance methods. You will now actually use them: 

Start by instantiating a driver and a passenger. Assign the driver to the variable `daniel` and assign the passenger to `niky`. 


```python
daniel = None # driver
niky = None # passenger
```

Alright, you have the passengers and drivers! Now you need to put those instance methods to use. Try them out and assign the return values to the variables below. 

- Have `daniel` greet his passenger, who is going to be `niky`. Assign the greeting to the variable `polite_greeting` 
- Have `niky` respond by calling `in_a_hurry()`, and assign the return value to the variable, `no_time_to_talk` 


```python
polite_greeting = None
print(polite_greeting)
```


```python
no_time_to_talk = None
print(no_time_to_talk)
```

## Feel like doing more? 

In the cells below, you'll create three different classes that represent animals in a zoo -- lions, tigers, and elephants. Each animal should have a method, `speak()`, which returns a string containing the sound they make (feel free to have some fun with this -- we don't know how to spell the sound an elephant makes any better than you do!). 


```python
# Create Lion class

```


```python
# Create Tiger class

```


```python
# Create Elephant class

```

Now, in the cell below, create an instance of each animal: 


```python
simba = None
tony = None
dumbo = None
```

Now, add each of them into the list `zoo` in the cell below: 


```python
zoo = None
```

Now, loop through the `zoo` list and call out the `.speak()` method for every animal in the zoo. Make sure you print this in order to see the output! 


```python

```

## Summary
In this lab, you practiced defining classes and instance methods. You then instantiated instances of your classes and used them to practice calling your instance methods. 
