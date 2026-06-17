# Github

## 정의
- git으로 관리하는 프로젝트를 저장하고 공유할 수 있는 클라우드 서비스

## 인증
- 아이디, 토큰
- 인증 등록
  - Mac: git config --global credential.helper osxkeychain
  - 윈도우: 자동으로 된다.(Git Credential Manager)

## 로컬 리포지토리와 원격 리포지토리의 연결
- git remote add [원격리포지토리별명] [원격리포지토리주소]
- git remote -v: 등록된 모든 원격리포지토리의 주소와 별명을 보여줍니다.

## 업로드
- git push [원격리포지토리별명] [업로드하고싶은브랜치이름]
  - git push origin master
  - 로컬 리포지토리에 트래킹 브랜치 origin/master가 리모트브랜치와 동기화됩니다.

## 다운로드
- git fetch [원격리포지토리별명] [다운로드하고싶은브랜치이름]
  - git fetch origin amster
  - 로컬 리포지토리에 origin/master 이름을 가진 트래킹 브랜치가 생성됩니다.

  - git clone [리모트리포지토리주소]
   - 프로젝트 폴더를 생성한다.
   - git init
   -  git remote add origin [리모트리포지토리주소]
   -  git fetch: 리모트 리포지토리에 있는 모든 브랜치를 전부 다운받아서 트래킹 브랜치를 생성합니다.
    - origin/master
  - git checkout -t origin/master
   - grigin/master와 동일한 master브랜치를 생성하고 master브랜치에 체크아웃됩니다.
  - master 브랜치에서 작업을 진행합니다.