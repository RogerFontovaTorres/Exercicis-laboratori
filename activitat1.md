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

MOVE x 3

MOVE y 4

CMP x 0
BRANCH_SMALLER end
    ADD result y
end:


