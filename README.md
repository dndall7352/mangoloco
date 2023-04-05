# MangoLoco팀
## 소프트웨어 요구사양 기반 노트북 스토어 서비스
### 하드웨어에 대한 전문적 지식이 부족한 사회 초년생, 대학 새내기 등을 위해 노트북의 소프트웨어 필터링을 제공하는 서비스이다.

> 노트북을 사는 고객
- 다섯 가지로 분류된 그래픽 소프트웨어에서 자신이 사용하고 싶은 프로그램을 선택할 수 있다.
- 검색 버튼을 누르면 최소 사양과 적정 사양에 맞는 노트북의 목록이 출력되며, 스크롤을 아래로 내리면 6개씩 목록이 자동 로딩 된다.
- 장바구니를 열고, 원하는 노트북을 드래그/드랍으로 끌어다 놓으면 장바구니에 선택한 노트북 목록이 더해진다.
- 개수를 늘리거나 줄일 수 있고, 결제하기 버튼을 누르면 KakaoPay 결제 API로 연결한 결제 페이지가 팝업된다.
- 노트북 이미지를 한 번 클릭하면, 세부 정보 페이지로 이동하여 제품의 세부 사양과 제품에 대한 리뷰를 확인할 수 있다.
- 자유 게시판 페이지로 이동하여 제품에 대한 의견 등을 자유롭게 나눌 수 있다.
> 스토어 관리자
- 회원이 작성한 글을 수정하거나 삭제할 수 있다.

## 시작하기
- 본 프로젝트는 웹 서비스를 제공하기로 설계 되었으나, 별도의 서버를 두지 않으므로 html 문서를 가동하기 위해 Apache Tomcat, Live Server 등의 별도 서버를 통해 실행시켜야 한다.

## 외부 리소스 정보
- HTML 문서 템플릿 소스 : HTML5UP - Miniport (https://html5up.net/miniport)
- 데이터 크롤링 소스 : 다나와 노트북 사이트 (https://prod.danawa.com/list/?cate=112758&15main_11_02) : 노트북 기본 정보, 세부 정보, 이미지, 개별 리뷰 등
- Passmark (https://www.passmark.com/) : CPU, GPU Benchmark 점수 (정량적 성능평가 점수)
- DB : JDBC, SQLDeveloper
- Server : Apache Tomcat - 9.0.71
- Mapper Framework : MyBatis
