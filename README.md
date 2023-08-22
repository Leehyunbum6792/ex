내 정보 등록 사용자 와 이메일 등록 또는 변경
git config --global user. name "xxx1234"
git config --global user. email "xxx1234@naver.com" 

정보 삭제
git config -- unset --global user. name "xxx1234"
git config -- unset --global user. email "xxx1234@naver.com"

디렉토리 깃 저장소로 초기화
git init

파일 미리 생성
touch xxxx.txt 

파일 추가
git add xxxx.txt

메시지 함께 커밋
git commit  -m "파일 설명"

이력 줄줄이 확인
git log

현 상태 확인
git status
 
파일 수정 후 계속 커밋 가능

브렌치 생성
git branch dev

브렌치 리스트 확인
git branch --list

dev 
main

main에서  dev로 이동 ()

git switch dev

(dev)

git branch --list
*dev
main

바로 직전 브랜치 위치 
git switch -

  dev 에 있는 텍스트 파일 main 으로 옮기기  dev 
 git merge dev

dev  라는 브랜치를 삭제
git branch -d dev

브랜치 새로 만들고 이동 가능
git switch -c about

커밋 내용 간결하게
git log --oneline

그래프로 
git log --oneline --graph 

포크된 데이터 로컬에 불러오기 
git clone 주소