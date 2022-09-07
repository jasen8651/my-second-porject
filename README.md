#TIL

##리눅스 명령어
1. ls
    > list (목록)

2. cd 
     change directory(작업결로 병경)

3. rm
   remove(삭제)
4. mkdir 
    make directory(작업목록 생성)

5. rmdir
   remove directory(작업목록 삭제)
6. touch 
   파일 생성
7. cat
    파일 내용 출력
  
  ##git
  1. init
     git 생성
  2. add <파일명>
     staging area에 이동
  3. commit -m <메세지>
     Repositoy로 이동
  4. push <원격저장소><브렌치> 
     원격(github)으로 데이터 이동
  5. pull <원격저장소><브렌치>
     원격에서 로컬로 복사
  6. clone<원격저장소><브렌치>
     원격에서 로컬로 복제
  7. status 
     Staging area의 상태
  8. log 
     repositoy의 상태
  9. git commit --amenj
     바로 전 commit과 Staging area의 merge을 할떼
  10. git restore --staged <파일명>
     Staging area의 파일을 working Directory로 가져옴

     ![Git Sheat Sheet](asset/gitcheatsheet.jpg)
