# 01. git

## 1. git 이란

- VCS(Version Control System)
  - cvs, subversion(SVN): 중앙 버전 관리
  - [git](https://git-scm.com): 분산 버전 관리

## 2. 설치

- [다운로드](https://git-scm.com/downloads)

- git 설치 확인
```sh
$ git --version
```

## 3. [GitHub Cheat Sheet](https://training.github.com/downloads/ko/github-git-cheat-sheet/)


- 환경 설정
```sh
# (.gitconfig) 확인
$ git config --list

# 사용자 설정
$ git config --global user.name "Yumi"
$ git config --global user.email "hyyumi2@gmail.com"

$ git config user.name
$ git config user.email

# 줄바꿈 설정 (Carriage Return, Line Feed)
# window(\r\n -> \n -> \r\n)
$ git config --global core.autocrlf true
# mac(\n -> \n -> \n)
$ git config --global core.autocrlf input
```

## 4. [Visual Git Cheat Sheet](https://ndpsoftware.com/git-cheatsheet.html)


## 5. 명령어 실습
