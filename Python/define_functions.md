#### ```trple```로 함수를 지정해주고 
```py
def triple(x):
  return x * 3
```
#### ```korean_age```도 함수를 지정해준다.
```py
def korean_age(birth_year):
  from datetime import datetime
  today = datetime.today()
  return today.year - birth_year + 1
```
#### 그다음 코드를 완성한다면 다음과 같다.
```py
def triple(x):
  return x * 3

def korean_age(birth_year):
  from datetime import datetime
  today = datetime.today()
  return today.year - birth_year + 1

if __name__ == '__main__':
  print("triple(2):", triple(2))
  print("triple('x')", triple('x'))
  print("korean_age(2000)", korean_age(2000))
``` 
