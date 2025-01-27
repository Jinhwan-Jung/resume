# 자주 사용하는 Git 명령어
- git add
  - git add .
  - git add 파일
- git branch
  - git branch -r
  - git branch 브랜치
  - git branch -d 브랜치
- git cherry-pick 해시 --> 커밋 하나를 지금 브랜치에 반영
- git clone 
  - git clone 저장소주소
  - git clone 저장소주소 .
- git commit
  - git commit -m "commit message"
  - git commit -am "commit message"
  - git commit --amend --> 마지막 커밋 수정
- git config
  - git config --global init.defaultBranch main
  - git config --global user.name "이름"
  - git config --global user.email "이메일"
  - git config --list
- git init
- git log
  - got log --all
  - got log --all --oneline
  - git log --stat
  - git log --oneline
  - git log --oneline --branches
  - git log --oneline --branches --graph
  - git log 브랜치1..브랜치2
- git merge
  - git merge 브랜치
- git push
  - git push origin master --> 로컬 저장소의 master를 원격 저장소인 origin에 푸시하라
  - git push -u origin master
- git pull
  - git pull origin master
- git remote
  - git remote add origin 주소
  - git remote -v
- git reset --> 옛날 커밋으로 브랜치 변경하기 
  - git reset HEAD^
  - git reset --hard
- git restore
  - git restore 파일
  - git restore --staged 파일
- git revert 해시 --> 커밋의 변경사항을 되돌리기
- git stash
  - git stash
  - git stash apply --> 가장 최근 스태시 적용
  - git stash apply stash@{x} --> 특정 스태시 x만 적용
  - git stash list --> 스태시 목록 확인
  - git stash push -m "메시지 내용"
- git status
 

