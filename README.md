# 공지사항❗

## 프로젝트명 : 'PetPlanet' 반려동물커뮤니티사이트 
## 기간 : 대략 7주 (12/18 ~ 2/3 )


```
협업관리 담당 : 유영준 
// 프로젝트 merging은 위 팀원만 권한이 있음. 
// 나머지 조원들은 commit, push 까지만 해놓기.
```
## 일정 : 
### 1주차: db설계 및 소셜로그인 기능 구현, 기능명세 작성 진행 
 - 소셜로그인 제일 오래걸릴 것 같아서 먼저 시작
 - 이전 프로젝트 기반으로 구현하면, db설계 완료후 이번프로젝트에 이어붙일 에정입니다.
```
⭐ 12/19 할일 ⭐
+ 팔로우 기능 db설계 연구
+ 참고 : https://gist.github.com/ffbit/3343910
+ Follow라는걸 엔티티로 볼 것이냐, 관계로 볼 것이냐에 따라 설계가 달라짐?
```
    
### 2주차: 기능명세작성 완료, 기능구현 진행 
### 3주차: 기능구현 진행 
### 4주차: 기능구현 진행  + 템플릿 다듬기
### 5주차: 기능구현 진행  + 템플릿 다듬기
### 6주차: 기능구현 진행  + 템플릿 다듬기 + 자잘한 버그 수정
### 7주차: 마무리 및 자잘한 버그 수정

## ERD 설계_1차수정
![image](https://github.com/second-project-team/project_team4/assets/143607484/5bb506dd-83ab-45c2-8134-a2bf5ce610ad)



```
사이트의 회원 계정 및 프로필을 인스타그램 처럼 진행 예정
현재 인스타그램 erd 보고 엔티티 구상
- 회원 : 회원가입시 입력된 개인정보 엔터티
- 프로필 : 사용자가 직접 관리하는 프로필 엔터티
- 반려동물 : 계정 하나당 여러개 연결가능한 반려동물 프로필 엔터티
- 관계 : 계정들간의 팔로우.. (이부분 추후 설명 수정하겠습니다)
- 사진파일 : 전체 프로그램에서 이미지파일들 담기위한객체. 자세한 동작은 imageservice의 메서드 들로 이루어집니다.
- 게시물 
- 게시물좋아요  
- 댓글  
- 댓글 좋아요  



```
