# git 명령어

- `git init`
    - 현재 폴더에 새로운 `.git` 폴더를 생성

- `git add <file, folder name>`
    - `working directory`에서 `staging area`로 추가
    - 일반적으로 모든 파일, 폴더를 추가하기 위해 아래의 코드를 사용
    - `git add .`

- `git commit -m 'message'`

## 설정 

- `git config`
    - git 설정을 하는 명령어
    - 일반적으로 `--global` 옵션으로 최초 한번만 실행
    - `git config --global user.email 'your@email.com'`
    - `git config --global user.name 'yourname'`

- `git commit -m 'message'`
    - `staging area` 에 올라간 파일들의 스냅샷을 찍어 `git directory` 에 저장