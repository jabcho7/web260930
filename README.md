https://jabcho7.github.io/web260930/

- HTML
	- 내용 / 스토리
- CSS (Cascading Style Sheets)
	- 모양 / 스토리
- JavaScript(JS)
	- 움직임 / 인터랙션 (interaction)    
<h3> --> DOM </h3>

<br>
<h4>CSS = 단계적으로 적용하는 style sheets</h4>
태그 {스타일}
- html, body 등 여러 태그를 묶거나, class로 여러 태그를 묶어 한번에 편집 가능<br>
- 174p 우선순위 확인 (선택 범위가 작을수록 우선)<br>
- border, color, background-color, font 등 사용 가능<br>
- 교재 194p 박스 모델 참고<br>

<h4>link rel="stylesheet" href="./style.css" 태그를 html head 태그 안에 넣어 css 적용하기</h4>

<h3> 가상 요소 선택자 </h3>
<strong> (태그)::before </strong>- 콘텐츠 앞 공간 선택<br>
<strong>  (태그)::after </strong>- 콘텐츠 뒷 공간 선택
<br>
<br>
<strong>a</strong>(링크 태그) 관련 css<br>
<strong>a:visited</strong> <-- 방문한적 있는 링크<br>
<strong>a:hover</strong> <-- 마우스가 링크 위에 올라가있을 때<br>
<strong>a:active</strong> <-- 마우스가 클릭하고있을 때<br>

<br>
<h4>구조적 가상 클래스 선택자</h4>
 -  교재 160p 참고
<br>
<h3> font family </h3>
google 폰트에서 폰트 선택 -> get font -> import -> style 태그 안쪽 내용 css에 붙여넣기<br>
font-family: (글꼴), (글꼴2) --> 글꼴 적용 실패시 글꼴2 적용<br>
- 교재 183p 참고
