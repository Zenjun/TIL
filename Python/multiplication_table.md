#### 자동으로 구구단을 출력하는 코드를 작성해보겠습니다.
#### 먼저 구구단을 할수 있는 코드를 함수를 이용해 작성하면
```py
def multi(m):
  for n in range(1,10):
    print(f'{m} * {n} = {m*n:2d}')
```
#### 가 됩니다. 
#### 이를 통해 반복하기 위해서 ```for```문을 통해 2단에서 9단까지 작성하게 되면 아래와 같습니다. 
```py
def multi(m):
  for n in range(1,10):
    print(f'{m} * {n} = {m*n:2d}')

if __name__ == '__main__':
  for i in range(2, 10):
    multi(i)
    print()
```
