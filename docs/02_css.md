# 2. CSS

## 2.1 CSS란?

- CSS는 Cascading Style Sheets의 약자입니다.
- CSS는 웹 페이지의 스타일을 지정합니다.
- CSS는 HTML과 별도로 작성합니다.
- CSS는 선택자와 선언부로 구성되어 있습니다.
- CSS는 선택자로 HTML 요소를 선택하고, 선언부로 스타일을 지정합니다.
- CSS는 여러 개의 스타일을 가질 수 있습니다.
- CSS는 여러 개의 선택자를 가질 수 있습니다.
- CSS는 여러 개의 선언부를 가질 수 있습니다.
- CSS는 여러 개의 선언을 가질 수 있습니다.
- CSS는 선언부를 중괄호({})로 묶어서 작성합니다.
- CSS는 선언을 콜론(:)으로 구분합니다.
- CSS는 선언을 세미콜론(;)으로 구분합니다.
- CSS는 선언의 마지막에 세미콜론(;)을 붙이지 않습니다.
- CSS는 주석을 /\* \*/로 작성합니다.

## 2.2 CSS 적용 방법

- CSS는 HTML에 적용할 수 있습니다.
- CSS는 HTML에 직접 작성할 수 있습니다.
- CSS는 HTML에 style 태그를 사용하여 작성할 수 있습니다.
- CSS는 HTML에 link 태그를 사용하여 파일로 분리하여 작성할 수 있습니다.
- CSS는 HTML에 link 태그를 사용하여 여러 개의 CSS 파일을 적용할 수 있습니다.
- CSS는 HTML에 여러 개의 style 태그를 사용하여 작성할 수 있습니다.
- CSS는 HTML에 여러 개의 style 태그를 사용하여 여러 개의 CSS를 적용할 수 있습니다.
- CSS는 HTML에 여러 개의 link 태그를 사용하여 여러 개의 CSS 파일을 적용할 수 있습니다.
- CSS는 HTML에 여러 개의 link 태그를 사용하여 여러 개의 CSS를 적용할 수 있습니다.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>CSS</title>
    <style>
      h1 {
        color: red;
      }
    </style>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>HTML</h1>
    <p>HTML은 웹 페이지의 구조를 작성하는 언어입니다.</p>
  </body>
</html>
```

```css
h1 {
  color: red;
}
```

## 2.3 선택자

- 선택자는 HTML 요소를 선택합니다.
- 선택자는 HTML 요소의 이름을 사용하여 선택합니다.
- 선택자는 HTML 요소의 id 속성을 사용하여 선택합니다.
- 선택자는 HTML 요소의 class 속성을 사용하여 선택합니다.

```css
h1 {
  color: red;
}

#title {
  color: red;
}

