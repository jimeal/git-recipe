## Amend
커밋 메시지 수정하기
```bash
git commit --amend
```
직전 커밋 메시지를 수정할수 있다
![alt text](image.png)

## Restore
unstaged상태로 되돌린다
```bash
git restore --staged .  # staged된 파일 전체
git restore --staged <파일명>  # staged된 특정파일만
```

## Reset
```bash
git reset --mixed <커밋아이디> # mixed 생략가능 변경사항은 남기고 unstaged상태로 되돌린다
git reset --soft <커밋아이디>  # 변경사항은 남기고 staged 상태로 되돌린다
git reset --hard <커밋아이디>  # 변경사항까지 되돌린다
```

