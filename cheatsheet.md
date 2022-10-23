# 명령어 모음
---

### 환결설정 확인
`cat .git/config` 로컬 레포지토리로 이동 후 cat 명령어로 .git 파일의 config 정보를 확인 할 수 있음

### init

`git init` 깃 지역 저장소로 지정

### config
`git config user.name` 깃허브 username 지정  
`git config user.email` 깃허브에 등록한 이메일 계정 지정

### add
`git add [파일 명]` 컷밋에 포함 시킬 파일을 등록  
`git add --all` 현재 디렉토리에 add 되지 않은 모든 파일을 add 시킴

### status
`git status` 파일 상태 확인. tracked 되고 있는지, 커밋에 등록 되어 있는지 여부 등을 확인할 수 있음  

### commit
`git commit` 좀더 자세한 커밋 메시지를 작성할 수 있으며 이를 위한 에디터 화면이 나타남  
`git commit -m` -m 옵션을 사용하면 커밋의 메시지를 작성할 수 있음

### log
`git log` 현재 작업 중인 브랜치의 커밋 로그 확인. q 눌러서 다시 터미널로 진입할 수 있음  
`git log --graph` 가시적으로 커밋 로그의 흐름 파악 가능

### remote add
`git remote add [원격 저장소 이름] [원격 저장소 주소]` 지역 저장소에 원격 저장소를 알려주어 커밋을 원격 저장소에 반영시킬 수 있음. 주로 git remote add origin [원격 저장소 주소]로 사용됨

### push
`git push [원격 저장소 이름] [원격 저장소 브랜치 이름]` 원격 저장소 이름이 origin이고, 브랜치가 main이라고 할 때 git push origin main

### show
`git show` 최신 commit 정보 확인

### remote update
`git remote update` 원격 저장소의 최신 정보를 가지고 옴

### branch
`git branch` or `git branch -l` 지역 저장소의 브랜치 정보를 보여줌  
`git branch {new branch name}` 새로운 브랜치 생성
`git branch -v` 지역 저장소의 브랜치 정보를 최신 커밋 내역과 함께 보여줌  
`git branch -r` 원격 저장소의 브랜치 정보를 보여줌  
`git branch -a` 지역 저장소와 원격 저장소의 브랜치 정보 확인  
`git branch -d [branch name]` 브랜치 삭제  
`git branch -d [branch name]` 지역 저장소 브랜치 삭제
`git push origin -d [brnach name]` 원격 저장소의 브랜치 삭제

### checkout
`git checkout` 사용할 브랜치를 지정  
`git checkout -t [branch name]` 원격 저장소에서 생성한 브랜치를 지역 저장소의 작업 브랜치로 설정  
`git checkout -b` 브랜치를 생성하고 사용할 브랜치로 지정  