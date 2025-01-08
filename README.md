
<h1>ItTrip Service</h1>

<div align="center">
  <img src="https://github.com/Fk1128/ittrip-project/blob/test/img/%EB%A9%94%EC%9D%B8%ED%8E%98%EC%9D%B4%EC%A7%80.png"/>
</div>

<br/>

> 🗺️ 여행 계획 관리 서비스
여행 계획을 쉽고 편리하게 !
> <br/>
> 여행 제목과 날짜를 설정하고,
> 경로와 준비물까지 한 번에 관리할 수 있는 서비스입니다. 
> <br/>
> 더불어, 지역별 추천 관광지, 숙박업소, 음식점 정보를 제공하여 여행 준비를 더욱 완벽하게 도와드립니다.

<br/>
<p align="center">
  <a href="http://ittrip.shop"><del></del> 🔗 지금 바로 ItTrip 사용하기</a>
</p>
<br/>


<h3>🚀 프로젝트 소개</h3>

<b>메인페이지 기능 사용녹화  </b>

<img src="https://github.com/Fk1128/ittrip-project/blob/test/react/src/img/background.svg" alt="홈"/>

<ul>
  <li>메인페이지 설명.</li>
  <li>메인페이지 설명</li>
  <li>메인페이지 설명</li>
</ul>

<b>NewPlan 기능 사용 녹화  </b>

<img src="" alt="피드"/>

<ul>
  <li>newplan 에서 사용하는 기능에 대한 설명  </li>
  <li>newplan 설명</li>
</ul>

<b>마이플랜 기능 사용 녹화   (1)</b>

<img src="" alt="일기 작성"/>

<ul>
  <li>마이플랜 기능에서 수정하는것에 대한 설명 .</li>
  <li>마이플랜 기능에서 수정하는것에 대한 설명.</li>
</ul>

<b>회원가입 로그인 소셜로그인  </b>

<img src="" alt="내 일기"/>

<ul>
  <li>회원가입 설명.</li>
  <li>로그인 설명.</li>
  <li>소셜로그인 설명.</li>
</ul>
<br/>

<b>마이페이지에서의 기능 </b>

<img src="" alt="내 일기"/>

<ul>
  <li>회원정보 수정시 일반로그인 사용자와 소셜로그인 사용자의 마이페이지.</li>
  <li>회원정보 수정시 일반로그인 사용자와 소셜로그인 사용자의 마이페이지.</li>
  <li>회원정보 수정시 일반로그인 사용자와 소셜로그인 사용자의 마이페이지.</li>
</ul>
<br/>




<h2>💻 기술적 도전</h2>

<h3>[FE] API 요청 최적화</h3>

<img src="https://github.com/boostcampwm2023/web18_Dandi/assets/75190035/d0b591b5-fc70-4f7a-a6c0-ac86eb67e491" alt="API 요청 최적화 결과"/>

<li>불필요한 서버 요청 비용을 줄이기 위해서 API 요청 최적화에 대해 고민했고, 이후 유지보수에서 어려움을 겪지 않도록 어떤 방식으로 API 요청을 최적화해야하는지 고민했습니다.</li>
<li>저희 팀은 API 응답 데이터 수정해 요청을 최소화하고 디바운싱, Tanstack Query staleTime 3가지 키워드로 해당 문제에 접근했고 기존 요청들을 평균 66% 수준으로 감소시킬 수 있었습니다.</li>

<br/>

> - <a href="https://www.notion.so/kimyoonju/af665439840e4367b379c7a2d1b0125a?v=e112c574bbc74ee09e0ddf14a9893c2e&p=695d6520aa9142658e81b6bbd19c1d55&pm=s">디바운싱과 쓰로틀링</a>
> - <a href="https://velog.io/@dohun2/React-Query%EB%A1%9C-API-%EC%9A%94%EC%B2%AD-%EC%A4%84%EC%9D%B4%EA%B8%B0">TanStack Query(React Query) API 요청 줄이기</a>

<br/>

<h3>[BE] 무중단 배포</h3>

<img src="https://github.com/boostcampwm2023/web18_Dandi/assets/75190035/d0ff1dc3-5a4a-44e9-bafc-0a5f80050172" alt=""/>

<li>서버 이전 과정에서 이전 서버와 동일하게 프로그램을 설치/세팅하는 과정에 번거로움을 느껴 도커를 도입했습니다. 도커 도입 후 배포 과정에서 불가피하게 5분의 다운 타임이 발생했는데 해당 문제 해결을 어떤 방식으로 배포를 진행해야하는지 고민했습니다.</li>
<li>해당 문제 해결을 위해서 블루-그린 방식으로 무중단 배포를 도입하기로 결정했고, 다운 타임을 5분 -> 0.3초로 줄일 수 있었습니다.</li>

<br/>

> - <a href="https://velog.io/@shunny/Docker%EC%99%80-Nginx%EB%A1%9C-%EB%AC%B4%EC%A4%91%EB%8B%A8-%EB%B0%B0%ED%8F%AC%EB%A5%BC-%ED%95%B4%EB%B3%B4%EC%9E%90">무중단 배포 도입기</a>
> - <a href="https://velog.io/@shunny/Zero-Downtime%EC%9D%84-%EC%9C%84%ED%95%B4">Zero-Downtime을 위한 노력</a>

