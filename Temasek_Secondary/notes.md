# Lesson 1

## Basic Data Types


Numbers - `1,2,3`

  `my_number = 1`

---

Strings - `"hello", "thomas"`

  `my_string = 'thomas'`

---

Lists - `[1,2,3], [1,2,'a'], ['hello','world'], [], [1]`

Collection of several items \
Can be indexed with `[]` \
Use the functions `.append()` and `.remove()` 

---

Dictionaries - `{'apples': 3, 'pears': 4}` 

Adding to dictionary: \
  `my_dict['oranges'] = 5` 
 
 Getting items from dictionary: \
  `num_apples = my_dict['apples']`
  
 ---
 
 
Booleans - can be either True or False

Truthy and Falsy
1. Empty lists are Falsy,        anything else is Truthy
2. Zero is Falsy,                Non-zero numbers are Truthy
3. An empty string is Falsy,     anything else is Truthy
4. An empty dictionary is Falsy, anything is Truthy
---

None - The None type 

None itself is Falsy
 
---

 If statements - 
 
 ```
 if (value < 5):
  print(value)
 else:
  print(other_value)
 ```
 
 For statements -

```
for num in my_list:
  print(num)
```
A common pattern with for loops is 
```
# create a variable to store some results
my_sum = 0

my_list = [15,31,12,15,17]
for i in my_list:
  my_sum += i
```
---


# Lesson 2

functions: 

```
def my_func(x,y):
  # code here
```
