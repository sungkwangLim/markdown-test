# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)
당신에게 여전히 난 기적이로군요 내겐 아득히 지난날들 그댄 기억하는 걸 보니 당신에게 여전히 난 소중한가 봐요

# 줄바꿈(Line Breaks)
당신에게 여전히 난 기적이로군요  
내겐 아득히 지난날들 그댄 기억하는 걸  
보니 당신에게 여전히<br/> 난 소중한가 봐요

# 강조(Emphasis)
_이텔릭_  
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록          
    1. 순서가 필요한 목록
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

[Naver](https://naver.com "Naver로 이동!")

타겟은 a태그를 이용해야 적용가능  
<a href="https://google.com" target="_blank">Google</a>

# 이미지(Image)
이미지 연결은 링크연결과 비슷하지만 !로를 붙이면된다 

![연습한 사이트](https://tourmaline-kulfi-84ddcb.netlify.app/images/starbucks_logo.png)

[![연습한 사이트](https://tourmaline-kulfi-84ddcb.netlify.app/images/starbucks_logo.png)](https://tourmaline-kulfi-84ddcb.netlify.app "연습한 사이트로 이동")

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1  
>>> 중중첩된 인용문2  
>>> 중중첩된 인용문3 

# 인라인(inline) 코드 강조
Css에서 `background` 혹은  
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(Block) 코드 강조
```html
<a href="https://google.com">Google</a>
```

```css
.main {
    background: #000;
    position: relative;
}
```

```javascript
function func() {
    const a = 'aaa';
    return a;
}
```

```bash
$ git commit -m 'Study Markdonw'
```

```plaintext
당신에게 여전히 난 기적이로군요
내겐 아득히 지난날들 그댄 기억하는 걸 보니
당신에게 여전히 난 소중한가 봐요
여기는 엔터만 쳐도 줄바꿈이 가능합니다.
```

# 표(Table)
position 속성  
값 | 의미 | 기본값  
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absoulte | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

복잡한구조 표는 markdown으로 만들수 없다.

# 원시 HTML(Raw HTML)
당신에게 여전히 <span style="text-decoration: underline;">난 기적이로군요</span><br/>
내겐 아득히 지난날들 그댄 기억하는 걸 보니<br/>
당신에게 여전히 난 소중한가 봐요

---

<a href="https://google.com" target="_blank">Google</a>  

---

<img width="30" src="https://tourmaline-kulfi-84ddcb.netlify.app/images/starbucks_logo.png" alt="테스트" />


# 수평선(Horizontal Rule)

---

***
___
