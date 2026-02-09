## 1) Funtions


### Exaample 1
```python

siddu_expence=[100,500,800,200]
nanuve_expence=[10,50,40,100]

s_t_exp=0
for s_exp in siddu_expence:
    s_t_exp+=s_exp
print(s_t_exp)

n_t_exp=0
for n_exp in nanuve_expence:
    n_t_exp+=n_exp
print(n_t_exp)

def find_total(expence):
    total=0
    for expences in expence:
        total+=expences
    return total
siddu_expence=[100,500,800,200,400]
nanuve_expence=[10,50,40,100]

total_siddu_expence=find_total(siddu_expence)
print(total_siddu_expence)
total_nanuve_expence=find_total(nanuve_expence)
print(total_nanuve_expence)
```

### Exaample 2
```python
def find_cylinder_radius(radius,height): #def find_cylinder_radius(radius,height=7): define default value
    print(radius)
    print(height)
    volume=3.14*(radius**2)*height
    #print(volume)
    return volume
r=10
h=7
#v=(find_cylinder_radius(r,h))
v=find_cylinder_radius(height=h,radius=r) # To specify parametername & variable
print(v)

def sum_all(*args):
    total=0
    for arg in args:
        total+=arg
    return total

total=sum_all(1,2,3,4,2.3)
print(total)

def company_info(**kwargs):
    for key in kwargs:
        print(f"{key}: {kwargs[key]}")

company_info(name="Styra",ceo="subodh",revenue="100 cr")
```
## 2) Tuple
A tuple is a collection of items that is ordered and immutable (unchangeable). Tuples are similar to lists, but once a tuple is created, you cannot modify it. They are often used to group related data together.
``` python
tpl=(5,10,20)
print(tpl[0])
print(type(tpl))
```
#### Creating a Tuple with One Element:
To create a tuple with only one element, include a trailing comma:
``` python
single_element_tuple = ("apple",)
```
####  Tuple Operations
Although tuples are immutable, you can perform various operations with them.

Tuple Concatenation:
You can combine two or more tuples using the + operator.
``` python
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
combined_tuple = tuple1 + tuple2
print(combined_tuple)  # Output: (1, 2, 3, 4, 5, 6)
```

#### Tuple Repetition:
You can repeat a tuple multiple times using the * operator.
```python
repeated_tuple = (1, 2) * 3
print(repeated_tuple)  # Output: (1, 2, 1, 2, 1, 2)
```
#### Checking Membership:
You can check if an item exists in a tuple using the in operator.
```python
print("apple" in fruits)  # Output: True
```
#### Tuple Methods
Though tuples are immutable, Python provides some built-in methods for working with tuples.
count(): Returns the number of times an element appears in the tuple.
```python
my_tuple = (1, 2, 3, 1, 1)
print(my_tuple.count(1))  # Output: 3

index(): Returns the index of the first occurrence of an element.
my_tuple = ("apple", "banana", "cherry")
print(my_tuple.index("banana"))  # Output: 1
```
#### Advantages of Using Tuples
1) Immutable: This property ensures that tuple data cannot be modified after creation, making them useful for fixed data.
2) Faster than Lists: Due to immutability, tuples are generally faster than lists.
3) Can Be Used as Keys in Dictionaries: Since tuples are hashable, they can be used as keys in dictionaries, unlike lists.









## 3) Dictionary

``` python
d={'siddu':7624882767,'appa':9880108856}
print(d)
print(type(d))
```

