# 2.04 Lists - Part 1  Instructions

## 1. In the console (right side)

### Type in the following:

```python
    a_list = ['a', 'b', 'c', 'd', 'e']
    print(len(a_list))
```

### Answer the following discussion questions as a comment:

1. What type do you think a_list is? (Hint: look at the variable name.)
2. What does `len` do?
3. Brainstorm how you would print the first element from `a_list`.

## 2. In your notebook, predict what will happen when the program below is run.

### In the console, type the following:

```python
    a_list = ['a', 'b', 'c', 'd', 'e']
    print(a_list[0])
    print(a_list[1])
    print(a_list[2])
    print(a_list[3])
    print(a_list[4])
    print(a_list[5])
    print(a_list[6])
```

### Continue in your notebook.

Describe what happened when the program was run.  Were there any differences from your predictions?
---

# 2.04 Lists - Part 1 `main.py`

## In the console (right side), type the following without the number symbols:
## a_list = ['a', 'b', 'c', 'd', 'e']
## print(len(a_list))

### Answer the following discussion questions:
# 1. What type do you think a_list is? (Hint: look at the variable name.)
# 2. What does `len` do?
# 3. Brainstorm how you would print the first element from `a_list`.

### In the console (right side), type the following without the number symbols:
## a_list = ['a', 'b', 'c', 'd', 'e']
## print(a_list[0])
## print(a_list[1])
## print(a_list[2])
## print(a_list[3])
## print(a_list[4])
## print(a_list[5])
## print(a_list[6])

### Answer the following discussion question:
# Describe what happened when the program was run.  Were there any differences from your predictions?

---

# 2.04 Lists - Part 2 Instructions

## 1. In your notebook

For each example below, predict what will be printed. Run the program and write down the output in your notebook.

### Example 1

```python
    a = ['a', 'b', 'c', 'd', 'e']
    print(a[0])
    print(a[3])
```

### Example 2

```python
    a = ['a', 'b', 'c', 'd', 'e']
    print(a[len(a) - 3])
```

### Example 3

```python
    a = ['a', 'b', 'c', 'd', 'e']
    print(a[len(a) - 6])
```

### Example 4

```python
    a = ['a', 'b', 'c', 'd', 'e']
    a[3] = 'haha'
    print(a)
```

## 2. Create a Game Show program, this time using lists and indexes

* Declare 10 prizes, stored in a single list variable.
* User picks a number.
* Print prize associated with the number user picked.

## 3. Create a quiz

Create a food quiz using lists and indexes.

1. List of 6 different foods.
2. Ask the user 8 general questions to find out what their favorite food is from the list.
3. Update a score list for each food. Print out the user's favorite food based on the score list.

Hint: Use a search engine to look up an efficient way to find the largest number in a Python list.

[Starter code here](Starter_food_chooser.py)

## Bonus

* Use the score list to print out the user's second favorite food as well as the favorite.
* Tied scores can be handled in any reasonable way -- e.g., print the tied-score food item earliest on the list as the "favorite", and the next item as the "second favorite".
* Alternatively, check for the existence of a tie, and acknowledge that situation when it happens by printing a separate message.

Hint: as with the favorite score, using syntax we've learned so far, we can only find this value if we know the length of our food list, using a series of if...elif statements. Alternate methods that use much less code can be found with an Internet search. Some of these methods will be covered in later units.

---

# 2.04 Lists - Part 2 `main.py`

## Make a prediction for each of the examples in the instructions. Record your prediction. Run the program in the IDE. Record the actual output

## Example 1: Prediction
## Example 1: Actual Output

## Example 2: Prediction
## Example 2: Actual Output

## Example 3: Prediction
## Example 3: Actual Output

## Example 4: Prediction
## Example 4: Actual Output


## ----------------- Game Show Program ----------------- ##
# You may comment out this program when you work on the Food Quiz Program.
### START ###

### END ###

## ----------------- Food Quiz Program ----------------- ##

### START ###
food = ['donuts', 'pancakes', 'bacon', 'waffles', 'eggs', 'bagels']
score = [0,0,0,0,0,0]

print('Please answer each question with "y" for "yes" and "n" for "no".')
user_input = input('Do you like food with holes? ')
if user_input == 'y':
  score[0] = score[0] + 1
  score[5] = score[5] + 1

## Add remaining questions below this line, and adjust scores similar to the above. ##

### END ###
