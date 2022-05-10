# note

- idle >> python shell running


## 변수와 함수
```

- 변수 사용
x = 'Hello'
print(x)

- 함수 사용

- 입력받는 함수.
name = input('what is your name?')
what is your name? dk
print(name)
dk

- 파일 작성 후 실행

idle >> new File >> source code edit >> save >> 'F5' to running

- 반복문
links = ['1','2','3']

for link in links:
  ...
  
- 문자열 자르기
string[start:end:step] >> step 미지정 시, 1 고정

- 위치 값 찾기(indexOf)
string.find('str') >> 있으면 양수 리턴, 없으면 -1 리턴

- 존재 여부 
in, not in >> value = 'str' in(not in) string >> return true/false
ex) 
value = 'str' in 'string'
if value:
  ...
else:
  ...
  
- 현재 날짜/시간 

import datetime

now = datetime.datetime.now()
print(now)          # 2015-04-19 12:11:32.669083

nowDate = now.strftime('%Y-%m-%d')
print(nowDate)      # 2015-04-19

nowTime = now.strftime('%H:%M:%S')
print(nowTime)      # 12:11:32

nowDatetime = now.strftime('%Y-%m-%d %H:%M:%S')
print(nowDatetime)  # 2015-04-19 12:11:32


```
