# Tech Stack & Open Source Libraries
- DFM
  - app : Android Entry Point
  - core
    - data : Repository로 DataSource의 데이터 가져옴 
    - remote : Network 통신으로 GitHub Api 호출 
    - locale : Database에서 데이터 저장 및 가져옴
  - feature
    - list 
      - api로 받아온 github user 목록 데이터 보여주기
      - paging3 사용하여 무한 스크롤
      - mvi
    - detail 
      - feature:list의 클릭된 이미지를 보여주는 화면
      - mvi
- Compose
- MVI
  - Orbit
- Coroutine + Flow for asynchronous
- JetPack
  - Paging3
  - Compose
  - ViewModel
  - Hilt
- Retrofit2 + OkHttp3
- Clean Architecture
- KSP
