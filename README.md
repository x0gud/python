# python
## 2026-10-21 


<함축식 리스트>
```python
squares = [ x*x for x in range(10) ]
```
____

<누적 합 리스트>
```python
list1 =  [10, 20 , 30, 40, 50]

list2 = [sum(list1[0:x+1])for x in range(0, len(list1))]

print("원래 리스트:",list1)
print("새로운 리스트:",list2)
```
____

<정상적인 파이썬 함수>
```python
def func1(x):
         return x + 1
```

<람다 함수>
``` python
func = lambda x, y : x + y

resut = func(2,3)
print(result)

myList = [1, 2, 3, 4, 5, 6, 7, 8, 9]
result = map(lambda x: x**2, myList)   #[1, 4, 9, 16, 25, 36, 49, 64, 81]
```
