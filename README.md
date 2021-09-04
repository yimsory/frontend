# frontend

## 참고링크

https://www.w3schools.com/

https://codesandbox.io/

## HTML

### Introduction

https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시

> 웹 페이지 콘텐츠 표시
>
> - 텍스트 콘텐츠
> - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오

### HTML Element

https://www.w3schools.com/html/html_elements.asp

`(backtick)

```
<tagname>Contents</tagname>

* 시작태그만 있는 경우 : Empty Element
```

> 포함관계(nested)

```
<html>
  <body>
    <h1>Heading</h1>
  </body>
</html>
```

> html-body-h1 관계
>
> html : body와 관계 - 부모요소 / h1과 관계 - 조상요소
>
> body : h1과 관계 - 부모요소 / html과 관계 - 자식요소
>
> h1 : body와 관계 - 자식요소 / html과 관계 - 자손요소

### HTML Attreibute

https://www.w3schools.com/html/html_attributes.asp

### Headings

https://www.w3schools.com/html/html_headings.asp

h1 ~ h6 : 제목태그(h -> heading)

### HTML Paragragh

https://www.w3schools.com/html/html_paragraphs.asp

### HTML Link

https://www.w3schools.com/html/html_links.asp

a : anchor

> URL(Uniform Resource Locator) : 파일식별자(위치표시), 가장 넓은 의미의 인터넷 주소
> 인터넷 주소
>
> - IP(Internet Protocol) : 숫자로 구성된 주소(192.168.0.1)
> - Domain Name : www.naver.com / DNS(Domain Name Server)
> - Ex) blog.naver.com/blog/12345 => URL

### HTML File 경로

https://www.w3schools.com/html/html_filepaths.asp

절대 vs 상대

- 경로 위치 표시 방식
- 경로 표시의 기준의 변경 여부
- 절대 경로 방식
- Ex) 대한민국 서울특별시 서초구 ~동 대호빌딩 803호
- -출발지 위치에 상관없이 항상 찾아갈 수 있도록 표시
- Ex) 도메인주소/상세경로=> httts://www.naver.com/blog/image.jpg
-
- 상대 경로 방식
- Ex) 강남역 12번출구에서 3분 대호빌딩
- 출발지 위치를 기준으로 표시
- Ex) 상세경로 => /blog/image.jpg || image.jpg

### HTML List

https://www.w3schools.com/html/html_lists.asp

> 중첩목록(Nested List)

### HTML Table

https://www.w3schools.com/html/html_tables.asp

table generator : https://www.tablesgenerator.com/

### HTML Images

https://www.w3schools.com/html/html_images.asp

alt : alternative

### HTML Video

https://www.w3schools.com/html/html5_video.asp

### HTML YouTube

https://www.w3schools.com/html/html_youtube.asp

### HTML Block & inline

https://www.w3schools.com/html/html_blocks.asp

> 영역의 특성
>
> - 블럭 요소 : 가로길이 - 부모요소에 채워짐 / 세로길이 - 자식요소에 맞춰짐
> - 인라인 요소 : 가로길이와 세로길이 모두 자식요소에 맞춰짐

> 포함관계
>
> - 블럭요소 : 다른 블록요소, 인라인 요소. 콘텐츠 포함 가능
> - 인라인 요소 : 다른 인라인 요소, 콘텐츠 포함 가능, 블록요소는 포함 불가능
> - 예외 : a - 인라인 요소이지만 블럭요소를 포함 가능

### HTML id & class

https://www.w3schools.com/html/html_id.asp

https://www.w3schools.com/html/html_classes.asp

> id attribute
>
> - id로 붙여주는 이름은 한 HTML 문서내에서 고유해야 함.(한번만 사용)
> - id는 한 대상의 HTML Element에 하나의 이름만 지정할 수 있음.

> Class attribute
>
> - class로 붙여주는 이름은 한 HTML 문서내에서 여러번 중복 사용할 수 있음.
> - class는 한 대상의 HTML Element에 여러개의 이름을 지정할 수 있음.

### CSS 상속

> 부모요소에 적용된 CSS 속성이 자식요소에 적용되는것

### CSS Text

https://www.w3schools.com/css/css_text.asp

> - color
> - text-align
> - text-decoration
> - letter-spacing
> - line-height

### CSS Font

https://www.w3schools.com/css/css_font.asp

> Web Font

> 웹에서 사용하는 폰트는 브라우저에서 랜더링되기 때문에 기존에는 사용자 PC에 설치되어 있는 폰트를 사용
>
> 사용자 pc에 설치된 폰트를 찾지 않고 서버에 폰트를 저장해서 사용하는 방식 => 웹폰트 방식
>
> 웹폰트 서비스
>
> - 구글 폰트(영문/한글) : https://fonts.google.com/
> - 눈누 폰트(한글) : https://noonnu.cc/

> font-family
>
> - 항상 폰트 목록끝에 기본 폰트 이름을 입력해야 함.
> - 고딕 : sans-serif / 명조 : serif
>
> font-size
>
> font-style:italic
>
> font-weight
>
> - 100,200,300 ... : 숫자로 표시

### Box Model

https://www.w3schools.com/css/css_boxmodel.asp

> - Content(width/height) : 콘텐츠의 너비 또는 높이
> - Padding : 안쪽 여백
> - Border : 테두리
> - Margin : 바깥 여백

### Height / Width

> - 클릭요소의 가로길이/세로길이 적용시
> - auto : 요소의 기본 특성을 따라감 / defaut 값 : 적용하지 않은 상태와 같음
> - px : px 값으로 고정
> - % : 부모요소를 기준으로 특정 비율만큼 설정
> - 인라인 요소에 가로길이/세로길이는 적용되지 않음

### Padding

> - padding-top / padding-right / padding-bottom / padding-left
> - padding : 10px 20px 30px 40px;
> - padding : 10px 20px 30px;
> - padding : 10px 20px;
> - padding : 10px;

### Margin

> - 마진 겹침 : 박스가 상하배치 되어있을 때 사이 마진이 한쪽만 적용되는 현상
>
> - 두 박스 모두 마진 적용하지 않고 한 쪽에만 마진을 적용

### Border

> - boder : 1px solid red;
>
> border-top / border-right / border-bottom / border-left

### Background

https://www.w3schools.com/css/css_background.asp

> background-color
>
> background-image:url()

### Color 표현방식

> - RGB : - 가산혼합
> - 스크린에서 color 표현
>
> - CMYK : cyan magenta yellow black - 감산혼합
> - 프린터에서 color 표현

> color 코드값
>
> - 10진수 표현 : rgb(255, 255, 255)
> - 16진수 표현 : #1a9cf0

### Box-sizing

> - box-sizing:border-box; => width/height가 박스의 전체 길이가 됨

### CSS Flex

> 박스 레이아웃 구성에 관련된 CSS 속성
>
> Flex 적용
>
> - display:flex;
>
> 부모요소에 적용하는 속성
>
> - flex-direction : flex 박스의 배치 방향
> - justify-content : 가로 방향 정렬
> - align-items : 세로 방향 정렬
>
> 자식요소에 적용하는 속성
>
> - flex:1;

### Respinsive Web(반응형 웹)

> 반응형 웹
>
> - OSMU(One Source Multiuse)
> - 한 HTML 페이지에서 다양한 CSS를 통해 PC, Smart phone 레이아웃 구성을 표현
>
> - Viewport
> - Media Query
>   - break point : 레이아웃이 변경되는 지점
>   - Ex)
>   - (320px ~ 640px:s.p)(640px ~ 1024px:t.b)(1025px ~ 1080px:p.c)
>   - (320px ~ 799:s.p)(800px ~ 1920px:p.c)

```
@medua screen and(max-width:1920px){
  - pc style css code -
}

