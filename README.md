Git의 구조는:
1. `git commit` → 제목/설명 작성
2. `git push` → 그 커밋들을 서버에 업로드
```bash
git commit -m "Initial commit"
```
여기의 `"Initial commit"` 이 커밋 제목입니다.
더 자세히 쓰려면:
```bash
git commit
```
만 입력하면 에디터가 열리고:
```text
Add Spring Boot initial project structure

- Setup Gradle project
- Add controller classes
- Add Mustache templates
- Configure repository structure
```
정리하면:
* `commit` = 기록 작성
* `push` = 업로드

git status
git add .
git commit -m "설명"
git push
