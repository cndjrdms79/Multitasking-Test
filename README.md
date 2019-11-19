# Multitasking-Test
## 안동대학교 컴퓨터공학과 20141264 정혜성 20141233 고근호
### Multitasking-Test 과제를 제출합니다.
### 1. mult1.h -> #define WM_MY (WM_USER + 1) 추가 한다.
![1](https://user-images.githubusercontent.com/54826844/69139807-a25d0000-0b04-11ea-9ffd-60257992b2b8.JPG)
### 2. mult1Dlg -> 재정의 -> PreTranslateMessage 추가 -> 아래코드추가
![2](https://user-images.githubusercontent.com/54826844/69139815-a4bf5a00-0b04-11ea-8d01-7c7b52644582.JPG)
### 3. 솔루션 mult1 우클릭 -> 추가 -> 함수추가 -> 함수이름 OnMyFun 변환형식 LRESULT 매개변수 WPARAM wParam LPARAM lParam 추가
![3](https://user-images.githubusercontent.com/54826844/69139820-a6891d80-0b04-11ea-8d3a-d720d6322a16.JPG)
### 4. 추가된 OnMyFun에 아래코드추가
![4](https://user-images.githubusercontent.com/54826844/69139825-a7ba4a80-0b04-11ea-95b8-7ba45fa2f948.JPG)
### 5. mult1Dlg에 68라인에 아래코드 추가
![5](https://user-images.githubusercontent.com/54826844/69139830-aa1ca480-0b04-11ea-8345-61b46b343ac1.JPG)
### 6. mult1Dlg.h 안에 아래의 코드 
![7](https://user-images.githubusercontent.com/54826844/69139842-b0128580-0b04-11ea-9d83-05f297c90918.JPG)
### 7. 결과화면
![6](https://user-images.githubusercontent.com/54826844/69139837-ad179500-0b04-11ea-8311-10e38de2eb8e.JPG)

### 소감 및 감동
#### 고근호 : 수업시간에 멀티태스킹에 대해서 배워봤는데, 수업시간에 해결되지 않은 마지막에 오류 수정하는 부분이 잘 되지 않아서 어려움을 겪은것 같습니다.. 하지만 교수님이 올려주신 cafe에 MFC사용자 정의 메시지 처리에 대해서 읽으면서 팀원과 같이 차근차근 해보니 과제를 잘 마무리 할 수 있었던것 같습니다. 수업시간에 배운 내용을 복습할 수 있고 멀티태스킹에 대해서 좀 더 공부할 수 있는 유익한 시간이었습니다. 감사합니다. MFC사랑합니다♥

#### 정혜성 : 교수님이 알려주신대로 수업시간에 잘 따라가며 멀티태스킹에 대해서 학습하고 오류부분 수정을 위해서 팀원과 같이 노력하였으나 수정이 완벽하게 되지 않는것 같아 고심하고 있던 찰나에 교수님께서 올려주신 MFC카페에 있는 멀티태스킹 부분을 참고하여 과제를 제출하였습니다. 과제를 진행하면서 멀티태스킹에 대한 학습에 많이 도움이 되었고, 오류를 수정하며 좀 더 자세히 공부할 수 있었던 유익한 시간이었습니다. MFC수업 사랑합니다♥ 
