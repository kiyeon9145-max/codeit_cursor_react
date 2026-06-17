# Cancel 

## reset
- 이미 완료된 커밋을 최신부터 순서대로 취소할 때 사용합니다.
- git reset --soft head~1
  - 커밋 직전으로 회귀
- git reset --mixed head~1
  - add 직전으로 회귀
- git reset --hard head~1
  - 코드 수정 직전으로 회귀
- git reset --hard [커밋아이디]

## revert
- 이미 완료된 커밋의 역변환이 되는 커밋을 생성할 때 사용합니다.
- git revert HEAD
- git revert [커밋아이디]
- 충돌
  - 직접 "수동으로" 충돌을 해결한다.
  - 직접 "수동으로" 스테이징 에어리어에 추가하합니다.
  - git revert --continue

## stash
- git stash
- git stash drop
- git stash pop