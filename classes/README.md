# class
`id`는 유니크한 태그를 가져야하지만, `class`는 그렇지 않다. 조금 더 general한 스타일은 `class`를 사용한다.

## class 중복 제거
`.teal`과 `.tomato` 사이에 중복이 존재한다. 
```html
<body>
  <span class="teal">hello</span>
  <span class="tomato">hello</span>
  <span class="teal">hello</span>
  <span class="tomato">hello</span>
  <span class="teal">hello</span>
  <span class="tomato">hello</span>
</body>
```
```css
.teal {
  padding: 5px 10px;
  border-radius: 5px;
  background-color: teal;
}
.tomato {
  padding: 5px 10px;
  border-radius: 5px;
  background-color: tomato;
}
```

<br>

이러한 중복은 `.round` class를 추가하여 없앨 수 있다.

```html
<body>
  <span class="round teal">hello</span>
  <span class="round tomato">hello</span>
  <span class="round teal">hello</span>
  <span class="round tomato">hello</span>
  <span class="round teal">hello</span>
  <span class="round tomato">hello</span>
</body>
```
```css
.round {
  padding: 5px 10px;
  border-radius: 5px;
}
.teal {
  background-color: teal;
}
.tomato {
  background-color: tomato;
}
```

<img width="750" alt="classes" src="https://user-images.githubusercontent.com/31913666/201463084-2d0853cf-73ed-41d8-bc5a-a3a8e5aac26e.png">
