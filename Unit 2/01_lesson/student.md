# Lesson 2.01: Data Types & Casting

## Objectives

Students will be able to...

* Define and identify: **type, string, casting, floating point number (float), integer**
* Describe different representations of data in Python
* Convert from one data type to another data type

## Instructions
1. Do Now
2. Lesson
3. Lab

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

Try typing the following into the console:
```python
    n = int(input())
    9
    type(n)
```

Expected output from Python:
```
    <class 'int'>
```

* Because Python 3 is strongly typed, concatenating strings and numbers requires casting.  

Try typing the following into the console:
```python
    n = int(input())
    9
    print ("You entered " + n)
```

Expected output from Python:
```
    TypeError: Can't convert 'int' object to str implicitly
```

* Cast the integer to a string.

Try typing the following into the console:
```python
    n = int(input())
    9
    print ("You entered " + str(n))
```

Expected output from Python:
```
    You entered 9
```

* Take a few minutes to have students write down how they would produce the following output:

Try typing the following into the console:
```
    Give me a number you want to multiply by 2: 4
    8
```

* Explain to students that in Python
  * when asking for input from the user, *the input is automatically stored as a string*
  * if the input will be used for calculations or numeric comparisons, it will be necessary to cast it to another data type.

#### Swapping Variables

Imagine you had the following:
```python
a = 32
b = 15
```
Think to yourself: *How would you swap the values of these two variables?*

#### Student Sharing

* Call on 2-3 students to write their answers on the board.
* Discuss what would happen if the user types in 1.5 instead of 4.
* If input is a float, can cast with `float(num)`
* `type`: ask students what they think `type('a')` would output.  
* Why might you want to use `type`?

### 3. Lab

* Practice predicting what casting will do to inputs.
* Create a program that halves an inputted value.
* Modify the same program that converts any fractional output values into whole numbers.
