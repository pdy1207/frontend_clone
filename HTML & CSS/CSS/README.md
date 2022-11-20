### CSS 넣는법

1. HTML의 CSS 넣는법 <BR>  
    1-1. 같은 HTML 파일에 HTML, CSS 코드를 놓는 방법 head tag 안에 style tag를 작성한다. 
  
  2. CSS와 HTMl을 분리시키는 방법(추천) <BR>  
    2-1. link tag를 이용해 style.css와 연결하고 rel을 이용해 관계를 적어준다.

  <hr>
  
  ### CSS 규칙
  
   -  HTML 의 어떤 태그를 가리키고 CSS로 잡아와서 우리가 원하는 건 모든 쓸 수 있음
  
          CSS는 HTML을 가리키는 언어이다.(가리키는것 자체를 selector라고 함)
          selector는 많은 속성을 가지고있다. (속성은 중괄호 안에 적어줌)
          selector {
          속성 : 값;
          } 형태로 작성한다.
          CSS 모든 속성은 어떤 값이든 쓸 수 있지만 브라우저가 이해하지는 못하므로 속성마다 맞는 값을 써줘야 함.
  
  
   - 브라우저가 CSS를 읽을 때 위에서부터 순서대로 읽는다.
   - CSS를 직접 적는 것을 inline CSS, CSS 파일을 include 하는 것을 external CSS라고 한다.
   - 만약 같은 selector를 가리키는 CSS가 여러개이면, `가장 마지막 스타일`이 적용된다.<BR>  
  ※ 따로따로 쓰지말고 같이 써주는게 좋다.
  
### media 

        @media screen and (min-width: npx) and (max-width:npx) and
         (orientation : landscape혹은portrait) => 
        스크린 사이즈에 따라서 property 조정 가능함. orientation으로 가로 세로 감지 가능
