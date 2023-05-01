# github_connect

##1.{깃설치}https://git-scm.com/download/win)

git을 통해서 github과 연결 할수 있다
올려야함에 폴더에 가서 shift+ 우클릭하여  Powershell창열기

git init

git 폴더가 생성됨

git을 통해서 github과 연결 


---------------------------------------------------

##2.깃설치후 git bash 열기

유저이름설정

        git config --global user.name "your_name"
        
유저 이메일 설정하기 (반드시 github에 가입했던 이메일주소와 동일해야한다

$ gir config --global user.email "drg1230@naver.com"
bash: gir: command not found

내정보 확인 하기
gir config --list

위의 연결은 확인 컴퓨터에서 한번에 설정하면 됩
---------------------------------------------------

github에 코드 업로드하기

초기화

git init

추가할 파일(폴더안에 내용을 모두 틀림)

git add

히스토리 만들기 (-m을 메세지를 의미를 ""안에는 히스토리이름을 적용)

git commin -m  "작업올리기"


github의 repository를 만들고 그 주소의 연결하기
                git remote add origin https://github.com/heoyounggyu/css_flex.git
                
 연결이 잘 되는었는지 확인 하기
 
 git remote v
          
 githhub의 붙이기
               git push origh master
