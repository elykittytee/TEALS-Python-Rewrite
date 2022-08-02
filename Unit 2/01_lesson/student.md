# Lesson 2.01: Data Types & Casting

## Objectives

Students will be able to...

* Define and identify: **type, string, casting, floating point number (float), integer**
* Describe different representations of data in Python
* Convert from one data type to another data type

## Instructions

### 1. Do Now

* Complete the **Do Now**

### 2. Lesson

#### Discussion

* What is **type**?
  * Types are a way to represent data in different forms.
  * What are some types of "data" in your life?

#### Casting

* _type casting_ is being able to change the data type of a piece of data into another type.
* For example:

```python
str(123)
```
* What is the output of the code above?

Now explore the next few code snippets:

```python
    n = int(input())
    9
    type(n)
```

Output from Python:
```
    <class 'int'>
```

* Because Python 3 is strongly typed, concatenating strings and numbers requires casting.  Demonstrate by typing the following:

```python
    n = int(input())
    9
    print ("You entered " + n)
```

Output from Python:
```
    TypeError: Can't convert 'int' object to str implicitly
```

* Cast the integer to a string. Demonstrate by typing the following:

```python
    n = int(input())
    9
    print ("You entered " + str(n))
```

Output from Python:
```
    You entered 9
```

* Take a few minutes to have students write down how they would produce the following output:

```
    Give me a number you want to multiply by 2: 4
    8
```

* Explain to students that in Python
  * when asking for input from the user, *the input is automatically stored as a string*
  * if the input will be used for calculations or numeric comparisons, it will be necessary to cast it to another data type.

#### Swapping Variables

* Go over the method of swapping two variables using Python syntax covered so far, with a third temporary variable.
  * Python includes a way to swap two variables directly. The syntax for this will be covered in a later unit.

#### Student Sharing

* Call on 2-3 students to write their answers on the board.
* Discuss what would happen if the user types in 1.5 instead of 4.
* If input is a float, can cast with `float(num)`
* `type`: ask students what they think `type('a')` would output.  
* Why might you want to use `type`?

### 3. Lab

* Practice predicting what casting will do to inputs.
* Create a halving program, and a variant of the same program that converts any fractional output values to whole numbers.
* 

### 4. Debrief

* Check student progress and completion of the lab, wrap up by taking any final questions.
