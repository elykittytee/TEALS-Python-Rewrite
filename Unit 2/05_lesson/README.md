# 2.05 Lists-2 Part 1

### PART 1 ###
##  Open up the IDE. Type the following example code:

### Example 1 - Slice

```python
a_list = [123, 'First Item', 456, 'Second Item']
b_list = a_list[0:2]
print(a_list)
print(b_list)
```

#### As a comment, respond to the following:

1. What happens to `a_list`?
2. What is in `b_list`?

### Example 2 - Remove

```python
a_list = [123, 'First Item', 456, 'Second Item']
a_list.remove('First Item')
print(a_list)
```

#### As a comment, respond to the following:

1. What does `remove` do?
2. What is the length of a_list after the remove?

### Example 3 - Pop

```python
a_list = [123, 'First Item', 456, 'Second Item']
popped_value = a_list.pop()
print(a_list)
print(popped_value)
```

#### As a comment, respond to the following:
1. what does `pop` do?
2. What is the difference between `remove` and `pop`?

### Example 4 - Concatenation

```python
a_list = [123, 'First Item', 456, 'Second Item']
b_list = a_list + ['Third Item']
print(a_list)
print(b_list)
```

#### As a comment, respond to the following:

1. What happens to a_list?
2. What is in b_list?

### Example 5 - Append

```python
a_list = ['First Item']
print(a_list)
a_list.append('Second Item')
print(a_list)
```

#### As a comment, respond to the following:

1. What does `append` do?
2. What would be the length after `append`?

## Assignment
1. Create an array containing the names `[Twilight, Pinkie, Fluttershy, Rainbow, Apple, Rarity]`
	* Print the array to the console.
2. *Slice* the array (see Example 2) from `[Fluttershy]` to `[Rarity]`.
	* Print the result to the console.
   * HINT: make a new variable 
3. Remove `[Twilight]`.
	* Print the modified array to the console.
4. Using *concatenation*, add `[Twilight]` back to the array. 
	* Print the modified array to the console.
5. *Pop* the last value of the array. 
	* Print the modified array to the console.
   * Print the *pop* value.
   * HINT: make another new variable
6. *Append* the popped value back into the array.
	* Print the modified array to the console.

## 2.05 Lists 2 - `main.py`
# 2.05 Lists-2 - `main.py`

### Example 1 ###
## Run your code in the IDE or in the console (right side)
## Answer the questions in your instructions below:
# 1. 
# 2. 

### Example 2 ###
## Run your code in the IDE or in the console (right side)
## Answer the questions in your instructions below:
# 1. 
# 2. 

### Example 3 ###
## Run your code in the IDE or in the console (right side)
## Answer the questions in your instructions below:
# 1. 
# 2. 

### Example 4 ###
## Run your code in the IDE or in the console (right side)
## Answer the questions in your instructions below:
# 1. 
# 2. 

### Example 5 ###
## Run your code in the IDE or in the console (right side)
## Answer the questions in your instructions below:
# 1. 
# 2. 

## ---------------------------- Assignment ----------------------------##
# Create an array containing the names [Twilight, Pinkie, Fluttershy, Rainbow, Apple, Rarity]
# Print the array to the console.
### BEGIN CODE ###



### END ###

# Slice the array (see Example 1) from [Fluttershy] to [Rarity].
# Print the slice result to the console.
# HINT: make a new variable
### BEGIN CODE ###



### END ###

# Remove [Twilight] (see Example 2).
# Print the modified array to the console.
### BEGIN CODE ###



### END ###

# Using concatenation, add [Twilight] back to the array. (see Example 4)
# Print the modified array to the console.
### BEGIN CODE ###



### END ###

# Pop the last value of the array. (see Example 3)
# Print the modified array to the console.
# Print the pop value.
# HINT: make another new variable
### BEGIN CODE ###



### END ###

# Append the popped value back into the array. (see Example 5)
# Print the modified array to the console.
### BEGIN CODE ###


### END ###
