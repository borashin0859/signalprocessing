## google colab 사용법

#### edit- notebook setting에서  gpu
 gpu 사용하면 100배 정도 빨라짐
 
#### drivem github, local 백업 및 공유
 로컬에서 작업한 파일을 github에 push해야하는 경우, colaboratory에서는 **save a copy in github** 버튼만 누르면 repository에 push해준다.
 revision history에는 내가 지금까지 변경한 소스코드의 history도 보여준다.
 
#### github에 커밋된 notebook을 colab에서 열고 실행

예를 들어, 
  https://github.com/borashin0859/study/googlecolab.md
  를 아래와 같이 바꾸면 colab에서 열 수 있음
  httpsL//colab.research.google.com/github/borashin0859/study/googlecolab.md
 
#### kaggle data 와 같이 대용량 데이터 분석할 경우
  Google Drive에 미리 업로드 해놓은 Sample data를 load해서 트레이닝 하는 방법
  * sample data를 drive 상의 임의의 폴더를 만들어 업로드시키기
  ![sample data](https://teddylee777.github.io/images/2018-09-07/image-20180907020018519.png)
  * google drive api를 활용하기 위해서는   PyDrive package를 인스톨한다
      !pip install -U -q PyDrive
