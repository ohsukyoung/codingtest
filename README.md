# ✍️<ReadMe.md 작성하기>

- ReadMe 작성: MarkDown(마크다운) 문법으로 작성
- MarkDown: <br>
  ㄴ 장점) 사용이 쉽고 마크업 언어인 HTML태그에 비해 간단해 문서 작성이편리 <br>
  ㄴ 단점) 마크다운을 지원하는 프로그램 or 사이트에서만 사용 가능 <br>
          (ex. 깃허브, 디스코드, 벨로그, 티스토리 등)

<br><br>
*******
<br><br>

## 1. 헤더(header)
: `<h1>` ~ `<h2>` 까지 제목으로 표현가능
- 텍스트 앞에 `#` 붙임

※ `#`과 텍스트 사이 한칸 띄움
- `#`이 갯수가 클수록 레벨이 낮아짐
- `#`은 1~6까지
- h1: ===, h2: --- 가능

<br><br>

### 1.1. 방법 ①
#### 1.1.1. Edit
```html
# `#`이용 제목1
## `#`이용 제목2
### `#`이용 제목3
#### `#`이용 제목4
##### `#`이용 제목6
```

<br><br>

#### 1.1.1. Preview
# `#`이용 제목1
## `#`이용 제목2
### `#`이용 제목3
#### `#`이용 제목4
##### `#`이용 제목6

<br><br>

### 1.1. 방법 ②
#### 1.1.1. Edit
```html
`#`이용 제목1
===
`#`이용 제목2
---
```

<br><br>

#### 1.1.1. Preview
`#`이용 제목1
===
`#`이용 제목2
==

<br><br>
*******
<br><br>

## 2. 수평선(Horizontal Rules)
- `-` or `*` or `_`을 3개 이상 작성
※ `-`을 사용할 경우 header로 인식할 수 있으므로, 이 전 라인 비워둬야함

<br><br>

### 2.1. Edit
```html
*******
* * * (Hyphens)
*******
---
- - - (Asterisks)
---
___
_ _ _ (unerscores)
___
```

<br><br>

### 2.2. Preview
* * *
*******
---
- - -
---
___
_ _ _
___

<br><br>
*******
<br><br>

## 3. 줄바꿈(Line Breaks)
- `띄어쓰기 두번` or `<br>` 활용해 줄바꿈
- 엔터로 칸 띄우면 다음행 넘어감. `<br>` 하나의 문장에서 줄바꿈

<br><br>
 
### 3.1. Edit
```html
오늘 하루도 화이팅
입니다 <br>
아자아자
화이팅!
```

<br><br>

### 3.2. Preview
오늘 하루도 화이팅
입니다 <br>
아자아자
화이팅!

<br><br>
*******
<br><br>

## 4. 강조(Emphasis)
: `<em>`,`<strong>`,`<del>` 태그로 변환 / `<u>` 밑줄 입력
- 기울여쓰기(italic): `*` 또는 `_`(언더바) 로 감싼 텍스트
- 두껍게 쓰기(bold): `**` 또는 `__` 로 감싼 텍스트
- 취소선: `~~` 로 감싼 텍스트
※ 기울여쓰기 & 두껍게 쓰기 같이 사용 가능
 
### 4.1. Edit
```html
*hello*
_How was your day?_
**hi**
__Good to see you__
~~happy day~~
****Have a great day!***
```

<br><br>

### 4.2. Preview
*hello*<br>
_How was your day?_<br>
**hi**<br>
__Good to see you__<br>
~~happy day~~<br>
****Have a great day!***

<br><br>
*******
<br><br>

## 5. 인용(Blockquote)
- `>` 로 시작하는 텍스트
- `>`~`>>>`: 3개까지 가능
※ 인용구 안에 제목, 리트스, 텍스트박스 가능

<br><br>
  
### 5.1. Edit
```html
> 오늘 하루도 화이팅
>> 입니다
>>> 아자아자 화이팅!
```

<br><br>

### 5.2. Preview
> 오늘 하루도 화이팅
>> 입니다
>>> 아자아자 화이팅!

<br><br>
*******
<br><br>

## 6. 목록(List)
### 6.1. 순서가 있는 목록(순서O 목록)
: `<ol>` 목록 태그로 변환
- 순서O 목록: 1, 2, 3...
- 들여쓰기에 따라 모양 바뀜
※ 어떤 숫자를 쓰는지- 의미X, 순서대로 알아서 숫자 매겨짐