<br/>

<h3>[BE] 엘라스틱서치 적용기</h3>

<img width="788" alt="image" src="https://github.com/boostcampwm2023/web18_Dandi/assets/75190035/cb305f89-2609-4002-a33f-3c47cd85315d">

<li>저희 서비스의 목표 중 하나는 검색을 통해 사용자가 지난을 쉽게 돌아보게 하는 것입니다. 일기 검색을 위해 최대 10,000자의 일기 본문에 검색 기능을 적용해야했는데, MySQL만을 사용했을 때 Like문의 느린 조회 속도와 Full Text Index의 느린 삽입 속도를 우려해 다른 방식을 고민했습니다.</li>
<li>저희 팀은 역색인을 통한 빠른 검색을 지원하는 엘라스틱서치를 도입해 10초간 500명의 사용자가 검색을 사용하는 시나리오에서 요청 시간을 약 50% 수준으로 감소시킬 수 있었습니다.</li>

<br/>

> - <a href="https://www.notion.so/kimyoonju/2-Elasticsearch-Like-7bb08e2d93584255a95a9e075afdbfc0?pvs=4">검색 기능 개선기(2) - Elasticsearch에서 Like문 구현하기</a>
> - <a href="https://www.notion.so/kimyoonju/af665439840e4367b379c7a2d1b0125a?v=e112c574bbc74ee09e0ddf14a9893c2e&p=396733db362e4f20bdad9e03037f5da0&pm=s">검색 성능 개선기(3) - CDC를 못하면 redis로 라도…</a>

<br/>

<h3>📚 단디 개발 일지</h3>
<ul>
  <li>
    <a href="https://www.notion.so/kimyoonju/DB-cfaa6625be3842d6a41dd341bf777039?pvs=4">[Elasticsearch | 박효종] DB 데이터를 가져오는데 할게 왜이리 많죠?</a>
  </li>
  <li>
    <a href="https://velog.io/@shunny/Web-%EC%95%8C%EA%B3%A0-%EB%B3%B4%EB%A9%B4-%EC%A2%8B%EC%9D%80-%EB%86%88...-CORS">[CORS | 최수현] 알고보면 좋은 놈 CORS</a>
  </li>
  <li>
    <a href="https://velog.io/@gimewn/useRef-%EC%99%9C-%EC%93%B0%EB%8A%94-%EA%B1%B4%EA%B0%80%EC%9A%94">[React Portal | 김윤주] 리액트로 닥터스트레인지가 되는 법</a>
  </li>
  <li>
    <a href="https://velog.io/@dohun2/Emotion%EA%B3%BC-Tailwind-CSS">[Emotion & Tailwind CSS | 이도훈] Emotion과 Tailwind CSS</a>
  </li>
  <li>
    <a href="https://surpise.tistory.com/6">[Query Invalidation | 서종현] 이건 무효야! Query Invalidation</a>
  </li>
</ul>

<br/>
<h3>⚙️ 프로젝트 구조</h3>
<img src="https://github.com/boostcampwm2023/web18_Dandi/assets/75190035/fad709f3-3599-4dcc-83ad-51566a65e969" alt="테크 스택"/>
<br/>

<h3>🚀 인프라 구조</h3>
<img src="https://github.com/boostcampwm2023/web18_Dandi/assets/86141652/ed822c7f-7511-4604-9d95-f4ff2568e01b" alt="인프라 구조"/>
<br/>

<h2>👨‍👨‍👧‍👧 팀원</h2>

| <img src="https://github.com/boostcampwm2023/web18_Dandi/assets/86141652/2968ee75-3357-4378-ab32-202ad12bc76f" height=150 width=150 /> | <img src="https://github.com/boostcampwm2023/web18_Dandi/assets/86141652/0d3085f3-c588-4b21-98b1-bf6829793e0b" height=150 width=150 /> | <img src="https://github.com/boostcampwm2023/web18_Dandi/assets/86141652/4bd0fd8a-c94f-4175-9c1e-d75a73be5858" height=150 width=150 /> | <img src="https://github.com/boostcampwm2023/web18_Dandi/assets/86141652/06cb3533-d927-4ed1-bd8b-cddffe298e3f" height=150 width=150 /> | <img src="https://github.com/boostcampwm2023/web18_Dandi/assets/86141652/7b8fde40-bc13-4cf2-81ea-d538d69cdf82" height=150 width=150 /> |
| :------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                   BE                                                                   |                                                                   BE                                                                   |                                                                   FE                                                                   |                                                                   FE                                                                   |                                                                   FE                                                                   |
|                                                [박효종](https://github.com/HyoJongPark)                                                |                                                 [최수현](https://github.com/shunny822)                                                 |                                                  [김윤주](https://github.com/gimewn)                                                   |                                                  [서종현](https://github.com/surpise)                                                  |                                                  [이도훈](https://github.com/dohun2)                                                   |
