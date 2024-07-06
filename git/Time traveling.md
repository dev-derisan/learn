# Time traveling

- 이전 커밋 확인하기

```
git checkout <commit-hash>

git checkout 9518e20
git checkout HEAD~1
```

- Detached HEAD  재연결하기

```
git switch <branch-name>
git switch -
```

- 변경사항 폐기하기

```
git checkout HEAD <file>
git checkout -- <file>
git restore <file-name>
git restore --source HEAD~1 <file-name>
```

- 스테이징 취소하기

```
git restore --staged <file-name>
```

- 커밋 취소하기

```
git reset <commit-hash> // mixed mode
git reset --hard <commit-hash 
git revert <commit-hash>
```

reset은 커밋 자체를 삭제해 버리고,  revert는 커밋 이력을 남겨둔다. 협업 중이라면 revert 써야한다.