#### 원금, 단리 이율, 기간이 주어졌을 때 이자를 구하는 함수 ```simple_interest()```를 구하고,
#### 원금, 단리 이율, 기간이 주어졌을 때 원리금을 계산하는 함수 ```simple_interest_amount()```를 구하는 코드를 작성해보겠습니다.
#### 먼저 이자를 구하는 함수 ```simple_interest()```를 다음과 같이 정하고
```py
def simple_interst(p, r, t):
  return p * r * t
```
#### 원리금을 계산하는 함수 ```simple_interest_amount()```를 다음과 같이 정합니다.
```py
def simple_interest_amount(p, r, t):
  return p * (1 + r * t)
```
#### 그리고 코드를 작성하면 다음과 같습니다.
```py
def simple_interest(p, r, t):
  return p * r * t

def simple_interest_amount(p, r, t):
  return p * (1 + r * t)

if __name__ == '__main__':
  print('Quiz 1')
  print('ex 1:', simple_interest(10000000, 0.03875, 5))
  print('ex 2:', simple_interest(1100000, 0.05, 5/12))

  print('\nQuiz 2')
  print('ex 1:', simple_interest_amount(10000000, 0.03875, 5))
  print('ex 2:', simple_interest_amount(1100000, 0.05, 5/12))
```
