# Bugs HTML Markup Code Refactoring

markup시 고려해야 할 사항!
---
[웹표준 준수] HMTL 문법은 유효한가?
[접근성 고려] 사용자 입장에서 접근하는데 문제가 없는가? (음성 출력/키보드 접근 등)
[의미 구조화] HTML 구조는 올바른 의미를 가지는가?
[코드 최적화] 불 필요한 <div> 또는 <span> 요소의 남용은 없었는가?
[팀원간 소통] 코드는 읽기 쉽고, 간결한가?    
---

## 아직 고민해야 할 부분
1. 버튼을 클릭하면 같은 내용의 컨텐츠가 뜨는데 이걸 다 하나하나 마크업을 해줘야 할까?
2. 버튼 처럼 생긴 <a> 는 어떻게 해야하나?
3. 대부분 ul>li 로 코드를 짰는데 <li> 요소 안 컨텐츠 부분에 <div>을 너무 많이 쓴건 아닐까?
4. 곡차트 부분 <ol>로 마크업했는데 공간만 만들어줘야하는걸까, 내가 컨텐츠 내용까지 다 써야하는걸까?(실시간 차트변경부분)
5. <img> vs background-image
					



##수정사항!


1. <header>영역에 포함시켰던 <div class="nav">을 <header>영역 바깥으로 빼서 <nav>으로 감싸줌