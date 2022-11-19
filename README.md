># HTML
>### 구조, 요소, 태그, 주석
---
## 구조
```angular2html
<!DOCTYPE html>
<html>

<head>
    <title>제목</title>
</head>

<body>
    <p>내용</p>
</body>

</html>
```
>``<!DOCTYPE html>`` : html5 문서 선언<br>
>``<html> ~ </html>`` : html5 문서 시작&종료<br>
>``<head> ~ </head>`` : 웹 페이지 상단 메뉴<br>
>``<body> ~ </body>`` : 웹 페이지 하단 본문
<hr>

## 요소
시작태그와 종료태그로 이루어진 모든 명령어
```angular2html
<태그 속성1="값" 속성2="값" ... 속성n="값"> 내용 </태그>
```
- 블록 요소 : 한 줄을 차지하는 요소
    ```
    요소1
    요소2
    요소3
    ...
    요소n
    ```
- 인라인 요소 : 줄을 차지하지 않는 요소
    ```
    요소1  요소2  요소3  ...  요소n
    ```
--- 
## 태그
- 블록 태그
    >div, p, h#, ul, ol, blockquote, form, hr, table


- 인라인 태그
    >span, img, br, sub, sup, input, textarea, label, button

---
## 주석
```
<!-- 주석 -->
```
---

# CSS
스타일

>## 인라인
>```
><선택자 style="속성:속성값;">
>```
>## 블록
>```
><head>
>    <title>제목</title>
>        <style>
>            [ <link href="[상위폴더/]스타일_이름.css/text" rel="stylesheet" type="text/css"> ]
>            
>        ★   선택자 { 속성1:속성값; [, ... 속성n:속성값] }   ★ 
>                            ...
>        </style>
></head>
>```
>
>+ ### [ <link href ... ] : 외부 css

+ ### 선택자
  기본, 그룹, 연결, UI, 동적
    
+ ### 속성 
  텍스트&목록, 색깔, 표, 박스, 배치
