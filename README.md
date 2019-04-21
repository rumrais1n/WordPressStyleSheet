# WordPress Style Sheet
## Overview
This repository has stylesheets for [my blog](https://blog.rumraisin.tokyo/).

## Imported Fonts
`style.css` imported these fonts below:
- M PLUS Rounded 1c
- Noto Sans JP
- M PLUS 1p

## Usage
### Import in CSS
Write in CSS like below:
```
@import url('https://fonts.googleapis.com/css?family=M+PLUS+1p:100,300,400,500,700,800,900|M+PLUS+Rounded+1c:100,300,400,500,700,800,900|Noto+Sans+JP:100,300,400,500,700,900&subset=japanese');
```

### Specify in CSS
Write in CSS like below:
```
h1 {
	font-family: 'Noto Sans JP', sans-serif;
	font-weight: 400;
}
h2 {
	font-family: 'M PLUS 1p', sans-serif;
	font-weight: 400;
}
body {
	font-family: 'M PLUS Rounded 1c', sans-serif;
	font-weight: 400;
}
```