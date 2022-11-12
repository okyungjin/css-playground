# flexbox
<img width="800" alt="flexbox" src="https://user-images.githubusercontent.com/31913666/201466723-b2f3cc6c-0a11-4a60-8115-625513b5a3cc.png">

## Usage
> 자식 element에게는 말하지 않고, 부모 element에만 말한다.

`div`를 배치하고 싶다면 `div`의 **부모**인 `body`에 flexbox 속성을 지정해줘야 한다는 뜻이다. 
```html
<body>
  <div></div>
  <div></div>
  <div></div>
</body>
```

<br>

## `justify-content` vs `align-items`
- main axis 👉 `justify-content`
- cross axis 👉 `align-items`

<img width="500" src="https://user-images.githubusercontent.com/31913666/201465626-8e820794-6b83-46cc-b4c6-6b0a03fd434f.png"  alt="flex-axis"/>

<br>

## `flex-direction`
- row
- row-reverse
- column
- column-reverse

> **row, column을 변경하면 main/cross axis가 변경된다.**

<br>

## TroubleShooting
### 1) `align-items: center`가 적용되지 않을 때
flex 속성이 적용된 element의 height을 확인해보자. `height: 100vh`를 추가해주니 정상적으로 동작한다.


### 2) 현재 index.html 코드에서 `align-items: strech`가 적용되지 않는 이유
`div`에 `height: 300px` 속성이 잡혀있기 때문이다. 이 속성을 삭제해주면 `strech`가 적용된다.

<img width="800" alt="스크린샷 2022-11-12 오후 5 35 16" src="https://user-images.githubusercontent.com/31913666/201466112-7151862c-c637-4107-a4e5-5b92e2fda6e9.png">
