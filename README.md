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
  
  
 #####2020-05-27 내용 추가
 1. npm install / npm -g install / npm --save-dev install 의 차이
 npm install : node_module 폴더에 설치만 하고 끝
 npm -g install : npm install + package.json의 dependencies에 해당 패키지 저장 (전역으로 저장)
 npm --save-dev install : npm install + package.json의 devDependencies에 해당 패키지 저장

2. npm init시 생성되는 package.json의 설정값 의미 (추가)
- main : 프로젝트 시작시 실행될 파일 지정
- script : fullname으로 사용하면 피곤할 명령어를 축약해서 쓸수 있게 해주는 존재
- keyword : npmjs에서 검색하면 라벨처럼 붙어나오는 그녀석

3. Vue-cli
- npmjs에서 검색하지 말고 정식서비스를 설치할거면 npm install -g @vue/cli 이 명령어를 치자
- Vue-cli는 작업자 기준에서 좀더 편리하게 작업하게 환경 조성을 해주는 고마운 존재
- vue create [프로젝트명] 을 하면 해당 프로젝트 명으로 내가 설정한 세팅값으로 폴더를 생성해서 만들어준다.

4. Webpack
- 클로이 강사의 설명을 듣고 집에와 책상앞에 앉으니 기억이 나지 않는군요.
- 열심히 공부하고 채워나가도록 합시다.
