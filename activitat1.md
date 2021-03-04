Pregunta 1:

```python
num1 = int(input("Numero 1: "));
num2 = int(input("Numero 2: "));
result = 0

while num1 > 0:
    result += num2
    num1-=1

print(result)
```
Pregunta 2:

MOVE x 3 # 3

MOVE y 4 # 3

MOVE result 0 # 3

#cost of 9 cycles

CMP x 0 # 2
BRANCH_SMALLER end # 5
    ADD result y # 3
    
    # cost of 10 cylces each loop
end:

Pregunta 3:

a) 11,13  -> 11 * 10 + 9 = 119 cycles   --> time = 119 / 4.77 * 10^6
b) 8,15 -> 8 * 10 + 9 = 89 cylces   --> time = 89 / 4.77 * 10^6
c) 15,8 -> 15 * 10 + 9 = 159 cycles   --> time = 159 / 4.77 * 10^6
