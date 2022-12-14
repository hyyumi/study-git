# 02. 원격저장소/github

- 리모트 저장소는 인터넷이나 네트워크 어딘가에 있는 저장소를 말한다.
- 대표적인 github는 코드 웹 호스팅 플랫폼으로 git 원격저장소뿐만 아니라 다양한 협업을 위한 기능들을 제공한다.

## 브랜치

- Learn Git Branching  
: git 리포지토리 시각화 도우미, 샌드박스 및 교육 자습서 및 과제입니다.  
다양한 git 명령에 익숙해지기 위해 다양한 수준의 게임을 통해 달성됩니다. 
  - [브랜치 데모](https://learngitbranching.js.org/?demo=&locale=ko)
  - [게임](https://learngitbranching.js.org/?locale=ko)


## 협업 실습

- ### 원격 저장소 만들기
![](../asset/02-01.png)

```sh
# 기본 브랜치명 변경
$ git config --global init.defaultBranch main
```

  <img src="../asset/git_cheatsheet_2.png" width="780px">

- ### 브랜치 명령어 실습
```sh
# feature 브랜치 만들기
# 브랜치 이동(새 브랜치 체크아웃)
# 변경사항 만들기 - src/index.html (https://www.w3schools.com/js/tryit.asp?filename=tryjs_myfirst)

# main 브랜치 이동(checkout)
# 브랜치 병합(merge) - Fast Forward 방식
# 푸시

# feature 브랜치 삭제
```

- ### 원격 저장소 명령어 실습
```sh
# clone
# feature 브랜치 생성
# 브랜치 이동(새 브랜치 체크아웃)
# 변경사항 만들기 - src/menu.html
# 커밋,푸시
```

## 브랜치 전략

- [브랜치 전략 수립을 위한 전문가의 조언들](http://blog.hwahae.co.kr/all/tech/tech-tech/9507/)



## Pull Request

## Action