@medua screen and(max-width:1024px){
  - tablet style css code -
}

@medua screen and(max-width:640px){
  - smartphone style css code -
}
```

> - 해상도
>
>   - smart phone : 320px ~ 640px
>   - tablet : 768px ~ 1024px
>   - pc : 1024px ~ 1920px
>
> - Fluid Layout(유동형 레이아웃)
> - % 단위를 활용해서 부모 요소의 크기가 변경될 때 자식 요소의 크기도 같이 부드럽게 변하도록 하는 레이아웃

### Combinator Selector(조합 선택자)

> 2개 이상의 선택자를 조합해서 사용하는 형태

```
* 여러개 선택자에 모두 동일한 css 적용
.name1,.name2

* 여러개 선택자를 동시에 가지고 있는 경우
.name1,name2 : Element가 class이름을 name1과 name2를 동시에 가지고 있는 경우
div.name1 : div Element가 name1 클래스 이름을 가지고 있는 경우
#name1,name2 : id이름이 name1 이면서 클래스 이름이 name2인 경우

* 자손 요소 선택
.name1 .name2 : 클래스 이름이 name1인 요소의 자손요소 중 클래스 이름이 .name2인 요소를 선택

* 자식 요소 선택
.name1>.name2 : 클래스 이름이 name1인 요소의 자식요소 중 클래스 이름이 .name2인 요소를 선택
```
