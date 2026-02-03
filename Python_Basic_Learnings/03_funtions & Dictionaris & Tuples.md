## Funtions


### Exaample
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
