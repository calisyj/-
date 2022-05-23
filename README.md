# calisyj's daily github journal
# 그날그날 깃허브 사용일지

### 2022-04-30(깃허브 시작) ~ 

## 2022-05-23
밑의 git command자료의 11번 수정. (git pull main -> git pull origin main)  
add, commit, pr merge, branch삭제 이후 변경사항을 git으로 받아오는 과정에서의 오류를 없엘 수 있게 됨.  
git-command  
Organization repository commit 작업 git 명령어 순서   
reference: https://github.com/inseonyun
1. git checkout main -> main 브렌치로 switch
2. git pull -> main 브렌치의 변경사항 내려받음 
3. git checkout -b 본인깃허브닉네임(소문자)
4. 소스 코드 파일 구조에 맞게 생성 (ex. BOJ폴더 생성 -> 생성된 폴더 안에 Stack폴더 생성 -> 그 안에 본인 id폴더 생성
-> 그 안에 문제 이름(ex. balloons) 폴더 생성)
5. git add .
6. git commit -m "양식내용" 양식에 맞게 잘하면 됨
7. git push origin 본인깃허브닉네임(소문자)
8. Pull request 생성
->repository하려는 github 페이지 상단에 뜬 Compare& pull request 클릭 후 양식 rule에 맞춰 PR 생성
9. merge 진행하고 delete 브렌치 수행
10. git checkout main
11. git pull origin main
12. git branch -d 본인깃허브닉네임(소문자)

## 2022-05-07
- 깃허브 마크다운 아이콘 코드 사용 (reference: https://gist.github.com/rxaviers/7360908)
- self-algorithm-study Readme 규칙 생성 (reference: https://github.com/hs-study-group/algorithm)
- 깃허브에서 commit 커밋이란
 ![image](https://user-images.githubusercontent.com/77192299/167232750-b6f5f52c-0d47-4d35-bf6e-10ed58dc0583.png)

- 깃허브에 로컬 폴더 연결하기(reference: https://kim-dragon.tistory.com/122)
- 깃허브 access token 발급하기(reference: https://kim-dragon.tistory.com/122)
-> 스터디한 내용과 코드를 깃허브 온라인 저장소에 업로드하기 위해 깃을 사용하며 커밋 하는 과정에서 아이디와 패스워드를 입력하는 과정에서 에러가 났었고, 에러의 이유는 Github에서 ID/PW기반의 Basic Authentication 인증을 금지하고, ID/Personal Access Token 방식의 Token Authentication 인증을 사용하도록 변경하였기 때문이다. (2021년8월13일 이후로 패스워드 인증 방식에서 토큰 방식으로 변경)
![image](https://user-images.githubusercontent.com/77192299/167232717-3c9defde-0cdf-436a-8c84-cc598c47d2b5.png)
- 백준 알고리즘 3307 업로드


## 2022-05-02
- Readme 줄바꿈 방법
  1) 라인의 마지막에 공백 두 칸 입력
  2) 문단을 구분하려면 엔터 두 번
- REadme 표 작성법
![image](https://user-images.githubusercontent.com/77192299/166233392-3a6b87ba-229c-4704-82e5-7e4b0a79fda1.png)

출처: https://inasie.github.io/it%EC%9D%BC%EB%B0%98/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%ED%91%9C-%EB%A7%8C%EB%93%A4%EA%B8%B0/

## 2022-05-01
친구의 깃허브 프로필을 참고하여 이것저것 손보기 시작
- 개인 repository 2개 생성(알고리즘 스터디, 머신러닝 스터디)
- 개인 깃허브 소개 및 기초공사(참고: https://velog.io/@dding_ji/Github-Readme-Profile)
-> 개인 깃허브 소개 창을 만드는 것도 Repository를 통해 생성한다.  Repository를 생성할 때 Repository name을 본인의 깃허브 id와 똑같은 것을 넣어주면 된다. 나의 경우 calisyj를 넣었다. 이후 다른 사람들이 볼 수 있도록 public을 체크해주고 추가적인 소개를 넣을 수 있도록 Add a README file을 체크해주었다
- 아이콘 추가(ex. 인스타그램) (참고: https://velog.io/@dding_ji/Github-Readme-Profile)
- 스탯(Stats) 추가(참고: https://velog.io/@dding_ji/Github-Readme-Profile)
- 깃허브 아이디 소문자화 (CalisYJ -> calisyj)
- repository의 대표 언어는 등록된 코드 중 가장 빈도수가 높은 것으로 뜬다고 한다.
![image](https://user-images.githubusercontent.com/77192299/166131915-65949917-10eb-4cd3-8c4d-4878120e2811.png)의 분혹생 c++이 그 예시이다. 레포(repository)에 여러 언어가 사용됏을 경우 대표 언어 컨트롤이 가능하다. 다음 사진 참고. ![image](https://user-images.githubusercontent.com/77192299/166131939-7adc6017-6a03-44ae-8b1f-2944310cf264.png)
출처: https://ndb796.tistory.com/424

## 2022-04-30
삼성메디슨에서 인턴 중인 개발자 친구의 알고리즘 스터디 제의로
깃허브를 통한 공부 내용 정리를 위한 알고리즘 organization 생성과 repository 생성 과정에 참여하면서
깃허브 활동을 본격 시작하게 되었다.
- hs-study-group 생성

