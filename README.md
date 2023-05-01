# github_connext

## 🎠 [깃설치](https://git-scm.com/download/win)

     git을 통해서 github과 연결할 수 있다.      

   -깃을 올려야 할 폴더에 가서 shift + 우클릭하여 PowersShell창 열기
      
      git init 
      
      
   - .git 폴더가 생성됨   
---------------------------------

## 🎠 깃 설치 후 Git bash 열기

![image](https://user-images.githubusercontent.com/129017040/235417950-20f3d515-2abc-4341-80ea-299a9318a3ec.png)

![image](https://user-images.githubusercontent.com/129017040/235418343-beb6fb8d-9ec2-4d21-9d27-b9a586885fdb.png)

*유저이름설정하기

      git config --global user.name "jungmin"
      
*유저 이메일 설정하기(반드시 github에 가입했던 이메일주소와 동일해야한다.)

      git config --global user.email "jungmin3636@naver.com"
      
* 내 정보 확인하기

      git config --list 
      
      
## ⬆️ 위의 연결은 해당 컴퓨터에서 한번만 실행하면 됨.
---------------------------------------------------------

# github에 코드 업로드하기 

   * 초기화
       git init
   *추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미)
      git add .
   * 히스토리 만들기(-m 은 메세지를 의미함 ""안에는 히스토리이름을 적음
      git commit  -m "first commit"
      
   * github의 repository를 만들고 그 주소와 연결하기 ⬇️
   
   
          git remote add origin https://github.com/yangjungmin/css_flex.git   
          
   * 연결이 잘 되었는지 확인하기(사용안해도 됨)

             git remote -v      
             
   * github에 올리기
            git push origin master
            
## 수정하여 다시 업로드할 때

1.기본의 코드를 다운받는 행위를 해야한다

    git pull origin aster
    
2. 다시 push 해야한다

   git push origin master
       


