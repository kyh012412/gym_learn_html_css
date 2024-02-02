```CSS
<style>
      * {
        text-align: center;
      }
      .header {
        border: 2px solid red;
        line-height: 55px;
        height: 55px;
      }
      .nav {
        border: 2px solid blue;
        height: 110px;
      }
      .main {
        border: 2px solid blue;
        height: 300px;
        line-height: 300px;
      }
      .footer {
        border: 2px solid black;
        height: 55px;
        line-height: 55px;
      }
      ul {
        list-style: none;
        padding-left: 0px;
      }
</style>
```

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
