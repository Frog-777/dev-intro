# 개발 입문 스터디 4주차 배운 내용 정리

## github flow
git flow의 라이벌 github flow는 단순하고 가벼운 브랜치 전략이다. 
**git flow vs github fow**
**git flow**
복잡, 브랜치 수 많음, 배포 주기-정해진 릴리즈, 대형 프로젝트에 적합
**github flow**
단순, 브랜치 수 적음, 수시로 배포, 소규모/빠른 개발

* main 브랜치는 항상 배포 가능한 상태여야 한다

github flow의 배포 흐름 정리
(1) main에서 브랜치 생성 
(2) 기능 개발 & 커밋
(3) PR(Pull Request) 올리기
(4) 코드 리뷰
(5) main에 merge
(6) 배포

## commit convention
(1) feat : 새로운 기능 추가
(2) fix : 버그 수정
(3) docs : 문서 수정
(4) style : 코드 스타일 변경
(5) refactor : 코드 리펙토링
(6) test : 테스트 코드 추가/수정
(7) chore : 기타 잡일

나쁜 예시) commit -m "수정"
좋은 예시) commit -m "feat : 로그인 기능 구현"

## PR 템플릿
