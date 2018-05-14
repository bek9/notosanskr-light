# Noto Sans KR Light

Google의 [Noto Sans KR](https://fonts.google.com/earlyaccess#Noto+Sans+KR) 폰트에서 [KS X 1001](https://ko.wikipedia.org/wiki/KS_X_1001) 기준 기본 한글 2350자와 로마 문자, 특수 문자만 추출한 폰트입니다. 원본은 11,172자로 773 KB - 2.5 MB 이고, light 버전은 3432자로 166 - 404 KB 입니다.

## 디렉토리 설명

- `KS_X_1001_(3432_characters).txt` 경량화에 사용된 기준 글리프 3432자입니다.
- `notosanskr` https://fonts.google.com/earlyaccess#Noto+Sans+KR 의 CSS 파일은 폰트를 구글 CDN에서 가져오기 때문에 직접 서빙할 수 있도록 CSS 내 URL만 상대경로로 수정한 버전입니다.
- `notosanskr-light` Google에서 제공하는 [원본 OTF 폰트들](http://fonts.gstatic.com/ea/notosanskr/v2/download.zip)을([2015-06-16에 릴리즈](http://www.google.com/get/noto/updates/)된 1.004버전으로 추정) KS X 1001 기준으로 3432자만 서브셋으로 추출한 경량화 버전입니다.

## Noto Sans KR Light 적용 방법

### 1. 폰트 불러오기

아래와 같이 HTML 또는 CSS에서 `notosanskr.css` 파일을 불러옵니다.

#### 1-1. HTML에서 폰트 불러오기

직접 서빙 시

`<link rel="stylesheet" type="text/css" href="path/to/notosanskr-light/notosanskr.css">`

CDN 사용 시

`<link rel="stylesheet" type="text/css" href="https://rawgit.com/bek9/notosanskr-light/master/notosanskr-light/notosanskr.css">`

#### 1-2. 또는 CSS에서 폰트 불러오기

직접 서빙 시

`@import url(path/to/notosanskr-light/notosanskr.css);`

CDN 사용 시

`@import url(https://rawgit.com/bek9/notosanskr-light/master/notosanskr-light/notosanskr.css);`

> - Rawgit은 안정성이 보장된 CDN이 아니므로 **직접 서빙하는 방법**을 추천합니다.
> - Notosanskr 원본은 URL을 아래와 같이 바꾸면 사용할 수 있습니다.
>   - 직접 서빙 시 `path/to/notosanskr/notosanskr.css`
>   - CDN 사용 시 `http://fonts.googleapis.com/earlyaccess/notosanskr.css`
> - [로딩 속도를 향상](http://www.stevesouders.com/blog/2009/04/09/dont-use-import/)시키거나 [FOUT(Flash Of Unstyled Text)](https://www.paulirish.com/2009/fighting-the-font-face-fout/)을 피하려면 CSS에서 `@import` 대신 HTML에서 `link` 태그를 사용하는 것이 더 바람직합니다.

### 2. 폰트 사용하기

이제 `font-family: 'Noto Sans KR', sans-serif;` 같은 식으로 스타일을 정의하면 폰트를 사용할 수 있습니다.

## 라이센스

[SIL Open Font License, 1.1](http://fonts.gstatic.com/ea/notosanskr/v2/OFL.txt)

## 참고 자료

- [Noto CJK (GitHub)](https://github.com/googlei18n/noto-cjk)
- [한글 웹 폰트 경량화해 사용하기](http://coderifleman.tumblr.com/post/111825720099/%ED%95%9C%EA%B8%80-%EC%9B%B9-%ED%8F%B0%ED%8A%B8-%EA%B2%BD%EB%9F%89%ED%99%94%ED%95%B4-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)
- [스포카 한 산스와 글꼴 경량화](https://spoqa.github.io/2015/10/14/making-spoqa-han-sans.html)
- [NotoSansKR-Hestia by theeluwin](http://theeluwin.github.io/NotoSansKR-Hestia/)
- [NotoSans-subset 2350자](https://raw.githubusercontent.com/UYEONG/NotoSans-subset/master/korean2350.txt)
- [바람체 2350자](https://tumblbug.com/eyongje)
- [서브셋 폰트 메이커](http://opentype.jp/subsetfontmk.htm)
- [otf to woff2 converter](https://everythingfonts.com/otf-to-woff2)
- [otf to woff converter](https://everythingfonts.com/otf-to-woff)
 
