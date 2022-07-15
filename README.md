## 테스트 중 사용한 git 명령어 정리

1. git init
   - git 초기화 : 현재 디렉토리에서 git을 사용할 수 있도록 설정
2. git add .
   - 커밋을 남기기 전 임시저장 
   - 장바구니에 담아놓는 너낌
3. git commit
   - 간단한 커밋메세지와 함께 남기려면 `git commit -m "커밋메세지"`
   - 디테일하게 남기려면 그대로 `git commit` 후 vim화면에서 커밋 남기기
4. git remote add origin "repository_url"
   - gitHub의 repository와 연결
   - 연결 후 확인하려면 `git remote -v`
5. git push origin "branch_name"
   - 연결된 remote repository로 git push

