# 읏맨-궁서체

[배포처 바로가기](http://www.3jong.com/font.html)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `OKGUNG`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/OKGUNG.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/OKGUNG.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'OKGUNG';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/OKGUNG.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/OKGUNG.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/OKGUNG.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/OKGUNG.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/subsets/OKGUNG-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/OKGUNG/subsets/OKGUNG-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "OKGUNG", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
읏맨체 라이선스  

아래 라이선스를 확인하시고, 유의하여 사용해 주세요.  

읏맨체 폰트의 지적 재산권을 포함한 모든 권리는 OK금융그룹에 있습니다. 
읏맨체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공됩니다. 
읏맨체 폰트 파일을 유료로 판매하는 것은 금합니다. 
온라인, 인쇄, 상품, 광고물 등 상업적으로도 자유롭게 사용 가능합니다. 
기업 및 브랜드 로고와 슬로건, 캐치프레이즈 등에는 사용할 수 없습니다. 
폰트 파일은 배포된 형태 그대로 사용해야 합니다. 
폰트 파일의 임의적인 수정은 금하며, 수정된 파일로 재배포하거나 유료로 판매할 수 없습니다. 
폰트의 출처 표기를 권장하며, 읏맨체를 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 당사의 프로모션을 위해 활용될 수 있습니다. 
OK금융그룹의 이미지를 훼손할 수 있는 불법 사이트, 허위 과장 광고 등을 포함한 인쇄물, 광고물, 제작물에 사용을 금합니다.
```
