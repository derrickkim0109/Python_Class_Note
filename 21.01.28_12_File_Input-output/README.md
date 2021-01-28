# 파일 입출력


파일을 쓰기모드로 열어 출력값 저장하기
file 은 open()이라는 것으로 열어서 사용
new.txt라는 파일을 만들어서 w = write 모드다 
---
###  파일 읽고 쓰기
        -  파일을 읽기모드로 열어 파일내용 출력하기 - 1
           r = read 모드로 읽을것이다는 명령어
        -  파일을 읽기모드로 열어 파일내용 출력하기 - 2
           r = read 모드로 읽을것이다는 명령어 
           for 문 쓸려면 Data값을 다 가져와야 쓸수가 있다. 
           readline 은 1개 씩 데이터 불러온다 ex) 1 , 번, 째, 줄, 입, 니, 다, .
           readlines 하면 한줄씩 불러온다 ex) 1번째 줄 입니다. / 2번째 줄 입니다. / 3번째 줄 입니다.
        -  파일을 읽기모드로 열어 파일내용 출력하기 - 3
           한꺼번에 한줄 별로 다 출력 시켜 준다.
        -  pandas쓰면 훨씬더 간단해 진다. 
           이미지, 동영상, 음성 -> 파일로 만들어서 써야한다
           파일에 새로운 내용 (데이터) 추가하기
           open(location, 'order')
           a = append
           
### with문
- 파일의 열고/닫음 을 자동으로 처리, with문을 벗어나면 자동으로 close
            
        -  파일 만들기 
           그냥 open이 아니라 with open
           
---
### Pandas로 불러오기
        - python으로 크롤링과 데이터 분석을 하고싶으면 Pandas
        - txt file 불러오기
        - R의 data.framework와 비슷하게 생겼네?
        - header = None는 header가 없을때 
        - Window 일경우 encoding = "euc-kr"
        - txt file 저장하기
        - index 안쓸때 
        - index 는 줄 번호이다. 



