# git 명령어
## git 시작하기
### git 프로젝트 초기화
- 현재 폴더 및 파일 및 하위 폴더 & 파일을 git으로 관리한다.
```bash
git init
```

## 작업 내역 commit 하기
### 프로젝트 add 
- 프로젝트를 staging area로 이동시킨다
```bash
git add .
```

### 프로젝트 commit
- 레포지토리(저장소)로 이동시킨다.
```bash
git commit -m "메세지"
```

### 깃 설정
```bash
git config user.name "Doyoung-David"

git config user.email "brightenway@outlook.com"

git branch -M main

git remote add origin https://github.com/Doyoung-David/practice.git
```

### 프로젝트 push
- 로컬 저장소에서 원격 저장소로 이동시킨다.
```bash
git push origin main
```

### 