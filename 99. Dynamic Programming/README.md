# Dynamic Programming
완전 탐색의 문제점 보완 (비효율 개선)
구현해야 할 기능이
- 특정 범위를 반복적으로 호출하거나 = 전체 문제의 답을 부분 문제로 쪼개서 풀 수 있어야 함
- 조금씩 겹치는 구조를 갖는다면 = 동시에 문제들 중 중복되는 부분이 있을 때.

https://blog.naver.com/ndb796/221233570962   
'하나의 문제는 단 한번만 푼다'
- 이미 계산한 결과는 배열에 저장
    - 추후 동일한 계산이 필요할 때 저장된 값 반환 -> 반복 연산 X

Fibonacci number

![image](https://user-images.githubusercontent.com/53294075/222070405-2c8cbf5d-fd25-4615-9485-ae53a7f41df4.png)

~~Chibonacci 🍗~~   
~~Fibonachicken 🐔~~
- Recursive function
- Dynamic Programming
