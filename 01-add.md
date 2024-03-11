## Git Setup하기
[설치하러가기](https://git-scm.com/)

## Add, Commit, Push, Pull
### 01. Add
먼저, 초기화 선언을 해준다
```bash
git init
# Initialized empty Git repository in D:/Git/.git/
```
폴더 리스트를 확인해 보면 .git (숨김처리된파일)이 생성되어 있다   
![alt text](assets/image.png)

새로운 파일을 생성한 후,
```bash
git add <file name> # 단일 파일만 staiging
git add . # 모든 파일 staiging
```
![alt text](assets/image-status.png)

### 02. Commit
```bash
git commit -m "메시지내용"
```
![alt text](assets/image-log.png)

### 03. Push
원격저장소 주소 등록 및 확인 삭제
```bash
git remote add origin 저장소주소.git  # 저장소 등록
git remote -v  # 저장소 확인
git remote rm origin  # 저장소 삭제
```
원격저장소로 푸시
```bash
git push -u origin main  
```

### 04. Pull


