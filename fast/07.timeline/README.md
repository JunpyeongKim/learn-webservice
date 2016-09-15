7. 실전 "웹 프로젝트 구축에서 서비스까지"
================================

# 7.1 예제 프로젝트 구축에 대해
- 가벼운 SNS
    - HTML 페이지 : 5개
        - 각 페이지는 기술 세트 중 하나 구현 
    - Django Admin : 1개
    

# 7.2 예제 프로젝트를 시작하기 전에, 실전 예제
- 프로젝트 이름 : ClientExample
- Bootstrap 다운로드
- example.html
    - 기본 틀잡기
        - bootstrap : css, js
        - jquery & jqueryui : js, css
    - 배경
        - background-color
    - 내비게이션 메뉴
        - class
            - nav
            - navbar navbar-inverse navbar-fixed-top
            - container
            - brand (bootstrap2) --> navbar-brand (bootstrap3)
            - navbar-inner (bootstrap2) --> container (bootstrap3)
            - nav-collapse (bootstarp2) --> navbar-collapse (bootstrap3)
            - btn btn-navbar
            - icon-bar
        - bootsra
    - hero-unit
        - Bootstrap 이 제공하는 메인을 구성가ㅡㅇ한 컴포넌트
        - container : 적당한 공백 적용
    - SPAN4 - 3 Column
        - span 뒤에 숫자를 이용해 각각의 크기를 갖는 영역 컴포넌트를 생성
        - .row-fluid div[class*="span"]
            - row-fluid 클래스 다음에 나오는 div 영역 속성 중에 클래스 이름이 span 이 들어가는 속성 지정
        - 라운딩 처리 : 각 브라우저에서 지원하는 속성이 다르므로
    - SPAN6 - 2 Column
        - class
            - progress progress-danger progress-striped
            - active
            - bar
            - tabbable
            - tab-content
    - SPAN12 - 1 Column
        - class
            - alert alert-error fade in close
    - 스크립트
        - toggle() 기능이 잘못 구현되어 있다 --> 변경 필요
    
            
        

7.3 "타임라인 서비스"의 개발

7.4 "타임라인 서비스"의 마지막 단계 클라우드 서비스
