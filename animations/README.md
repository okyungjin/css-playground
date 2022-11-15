# animations
`@keyframes`으로 애니메이션을 만들 수 있다.

```css
@keyframes coinFlip {
from {
  transform: rotateY(0deg);
  }
  to {
    transform: rotateY(360deg);
  }
}

img {
  border-radius: 50px;
  width: 50%;
  animation: coinFlip 5s ease-in-out infinite;
}
```

![coin-flip-animation](https://user-images.githubusercontent.com/31913666/201849263-ed11f7ce-2759-4cac-a08a-5f2971be5dfe.gif)

## 참고하면 좋은 사이트
- https://animista.net/