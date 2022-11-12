# inline elements
- padding (O)
- border (O)
- margin
  - 위, 아래 (X) 👈 높이가 없으니 위, 아래 margin 사용 불가
  - 왼쪽, 오른쪽 (O)

```html
<body>
  <span>hello</span>
  <span>hello</span>
</body>
```
```css
body {
  margin: 20px;
}
span {
  background-color: aquamarine;
  padding: 20px;
  margin: 30px;
}
```

<img width="750" alt="margin-in-inline" src="https://user-images.githubusercontent.com/31913666/201462258-4c942859-a11a-4f18-bb19-78c06bb5d61e.png">
