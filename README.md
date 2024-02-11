<h1>카카오 맵 API를 이용한 지도 서비스</h1>
<p>지도 내에 마커를 표시하고 마커에 해당하는 가게에 대한 정보를 표시합니다. <br/>가게를 클릭하면 해당 가게의 상세 정보 페이지로 이동합니다.</p>
<h2>가게 정보 표시</h2>
<p>카카오 API에서 제공하는 InfoWindow 클래스를 이용해 구현</p>
<img src="https://github.com/tptkds/MapServiceWithKakaoMap/assets/58039782/71814b66-c8ba-4571-83b6-49a611bf1b67">
<h2>현재 위치 표시</h2>
<P>navigator.geolocation.getCurrentPosition로 현재 위치의 위도와 경도를 구한 후 카카오 API에서 제공하는 setCenter 메서드의 인자로 넘겨줌으로써 구현</P>
<img src="https://github.com/tptkds/MapServiceWithKakaoMap/assets/58039782/f18949c5-fac4-49cb-bde4-8f127e348177">
