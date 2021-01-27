# Python 기초
---
###  연산자
-     사칙연산은 다똑같다
### 제곱 

---
### 파이썬 모듈을 이용한 수학계산 
        - 이젠 파이썬 함수를 이용한 거듭제곱 ==> pow
        - 수학 모듈 불러오기  --> import math as 수학 //도 가능 as를 python 에서 쓸수 있다. 
        -  sin 45 ?  math.sin(45) 

---
### 난수 발생
-     난수 발생 모듈 -> import random 
-      로또 645 번호 획득하기 -> 숫자 6개 1~45까지 --> random.sample(lotto_list, 6) 

---
### 반올림
        -- round(3.5) -> 4//인데 round(2.5)--> 2가 나옴 Bug이다

---
### 올림
        --

---
### 내림
        --

---
### 메모리에 있는 변수 삭제하기

        --

---
### 관계 연산자

        --
### 논리연산자
### 문자열 자료형
### 문자열 indexing과 slicing
### 문자열 formatting
        -  %d : 정수형 formatting
        -  %S : 문자열 formatting
        - 혼합형 formatting

### 문자열 관련 함수
        -  문자 count ? 몇글자이냐??
        -  문자 위치 알려주기 2가지 method가 있다  
        -  1. str01.find("x") 2. str01.index('e')
        -  문자열 삽입(join)  == > 합쳐지는것
        - 소문자를 대문자로 변환(upper)
        - 대문자를 소문자로 변환(lower)
        - 공백 지우기
        - 문자열 바꾸기(replace)
        - 문자열 나누기(split)
###  날짜형 변환
        - datetime 이라는 Package를 불러와야함
        - 형을 날짜형으로 바꿔주는 함수가 datetime이다. 
        - 날짜 계산 
          현재 일, 시간
        - 특정 날짜로부터 시간 계산
