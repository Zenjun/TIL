#### 전 회차와 같이 마찬가지로 반복적으로 조건을 적용하는 elif를 사용하여 조건문을 완성하는 식이다.
#### ```<input>```으로 사용자의 나이를 입력받은 후, 어느 세대에 속하는 나이인지 출력하는 코드이다.
```python
y= int(input('What year were you born'))
```
#### 위와 같은 코드로 언제 태어났는지 질문을 하고,
```python
gen = None
```
#### 답을 출력할 명령어를 지정한 후에 
```python
if y <= 1924:
  gen = 'the Greatest Generation'
elif y <= 1945:
  gen = 'the Silent Generation'
elif y <= 1964:
  gen = 'a baby boomer'
elif y <= 1980:
  gen = 'a millennial'
else:
  gen = 'a Gen Z'

print(f"you're {gen}.")
```
#### 위와 같은 식으로 여러 조건문을 걸어 내가 원하는 식을 출력할 수 있다. 
