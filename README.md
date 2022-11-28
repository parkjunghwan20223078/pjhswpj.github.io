## jekyll 설치
윈도우 jekyll을 설치함. 
현재 디렉토리에 jekyll new . --force를 설치함.

## GitHub 
나의 github repository 원격 저장소를 만든 후에 내 컴퓨터에 로컬 저장소와 연결함.
토큰을 생성해서 나의 깃헙 블로그 사이트를 만듦.

## 블로그 내용
Visual Studio Code 를 이용하여 config.yml 파일내용을 수정함. 
post 폴더에 MongoDB정리 파일과 Avengers 파일을 생성해서 내용을 작성함. 
변경된 내용을 저장하고, git add . 으로 추가한 후 git commit -m "add: jekyll on repository"로 커밋을 남김.
마지막으로 git push origin main으로 푸쉬하여 원격 저장소에 저장함.
블로그 사이트에 들어간 후 post를 눌러서 추가한 파일들이 작성되어있는지 확인함.

## 테마 추가
원하는 테마의 깃허브 사이트를 들어가서 나의 로컬 저장소에 복사를 하여 파일들을 가져옴.
파일들을 원격 저장소로 푸쉬한 후 테마가 변경된것을 확인함.

## 댓글 기능 추가
disqus 홈페이지에 가입 한 후 사이트를 생성함.
config.yml파일에 key value를 추가하고, layout/post.html 파일에 Universal Code를 복사함.
comments : true로 지정. 
변경사항을 푸쉬한 후 블로그에 댓글 기능을 반영함.
사이트에 들어간 후 post로 들어 가서 각각의 내용들에 댓글 기능이 있는지 확인함. 
