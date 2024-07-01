# 추사 사랑체

[배포처 바로가기](https://www.yesan.go.kr/kor/sub04_01_01_05.do)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Chusa Love`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/ChusaLove.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/ChusaLove.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Chusa Love';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/ChusaLove-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/ChusaLove-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Chusa Love';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/ChusaLove-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/ChusaLove-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/subsets/ChusaLove-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/ChusaLove/subsets/ChusaLove-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Chusa Love", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
제 1유형 : 출처표시공공저작물의 자유이용 

출처표시 
상업적, 비상업적 이용가능 
변형 등 2차적 저작물 작성 가능 
* 주의 : 기관사용자는 공공누리 유형마크를 다운로드 후 사용시 지정된 유형마크 파일명 변경을 금지 

공공누리의 제 1유형 

이용자는 공공저작물을 이용할 경우, 다음과 같이 출처 또는 저작권자를 표시해야 합니다. 
ex) "본 저작물은 '예산군'에서 공공누리 제1유형으로 개방한 '추사사랑체'를 이용하였으며, 해당 저작물은 '예산군 www.yesan.go.kr'에서 무료로 다운받으실 수 있습니다."
```
