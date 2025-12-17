# git branch 명령어 정리

- 브랜치 확인

  - `git branch -a`

- 브랜치 생성

  - `git branch {branch_name}`

- 브랜치 전환

  - `git switch {branch_name}`
    - `-c` : 브랜치 생성과 동시에 전환
  - `git checkout {branch_name}`
    - `-b` : 브랜치 생성과 동시에 전환

- 브랜치 삭제
  - `git branch -d {branch_name}`
