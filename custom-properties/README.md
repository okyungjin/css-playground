# custom-properties
중복되는 스타일은 변수로 지정해놓고 사용하면 편리하다.
```css

:root {
  --main-color: #fcce00;
  --default-border: 2px solid var(--main-color);
}

p {
  background-color: var(--main-color);
}
a {
  color: var(--main-color);
}
button {
  border: var(--default-border);
}
```