# _**오픈소스 README파일 정리**_

* top

시스템의 상태를 전반적으로 가장 빠르게 파악 가능하다.

옵션 없이 입력하면 interval 간격(기본 3초)으로 화면을 갱신하며 정보를 보여준다.

|옵션|내용|
|---|---|
|-n|top 실행 주기 설정(반복 횟수)|
|shift + p|CPU 사용률 내림차순|
|shit + m|메모리 사용률 내림차순|
|shift + t|프로세스가 돌아가고 있는 시간 순|
|k|kill. k 입력 후 PID 번호 작성. signal은 9|
|f|sort field 선택 화면 -> q 누르면 RES순으로 정렬|
|a|메모리 사용량에 따라 정렬|
|b|Batch 모드로 작동|
|1|CPU Core별로 사용량 보여줌|

---

* ps

현재 실행되고 있는 프로세스 목록과 상태를 보여준다.

---

* jobs

작업의 상태를 표시하는 명령어

현재 쉘 셰션에서 실행시킨 백그라운드 작업의 목록이 출력된다.

kill명령어 뒤에 %번호를 입력하여 종료시킬 수 있다.




---

* kill

시스템상에서 동작하고 있는 프로세스에 간단한 메세지를 보내는 명령어다.

기본적으로 종료메세지를 보내며 프로세스에 종료하는 것을 요구한다.


---

* vim에서 메크로를 사용하는 법

1) 중립모드에서 q를 누른 후 이름으로 사용할 알파벳을 누른다.

2) 기록을 한다.

3) 중립모드에서 q를 눌러 기록을 끝낸다.

4) 중립모드에서 @a 를 누르면 매크로 a가 재생된다.

5) @@를 누르면 가장 마지막에 재생된 매크로가 재생된다.

![image](https://user-images.githubusercontent.com/104602224/171885242-6ef2ee4c-45b9-4b04-9589-3ae01e784757.jpeg)
