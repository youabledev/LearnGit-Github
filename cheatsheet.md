# 명령어 모음
---

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
`git commit -m` -m 옵션을 사용하면 커밋의 메시지를 작성할 수 있음

### log
`git log` 로그 확인. q 눌러서 다시 터미널로 진입할 수 있음

### remote add
`git remote add [원격 저장소 이름] [원격 저장소 주소]` 지역 저장소에 원격 저장소를 알려주어 커밋을 원격 저장소에 반영시킬 수 있음. 주로 git remote add origin [원격 저장소 주소]로 사용됨

### push
`git push [원격 저장소 이름] [원격 저장소 브랜치 이름]` 원격 저장소 이름이 origin이고, 브랜치가 main이라고 할 때 git push origin main