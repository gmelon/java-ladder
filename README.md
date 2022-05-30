# 사다리 게임
## 진행 방법
* 사다리 게임 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/nextstep-step/nextstep-docs/tree/master/codereview)

## 기능 요구사항
- 플레이어 이름을 입력받는다.
  - 이름은 비어있을 수 없다.
  - 이름은 최대 5글자를 넘을 수 없다.
- 사다리 높이를 입력받는다.
  - 사다리 높이는 최소한 1칸 이상이어야 한다.
- 사다리 높이만큼 사다리가 만들어진다.
- 사다리 선을 만든다.
  - 연속되지 않은 경우에만 선을 만들 수 있다.
    (사다리 선은 연속해서 만들어질 수 없다.)

## 실행 예시
```text
참여할 사람 이름을 입력하세요. (이름은 쉼표(,)로 구분하세요)
pobi,honux,crong,jk,solar
최대 사다리 높이는 몇 개인가요?
10
pobi  honux crong jk    solar 
|-----|     |-----|     |
|     |-----|     |-----|
|-----|     |-----|     |
|-----|     |-----|     |
|-----|     |     |-----|
|-----|     |-----|     |
|     |-----|     |     |
|-----|     |-----|     |
|     |-----|     |-----|
|-----|     |     |     |
```
