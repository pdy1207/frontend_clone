# [flex 연습 개구리 게임](https://flexboxfroggy.com/#ko)

### div (보통적으로 박스 연습 중요도 ***** ) 

  - 레이아웃을 그린다고 생각하면 됨.

 - `div`는 옆에 다른 div가 오지 않는다.
 - `span`은 옆에 다른 span이 올 수 있다.
 - `link`는 옆에 올 수 있다.
 - `p`는 옆에 올 수 없다.
 - 옆에 다른 요소가 못 오는걸 `block` 올 수 있는걸 `inline`라고 한다. (in the same line)

 ※ inline의 대표적인 태그 span, link, img

### inline-block === Responsive Design(반응형 디자인)을 지원하지 않음!

block 속성을 inline로 바꾸고, width와 height를 가지게 하고 싶을 때는 inline-block을 사용한다. <Br>
하지만 많은 문제가 있고, 오래됐기 대문에 잘 사용하지 않음. <Br>

## 그래서 나온게 ** flex!!! ** 
  
      flex-container가 height를 가지고 있지 않으면 align-items를 사용하더라도 위치가 바뀌지 않음.  
  #### 사용 규칙
  
- 자식 엘리먼트를 움직이게 하려면 부모 엘리먼트를 flex container로 만들어야 한다.
- align-items : cross axis에서 작용 (세로)
- justify-content : main axis에서 작용 (가로) (디폴트)
  
  
  
  