.title {
  color: red;
}
```

## 2.4 속성

- 속성은 스타일을 지정합니다.
- 속성은 HTML 요소의 특징을 지정합니다.
- 속성은 HTML 요소의 특징을 스타일로 지정합니다.
- 속성은 HTML 요소의 특징을 스타일의 속성으로 지정합니다.

```css
h1 {
  color: red;
  font-size: 24px;
}
```

### 2.4.1 색상

- 색상은 color 속성으로 지정합니다.
- 색상은 색상 이름으로 지정합니다.
- 색상은 색상 코드로 지정합니다.
- 색상은 색상 코드를 사용하여 지정합니다.
- 색상은 색상 코드를 사용하여 16진수로 지정합니다.
- 색상은 색상 코드를 사용하여 RGB로 지정합니다.
- 색상은 색상 코드를 사용하여 RGBA로 지정합니다.
- 색상은 색상 코드를 사용하여 HSL로 지정합니다.
- 색상은 색상 코드를 사용하여 HSLA로 지정합니다.

```css
h1 {
  color: red;
  color: #ff0000;
  color: #f00;
  color: rgb(255, 0, 0);
  color: rgba(255, 0, 0, 1);
  color: hsl(0, 100%, 50%);
  color: hsla(0, 100%, 50%, 1);
}
```

### 2.4.2 배경

- 배경은 background 속성으로 지정합니다.
- 배경은 배경 색상으로 지정합니다.
- 배경은 배경 이미지로 지정합니다.
- 배경은 배경 이미지를 사용하여 지정합니다.
- 배경은 배경 이미지를 사용하여 배경을 지정합니다.
- 배경은 배경 이미지를 사용하여 배경 색상을 지정합니다.
- 배경은 배경 이미지를 사용하여 배경 이미지를 지정합니다.
- 배경은 배경 이미지를 사용하여 배경 이미지의 위치를 지정합니다.
- 배경은 배경 이미지를 사용하여 배경 이미지의 크기를 지정합니다.
- 배경은 배경 이미지를 사용하여 배경 이미지의 반복을 지정합니다.
- 배경은 배경 이미지를 사용하여 배경 이미지의 공간을 지정합니다.

```css
h1 {
  background-color: red;
  background-image: url("image.jpg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}
```

### 2.4.3 글꼴

- 글꼴은 font-family 속성으로 지정합니다.
- 글꼴은 글꼴 이름으로 지정합니다.
- 글꼴은 글꼴 이름을 사용하여 지정합니다.
- 글꼴은 글꼴 스타일을 사용하여 지정합니다.
- 글꼴은 글꼴 스타일을 사용하여 글꼴을 지정합니다.
- 글꼴은 글꼴 스타일을 사용하여 글꼴의 스타일을 지정합니다.

```css
h1 {
  font-family: "Times New Roman";
  font-style: italic;
  font-weight: bold;
}
```

### 2.4.4 텍스트

- 텍스트는 text-align 속성으로 지정합니다.
- 텍스트는 텍스트 정렬을 사용하여 텍스트의 정렬을 지정합니다.

```css
h1 {
  text-align: center;
}
```

### 2.4.5 여백

- 여백은 margin 속성으로 지정합니다.
- 여백은 여백을 사용하여 여백을 지정합니다.
- padding 속성은 여백을 사용하여 여백을 지정합니다.

```css
h1 {
  margin: 10px;
  /* margin: 10px 20px 30px 40px; */
  padding: 10px;
}
```

### 2.4.6 크기

- width, height 속성은 크기를 사용하여 크기를 지정합니다.

```css
h1 {
  width: 100px;
  height: 100px;
}
```

### 2.4.7 테두리

- 테두리는 border 속성으로 지정합니다.
- 테두리는 테두리를 사용하여 테두리를 지정합니다.
- 테두리는 테두리 스타일을 사용하여 테두리의 스타일을 지정합니다.

```css
h1 {
  border: 1px solid black;
  border-radius: 10px;
}
```

### 2.4.8 그림자

- 그림자는 box-shadow 속성으로 지정합니다.
- 그림자는 그림자를 사용하여 그림자를 지정합니다.

```css
h1 {
  box-shadow: 10px 10px 10px black;
}
```

### 2.4.9 애니메이션

- 애니메이션은 animation 속성으로 지정합니다.
- 애니메이션은 애니메이션을 사용하여 애니메이션을 지정합니다.

```css
h1 {
  animation: 1s ease-in-out infinite alternate;
}
```

### 2.4.10 변형

- 변형은 transform 속성으로 지정합니다.
- 변형은 변형을 사용하여 변형을 지정합니다.

```css
h1 {
  transform: rotate(45deg);
}
```

## 2.5 단위

- px, em, rem, %, vw, vh, vmin, vmax 단위는 크기를 지정할 때 사용합니다.

```css
h1 {
  width: 100px;
  height: 100px;
  font-size: 24px;
  margin: 10px;
  padding: 10px;
  border: 1px solid black;
  border-radius: 10px;
  box-shadow: 10px 10px 10px black;
  animation: 1s ease-in-out infinite alternate;
  transform: rotate(45deg);
}
```
