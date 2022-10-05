# 2.03 - Conditionals - Warm-Up

In the console, create a schedule program. Given the hour of the day, print out where you should be. If you're not doing anything else you should be "sleeping".

### Example
```python
>>> What hour? 12pm
>>> You should be at lunch!
```
### Underneath your program, answer the following reflection questions as comments:

1. How did you accomplish this?
2. Did you feel like something was missing in your program?  
3. What if you wanted to add in a weekly functionality? For instance, maybe on Tuesday at 4pm you are at soccer practice, but on Thursday at 4pm you are at math club!
4. How would you implement this in your program?

## Warm-Up - `main.py`
```python
# 2.03 - Conditionals - Guided Notes

## Using the example in the instructions, create a schedule program. Given the hour of the day, print out where you should be. If you're not doing anything else you should be "sleeping".

### START CODE ###

### END ###
# --------------------------------------------------
## Answer the reflection questions
### 1. 
### 2. 
### 3. 
### 4. 

```

# Lesson 2.03: Conditionals - Guided Notes

## `if-statements`

* In order to write useful programs, we almost always need the ability to check conditions and change the behavior of the program accordingly.
* **Conditional** statements give us this ability to affect the **flow of control**.
* The simplest way is the `if-statement`. The Boolean expression after `if` is called the **condition** or **conditional**. 


**If the conditional is `True`**, then the indented statement gets executed. 

**If `False`**, the if-statement ends..

Code Trace these examples:

#### Example 1
```python
if x > 0:
    print("x is positive")
```
#### Example 2
```python
animal = input("What is your favorite animal?")
if animal == 'cat' or 'dog':
print("A great pet!")
else:
print("Good choice")
```

## `else` and `elif`
`else` is used when there is something that needs to be executed if the conditional is `False`
* You do not have to include an `else` with every `if-statement`

`elif`
Short for "else if". 
* Sometimes there are more than two possibilities and we need more than two branches. It allows us to check for *multiple* expressions via a chained conditional. 
* If the condition for `if` is `False`, the program checks the condition of the next elif block and so on. 

```python
if num > 0:
      print('positive')
 elif num < 0:
      print('negative')
 else:
      print('0')
```

`if` is always the first in a sequence. 
After the program gets to the `if` statement, either the condition of the statement is true, and it runs the `if` code
Or its `false`, and then the program checks for an attached elif/else.

## Concepts
* `if-else` statements control the flow of the program by providing ways to make decisions
` * Boolean expression(condition), the colon, and the indentation

* `else/elif` is used when there are two or more possibilities and the condition determines which one gets executed.
  *  If the `if-statement` conditional is `true`, then the action under the `if` statement is executed. 
  *  If the `if-statement` conditional is `false`, then the program will check for an `else/elif`.
  *  when none are present, the program exits the `if` statement and continues on with the program (like it never happened)

### Lab
## Re-write the schedule program
Given the hour of the day, print out where you should be. If you're not doing anything else you should be "sleeping".

Example Output:
```python
What time of day is it? 12

```

## Write a triangle program in Python 3.
