---
layout: post
title:  "Python_pracitce01"
date:   2022-12-13
categories: psm
---

## Python_pracitce01

### 1. 파이썬 기초 코딩
'''
    python -m venv 가상환경이름

        Scripts\activate
'''

### 2. 파이썬 기본 입출력
'''
    1. print(값)
       print(값1, 값2, ...)
        - end 속성
        - sep 속성
'''

data = "Hello Ezen!"
print(data)

print('Hello ezen')
print("Hello Ezen")
print("""Hello Ezen!""")
print('''Hello Ezen!!''')
print()

data1 = 7
data2 = 5
data3 = 8
print(data1, data2, data3)
print(data1, data2, data3, sep=",")
print(data1, data2, data3, end="[END]")
print()


print("2022", "12", "07", sep="-")
print("niceyear", "gamil.com", sep="@")


### f-string을 사용하려면 간단히 문자열을 출력할 수 있음
score = 70
print(f"학생의 점수는 {score}점 입니다.")

print("test1: %5d, price: %4.2f" %(776, 6534.123))
print()


'''
    2. input()을 이용한 표준 입력
        1) input(): 키보드로부터 문자열을 입력받음
        2) int(): 사용자로부터 입력받은 정보를 정수 형태로 처리하기 함께 사용함
'''

### data = input()
### print(data)

