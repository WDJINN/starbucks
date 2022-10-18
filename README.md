# Starbucks

# 제목 1
## 제목 2
### 제목 3


# 문장(Paragraph)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세

# 강조(Emphasis)
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>


# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 서브 순서는 들여쓰기 2개
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크(Links)
<a href="https://google.com">Google</a>

[Google](https://google.com)


<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

마크다운에서는 target 속성 지원은안한다 -> 원시 HTML으로...

# 이미지(Images)
![대체텍스트](주소)  


![HEROPY](https://heropy.blog/css/images/logo.png)

이미지를 클릭하면 블로그로 이동되게하려면..
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)



# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따운 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3


# 인라인(inline) 코드 강조

CSS에서 `background`혹은 `background-image` 속성으로 욧에 배경 이미지를 삽입할 수 있습니다.

위처럼 백틱 기호를 통해 인라인코드를 강조할 수 있음.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr">Google</a>
```

# 표(Table)

position 속성

값 | 의미 | 기본값  
--|--|--  
static| 기준 없음 | O
relative | 요소 자신 | X
absolute|위치 상 부모 요소 | X
fixed | 뷰포트 | X

기본적으로 왼쪽 정렬이 되어있다.

의미 열을 가운데 정렬을 해본다.(:--:)
기본값은 오른쪽 정렬을 해본다.(--:)
값 | 의미 | 기본값  
--|:--:|--:  
static| 기준 없음 | O
relative | 요소 자신 | X
absolute|위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <u>백두산이</u> 마르고 닳도록<br/> 하느님이 보우하사 우리나라 만세

동해물과 <span style="text-decoration:underline;">백두산이</span> 마르고 닳도록<br/> 하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<img width="70" src ="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

# 수평선(Horizontal Rule

---
hyphen 3 times

***
asterisk 3 times
___

underbar 3 times