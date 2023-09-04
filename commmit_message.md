# 🔖커밋 메세지

## 1. 커밋 메시지?
  - 커밋(commit)은 로컬 저장소에 쓰여지는 로컬 파일들의 단편본
  - git은 파일의 변경된 내용만 기록하지 않고 모든 파일의 버전을 모두 기록함
  - 커밋과 커밋하이에 변경된 내용이 없다면, git은 동일한 파일에 대해 링크만 생성

## 2. 커밋메세지가 중요한 이유
  - 코드 리뷰시간 단축 → `능률적 처리`
  - `변경 사항 이해`에 도움
  - 코드만으로 설명이 어려운 `"왜 이렇게 했을까"`를 설명
  - 추후 작업할 사람이 `왜/어떻게 변경 사항이 만들어졌는지 이해`하는데 도움
  - `문제 해결`과 `디버깅 쉽게`만듦

## 3. 커밋 메세지 구조
- `Header`, `Body`, `Footer`는 빈행으로 구분
```
타입(Type) (<scope>): 제목(Subject)  //헤더

본문(Body)                 //바디

바닥글(Footer)             //푸터

```

### 3.1. Header
#### 3.1.1. Type
- 필수

| 타입 이름 | 내용 |
| --- | ---|
| Feat | 새로운 기능에 대한 커밋 |
| Fix | 버그 수정 |
| Build | 빌드 관련 파일 수정 |
| Ci | Ci 문서(문서 추가, 수정, 삭제) |
| Docs | 문서 수정 |
| Style | 스타일(코드 형식, 세미콜론 추가 등), 기능수정 없는 경우 |
| Design | 사용자 UI 디자인 변경(CSS 등)
| Refactor | 코드 리펙토링 |
| Test | 테스트(테스트 코드 추가, 수정, 삭제), 기능수정 없는 경우 |
| Perf | 성능 개선 |
| Chore | 기타 변경사항(빌드 스크립트 수정 등) |
| Rename | 파일 혹은 폴더명 수정 |
| Remove | 파일 삭제만 한 경우 |

#### 3.1.2. scope
- 선택 사항으로 모든 커밋에 작성X
- ex) 함수 변경시 `함수명`, 메소드추가시 `클래스명` 기입 등

#### 3.1.3. Subject
- 커밋 메세지 제목
1. 제목과 본문은 `빈 행으로 구분`
2. 제목은 `50글자` 이내로 제한
3. 제목의 `첫 글자는 대문자로 작성`
4. 제목 끝에 `마침표 넣지 않기`
5. 제목은 `명령문`으로 사용 O, `과거형 사용 X`

#### 3.2. Body
- 커밋 메세지 본문
- 선택 사항으로 모든 커밋에 작성X
1. 제목과 본문은 `빈 행으로 구분`
2. 본문의 `각 행은 72글자 내`로 제한
3. 어떻게 보다는 `무엇 & 왜`를 설명

#### 3.3. Footer
- 커밋 메세지 맺음말
- 선택 사항으로 모든 커밋에 작성X
- 이슈 추적을 위한 ID추가할 때 사용
  + `해결` - 해결 이슈 ID
  + `관련` - 해당 커밋에 관련된 이슈 ID
  + `참고` - 참고할만한 이슈 ID

| 사용 시점 | 사용 키워드 |
| --- | --- |
| 해결 | `Closes(종료)`, `Fixes(수정)`, `Resolves(해결)` |
| 참고 | `Ref(참고)`, `Related to(관련)`, `See also(참고)` |


## 4. 커밋 메세지 예시
```
Feat: 관심지역 알림 ON/OFF 기능 추가(#123)

시군구의 알림을 각각 ON/OFF 할 수 있도록 가능 추가함
- opnion0055: 구분 코드

해결: close #123
```

## 5. 기타
### 5.1. 작성참조 링크
- [커밋 메시지 가이드](https://github.com/RomuloOliveira/commit-messages-guide/blob/master/README_ko-KR.md)
- [Github Commit Message Rules](https://junhyunny.github.io/information/github/git-commit-message-rule/)
- [[Git] 규칙적인 Commit 메세지로 개발팀 협업하기](https://xtring-dev.tistory.com/entry/Git-%EA%B7%9C%EC%B9%99%EC%A0%81%EC%9D%B8-Commit-%EB%A9%94%EC%84%B8%EC%A7%80%EB%A1%9C-%EA%B0%9C%EB%B0%9C%ED%8C%80-%ED%98%91%EC%97%85%ED%95%98%EA%B8%B0-%F0%9F%91%BE)
- [[Git] 좋은 commit message 작성법](https://jane-aeiou.tistory.com/93)
- [느낌 있는 Commit Message 작성하기](https://nohack.tistory.com/17)
