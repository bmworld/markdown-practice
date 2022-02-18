# MARKDOWN 문법 모음
#####  <b style="color:orange;">**VS CODE에서 미리보기 아이콘을 누르면, 아래 마크다운이, HTML문법으로 변환되어서 나타나는 것을 볼 수 있다. (책모양에, 돋보기가 들어있는) </b>

<br/><br/>

# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6



# 문장 (Paragraph)

동해물과 백둗산이 마르고 닳도록
하나님이 보우하사 우리나라 만세


# 줄바꿈 (Line Breaks)

동해물과 백둗산이 마르고 닳도록  (띄어쓰기가 2번 = 줄바꿈)  
하나님이 보우하사 우리나라 만세
무궁화 삼천리 화려 강산 <br>
대한사람 대한으로 길이 보전하세


# 강조 (Empasis)
_이텔릭_  
**두껍게**  <br>
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>


# 목록(List)

1. 순서가 필요한 목록: 숫자+마침표+띄어쓰기할 경우, 자동으로 순서에 맞게 번호를 붙여줌  
1. 순서가 필요한 목록
    1. 들여쓰기를 2번해주면, 한 단계 더 들여쓰기 된다
1. 순서가 필요한 목록  
    1. 들여쓰기를 2번해주면, 한 단계 더 들여쓰기 된다
        1. 들여쓰기를 2번하고, 그 뒤에 3번을 해주면, 추가로 한 단계 더 들여쓰기



- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크(Links)

<a href="https://google.com">GOOGLE</a>  
[GOOGLE!!](https://google.com)


<a href="https://naver.com">NAVER</a>  
[NAVER:마우스를 올려보세요](https://naver.com "마우스 올렸을 때 나타나는 텍스트")


<a href="https://daum.net" target="_blank">DAUM</a>  
[DAUM: 새창으로 열기위해 순수 HTML attribute를 사용](https://daum.net "마우스 올렸을 때 나타나는 텍스트")


# 이미지 첨부(Image)
![Image첨부: 느낌표를 앞에다가 붙이면 이미지가 바로 출력된다.](https://www.google.com/images/branding/googlelogo/2x/googlelogo_light_color_272x92dp.png "마우스를 올리면 나타남. 구글 로고입니다이")



<br><br>


# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>>> 중중첩된 인용문 2
>>>>> 중중첩된 인용문 3


<br><br>

# 인라인(Inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.  
<br>
해당 언어에 맞게 코드를 강조해준다.
<br>

# 블록(Block)) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```


```css
.list > li {
    position:abslute;
    top:50px;
    z-index:1
}
```


```javscript
function JS_func(){
    const a = 'english';
    return a;
}
```


```bash
$git commit -m "220219 Study Markdown"

```


```plaintext
plain text는 강조할게 없으니까, 전부 흰색 글자로 표현된다. <strong>전혀 코드강조가 안되는 것을 보시라.</strong>
```


<br><br>


# 표(Table)
 
Position 속성
행의 개수와 --|--|--| 이 구분선을 일치시켜주면 정상작동하는 것이다.  
- 중앙 정렬: 콜론을 양쪽 삽입  
- 좌측 정렬: 콜론을 왼쪽 삽입  
- 우측 정렬: 콜론을 오른쪽 삽입

값 | 의미 | 기본값 | 비고
--|:--:|:--:|--:|
static | 기준 없음 | O | -
relative | 요소 자신 | X | -
absolute | 위치 상 부모에 해당한다 | X | -
fixed | view port | X | -


<br><br>

# 원시 HTML (Raw HTML)
동해물과 <u style="position:absolute; left:30px; top:-20px; color:red; font-weight:700 ">백두산</u>이 마르고 닳도록   <br/>
하나님이 보우하사 우리나라 만세


<br><br>

# 수평선(Horizontal Rule)

---
하이픈 3개
***
별표 3개
___
언더바 3개