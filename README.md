# LAB3
시스템프로그래밍 LAB3

## 개요
- 리눅스 파일 처리, 프로세스 및 프로세스간 통신 기법에 대한 기본 개념 확립, 프로그래밍 설계 능력 함양을 위한 프로젝트

## 요구사항
1. 자신의 github 저장소에 lab3 프로젝트를 생성하고 아래의 모든 과제 프로그램을 업로드한다.
2. 파일 및 디렉토리와 관련된 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
3. 주어진 디렉토리 내에 존재하는 파일과 디렉토리를 나열하고, 디렉토리의 경우 재귀적으로 방문해서 그 디렉토리 내에 존재하는 파일과 디렉토리를 나열하는
프로그램을 작성하시오. 즉, “ls –R” 명령과 동일한 결과를 보이도록 하시오.
4. 몇 개의 문장을 타자하도록 하여 잘못 타이핑한 횟수와 평균 분당 타자수를 측정하는 타자 연습 프로그램을 구현하여 보시오.
5. 프로세스와 관련된 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
6. system 함수는 쉘 명령이 실행되도록 하는데, 예를 들면, system("ls -la") 을 호출하면, 현재 디렉토리의 파일들을 나열해 준다. 이와 같은 기능을 수행하는 함수를 직접 구현하여 보자. 또, 이 함수를 이용하는 예제 프로그램을 통해서 “a.out ls -la" 와 같이 명령이 잘 동작하도록 해 보자.
7. 시그널과 관련된 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
8. 프로세스 간 통신 함수들을 사용하여 프로그램을 작성하고 실행하여 보고, 익숙해지도록 사용해 본다.
9. 메시지 큐를 사용하여 텍스트 기반의 간단한 채팅 프로그램을 구현하시오.
10. 공유 메모리를 사용하여 한 파일의 자료를 다른 파일로 복사하는 프로그램을 작성하시오. 단, 부모(읽는 프로세스) 와 자식(쓰는 프로세스) 프로세스를 생성하되, 공유 메모리 영역을 동시에 접근하는 일이 없도록 세마포어와 같은 동기화 기법을 활용하시오.

### 작성자
- Sangwoo LEE(sangwoo239@naver.com)
  - [Go to Author's Github Page](https://github.com/eple0117)
