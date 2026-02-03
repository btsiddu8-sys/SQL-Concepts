## 1) List
A list is a collection of items that are ordered, mutable (changeable), and allow duplicate elements. Lists can hold items of different data types, such as integers, strings, or even other lists.
01) Lists allow you to store sequential data.
2) Lists are ordered, meaning each item has a fixed position unless explicitly changed.
3) Python lists can hold different data types in a single list, including numbers, strings, and other
   lists. This means they are heterogeneous. For example my_list = [”car”, 4.5, True]
4) Lists are mutable, allowing for elements to be added, removed, or changed within the same list.
5) List slicing lets you access a specific range of elements quickly, using the syntax list[start : end : step]


### Example
```python
list=['siddu',123,1.34]
```

### 2. Accessing List Elements
You can access individual elements in a list using indexing. Remember that Python uses zero-based indexing, so the first item is at index 0
```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # Output: apple
print(fruits[2])  # Output: cherry
```
### You can also use negative indexing to access elements from the end of the list:
```python
print(fruits[-1])  # Output: cherry
print(fruits[-2])  # Output: banana
```
### 3. Modifying Lists
Lists are mutable, which means you can change the value of items in a list.
#### 
Changing a specific element
```python
fruits[1] = "orange"
print(fruits)  # Output: ['apple', 'orange', 'cherry']
```

## 2) IF Condition
1) If statements execute a block of code only if the condition is true, enabling conditional logic in programs.
2) Use elif to specify additional conditions if the initial if condition fails, allowing for multiple sequential checks.
3) else provides a fallback block of code when all preceding if and elif conditions are false.
4) Combine logical operators like and, or, and not within if statements to handle complex conditional expressions.
5) Nested if statements allow for checking multiple layers of conditions, enabling detailed decisionmaking processes in code.


## 3) For Loop
1) For loops iterate over a sequence, such as a list, tuple, or string, executing a block of code for each item.
2) The range() function is often used with for loops to generate a sequence of numbers, facilitating iteration over a set number of steps.
3) Loop control statements like break and continue can alter the flow of a loop, with break exiting the loop and continue skipping to the next iteration.
4) enumerate() will allow you to access both the index and the element from a list inside the for loop

   ### Example 1
   ```python
   amt=[1,2,3,4,5]
      total_amt=0
         for amount in amt:
          total_amt=total_amt+amount
         print(f"Total Amount: {total_amt}")
   ```
   ### Example 2
```python
monthly_sales=[100,200,500,1000]
cutoff=400
for month in monthly_sales:
    if month < cutoff:
        print(f"{month} is less than cutoff")
       # break
        continue
    else:
        print(f"{month} is more than cutoff")
```
 ### Example 3
 ```python
n=0
while n<10:
    print(n)
    n=n+1
```



   
