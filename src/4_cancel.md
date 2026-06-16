# Cancel

## reset
- 이미 완료된 커밋을 최신부터 순서대로 취소할 때 사용합니다.

- git reset --soft head~1 
  - 커밋 직전으로 회귀
- git reset --mixed head~2
  - add 직전으로 회귀
- git reset --hard head~1
  - 코드 수정 직전으로 회귀
- git reset --hard [커밋아이디]