<br><br>
 
#### 6.1.1. Edit
```html
1. 순서O 목록
1. 순서O 목록
  - 순서X 목록
  - 순서X 목록
1. 순서O 목록
  1. 순서O 목록
  2. 순서O 목록
```

<br><br>

#### 6.1.2. Preview
1. 순서O 목록
1. 순서O 목록
  - 순서X 목록
  - 순서X 목록
1. 순서O 목록
  1. 순서O 목록
  2. 순서O 목록

<br><br>

### 6.2. 순서가 없는 목록(순서X 목록)
: `<ul>` 목록 태그로 변환
- 순서X 목록: `*`, `+`, `-` 이용 순서 없는 목록
- 들여쓰기에 따라 모양 바뀜

<br><br>
 
#### 6.2.1. Edit
```html
* MBTI
  * I유형
    * ISTP
    * INTP
  * E유형
    * ESTP

+ MBTI
  + I유형
    + ISTP
    + INTP
  + E유형
    + ESTP

- MBTI
  - I유형
    - ISTP
    - INTP
  - E유형
    - ESTP
```

<br><br>

#### 6.2.2. Preview
* MBTI
  * I유형
    * ISTP
    * INTP
  * E유형
    * ESTP

+ MBTI
  + I유형
    + ISTP
    + INTP
  + E유형
    + ESTP

- MBTI
  - I유형
    - ISTP
    - INTP
  - E유형
    - ESTP

<br><br>
*******
<br><br>

## 7. 링크(Links)
: `<a>`로 변환
- 문서 안에서 `[참조 링크]`를 그대로 사용 가능
- 무서 내 일반 URL이나 꺽쇠 괄호( `<`,`>`) 안의 URL은 자동으로 링크 사용

<br><br>

### 7.1. 외부링크
### 7.1.1. Edit
```html
[Google](http://www.goole.com)
[Google](http://www.goole.com "링크대체텍스트")
[상대적 참조](../user/login)
[Google][Naver link]
Google <http://www.goole.com "링크대체텍스트">

[Naver link]: http://www.naver.com
```

<br><br>

