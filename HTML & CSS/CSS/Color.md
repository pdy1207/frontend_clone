
### Color

      color는 정말 css 에서중요하다 css에서 알아야할 color system
      
1) hexadecimal color (16진수 컬러)

    #000000 <  
    
    
2) RGB 방식

-> 이건 디자이너들이 많이쓴다 <br>

rgb(252,206,0); 이런식 rgba (205,23,0, 0.5); 4번째 숫자는 투명도를 말한다 ! <br>
a 즉 알파는 투명도를 말하는 것이다.

`Variable` (custom properties )

variable도 정말 중요하다 !!! 이게 css를 프로그래밍언어처럼 보여준다 <br>
프로그래밍언어는아니지만 그 장점을 보여주는것임 :root 라는 엘리먼트에 변수를 추가하는 것이다 <br>
:root은 기본적으로 모든 document의 뿌리가 되는 것이다 <br>
출발점이 되는 것이다 여기에 변수이름을 쓰고 <br>
--main-color라고 변수이름을 주고 <br>
이것을 document의 root에 저장하는것이다 <br>

--를 써주고 변수이름을 써줘야한다 변수는 -- 2개 그리고 변수이름 빈공간이 있다면 -로 채워야한다. 물론 컬러만 저장할 수 있는게 아니다!<br>

--default-border: 1px solde var(--main-color);

그 다음 이 변수를 사용할 곳에 <br>
p {
background-color: var(--main-color); 
} <br>
a {
background-color: var(--main-color); 
}
