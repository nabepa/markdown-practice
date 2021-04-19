# 제목(Header)


# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
기호와 텍스트 사이에 띄어쓰기가 있어야 제대로 인식하는 환경이 많음

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

띄어쓰기 두번으로도 줄바꿈 가능하나, 지원하지 않는 환경도 있음

# 강조(Emphasis)

_이텔릭_ <br/>
**볼드** <br/>
**_이텔릭 + 볼드_** <br/>
~~취소선(tilde)~~ <br/>
<u>밑줄</u> <br/>

# 목록(list)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 서브목록은 들여쓰기 2번
    1. 서브목록은 들여쓰기 2번
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
    - 서브목록은 들여쓰기 2번
    - 서브목록은 들여쓰기 2번
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Link)

<a href="https://google.com">GOOGLE</a> <br/>
[GOOGLE](https://google.com)

<a href="https://naver.com"
title="NAVER로 이동">NAVER</a> <br/>
[NAVER로 이동](https://naver.com "NAVER로 이동")

<a href="https://naver.com"
title="NAVER로 이동"
target="_blank">NAVER</a> <br/>

# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)
이미지에 링크 달기

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 도는 간접적으로 따온 문장. <br/>
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첨된 인용문
>>> 중첩된 인용문 1 <br/>
>>> 중첩된 인용문 2 <br/>
>>> 중첩된 인용문 3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 <br/>
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://google.com">GOOGLE</a> <br/>
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

| 값       |       의미       | 기본값 |
| -------- | :--------------: | -----: |
| static   |    기준 없음     |      O |
| relative |    요소 자신     |      X |
| absolute | 위치상 부모 요소 |      X |
| fixed    |      뷰포트      |      X |

위에 하이푼에 콜론 기호 조합해서 정렬하고 있음

# 원시 HTML(Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com"
title="NAVER로 이동"
target="_blank">NAVER</a> <br/>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

# 수평선(Horizontal Rule)

---

***

___