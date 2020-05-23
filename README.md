# Study-practice

###1일차 npm init 사용하기

##### npm init
- npm (Node Packaged Manager) + init
- 노드 패키지 매니저를 초기화한다 
  = node 프로그램을 시작하는 명령어
- package.json 파일을 생성

### 2일차 package.json 생성 (기본 property 확인하기)
- name
- version
- description
- main
- scripts.test
- repository
- keywords
- author
- license

##### 오늘 사용한 git command
- git clone <git 경로>
  <git 경로>에 있는 프로젝트 히스토리 내려받기
- git pull origin master
  master 브랜치에 있는 내용 local에 업데이트
- git status
  git에 있는 파일의 상태 값 확인 (ex. 파일 생성, 파일 변경, 파일 삭제 등)
- git add <file name>
  특정 <file name>을 git staging에 올리기
  git add .
  변경사항이 있는 모든 관련 내용에 대한 내용을 staging에 올리기
- git commit -m <커밋내용>
  staging에 올렸던 변경사항을 확정적으로 변경
  (git add와의 차이점은 add의 내용은 이력 없이 unstaged가 가능하나 commit을 한 이후에는 기존 내용을 다시 변경하려 해도 이력에 남게 됨)
- git push origin master
  master branch에 해당 내용 업로드