### 7.1.2. Preview
[Google](http://www.goole.com)<br>
[Google](http://www.goole.com "링크대체텍스트")<br>
[상대적 참조](../user/login)<br>
[Google][Naver link]<br>
Google <http://www.goole.com "링크대체텍스트"><br>

[Naver link]: http://www.naver.com<br>

<br><br>

### 7.1. 내부링크
- [보여지는 내용](#이동할 헤드(제목))
- 괄호 링크 쓸 때 띄어쓰기 `-`로 연결
- 영어는 모두 소문자로 작성
### 7.1.1. Edit
```html
[1. Headers 헤더](#1-headers-헤더)
```

<br><br>

### 7.1.2. Preview
[1. Headers 헤더](#1-headers-헤더)

<br><br>
*******
<br><br>

## 8. 코드강조
: `<pre>`, `<code>`로 변환됨
- 숫자 1번키 왼쪽 `` ` ``(Grave) 사용

<br><br>

### 8.1. 인라인(inline) 코드 강조
#### 8.1.1. Edit
```html
`인라인코드강조` 구문입니다.
'' ' '' Grave를 인라인 강조할 때
```

<br><br>

### 8.1.2. Preview
`인라인코드강조` 구문입니다.
'' ' '' Grave를 인라인 강조할 때

### 8.1.2. 블록(block) 코드 강조
- `` ` ``를 3번 이상 입력하고 코드 종류 작성
- 코드여러 줄 일 경우, 줄 앞에 공백 네칸추가

<br><br>
 
#### 8.2.1. Edit
```java
public class Test
{
	public static void main(String[] args)
	{
    System.out.print("Hello World!");
  }
}
```

<br><br>

### 8.2.2. Preview
public class Test
{
	public static void main(String[] args)
	{
    System.out.print("Hello World!");
  }
}

<br><br>
*******
<br><br>

## 9. 테이블
: `<table>` 로 변환
- 헤더 셀 구분시 3개 이상 `-`(hyphen/dash) 기호 필요
- 헤더 셀 구분하면서 `:`(Colons) 기호로 셀(열/칸) 안에 정렬 가능
- 가장 좌측과 가장 우측에 있는 `|`(vertical bar) 기호는 생략 가능
- 좌측졍렬 `:---`, 가운데정렬 `:---:`, 우측졍렬 `---:`

<br><br>

### 9.1. Edit
```html
| 제목1 | 제목2 | 제목3 |
| --- | --- | --- |
| 열1 | 열2 | 열3 |
| 열4 | 열5 | 열6 |

| 제목1 | 제목2 | 제목3 |
| :--- | :---: | ---: |
| 열1 | 열2 | 열3 |
| 열4 | 열5 | 열6 |
```

<br><br>

### 9.2. Preview
| 제목1 | 제목2 | 제목3 |
| --- | --- | --- |
| 열1 | 열2 | 열3 |
| 열4 | 열5 | 열6 |

<br><br>
*******
<br><br>

## 10. 이미지(Images)
: `<img>` 로 변환됨
- 인라인 이미지 `![ alt text](/imgname.png)`
- 링크 이미지 `![alt text](imagename_URL)`
※ 링크와 비슷하지만, 앞에 `!`가 붙음
※ 이미지 사이즈 변경시 `<img width="가로값px" height="높이값px"></img>`와 같이 표현

<br><br>

### 10.1. Edit
```html
![텍스트](이미지파일경로.jpg)
![텍스트](이미지파일경로.jpg, "이미지 대체텍스트")
![텍스트](이미지파일URL)
![텍스트](이미지파일URL, "이미지 대체텍스트")

![화이팅](https://mblogthumb-phinf.pstatic.net/MjAxODExMjBfMjYz/MDAxNTQyNzEzNTIwMTg1.1aqhgkoEKUy_EX7SGgLU9BqMrq43tJe5kEmpWABMfHYg.oOa6NRYBH6hX1XSfyomwqeQgsut8G0hZo6XC8taFbEwg.JPEG.yellowouk2/195a4f324494ad4db1a0209a41ff8b79.jpg?type=w800)<br>

<img src="https://mblogthumb-phinf.pstatic.net/MjAxODExMjBfMjYz/MDAxNTQyNzEzNTIwMTg1.1aqhgkoEKUy_EX7SGgLU9BqMrq43tJe5kEmpWABMfHYg.oOa6NRYBH6hX1XSfyomwqeQgsut8G0hZo6XC8taFbEwg.JPEG.yellowouk2/195a4f324494ad4db1a0209a41ff8b79.jpg?type=w800" width="200px" alt="sample image">
```

<br><br>

### 10.2. Preview
![화이팅](https://mblogthumb-phinf.pstatic.net/MjAxODExMjBfMjYz/MDAxNTQyNzEzNTIwMTg1.1aqhgkoEKUy_EX7SGgLU9BqMrq43tJe5kEmpWABMfHYg.oOa6NRYBH6hX1XSfyomwqeQgsut8G0hZo6XC8taFbEwg.JPEG.yellowouk2/195a4f324494ad4db1a0209a41ff8b79.jpg?type=w800)<br>

<img src="https://mblogthumb-phinf.pstatic.net/MjAxODExMjBfMjYz/MDAxNTQyNzEzNTIwMTg1.1aqhgkoEKUy_EX7SGgLU9BqMrq43tJe5kEmpWABMfHYg.oOa6NRYBH6hX1XSfyomwqeQgsut8G0hZo6XC8taFbEwg.JPEG.yellowouk2/195a4f324494ad4db1a0209a41ff8b79.jpg?type=w800" width="200px" alt="sample image">

<br><br>
*******
<br><br>

## 11. 체크박스
- 줄 앞에 `- [ ]` 사용시 미완료 리스트
- 줄 앞에 `- [x]` 사용시 완료 리스트
- 체크 안에서 여러 기능 사용가능

<br><br>

### 11.1. Edit
```html
- [ ] 사용시 미완료 리스트
- [x] 사용시 완료 리스트
```

<br><br>

### 10.2. Preview
- [ ] 사용시 미완료 리스트
- [x] 사용시 완료 리스트

## 12. 기타
### 12.1. 작성참조 링크
- [마크다운 문법 정리](https://inpa.tistory.com/entry/MarkDown-%F0%9F%93%9A-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%AC%B8%EB%B2%95-%F0%9F%92%AF-%EC%A0%95%EB%A6%AC)
- [MarkDown 사용법 총정리](https://heropy.blog/2017/09/30/markdown/)
