# 2022.08.18 Audio-Technica PF-TEST
Audio-Technica 모바일 웹앱
(10차 평가 스마트문화앱 UI 디자인)

------------------------------

사이트 링크: https://asben1.github.io/2022.08.18_Audio-Technica_PF-TEST/

------------------------------

모바일 기준: 아이폰 SE(w: 375px * h: 667px)<br>
PC에서 보실 떄는 크롬의 개발자 도구(F12)를 통해 보시는 것을 권장합니다!

토글 메뉴에 검색창 추가(+애니메이션)


# 기능 구현

-----------------
## 메인프레임

 - 헤더, 푸터, 토글메뉴창이 모든 페이지마다 실행되도록 했습니다.
 - 헤더 안에 뒤로가기버튼, 두가지 로고가 번갈아<br>
 Fadein&out하는 로고애니메이션, 토글 메뉴버튼을 넣었습니다.
 - 뒤로가기버튼이 필요없는 페이지는<br>
 간단한 클래스를 추가하여 보이지 않게 했습니다.  <br>{onclick="history.back()"}
 - 토글메뉴버튼 클릭시 메뉴창이 실행되며,<br>
 토글메뉴버튼은 닫기버튼으로 전환됩니다.
 - 메뉴창 안에 로그인, 장바구니, 찜한 상품등<br>
 간단한 페이지로 넘어갈 수 있도록 구현해 놓았습니다
 - 메인카테고리메뉴 옆 + 버튼을 누르면<br>
 서브 메뉴가 애니메이션으로 Slidedown이 적용됩니다.

------------------
## 메인페이지

* 메인 화면에 회사 홍보 영상이 무한 재생되고,<br>
계속 보기를 원치 않으면 밑으로 가기 버튼을 추가하여<br>
바로 상품을 볼 수있게끔 추가했습니다.

* 메인페이지 각각의 칼럼에 간단한 정보가 기입되어 있습니다.

-------------------
## 로그인 창
 
- input 태그를 사용하여 아이디 및 패스워드를 입력할 수 있게 하였으며<br>
아이디 저장 및 자동 로그인에 checkbox를 삽입하였습니다.

------------------
## 제품 페이지

- 제품의 정보는 JSON파일로 정리하였으며<br>
fetch 코드로 불러내어 html형식에 맞게 출력되도록 작성하였습니다.
- 카테고리 필터 버튼 클릭시 2x2, 한줄 로 전환됩니다.
- 제품 페이지 카테고리메뉴(소세지 메뉴)를 클릭하면<br>
카테고리별로 분류가 됩니다.
- 제품 클릭시 상세페이지로 이동됩니다.

------------------
## 상세 페이지

- 상세페이지 상단에는 제품 정보가 기입되어 있고,<br>
이미지 슬라이더(swiper)를 삽입하여 사용자가 직접 넘겨서 다음이미지를 볼 수 있게끔 설정해놨습니다.<br>
- radio버튼으로 색상을 선택할 수 있고 수량버튼을 추가하여<br>
플러스버튼과 마이너스버튼으로 수량을 선택할 수 있게 만들었습니다.(Javascript 사용)
<br>
<br>
<br>

## 사용한 언어
|HTML5|CSS3|Javascript|
|---|---|---|
