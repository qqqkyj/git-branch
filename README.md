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

- 커밋 히스토리 확인 (option : --graph)

  - `git log --oneline --graph`
  - `--oneline` : 간소화 출력
  - `--graph` : 그래프 형태로 출력

- 원격 저장소 추가

  - `git remote add origin {git_address}`

- 원격 저장소에 파일 올리기

  - `git push origin {branch_name}`

- 병합

  - `git merge {target_branch}`
    - 현재 내가 있는 브랜치에 타겟 브랜치를 가져와서 병합
