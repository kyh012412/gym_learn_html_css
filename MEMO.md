### 정리

- HTML이란?

### Emmet

자동완성 기능하여 작성시간을 단축시켜주는기능

```link
https://docs.emmet.io/abbreviations/syntax/
https://gymcoding.notion.site/Emmet-3b8a259ba1cf412388443234c8bbfef5
```

### multiselect

- window기준 alt + ctrl + 화살표로 아래아래
- ctrl + → 가능

### Semantic(의미론적)

### display:none과 visibility:hidden의 차이

### 인라인요소 vs 블록요소

- 블록요소는 가로세로 크기조정가능
- 인라인요소는 불가능

### CSS 적용 우선순위

사용자 !important > 제작자 !important > 제작자 > 사용자 > 브라우저

### 자손결합자,

### 웹폰트

### 단위 em,rem

- em 요소의 글꼴 크기 (본인 태그의 적용된 font크기에 몇배로 적용할지)
- rem 루트 요소의 글꼴 크기 (최상위 요소의 몇배로 지정할지)

### vw,vh

상대적 비율(백분율)

### line-height

줄 간격 (단위로 px를써도 ok 추천하는 크기 1.8rem)

### letter-spacing

글자 간격 (디폴트 0rem)

### box-sizing

- content-box
- border-box

### float

### position

- static : 일반적흐름에 따르도록 (기본값)
- relative : 원래있어야할위치(static)보다 상대적인 값을 더줘서 이동시킬수 있음
- absolute : 부모를 기준으로 움직임, / 부모중에 포지션이 relative,absolute,fixed가 없다면 가장위의 태그(body)가 기준이 된다.
- fixed : 일반적흐름 제거 / viewport 기준으로 스크롤되어도 움직이지 않는 고정된 자리를 갖게됨.
- sticky : 일반적인 흐름을 따르다가 스크롤이동으로 화면가장자리가 감지되면 fixed 가 되는 속성

### z-index 속성

- position (relative,absolute,fixed) 속성이 적용된 요소에서만 작동합니다. / 큰숫자의 값이 더 위에나온다. (최우선으로 보인다.)
