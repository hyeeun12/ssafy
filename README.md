git log --oneline (커밋 로그 확인)
git status (git 현재 상태 확인)
git add <file이름>: 변경사항을 stage area로 이동


Untracked files: < 확인되지 않은 파일
add 하고나면 확인됨.

git commit -m "커밋 메시지"   -m:메시지
-> who you are?
git config --global user.email "ha7988@naver.com"
git config --global user.name "박혜은"
깃 시스템에다 내가 누군지 이야기한 것. 이제 깃 커밋이 됨
git commit -m "커밋 메시지"

git add . : 현재 경로 하위에 있는 파일들 모두 stage area로 전송

<vi 편집모드 띄워서 편집 후 나가는 방법>
git commit --amend: 텍스트 편집 화면이 뜸
i눌러서 인서트 띄우면 편집모드가 됨/명령모드로:ESC
나갈때: ESC 연타 -> 젤밑칸에 : ->
:q!(변경사항 저장안하고 나가기)
:wq (저장하고 나가기) 
:q (나가기)

