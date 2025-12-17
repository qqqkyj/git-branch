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

- 브랜치 로그 확인 (option : --graph)

  - `git log --oneline`

- 원격 저장소 추가

  - `git remote add origin {git_address}`

- 원격 저장소에 파일 올리기
  - `git push origin {branch_name}`
