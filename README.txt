평안노인주간보호센터 홈페이지 (단일 파일)

1. index.html 을 메모장/VS Code로 열어 맨 아래 <script> 안의 INFO 값을 채웁니다.
   - "[" 로 시작하는 값은 아직 안 채운 것으로 보고 화면에 노란색으로 표시됩니다.
   - kakao(카카오톡 채널 주소), naverMap(네이버 지도 공유 링크)는 비워 두면 버튼이 자동으로 숨겨집니다.
2. 사진은 img/ 폴더에 아래 이름으로 넣으면 자동으로 표시됩니다.
   hero1.jpg hero2.jpg hero3.jpg (첫 화면 슬라이드, 가로 1920px 권장), about.jpg (센터장·직원), p1~p5.jpg (프로그램·식사·나들이·만들기·생신), og.jpg (카톡 공유 썸네일 1200x630)
   - 다른 이름을 쓰려면 index.html 의 data-src 값을 바꾸세요.
3. 지도: <div class="map" id="mapbox"> 안에 구글 지도(주소로 표시, 키 필요 없음)가 들어가 있습니다.
   주소가 바뀌면 iframe src 의 q= 뒤 주소만 고치면 됩니다. "네이버 지도" 버튼은 INFO.naverMap 링크로 열립니다.
4. 올리기: GitHub Pages(무료) 또는 어떤 정적 호스팅이든 index.html 과 img/ 폴더만 올리면 됩니다.
   - 도메인을 살 경우 pyeongan-daycare.kr 처럼 짧은 것을 권합니다.
5. 올린 뒤 네이버 서치어드바이저(searchadvisor.naver.com)에 사이트를 등록하면 네이버 검색에 잡힙니다.
