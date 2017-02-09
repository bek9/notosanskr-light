# Noto Sans KR Light

## 구성

 - `KS_X_1001_(3432_characters).txt` 경량화에 사용된 [KS X 1001](https://ko.wikipedia.org/wiki/KS_X_1001) 기준 글리프 3432자입니다.
 - `notosanskr` Google에서 제공하는 [Early Access v2](https://fonts.google.com/earlyaccess#Noto+Sans+KR)를 로컬에서 사용할 수 있도록 링크를 수정한 버전입니다.
 - `notosanskr-light` 아래 OTF 폰트들을 KS X 1001 기준으로 3432자만 서브셋으로 추출한 경량화 버전입니다.
 - `notosanskr-origin` Google의 Early Access에서 제공하는 OTF 원본 파일들입니다. [2015-06-16에 릴리즈](http://www.google.com/get/noto/updates/)된 1.004버전으로 추정하고 있습니다.

## 사용법

1.
`notosanskr` 또는 `notosanskr-light` 디렉토리를 서버 리소스 디렉토리에 옮겨두세요.
light 버전은 166 - 404 KB 인데 반해 원본은 2.5 MB - 773 KB 이므로 경량화 버전인 `notosans-lignt`를 추천합니다.

2.
CSS에서:
```
@import url(리소스_디렉토리/notosanskr-light/notosanskr.css); // 원본을 사용하고 싶으신 분은 '리소스_디렉토리/notosanskr/notosanskr.css'로 경로를 변경하세요.
```

또는 HTML에서:
```
<link rel="stylesheet" type="text/css" href="리소스_디렉토리/notosanskr-light/notosanskr.css"> <!-- 원본을 사용하고 싶으신 분은  '리소스_디렉토리/notosanskr/notosanskr.css'로 경로를 변경하세요. -->
```

위와 같이 파일을 불러옵니다. [로딩 속도를 향상](http://www.stevesouders.com/blog/2009/04/09/dont-use-import/)시키거나 [FOUT(Flash Of Unstyled Text)](https://www.paulirish.com/2009/fighting-the-font-face-fout/)을 피하려면 link 태그를 사용하는 것이 더 바람직합니다.

3.
이제 `font-family: 'Noto Sans KR', sans-serif;` 같은 식으로 스타일을 정의하면 폰트를 사용할 수 있습니다.

## License

Google Noto Font 라이센스에 의해 [SIL Open Font License, 1.1](http://fonts.gstatic.com/ea/notosanskr/v2/OFL.txt)을 명시합니다.

## References

 - [한글 웹 폰트 경량화해 사용하기](http://coderifleman.tumblr.com/post/111825720099/%ED%95%9C%EA%B8%80-%EC%9B%B9-%ED%8F%B0%ED%8A%B8-%EA%B2%BD%EB%9F%89%ED%99%94%ED%95%B4-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)
 - [스포카 한 산스와 글꼴 경량화](https://spoqa.github.io/2015/10/14/making-spoqa-han-sans.html)
 - [NotoSans-subset 2350자](https://raw.githubusercontent.com/UYEONG/NotoSans-subset/master/korean2350.txt)
 - [바람체 2350자](https://tumblbug.com/eyongje)
 - [서브셋 폰트 메이커](http://opentype.jp/subsetfontmk.htm)
 - [otf to woff2 converter](https://everythingfonts.com/otf-to-woff2)
 - [otf to woff converter](https://everythingfonts.com/otf-to-woff)

