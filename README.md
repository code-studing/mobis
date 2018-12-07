# mobis 수업내용

## 저장소 생성
	git init <새로운 디렉토리 명>

## 스테이징 영역에 등록
	git add <file name>
	git add <파일이름>
## 버전 생성
	git commit -m "working name"
	git commit -m 'message'
## 버전 역사 보기
	git log --oneline -- branches --graph
	git log
	git log [--oneline] [--graph] [--branches] [-p]
## 버전 삭제
	git reset --hard <sh-1 id>

## 브랜치 생성 
	git branch <branch name>

## 다른 브랜치로 체크아웃
	git checkout <branch name>
 
## 브랜치 병합
	git merge <branch name>
## 버전 수정
	git revert
	git commit --amend <Commit_ID>
## 브랜치 생성 
	git branch <Branch_Name>
## 다른 브랜치로 체크아웃
	git checkout <branch 명>
	git merge <병합할 branch 명>
	git branch
## Cherry-pick
### teach cherry-pick
