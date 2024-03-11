## Git Setup하기
[설치하러가기](https://git-scm.com/)

## Git Config
초기설정
```bash
git config --global user.name <이름>
git config --global user.email <이메일주소>
git config --global core.editor "code --wait" # vscode
```
설정후 확인
```bash
git config --list
```
vscode 에디터에서
```bash
git config --global -e
```
.gitconfig파일 실행
```text
[core]
	editor = 
	autocrlf = true
[user]
	name = 
	email = 
[init]
	defaultBranch = main
```

git bash에서 vscode열기
```bash
code .  # 새창에서 열림
code . -r  # 사용중인 에디터에서 열림
```