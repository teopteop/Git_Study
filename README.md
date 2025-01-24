###📃 깃 사용법 익히기  
git init > 깃으로 관리할 폴더를 초기화  
git config --global user.name "이름"​  
git config --global user.email "이메일"  
//초기화시 이름 이메일 따로 등록  
  
관리 폴더 아래에 버전 관리할 파일 생성 ex) abc.txt  
git status  현재 작업 중인 Git 리포지토리의 상태확인  
git add . > 모든파일 / git add 파일명 / 해당파일 추가  
git commit -m "내용"  
git log 리포지터리 커밋 기록 확인  
  
<되돌리기>  
git reset --옵션 해시코드(돌아가고자 하는 해시코드)  
soft > 커밋 이전으로 돌아감 > 커밋 로그 수정할 경우  
mixed > add 이전으로(수정 파일만 있음) > 작업 내용 다시변경  
hard  > 전부 리셋(인덱스, 히스토리, 수정작업) >원격에 푸시할때 강제 푸시  
   
로컬에 내 원격 알려주기  
git remote add origin 저장소 주소  
  
git ls-remote 연결확인  
  
커밋된 내용 업로드(파일 업로드와 병행)  
git push origin master   로컬과 연동  
git pull origin master 깃에서 다운  
  
git clone 저장소주소 .(주소다음 공백 하나하고 . 까지 붙여야 해당 디렉토리에 바로 생성) => 초기화 연결 다운로드를 한꺼번에  
  
원격지와 내 현재 작업이 일치하는지 항상 확인  
-> 작업이 끝날때마다 항상 push 하는것을 잊지말기  😊
