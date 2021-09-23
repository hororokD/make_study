# make_study
내가 만드는 공부
======================================================
개발공부를 시작하고 나중에 회사에 지원할 때 좋은 이력서를 위해
어떤걸 개발해야할지 생각하니 다른사람들이 하는 다양한 기술를 활용한 todo앱 등을 개발해야하나
고민하던중 그냥 내가 만들고 싶은걸 만들자는 생각에
이전에 공무원 시험공부 중 이런 앱이 있었으면 좋겠다 싶은 것을 만들기로 함
======================================================
메뉴
영어단어
영어
-문법
-어휘
-기출
국어
-한자
-한자성어
-기출
한국사
-기출
내가 만드는 문제
시간관리
======================================================
-> 이 앱을 사용하는 사람들은 공시생으로 모바일환경에서 암기, 오답노트, 문제풀이  등 암기를 위해 사용하기 때문에
-> 이에 적합한 환경을 검색 
-> 한번 사용하고 이후 빠른 환경을 제공하는 CSR(Client Side Rendering)으로 하기로 결정
-> 앱의 content들은 구성이 비슷하기에 SPA으로 결정
-> 이와 관련된 view libary에 React가 있고 이에 평소에 관심이 있어 결정
-> React로 개발은 처음이기에 검색과 '리액트 교과서'라는 책을 읽고 개발준비
-> 개발에대해 흐름을 찾아보니  React는 view libary 이니까 정적이라고 한다
-> 나중에 문제들을 저장하고 불러오는데 네트워킹 기능(api 데이터 주고 받기)이 필요하다 생각 
==============>
-> 데이터를 주고받는게 자주 발생하지 않을것 같다
-> 나중에 배포는 aws를 생각
-> S3 - 정적 웹 구성, ec2 - 필요한 데이터 요청, RDS-> mariaDB로 DB구성 이 적합하다고 판단
-> 프론트 - React, 백 - 스프링 부트 
================>
https://happyer16.tistory.com/entry/%EC%84%9C%EB%B2%84-%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%9D%98-SPA-%EC%A0%81%EC%9A%A9%EA%B8%B0-NHN-FORWARD

https://m.blog.naver.com/rudnfskf2/222150927977

====================================================
프론트 : react
백엔드 : spring boot
DB : mariaDB
react 와 spring boot 사용하는데에 있어 
1.연계가 도움이 되는지 
2.어떻게 이루어지는지
/structure.png
==========================================
백엔드를 꼭 spring 을 써야할까?
지금 프로젝트 특성상 복잡한 구조가 될 것같지 않아 굳이 spring을 쓰지 않아도 될 것 같다
조금 더 확인해보자
https://www.youtube.com/watch?v=A6J74xLWqYg&ab_channel=%EC%9A%B0%EC%95%84%ED%95%9CTech  // 프론트엔드 성능 측정


====================================
react 프로젝트 만들기
crud 구현(db 연계)

 