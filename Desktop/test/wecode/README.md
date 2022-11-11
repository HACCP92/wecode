## Init
    
    git init
1. git init 명령어는 내 컴퓨터에서 생성한 디렉토리(폴더)를 Git에 등록하여 관리할 수 있도록 하는 명령어이다. 즉, 기존 디렉토리(폴더)를 로컬 저장소로 사용할 수 있도록 하는 것이다. 깃허브의 원격 저장소와 연결시키거나 새로운 저장소를 초기화하는 데 사용한다.

## Remote
    
    git remote add origin <http://korea/seoul.git> "예를 들어, 깃허브 계정이 korea 이고, 연결할 리포지토리 이름이 seoul이라면, 다음과 같이 명령어를 입력한다."
1. git remote add origin 명령어는 init 명령어를 통해 로컬 저장소로 변환한 디렉토리(폴더)를 Github에서 원격으로 관리할 수 있도록 연결하는 명령어이다.
2. Github에 디렉토리(폴더) 이름과 같은 원격 저장소를 생성하고, git remote add 명령어를 입력함으로 원격 저장소와 로컬 저장소가 연결이 완료된다.

## Status
    
    git status
1. git status는 로컬 리포지토리의 변경된 사항이 있는지 상태를 보여주는 명령어이다.

## Add

    git add .
    git add filename
1. git add 명령어는 git에 등록하여 commit을 할 수 있는 상태로 만든다. 즉, Untracked files를 Staging area로 추가하여 git이 관리할 수 있도록 한다.
2. git add . 명령어를 입력하면, 변경된 사항 모든 파일들을 등록한다.
3. 많은 파일을 변경했을 시 유용하지만, 불필요한 파일까지 모두 등록될 수 있기 때문에 주의해야 한다.

## Commit

    git commit -m '커밋 메시지'
1. git commit 명령어는 커밋이 가능한 파일들의 변경 사항을 저장하는 명령어이다. 즉, Staging area에 있는 변경된 파일들을 뜻한다.

## Push
    git push
    git push origin main(or master)
    git push origin branch
1. git push는 Local에서 변경, commit 된 사항을 원격 저장소에 업로드하는 명령어이다.
2. git commit -m '커밋 메시지' 명령어를 통해 커밋을 했다면, 이를 깃허브 원격 리포지토리(Remote Repository)에 등록을 요청해야 한다.

