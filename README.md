# 제목(Header)

# 제목 1 <h1태그>

## 제목 2

### 제목 3 <h3태그>

# 문장 (Paragraph)

연습용이다 (그냥 치면 p태그랑 똑같다 )

# 줄바꿈(Line Breaks)

1번  
2번  
3번  
1.띄어쓰기 2번 + 엔터
2.br태그 </br쓰기>

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(list)

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

# 링크

<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)  
<a href="https://naver.com" title="NAVER로 이동">NAVER</a>  
[NAVER](https://naver.com 'NAVER로 이동!')

# 이미지 삽입

![HEROPY](https://heropy.blog/css/images/logo.png)

삽입한 이미지에 링크를 걸고 싶은경우  
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문

> 남의 말이나 글에서 직접 또는  
> 간접으로 따온 문장.
> (네이버 국어사전)

> 인용문을 작성
>
> > 중첩된인용문
> >
> > > 중첩 인용문1  
> > > 중첩 인용문2

# 인라인 코드 강조

css에서 `background` 혹은 `backgroung-image` 속성으로  
요소에 이미지를 삽입할 수 있습니다.

# 블록 코드 강조

```html
<a href="https://google.com">GOOGLE</a>
```

```bash
$ git commit -m 'Study'
```

```javascript
function func() {
  var a = 'aaa';
  return a;
}
```

```plaintext
그냥 입력 하는 텍스트
```

# 표 table

position 속성  
값 | 의미 | 기본값
--|:--:|--  
static | 기준 없음 | O  
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X

가운데 정렬시 :--:, 오른쪽 정렬시: --:

# 원시 HTML

<br/ 은 줄바꿈>  
<u>는 텍스트에 밑줄</u>  
a태그의 target 속성이 필요할 경우 원시 HTML 사용  
image 삽입 시 필요한 경우 사용

# 수평선

---

사용하면 '---' 수평선 생김, 보통 구분을 위해 사용
'\*\*\* , \_\_\_'도 사용가능

---

---
