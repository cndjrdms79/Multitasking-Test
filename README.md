# Multitasking-Test
## 안동대학교 컴퓨터공학과 20141264 정혜성 20141233 고근호
### Multitasking-Test 과제를 제출합니다.
### mult1.h -> #define WM_MY (WM_USER + 1) 추가 한다.
![1](https://user-images.githubusercontent.com/54826844/69139807-a25d0000-0b04-11ea-9ffd-60257992b2b8.JPG)
### mult1Dlg -> 재정의 -> PreTranslateMessage 추가 -> 아래코드추가
![2](https://user-images.githubusercontent.com/54826844/69139815-a4bf5a00-0b04-11ea-8d01-7c7b52644582.JPG)
### 솔루션 mult1 우클릭 -> 추가 -> 함수추가 -> 함수이름 OnMyFun 변환형식 LRESULT 매개변수 WPARAM wParam LPARAM lParam 추가
![3](https://user-images.githubusercontent.com/54826844/69139820-a6891d80-0b04-11ea-8d3a-d720d6322a16.JPG)
### 추가된 OnMyFun에 아래코드추가
![4](https://user-images.githubusercontent.com/54826844/69139825-a7ba4a80-0b04-11ea-95b8-7ba45fa2f948.JPG)
### mult1Dlg에 68라인에 아래코드 추가
![5](https://user-images.githubusercontent.com/54826844/69139830-aa1ca480-0b04-11ea-8345-61b46b343ac1.JPG)
### mult1Dlg.h 안에 아래의 코드 
![7](https://user-images.githubusercontent.com/54826844/69139842-b0128580-0b04-11ea-9d83-05f297c90918.JPG)
### 결과화면
![6](https://user-images.githubusercontent.com/54826844/69139837-ad179500-0b04-11ea-8311-10e38de2eb8e.JPG)
