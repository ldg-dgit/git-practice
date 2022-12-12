# hello git

## git 명령어 요약

- clone : 원격 저장소 복사
- add : 스테이지 영역에 작업 파일 추가
- commit : 세이브, 스테이지 영역의 파일들을 가지고 커밋을 만들 수 있다
- push : 원격 저장소에 커밋을 업로드한다

### 변경사항 확인

git status

- 추적하지 않는(untracked) 파일: Git의 관리에 들어간 적 없는 파일

### 파일 담기

git add (file name)

### 모든 파일 담기

git add .

### 커밋

git commit

### vi 명령어

입력 시작 i 명령어 입력 모드에서 텍스트 입력 모드로 전환
입력 종료 ESC 텍스트 입력 모드에서 명령어 입력 모드로 전환
저장 없이 종료 :q
저장 없이 강제 종료 :q! 입력한 것이 있을 때 사용
저장하고 종료 :wq 입력한 것이 있을 때 사용
위로 스크롤 k git log등에서 내역이 길 때 사용
아래로 스크롤 j git log등에서 내역이 길 때 사용

### 커밋 메시지까지 함께 작성

git commit -m "(commit message)"

### 확인

git log

:q로 종료

### 세부적으로 확인

git diff

위로 스크롤 k git log등에서 내역이 길 때 사용
아래로 스크롤 j git log등에서 내역이 길 때 사용
끄기 :q :가 입력되어 있으므로 q만 눌러도 됨

### add와 commit 한꺼번에

git commit -am "(메시지)"

하지만 새로 추가된 파일이 없을 때만 가능하다
