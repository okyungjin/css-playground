# position: fixed
`position` 속성은 기준 위치에서 아주 조금씩만 움직일 경우 사용된다.

## static (default)
element를 일반적인 문서 흐름에 따라 배치한다.

## fixed
![position-fixed](https://user-images.githubusercontent.com/31913666/201614995-6b555aee-0285-4f47-8ed5-59e06963fe8b.gif)

## relative
`position: relative`이면 top, bottom, left, right 속성을 사용할 수 있다.
이 값을 조정하면 엘리먼트가 **처음 놓인 자리**에서 상하좌우로 움직인다.

## absolute
**가장 가까운 relative 부모를 기준으로 이동시켜준다.**
아래 예시에서는 `.green`의 부모인 `.wheat`는 relative가 아니기 때문에, 그 위의 body가 relative한 부모가 된다.
````html
<div class="wheat">
  <div class="green"></div>
</div>
````

따라서 `.green`에 `right: 0;` 속성을 주면 body의 가장 오른쪽으로 이동하게 된다.
이걸 막고 싶다면 `.wheat`를 relative로 만든다.

