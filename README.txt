1. www.github.com 가입
2. Create a new repository 생성
3. git 프로그램 설치 (구글링)
4. Git Bash 에서 환경설정
    > git config --global user.name "Yeong-Mun Cha"
    > git config --global user.email "ymcha1028@gamil.com"
    > git config --list (로 설정 확인가능. 이름과 이메일만 잘 들어갔는지 확인하면 됨)
5. 프로젝트 업로드 방법
    1) Terminal 열고, 해당 프로젝트로 이동
    2) 2.에서 나온 Quick setup을 참고하면 됨
    3) git init (맨 처음 프로젝트를 올릴 때 해주는 것 -> 해당폴더에 .git 폴더 생성됨)
    4) git add . (아무 반응도 일어나지 않음)
    5) git status (필수아님. 상태 확인용)
    6) git commit -m "first commit" (히스토리를 만드는 용)
    7) git remote add origin https://github.com/ymcha1028/github.git (이 히스토리로 보내는 기능. 내 PC의 Repository와 Githus 간 연결고리)
    8) git remote -v (연결고리 확인용)
    9) git push origin master
    10) git add . (업데이트 시)