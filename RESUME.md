__Ironhee (이철희)__
- [Github](https://github.com/ironhee)
- [Blog](http://ironhee.github.io/)

[__번개장터__](https://www.bunjang.co.kr/)
----
2013년 8월 ~ 2014년 3월

- 업무:
  - 관리센터(Admin) 개발 및 운영 (기존 관리센터 리펙토링 및 재구현)
  - 개발광고센터 개발 (기존 관리센터 리펙토링 및 재구현)
  - 간단한 퍼블리싱
  - [flask](https://github.com/mitsuhiko/flask) 를 이용하여 백엔드 개발
  - [jquery](https://github.com/jquery/jquery) + [bootstrap](https://github.com/twbs/bootstrap) + [DataTables](https://github.com/DataTables/DataTables) 등을 이용하여 프론트엔드 개발.
  - 본 서버로 [Request](https://github.com/kennethreitz/requests) 를 이용하여 API 호출하도록 구현.
  - Git 으로 소스관리. http://mobicon.tistory.com/49 git branch 관리 전략을 사용

[__Ediket__](https://ediket.com/)
---
2014년 4월 ~ 현재

- 업무 (프론트엔드):
  - Vanilla javascript -> [Backbone](https://github.com/jashkenas/backbone): MVC 패턴 모듈화 및 리팩토링
  - [RequireJS](https://github.com/jrburke/requirejs) 이용하여 소스 모듈화 및 배포.
  - Vanilla CSS -> [LESS](https://github.com/less/less.js) 이용하여 리팩토링
  - [Grunt](https://github.com/gruntjs/grunt) 이용하여 빌드 + 테스트 등의 태스크 자동화
  - Backbone View -> [Marionette](https://github.com/marionettejs/backbone.marionette): View 레이어 변경 및 리펙토링.
  - Edikit 제작 및 유지보수 (HTML track change wysiwyg 에디터)
    - Gulp + Mocha + Karma 이용하여 빌드 + 테스트 자동화
    - 독립 node package 로 개발 (private package)
    - ediket 에서 첨삭을 할 때 사용함.
  - Grunt -> [Gulp](https://github.com/gulpjs/gulp): 태스크 관리 툴 변경.
  - RequireJS -> [Browserify](https://github.com/substack/node-browserify): 소스 모듈화 및 배포방식 변경.
  - Marionette -> [React](https://github.com/facebook/react): View 로직 변경 및 리펙토링.
  - Vanilla HTML -> [Bootstrap](https://github.com/twbs/bootstrap): Bootstrap 을 커스터마이징 하여 사용하도록 기존의 프론트엔드  - 페이지 재구현.
  - Backbone Model 및 Controller -> [Reflux](https://github.com/reflux/refluxjs): Model 및 Controller 부분 설계 수정.
  - Browserify -> [Webpack](https://github.com/webpack/webpack): 소스 모듈화 방식 변경.
  - [Babel](https://github.com/babel/babel) 이용하여 ES6 적용.
  - 프론트엔드 repository 를 Backend에서 따로 분리.
    - [Nunjucks](https://github.com/mozilla/nunjucks) 이용하여 프론트엔드에서 Template 빌드하도록 변경
    - Git repository 분리. (ediket -> ediket_front + ediket_backend)
    - 모든 backend 와의 통신을 REST API 이용하도록 변경.
    - backend에서 처리하던 다국어 지원 로직 프론트에서 처리하도록 변경
      - 프론트엔드에서 json으로 Locale 관리.
      - [React-Intl](https://github.com/yahoo/react-intl) 이용하도록 변경.
      - Nunjucks 이용하여 언어별로 template 빌드.
  - HTTP API -> [jsonapi](http://jsonapi.org/): 기존의 api를 jsonapi 스펙을 따르도록 변경. 주로 프론트엔드 Model 단을 다룸.
  - [jsonapi.js](https://github.com/json-api/json-api) 제작 및 유지보수

[__애드투페이퍼__](http://add2paper.com/about/)
---
2015년 10월 (입사 확정) ~ 

- 업무 (프론트엔드):
  - Android
    - Java -> [Golang](https://golang.org/) 일부 포팅 
  - iOS
    - ObjectiveC -> [Swift](https://developer.apple.com/swift/) 포팅
  - Web
    - [jquery](https://github.com/jquery/jquery) -> [React](https://github.com/facebook/react): View 로직 변경 및 리펙토링. 

__개인 프로젝트__
---

- [step-by-step-frontend](https://github.com/ironhee/step-by-step-frontend): 프론트엔드 개발에 익숙하지 않는 개발자들이 쉽게 프론트엔드 최신 기술들을 하나하나씩 적용해가며 웹 사이트를 조금씩 성장시킬 수 있도록 만든 프로젝트.
- [jsonapi.js](https://github.com/ironhee/jsonapi.js): [jsonapi](http://jsonapi.org/) 라이브러리
- [beerr](https://github.com/ironhee/beerr)(개발중): Github Page + Travis + FIrebase 를 이용하여, 별도의 백엔드 없이 배포 및 데이터 관리가 가능하도록 만든 맥주 평가 사이트.
