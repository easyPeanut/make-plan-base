# temporary-base


## easyPeanut 프로젝트 구성

1. Front-end
  
2. Back-end

3. base : 프로젝트 진행 간, 약속했던 내용들 기술
  
  
  
  
## easyPeanut 규칙
### 1. Github Issue로 책임 할당
  
    - 지원이 필요한 내용들은 담당자의 레포지토리에서 이슈로 요청
    - ex) 백엔드 서비스 개발 후, 관련 화면이 필요하면 프론트엔드 레포지토리에서 이슈 생성하여 할당


### 2. Git Commit 양식

| 종류     | Description                                         |
|----------|----------------------------------------------------|
| feat     | 기능 추가                                           |
| refactor | 리팩토링                                            |
| chore    | 소스 코드가 아닌 사소한 수정 사항 (파일 삭제, 추가 등) |
| fix      | 버그 픽스                                           |
| docs     | 문서 작업                                           |
| build    | 빌드 관련 수정 사항                                  |
| style    | 디자인 스타일링                                      |
| test     | 테스트 코드 관련 수정 사항                            |


### 3. Branch 전략
master : version milestone과 같이 원했던 기능들이 추가가 완료된 시점에 반영
dev    : 추가된 기능들에 대한 현상 유지 branch
feat   : 필요 기능 추가 시 dev로 부터 분리. test등 검증 완료된 시점에 dev로 merge

