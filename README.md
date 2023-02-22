### 레포지토리 생성 
- 이미 생성된 레포지토리가 있는지 확인할 때 사용하는 명령어는?
  - git status
- 레포지토리를 생성하는 명령어는?
  - git init
- 이력을 남기기 전에 무엇을 하는 습관을 들여야할까?
  - git status 명령어로 상태를 확인하는 습관이 필요함.

### 첫 커밋 (commit) 추가하기
- 워킹 디렉토리 (working directory), 스테이징 에어리어 (staging area), 레포지토리 (repository)는 각각 무엇을 의미하는가?
  - working directory: 실제 작업이 이루어지는 단계
  - staging area: 레포지토리에 커밋을 남기기 전에 확인하는 단계
  - repository: 변경사항이 기록되는 단계
- .gitignore 파일은 왜 필요한가?
  - 이력을 관리할 필요가 없거나 보안상 추가하면 안되는 파일/폴더들을 .gitignore에 작성해서 git이 해당 파일/폴더를 추적하지 않도록 지정하는 역할을 한다.
- 워킹 디렉토리에서 스테이징 에어리어로 이동시키는 명령어는 무엇인가?
  - git add [파일명]
- 스테이징 에어리어에 있는 내용들을 레포지토리에 저장하는 명령어는 무엇인가?
  - git commit -m "[커밋 메시지]"
- 커밋 이력들을 확인하는 명령어는 무엇인가?
  - git log --oneline
  - --online 옵션은 커밋 메시지 중심으로 간략하게 표시함.