# 2018.08.25
 ## 프로그래머스 > 파이썬 입문 > 실습 문제
 ### for in range 실습(3)
  
  enumerate 는 range(len())와 같은 기능을 하는 함수
  리스트가 있는 경우, 순서와 리스트 값을 전달
   '''python
   rainbow = {"빨", "주", "노", "초", "파", "남", "보"}
   for i, color in enumerate(rainbow)"
    print('{}번째 색은 {}'.format{I+1,color))
  '''
  
  '''python
   rainbow = {"빨", "주", "노", "초", "파", "남", "보"}
   for i in range(len(rainbow))"
    color = rainbow
    print('{}번째 색은 {}'.format{I+1,color))
 '''
 
 ### datetime -실습
 
 datetime library 안의 datetime.date.today는 오늘 날짜를 출력해주는 함수
 '''python
    import datetime
    print(datetime.date.today())
 '''
 
 ### random - 실습(1)
 random.choice() 는 list의 element중 하나를 가져오는 함수
 '''python
    import random
    list = {"빨", "주", "노", "초", "파", "남", "보"}
    random_element = random.choice(list)
    print(random_element)
  '''
  
  ### random - 실습(2)
  random.randint(a,b)는 a보다 크거나 같고 5보다 작은 임의의 정수를 가져오는 함수
  '''python
    import random
    random_number = random.choice(2,5)
    print(random_number)
  '''

### random - 실습(3)
random.shuffle()은 list의 순서를 섞는 함수
'''python
    import random
    list = {"빨", "주", "노", "초", "파", "남", "보"}
    random.shuffle(list)
    print(list)
'''

### 딕셔너리와 반복문 - 실습(1)
딕셔너리의 반복문에서는 key와 value를 가져올 수 있다.
```
    days_in_month = {"1월":31, "2월":28, "3월":31, "4월":30, "5월":31}
    for key in days_in_month.keys():
        print(key)
    
    for value in days_in_month.values():
        print(value)
```

### 딕셔너리와 반복문 - 실습(2)
key와 value를 한번에 가져올떄는 items()를 사용

'''python
    days_in_month = {"1월":31, "2월":28, "3월":31, "4월":30, "5월":31}
    for key,value in days_in_month.items():
        print("{}은 {}일이 있습니다.".format(key,value))
```



    
    
    '