## 변경사항 없는 빈커밋 만들기

메시지 없이 커밋 (add 필수)
```bash
git commit --allow-empty-message -m ""
```

변경사항 없는 빈 커밋(add 필요없이 커밋 내용만)
```bash
git commit --allow-empty -m "변경사항없음"
```

메시지, 변경사항 없는 빈커밋
```bash
git commit --allow-empty --allow-empty-message -m ""
```