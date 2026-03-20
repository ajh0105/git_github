# git
로컬 저장소

<br>

## | 1.1 로컬 저장소 초기화
```bash
git init
```

<br>

## | 1.2 로컬 저장소에 원격 저장소 지정
```bash
git remote add origin 레포지토리(원격저장소) 주소.git
```

<br><br>

## | 1.3 브랜치 통합
```bash
git branch -M 브랜치명
```

<br>

## | 1.4 토큰 등록
1. `.git/config` 파일 메모장 실행
2. [remote "origin"] 항목의 url 값에 토큰과 계정을 추가하여 내용 수정
   1. url = https://본인계정:토큰@github.com/깃허브 레포지토리 주소.git
   

<br>

## | 1.5 작업 목록에 추가
```bash
git add 작업파일명 (작업 파일 수동 입력)
git add . (현재 폴더의 모든 것)
```

<br>

## | 1.6 커밋
```bash
git commit -m "내용 입력"
```

<br>

## | 1.7 깃허브에 배포(푸쉬)
```bash
git push -u origin main
```

<br><br>

# 2. git 작업

## | 2.1 git 복제(clone)
```bash
git clone 레포지토리 주소
```
+ 클론으로 가져오기 후 config에 본인 토큰 주입
```bash
git branch -M dev
```
+ 기존 레포지토리에 branch로 새로운 내용 추가하려면 branch 변경
+ 예시에선 dev라는 branch를 사용함
```bash
git push -u origin dev
```
+ 클론에서 가져온 항목을 기존 팀 리더 main 브랜치 외에 추가 dev 브랜치에 업로드

<br>

## | 2.2 git 복제(fork)

<br><br>

# github
원격 저장소
