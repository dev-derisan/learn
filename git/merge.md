# merge

- merge workflow

```
git switch <merge가 수행되는 브랜치>
git merge <merge 할 브랜치>
```

- Three kinds of merge

```
1. Fast-foward merge(FF merge)
	- 병합되려는 브랜치가 단순히 병합하는 브랜치보다 앞서 있을 경우에 수행됨

2. No-conflict merge
  - 자동으로 merge commit 생성
  - 공통 조상 커밋을 기준으로 같은 부분이 변경되지 않았을 경우에 수행됨

3. conflict merge
  - 공통 조상 커밋을 기준으로 같은 부분이 변경되었을 경우에 수행됨.
  - conflict를 해결한 후 add, commit 순으로 진행
```
