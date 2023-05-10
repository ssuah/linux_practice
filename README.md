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

**rm (remove)**<br>

파일이나 디렉토리를 삭제<br>
디렉토리를 삭제할때는 r 옵션을 주어야 한다.<br>
-f 옵션을 주면 사용자에게 삭제 여부를 묻지 않고 바로 삭제한다.<br>
디렉토리를 삭제할 때에는 하위 디렉토리까지 모두 삭제되므로 유의

**touch**<br>

파일이나 디렉토리의 최근 업데이트 일자를 현재 시간으로 변경한다<br>
최근 업데이트 일자는 ls -l 명령을 통해 확인할 수 있다<br>
파일이나 디렉토리가 존재하지 않으면 빈 파일을 만든다

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


**vi**
파일만들때, 파일 수정시에 씀 //   vi 파일명
