# 버전관리
1. workspace
  내 작업 공간
2. staging
  git add ""
  커밋 될 작업내용들을 모아두는 곳 (후보군 모음)
3. local git repository
  git commit -m ""
  여기서 버전이 부여됨
  아직 작업 내용이 나의 로컬 환경에만 머무르고 있음
4. remote repository 
  git push orgin main
  원격 환경에 내 작업 내용이 올라감
  팀 작업 공간으로, 내가 팀원들의 작업을 다운로드 받기도 함 (clone, pull)

# git fetch
  git fetch는 remote repository 에서 local repository 까지만 도달
  원격환경에 있는 업데이트된 작업 내용이 내 로컬 환경에 다운로드 되지는 않은 상태
  
