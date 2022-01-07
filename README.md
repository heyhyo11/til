# TIL
지금까지 배운 것을 정리했습니다.

# 전체 요약정리
* **1주차. 나를 위한 Git! : 내 프로젝트를 위해 Git을 바로 쓸 수 있었다.**
핵심키워드: 버전관리, commit, pull, push, TIL
 
* **2주차: 같이 하기 위한 Git! : 협업하기 위한 기초 개념을 배웠다.**
핵심키워드: Issue, branch, merge

* **3주차: 모두의 Git! : Git으로 의사소통하는 방법과 Github으로 만날 수 있는 새로운 세계를 만나봄.**
1. 협업을 위한 작업(commit) 관리
* 주요키워드: PR, commit 되돌리기 - amend, revert, reset, 작업내역 임시저장 - stash
2. Git 프로젝트 관리 - 협업 매너
* 주요키워드: commit 메시지 컨벤션, gitignore, README
3. 오픈소스로 정보 탐색하고 함께 즐기기: 개발자스럽게 진짜 개발정보를 찾는 방법
* 주요키워드: github explore, 오픈소스(open source)
4. Github으로 개발자인 나를 나타내자 - 포트폴리오
* 개발자들 명함과 이력서에 Github 주소가 들어가는 이유! 
* 주요키워드: github profile, repo 소개, github page


# 1주차 총 정리

* **버전관리**: 변경되는 프로젝트 상태정보를 알고 있다는 것. Git은 가장 널리 쓰이는 버전관리 도구 중 하나.
* **git 초기화(git initialize)**: 컴퓨터에 있는 프로젝트를 git이 관리하는 프로젝트로 만들기
* **commit**: 현재 프로젝트 상태를 찰칵 저장하는 것. 누가, 언제, 프로젝트 변경 내용. 커밋 메시지 남김
* **add(staging)**: commit에 반영할 파일을 선택하는 것.
* **commit history**: commit 한 순서대로 리스트. 작업내역.
* **repo**: 내 컴퓨터에 저장되어 있는 Git 저장소(로컬 repo), 다른 곳의 접속 공간에 저장된 것(원격 repo)
* **Tracking(추적)**: 로컬 repo branch와 원격 repo branch를 연결한다.
* **push**: 로컬 repo branch의 commit 들을 원격 repo branch 에 반영하기
* **pull**: 원격 repo branch의 commit 들을 로컬 repo branch 에 반영하기
* push, pull은 기본적으로 tracking 되고 있는 브랜치를 기준으로 커밋 내역을 반영함.
* **clone**: 원격 repo 를 내 컴퓨터에 가져와서 초기 repo 세팅하는 것
* **초심자 꿀패턴**: pull(원격, 로컬 repo 상태 동등하게) - commit(작업내용 저장) - push(원격에 반영)
 

# 2주차 총 정리

* Issue - Branch - Merge - PR Merge
* **Issue**: 내가 할 작업, 기능 추가, 버그 리포트 등 여러가지 방식으로 사용 가능
* 협업하기 위해 Issue 를 만들어 누가 작업할지 정하고, 브랜치 만들어 작업할 공간을 나눔.
* **Branch**: 특정 커밋에서 갈라져나와 작업할 수 있음. 우리는 기능별로 이름을 만들어주어 브랜치에 작업함.
* **Checkout**: 작업할 브랜치로 바꾸는 것. 체크아웃한 브랜치에만 커밋이 반영됨.
* **Merge**: 브랜치의 작업내역 커밋들을 다른 브랜치로 반영하는 것.
* 작업이 완료되면 작업한 브랜치는 보통 삭제함. 나중에 브랜치 설정이 꼬이는 것을 방지할 수 있음.
* **Merge conflict**: Merge 과정에서 동일한 부분이 수정된 게 발견되면 병합 충돌이 발생함.
 

# 3주차 총 정리

* **PR**: 작업내역을 바로 병합하지 않고 충분히 리뷰받고 최종적으로 프로젝트에 반영하는 단계.
* **amend**: 최신의 commit을 수정하는 것. 가장 최신의 커밋만 수정 가능.
* **revert**: 이전 커밋들도 되돌리고 기록도 남김.
* **reset**: 작업내역을 말 그대로 리셋 시킴.
* **stash**: 프로젝트의 변경사항을 임시적으로 보관할 때 사용.
* **commit message convention**: 커밋 메시지 작성하는 규칙
* **convention**: 프로그래밍 세계에서 합의한 규칙
* **.gitignore**: 파일들을 없는 것처럼 무시하게 하는 설정
* **open source**: 누구나 프로젝트를 사용, 수정, 배포할 수 있는 프로젝트
* **contribution**: 프로젝트에 기여하며 발전시키는 것.


