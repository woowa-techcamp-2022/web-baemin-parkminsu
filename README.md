## 배민 회원가입 과제
#### :calendar: 프로젝트 기간: 2022.07.06 ~ 2022.07.08

# [🔗 배민회원가입](https://beamin-parkminsu.herokuapp.com/)

#### 프로젝트 소개 : node express 활용한 simple 회원가입/로그인 기능 (SSR)

## Getting Started

### install Packages

```
npm install
```

### run application

```
npm start
```


#### 메인 페이지 & 로그인 페이지
- 첫페이지에서 ‘로그인해주세요' 버튼 클릭 시, 로그인 페이지로 이동
- 세션에 사용자 정보가 있는 경우 사용자 이름 표시
- 전체 화면구성에서 동작가능한 기능은 없음

### 로그인 페이지
- 값 입력이 완료되지 않은상태에서 ‘로그인' 버튼을 누르면 해당항목을 입력하라는 메시지가 input영역 바로 아래 빨간색으로 표시된다.
- 로그인 실패 시 실패 에러 메시지를 나타낸다.
- 로그인 성공 시 사용자 정보를 세션에 저장하고 매인 페이지로 이동한다.
- 회원가입버튼을 누르면 ‘회원가입' 페이지로 이동한다.

![배민 로그인](https://user-images.githubusercontent.com/52727782/179357682-49ef42cf-64bf-4f91-b379-44b13b7dff74.gif)


### 회원가입 페이지 (약관동의)
- 필수 항목이 모두 선택되면 하단 ‘다음으로' 버튼이 활성화 된다.
- 전체 동의를 누르면 모두 선택된다.  다시 누르면 모두 해제된다.
- 나이는 두 개중 하나를 선택할 수 있다
- 위의 조건이 모두 충족되면 다음으로 가는 버튼이 활성화된다.
### 회원가입 페이지 (전화번호 입력)
- 숫자를 모두 입력하면 v 체크표시 색깔이 변한다.
- x 버튼을 누르면 입력값이 삭제된다.
- 숫자만 입력핻조 중간이 '-'가 자동으로 입력된다.
- '인증번호 받기'를 누르면 인증번호를 입력할 수 있다. (2초뒤에 랜덤 숫자로 표시)
- '인증번호 다시 받기'를 누르면 2초 지나서 다시 입력된다.
- 모든 값이 입력되면 '다음' 버튼이ㅣ 활성화 되고 선택시 다음 페이지로 이동한다.

![배민 회원가입](https://user-images.githubusercontent.com/52727782/179357684-0350fa46-3c2e-4f37-98e0-7f8ad80cdfb4.gif)



