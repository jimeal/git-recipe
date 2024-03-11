## Stash
```bash
git stash push -m "메시지"
```
사라진 내역 확인
```bash
git stash list
```
![alt text](assets/image-stash.png)   

사라진 내역 자세히 확인
```bash
git stash show <stash아이디> -p
```

사라진 내역 가져오기
```bash
git stash apply <stash아이디> # stash 내역은 남기고 가져오기
git stash pop <stash아이디> # stash 내역 삭제하고 가져오기
```

삭제하기
```bash
git stash drop <stash아이디> # 가져오지 않고 삭제
git stash clear # stash 내역 모두 삭제
```