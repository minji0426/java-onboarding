# 미션 - 온보딩

## ✔구현 기능 목록
문제 1
-[ ] 왼쪽과 오른쪽 페이지 번호의 각 자리를 곱하거나 더한 값 중 큰 값을 구하고, 그 중 가장 큰 값 구하기
  - [ ] 점수 비교하기 : 포비가 이기면 1, 크롱이 이기면 2, 무승부면 0, 예외사항은 -1 
  - [ ] 예외사항 : 
    - [ ] 페이지 번호의 왼쪽이 홀수, 오른쪽이 짝수가 아닐 때 
    - [ ] 왼쪽과 오른쪽의 페이지 번호가 연속이 아닐 떼
    
문제 2
- [ ] 연속되는 문자가 포함된 문자열이 있을 때 연속되는 문자 삭제 -> 반복
  - [ ] 예외사항 :
    - [ ] 문자열이 모두 소문자가 아닐 때

문제 3
- [ ] 1부터 number까지 숫자 중에 3, 6, 9가 포함된 갯수 구하기
  - [ ] 예외사항 : 
    - [ ] number가 자연수가 아닐 때

문제 4
- [ ] 주어진 단어의 알파벳을 청개구리 사전대로 변환하기 
  - [ ] 예외사항 : 
    - [ ] 주어진 문자열이 1 이상 1,000 이하의 문자열이 아닐 때 

문제 5
- [ ] 매개변수 money를 50,000, 10,000, 5,000, 1,000, 500, 100, 50, 1 순서대로 나누어서 몫을 크기 9의 배열에 순서대로 넣기
  - [ ] 예외사항 :
    - [ ] money의 크기가 1 이상 1,000,000 이하인 자연수가 아닐 때

문제 6
- [ ] 같은 글자가 연속적으로(두 글자 이상) 포함되는 닉네임의 지원자 이메일 목록 생성하기 (오름차순, 중복제거)
  - [ ] 예외사항 :
    - [ ] 이메일의 도메인이 email.com이 아닐 때
    - [ ] 닉네임과 이메일의 길이가 11자 이상 20자 미만이 아닐 때
    - [ ] 닉네임에 한글이 아닌 다른 문자가 있을 때

문제 7
- [ ] firends에서 user와 친구를 찾기
- [ ] 찾은 친구의 친구를 찾아 10점 부여하기
- [ ] visitors 배열의 유저 당 갯수 구하여 점수 부여하기 
  - [ ] 예외사항 :
    - [ ] 사용자의 아이디가 소문자가 아닌 경우

---

## 🔍 진행 방식

- 미션은 **기능 요구 사항, 프로그래밍 요구 사항, 과제 진행 요구 사항** 세 가지로 구성되어 있다.
- 세 개의 요구 사항을 만족하기 위해 노력한다. 특히 기능을 구현하기 전에 기능 목록을 만들고, 기능 단위로 커밋 하는 방식으로 진행한다.
- 기능 요구 사항에 기재되지 않은 내용은 스스로 판단하여 구현한다.

## 📮 미션 제출 방법

- 미션 구현을 완료한 후 GitHub을 통해 제출해야 한다.
    - GitHub을 활용한 제출 방법은 [프리코스 과제 제출](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse) 문서를 참고해
      제출한다.
- GitHub에 미션을 제출한 후 [우아한테크코스 지원](https://apply.techcourse.co.kr) 사이트에 접속하여 프리코스 과제를 제출한다.
    - 자세한 방법은 [제출 가이드](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse#제출-가이드) 참고
    - **Pull Request만 보내고 지원 플랫폼에서 과제를 제출하지 않으면 최종 제출하지 않은 것으로 처리되니 주의한다.**

## 🚨 과제 제출 전 체크 리스트 - 0점 방지

- 기능 구현을 모두 정상적으로 했더라도 **요구 사항에 명시된 출력값 형식을 지키지 않을 경우 0점으로 처리**한다.
- 기능 구현을 완료한 뒤 아래 가이드에 따라 테스트를 실행했을 때 모든 테스트가 성공하는지 확인한다.
- **테스트가 실패할 경우 0점으로 처리**되므로, 반드시 확인 후 제출한다.

### 테스트 실행 가이드

- 터미널에서 `java -version`을 실행하여 Java 버전이 11인지 확인한다. 또는 Eclipse 또는 IntelliJ IDEA와 같은 IDE에서 Java 11로 실행되는지 확인한다.
- 터미널에서 Mac 또는 Linux 사용자의 경우 `./gradlew clean test` 명령을 실행하고,   
  Windows 사용자의 경우  `gradlew.bat clean test` 명령을 실행할 때 모든 테스트가 아래와 같이 통과하는지 확인한다.

```
BUILD SUCCESSFUL in 0s
```

---

## 🚀 기능 요구 사항
아래의 7가지 기능 요구 사항을 모두 해결해야 한다.

1. [문제 1](./docs/PROBLEM1.md)
2. [문제 2](./docs/PROBLEM2.md)
3. [문제 3](./docs/PROBLEM3.md)
4. [문제 4](./docs/PROBLEM4.md)
5. [문제 5](./docs/PROBLEM5.md)
6. [문제 6](./docs/PROBLEM6.md)
7. [문제 7](./docs/PROBLEM7.md)

---

## 🎯 프로그래밍 요구 사항

- JDK 11 버전에서 실행 가능해야 한다. **JDK 11에서 정상적으로 동작하지 않을 경우 0점 처리한다.**
- `build.gradle`을 변경할 수 없고, 외부 라이브러리를 사용하지 않는다.
- 프로그램 종료 시 `System.exit()`를 호출하지 않는다.
- 프로그램 구현이 완료되면 `ApplicationTest`의 모든 테스트가 성공해야 한다. **테스트가 실패할 경우 0점 처리한다.**
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 이름을 수정하거나 이동하지 않는다.

---

## ✏️ 과제 진행 요구 사항

- 미션은 [java-onboarding](https://github.com/woowacourse-precourse/java-onboarding) 저장소를 Fork & Clone해 시작한다.
- 과제 진행 및 제출 방법은 [프리코스 과제 제출](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse) 문서를 참고한다.
