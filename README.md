# 제목(Header)

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 문장(Paragraph)

동해물과 백두산이 마르고 닭도록 <br>
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닭도록  ( 띄어쓰기 2번 )
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
    1. 순서가 필요한 목록 
    1. 순서가 필요한 목록 
1. 순서가 필요한 목록

- 순서가 필요없는 목록
- 순서가 필요없는 목록
- 순서가 필요없는 목록    
    - 순서가 필요없는 목록    
    - 순서가 필요없는 목록    
- 순서가 필요없는 목록

# 링크(Links)

<a href="https://google.com">Google</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

# 이미지 (Images)
_![이미지 이름 ](이미지 경로 )_
![HERROPY](https://heropy.blog/css/images/logo.png)

### 이미지 클릭시 링크 이동 
_[![이미지이름](이미지링크)](해당 경로)_

[![HERROPY](https://heropy.blog/css/images/logo.png)](https://cafe.naver.com/cstudycafe/162?boardType=L)

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접적으로 따온 문장.

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>>> 중중중첩된 인용문2

# 인라인(inline) 코드 강조 

CSS에서 `background`혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다. 

# 블록(block) 코드 강조 

```html
<a href="hhtps://naver.com">NAVER</a>
```

```css
.list > li {
  position:absolute;
  top:40px
}
```

```javascript
function func() {
  let a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성 

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 <span style="text-decoration: underline">보우하사</span> 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

# 수평선(Horizontal Rule )