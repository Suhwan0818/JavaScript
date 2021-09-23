# Hello world

간단한 예제로 바로 시작해 보겠다.  
visual studio code를 통해 hello_world.js라는 파일을 만들어 보겠다.

```html
<html>
  <body>
    <p>스크립트 적용 전</p>
    <script>
      alert('hello, world')
    </script>
    <p>스크립트 적용 후</p>
  </body>
</html>
```

완성 했으면 터미널 창에 **node hello_world.js**라고 작성해 실행해보자. 위 알람 창에 hello world라고 나온다면 성공한 것이다.

# 모던 마크업

`<script>` 태그에는 몇 가지 **속성(attribute)**이 들어있다. 최근엔 사용되지 않고 오래된 코드에서 찾아볼 수 있다.

`type` 속성: `<script type = ...>`  
HTML4에서 스크립트에 `type`을 명시하는 것이 필수였다. 그래서 `type="text/javascript"` 속성이 붙은 스크립트를 쉽게 찾아볼 수 있다. 하지만 이제는 필수가 아니다. 현재 JavaScript에선 속성의 의미가 바뀌었다. 이 내용은 뒷 내용에 설명을 추가하겠다.  
`language` 속성: `<script language = ...>`  
현재 사용하고 있는 스크립트 언어를 나타낸다. 지금은 자바스크립트가 기본 언어이기 때문에 의미가 없어졌다.
