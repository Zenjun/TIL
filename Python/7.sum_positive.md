#### 이번에는 양수만 더하다가 음수가 입력되면 중단하고 그 전까지 더한 값을 출력하는 코드를 짜보도록 하겠습니다. 
```py
sum = 0
while True:
  num = int(input())
  if num < 0:
    break
  else:
    sum += num

print(sum)
```
