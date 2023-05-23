# linux

**pwd (print working directory)**

현재 작업중인 디렉토리 정보 출력

**cd (change directory)**

경로 이동

**ls(list)**

디렉토리 목록 확인

**cp (copy)**<br>

파일 혹은 디렉토리를 복사<br>
디렉토리를 복사할때는 -r 옵션을 주어야함

**mkdir (make directory)**<br>

디렉토리 생성<br>
-p 옵션을 주면 하위 디렉토리까지 한 번에 생성 가능

**rm (remove)**<br> **rmdir(remove directory)**

파일이나 디렉토리를 삭제<br>
디렉토리를 삭제할때는 r 옵션을 주어야 한다.<br>
-f 옵션을 주면 사용자에게 삭제 여부를 묻지 않고 바로 삭제한다.<br>
디렉토리를 삭제할 때에는 하위 디렉토리까지 모두 삭제되므로 유의

**touch**<br>
유효한 빈 파일 작성하는 명령어 파일이나 디렉토리가 존재하지 않으면 빈 파일을 만든다 <br>
파일이나 디렉토리의 최근 업데이트 일자를 현재 시간으로 변경한다<br>
최근 업데이트 일자는 ls -l 명령을 통해 확인할 수 있다<br>

**cat**<br>
처음엔 여러파일 연결위해 고안됬으나, 파일내용 출력해주는데 사용.

**tail**

파일의 뒷부분을 보고싶은 줄 수만큼 보여준다<br>
옵션을 지정하지 않으면 파일 하위 10줄을 보여준다<br>
참고로 -F 옵션을 주고 실행하면,<br>
파일 내용을 화면에 계속 띄워주고 파일이 변하게되면 새로운 업데이트된 내용을 갱신해준다<br>
주로 실시간으로 내용이 추가되는 로그파일을 모니터링할때 유용하게 사용한다.

**date**
내가 지금 사용하는 서버의 시간을 알려줌<br>
ntp설정 맞출때 사용 
vi /etc/chrony.conf


**vi**<br>
파일만들때, 파일 수정시에 씀 //   vi 파일명

**mv**<br>
move의 줄임말<br>

현재 디렉토리에 있는 aaa.txt 파일을 디렉토리 내부의 new_folder 디렉토리로 이동
 mv (파일명)aaa.txt (디렉토리이름)new_folder

현재 디렉토리에 있는 test.txt 파일을 new_test.txt라는 파일로 이름 바꾸기
mv (원래파일명)test.txt (바꿀파일명)new_test.txt

/user/bbb 경로에서 test.txt 파일을 /user/aaa 디렉토리로 이동
ex) mv (파일이름)test.txt (경로)/user/aaa/new_folder

/user/aaa 경로 test.txt 파일을 /user/bbb 디렉토리에 new.txt로 바꾸어 이동
ex) mv (원래경로)/user/aaa/test.txt (새로운경로)/user/bbb/new.txt

**mount**<br>
sd카드나 usb연결시 mount명령으로 연결해야함.
<br><br><br><br>
 ## 시스템 조작을 위한 리눅스 명령어
<br><br> 
 **uname**<br>
 이름, 버전, 시스템 세부사항 같은 시스템 정보 얻기위한 기본 명령어
 
 **ps**<br>
 현재 시스템에서 실행주인 프로세스를 시각화할수 있는 명령어
 시스템 리소스 분석 시 사용되는 유연한 수단, 터미널로 시스템 프로세스 조작가능.<br>리눅스 모니터링 도구중 하나로 간주된다.
 
 <br>
 
 **kill**
 
 자원제한으로 인해 멈춘 프로세스 중지하는 강력한 방법.
 웬만하면 안하는게 좋다.
 <br>

**cal**<br>
 달력제공
 <br>

**history**
 터미널 세션 기록 확인
<br>

**clear**
기존 터미널 화면 지우기
<br>

**sort**<br>
정렬명령<br>

**chmod**<br>
파일이나 객체 액세스 권한 변경, 수정  //rwx<br>

**chown(change owner)**<br>
사용자가 파일 또는 디렉터리 소유권 변경
<br>
=>chmod 및 chown 명령은 모두 루트 권한 필요

**man** 
<br>매뉴얼
