# inline-block
`<div>` 태그를 좌우로도 배치하고 싶어서 `display: inline` 속성을 추가해주면 화면에서 사라진다.
inline은 width, height을 가질 수 없기 때문이다. 이럴 때 `display: inline-block`을 사용할 수 있다.
width, height을 가지는 inline을 만들 수 있다.

## inline-block의 단점
inline-block은 다음의 이유로 사용하지 않는 추세이다.
- Responsive design (반응형 디자인)을 지원하지 않는다.
- 좌/우 margin을 주지 않았는데 자동으로 추가된다. 심지어 유동적이다.

inline-block의 단점을 보완한 `flex`라는 속성이 존재하기 때문에 굳이 사용하지 않아도 되지만, 알아둘 필요는 있다.

<br>

**반응형을 지원하지 않는 inline-block**

<img width="1000" alt="inline-block" src="https://user-images.githubusercontent.com/31913666/201464637-277fb8d9-ca88-4895-8f65-6c0cf4070232.png">
