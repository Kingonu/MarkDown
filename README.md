# 마크다운(MarkDown) 문법

- 목차
- [제목(Header)](#제목(Header))
- 강조(Emphasis)
- 목록(List)
- 링크(Links)
- 각주(Footnotes)
- 접기
- 이스케이프(Backslash Escapes)
- 이미지(Images)
- 코드(Code) 강조
- 표(Table)
- 인용문(BlockQuote)
- 수평선(Horizontal Rule)
- 줄바꿈(Line Breaks)

-------------------------------------------------------------------
## 제목(Header)
h1 부터 h6 까지 제목을 표현할 수 있다.

```css
# 제목 1 
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```

# 제목 1 
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

-------------------------------------------------------------------
    
## 강조(Emphasis)

```css
이테릭체: _언더바(underscore)_ or *별표(asterisks)*
두껍게: __언더바(underscore)__ or **별표(asterisks)**
취소선: ~물결(tilde)~
```
    
이테릭체: _언더바(underscore)_ or *별표(asterisks)*  
두껍게: __언더바(underscore)__ or **별표(asterisks)**  
취소선: ~물결(tilde)~  

-------------------------------------------------------------------

## 목록(List)

```css
1. 순서가 필요한 목록
2. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브) 
3. 순서가 필요한 목록
    1. 순서가 필요한 목록(서브)
    1. 순서가 필요한 목록(서브)
4. 순서가 필요한 목록
 
- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
```
    
1. 순서가 필요한 목록
2. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브) 
3. 순서가 필요한 목록
    1. 순서가 필요한 목록(서브)
    1. 순서가 필요한 목록(서브)
4. 순서가 필요한 목록
 
- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
    
-------------------------------------------------------------------
    
## 링크(Links)
    
```css
[GOOGLE](https://google.com)
[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")
[상대적 참조](../users/login)
[Dribbble][Dribbble link]
[GitHub][1]
 
문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.
 
다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.
구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>
 
[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"
```

[GOOGLE](https://google.com)  
[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")  
[상대적 참조](../users/login)  
[Dribbble][Dribbble link]  
[GitHub][1]  
 
문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.  
 
다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.  
구글 홈페이지: https://google.com  
네이버 홈페이지: <https://naver.com>  
 
[Dribbble link]: https://dribbble.com  
[1]: https://github.com  
[참조 링크]: https://naver.com "네이버로 이동합니다!"  
    
```css
목차
[1.개발을 하고 싶어요](#개발을-하고-싶어요)
[2.코딩을 잘하고 싶어요](#coding을-잘하고-싶어요)
 
## 개발을 하고 싶어요
## Coding을 잘하고 싶어요
```    

목차  
[1.개발을 하고 싶어요](#개발을-하고-싶어요)  
[2.코딩을 잘하고 싶어요](#coding을-잘하고-싶어요)  
 
## 개발을 하고 싶어요  
## Coding을 잘하고 싶어요  

주의할 점  

띄어쓰기는 - 로 연결해준다.  
영어는 모두 소문자로 작성한다.  
()괄호는 없이 작성한다.  
이모지를 사용할 경우 :: 없이 작성한다.  

-------------------------------------------------------------------
    
## 각주(Footnotes)  
    
Github에서는 footnote를 지원해주지 않음😭  
Tistory 올릴 때 참고  

```css
각주입니다[^id]
[^id]: 각주에 대한 설명.
```

접기
```css
<details><summary>CLICK ME</summary>
안녕-난-영준이야
</details>
```
<details><summary>CLICK ME</summary>
안녕-난-영준이야
</details>
    
이스케이프(Backslash Escapes)  
마크다운으로 글을 작성하다 보면 * 문자나 _ 문자 등을 사용하고 싶은 경우가 있다. 그럴 때는 \ 문자로 회피할 수 있다.  

```css
강조는 \* 문자 혹은 \_ 문자를 사용한다.
```

강조는 \* 문자 혹은 \_ 문자를 사용한다.  
    
-------------------------------------------------------------------

이미지(Images)
```css
![Alt text](파일경로)
![Alt text](파일경로 "title")
```
    
이미지에 링크  
마크다운 이미지 코드를 링크 코드로 묶어 준다.  
```css
[![Vue](kubernetes/img/til.JPG)](https://github.com/jun108059/til)
```
    
이미지 크기 조정  
    
Github에서 이미지 크기 조절 markdown 문법으로 작용하지 않는다.  
html 문법의 <img>영역을 직접 텍스트로 입력해서 변환하는게 좋다.  

(1) 직접 사이즈를 지정하는 방법  
```css
<img src="kubernetes/img/til.JPG" width="150" height="50">
 ```

(2) 비율로 지정하는 방법(%)  
```css
<img src="kubernetes/img/til.JPG" width="30%" height="30%">
```

-------------------------------------------------------------------
    
## 코드(Code) 강조
인라인(inline) 코드 강조  
```css
`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
```

`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.  


블록(block) 코드 강조  
`를 3번 이상 입력하고 코드 종류도 적는다.  

꿀팁  
내부에 `을 사용하고 싶으면 ~~~과 혼용하여 사용하면 좋다  

```Language
code
```
    
html
```css
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```
    
css
```css
.list > li {
  position: absolute;
  top: 40px;
}
```
    
javascript
```css
function func() {
  var a = 'AAA';
  return a;
}
```
    
-------------------------------------------------------------------
    
## 표(Table)  
    
헤더 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요  
헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있다.  
가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능  
    
```css
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |
```
    
값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |
    
값	의미	기본값
static	유형(기준) 없음 / 배치 불가능	static
relative	요소 자신을 기준으로 배치	 
absolute	위치 상 부모(조상)요소를 기준으로 배치	 
fixed	브라우저 창을 기준으로 배치	 
    
-------------------------------------------------------------------
    
## 인용문(BlockQuote)
    
```css
인용문(blockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_
 
BREAK!
> 인용문을 작성하세요!
> 
> > 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
> > 
> > > 중중첩된 인용문 1  
> > > 중중첩된 인용문 2  
> > > 중중첩된 인용문 3
```
    
인용문(blockQuote)
    
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!
    
> 인용문을 작성하세요!
> 
> > 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
> > 
> > > 중중첩된 인용문 1  
> > > 중중첩된 인용문 2  
> > > 중중첩된 인용문 3
    
-------------------------------------------------------------------
    
## 수평선(Horizontal Rule)
    
각 기호를 3개 이상 입력하세요.
    
```css
---
(Hyphens)
 
***
(Asterisks)
 
___
(Underscores)
```
---
(Hyphens)
 
***
(Asterisks)
 
___
(Underscores)

-------------------------------------------------------------------
    
## 줄바꿈(Line Breaks)
    
```css
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세   <!--띄어쓰기 2번-->
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세
```
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세   <!--띄어쓰기 2번-->  
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세

출처 : https://dev-youngjun.tistory.com/51#%EB%A7%81%ED%81%AClinks
Github - 마크다운(MarkDown) 문법 정리
