
login
사용자 인증과정

passwd
패스워드 변경

du
하드 사용량 체크
#du
자신의 하드공간
#du -s directory_name
특정 디렉토리의 사용량

cp
파일 복사
#cp index.html index.old
index.html 파일을 index.old 라는 이름으로 복사

mv
파일이름, 위치 변경
#mv index.htm index.html
index.htm 파일을 index.html 로 이름 변경

mkdir
디렉토리 생성
#mkdir download
download 디렉토리 생성

rm
파일 삭제
#rm test.html
test.html 파일 삭제
#rm -r <디렉토리>
디렉토리 전체를 삭제
#rm -i a.*
a로 시작하는 모든 파일을 일일이 삭제할 것인지 확인하면서 삭제

rmdir
디렉토리 삭제
# rmdir cdi-bin
cgi-bin 디렉토리 삭제

whereis
소스, 실행파일, 메뉴얼 등의 위치를 알려줌
# whereis perl
perl의 위치를 알려준다

vi
새로운 파일을 만드는 방법
# vi newfile
vi편집기 상태로 들어감
touch
#touch newfile
빈 파일만 생성됨
cat
#cat > newfile
vi 편집기 상태로 들어감, 문서 작성 후 Ctrl+D로 빠져나옴

head -n
파일 내용만 보기
#head -n file
n줄 만큼 위에서부터
tail -n
#tail -n file
n줄 만큼 아래에서부터

top
메모리 상태 보여주기

less
텍스트 팡리 보기

ps
현재 작동중인 모든 프로세스를 보여줌

kill
프로세스 종료
#kill x
x는 ps명령으로 말게 된 PID

lilo
부트 디스크를 만듦
