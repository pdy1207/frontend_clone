### 개요

      브라우저는 요소들에게 많은 style 속성을 줌 원치 않아도!! 

 - `display` : inline 이 defult 값  / block


inline 은 높이와 넓이를 가질 수 없다. 즉
inline은 높이와 넓이가 없다. `줄을 바꾸지 않고 다른 요소와 함께 한 행에 위치하려는 성향이다.`

block 은 높이와 넓이가 있다. `한 줄에 나열되지 않고 그 자체로 한 줄을 완전히 차지한다.`

<hr>

### margin 

`margin` 
	margin은 공간인데, box의 border(경계)의 바깥에 있는 공간

`margin` 은 box 가 갖고 있는 속성 중 하나 

      box는 세가지 속성이 있음 margin / border / padding 


maring - top ... 사방에 값을 다 주는 것은 매우 힘든일이며, 간단하게 하는 법이 있다.

값이 `하나`면 사방에 다 적용하는것 `두개`면 상하 좌우 <Br>
`네개`를 다 주면 위쪽 오른쪽 아래쪽 왼쪽 시계방향 (상 우 하 좌)

 - ex ) margin 상 우 하 좌 

<hr> 

### Collapsing margin 현상 (상하에서만 발생함 / 마진 상쇄)

      body 안에 div의 위 아래 마진이 body의 마진과 만나면 둘 중 큰 값의 마진으로 body에 적용된다.

한가지 `팁` 을 드리자면

margin-top: a; <br>
margin-right: b; <br>
margin-bottom: c; <br>
margin-left: d; <br>

를 합쳐서

margin: a b c d; 하셔도 순서대로 적용 됩니다. <br>
상하, 좌우 혹은 상, 좌우, 하 등 여러가지 방식이 더 있는데 자세한건 링크를 통해 알아보자

 - [마진 예제](https://developer.mozilla.org/en-US/docs/Web/CSS/margin)

<hr>
	
### padding
	
padding은 공간인데 box의 경계로부터 '안쪽' 공간<br>
값의 개수에 따라 적용되는 방향은 margin과 동일하다.

	
## 요약
	
자 다시 <br>
margin은 box의 경계로부터 '바깥' 공간 <br>
 
그럼 padding은? <br>
padding은 공간인데 box의 경계로부터 '안쪽' 공간 


### border box의 경계
	
	border : 굵기, 스타일, 색상 순이다.	
	
<hr>
	
- span은 inline이기 때문에 높이와 너비를 가질 수 없으며, 그래서 위, 아래에 margin을 가질 수 없다.
- 하지만 padding은 사방에 가질 수 있다.
- 이와 같은 상황에 margin을 위, 아래에 적용하고 싶다면, inline 요소를 block으로 바꿔줘야 한다.
- 온점(.)은 class명이라는 뜻.
- id⇒ #tomato는 id="tomato" class⇒ .tomato는 class="tomato"
- id명과 다르게 class명은 유일할 필요가 없다. 여러 요소들이 같이 쓸 수 있다.
- 와 같이 class 속에는 btn과 tomato를 연이어 넣어 각각 다른 class 속성을 동시에 부여할 수도 있다.

	
