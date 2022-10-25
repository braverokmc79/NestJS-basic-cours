## [React JS 따라하며-배우는 리액트 노드 - 무비앱 시리즈 - John Ahn ]

#### 인프런   ==>    https://www.inflearn.com/따라하는-네스트-제이에스#curriculum

##### 유튜브 강의 목록 : https://www.youtube.com/playlist?list=PL9a7QRYt5fqkowXUgTj_tbkFClsPhO5XV

##### 강의 파일 : https://github.com/braverokmc79/NestJS-basic-cours/tree/main/NestJS-Diagram

##### 완성본 소스 (John Ahn)  :  https://github.com/jaewonhimnae/nestjs-board-app

## 섹션 0. Node JS

## 강의목차

#### Nest JS 소개

1-1. 강의 소개 \
1-2. NestJS란? \
1-3. Nodejs 설치하기 \
1-4. NestJS CLI 설치하기

#### Nest JS 기본 요소

2-1. 게시물 CRUD 애플리케이션 소개 \
2-2. NestCLI로 생성한 프로젝트 기본구조 알아보기 \
2-3. 기본 구조에서 살펴보는 NestJS 로직 흐름 \
2-4. NestJS 모듈이란 \
2-5. Board Module 생성하기 \
2-5. NestJS Controller 란 ? \
2-6. Board Controller 생성하기 \
2-7. NestJS Providers, Service 란? \
2-8. Board Service 만들기

#### CRUD 구현

3-1. 모든 게시물을 가져오는 Service 만들기 \
3-2. Board Model 정의하기 \
3-3. 게시물 생성하기Service 부분 \
3-4. 게시물 생성하기 Controller \
3-5. Data Transfer Object DTO \
3-6. 게시물 생성을 위한 DTO \
3-7. ID로 특정 게시물 가져오기 \
3-8. ID로 특정 게시물 지우기 \
3-9. 특정 게시물의 상태 업데이트

#### Postgres & TypeORM 연동

4-1. NestJS Pipes \
4-2. 파이프를 이용한 유효성 체크 \
4-3. 특정 게시물을 찾을 때 없는 경우 결과 값 처리 \
4-4. 없는 게시물을 지우려 할 때 결과 값 처리 \
4-5. 커스텀 파이프를 이용한 유효성 체크

#### 데이터베이스를 이용한 CRUD 구현

5-1 PostgresSQL 설치하기 \
5-2 TypeORM 소개 \
5-3 Typeorm 애플리케이션에서 이용하기 \
5-4 게시물을 위한 엔티티Entity 생성하기 \
5-5 Repository 생성하기

#### 인증 기능 구현하기

6-1. 데이터베이스와 함께 CRUD 구현을 위한 소스 코드 정리 \
6-2. ID를 이용해서 특정 게시물 가져오기 \
6-3. 게시물 생성하기 \
6-4. 게시물 삭제하기 \
6 5. 게시물 상태 업데이트하기 \
6 6. 모든 게시물 가져오기

#### 인증 기능 구현하기

7-1. 인증 기능 구현을 위한 준비 \
7-2. 회원가입 기능 구현 \
7-4. 유저 이름에 유니크한 값 주기 \
7-5. 비밀번호 암호화 하기설명 \
7-6. 비밀번호 암호화 하기소스 코드 구현 \
7-7. 로그인 기능 구현하기 \
7-8. JWT에 대해서 \
7-9. JWT를 이용해서 토큰 생성하기 \
7-10. Passport, Jwt 이용해서 토큰 인증 후 유저 정보 가져오기 \
7-11. 커스텀 데코레이터 생성하기 \
7-12. 인증된 유저만 게시물 보고 쓸 수 있게 만들기

#### 게시물에 접근하는 권한 처리

8-1. 유저와 게시물의 관계 형성 해주기 \
8-2. 게시물 생성 할 때 유저 정보 넣어주기 \
8-3. 해당 유저의 게시물만 가져오기getAllBoards \
8-4. 자신이 생성한 게시물을 삭제하기

#### 로그 남기기

9-1. 로그에 대해서

#### 설정 및 마무리

10-1. 설정Configuration이란? \
10-2. 설정 적용 & 강의 마무리

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

# React 앱 만들기 시작하기

이 프로젝트는 [Create React App](https://github.com/facebook/create-react-app)으로 부트스트랩되었습니다.

## 사용 가능한 스크립트

프로젝트 디렉토리에서 다음을 실행할 수 있습니다.

### `npm start`

개발 모드에서 앱을 실행합니다.\
브라우저에서 보려면 [http://localhost:3000](http://localhost:3000)을 엽니다.

변경하면 페이지가 새로고침됩니다.\
콘솔에 린트 오류가 표시될 수도 있습니다.

### `npm test`

대화형 감시 모드에서 테스트 실행기를 시작합니다.\
자세한 내용은 [테스트 실행](https://facebook.github.io/create-react-app/docs/running-tests) 섹션을 참조하세요.

### `npm run build`

프로덕션용 앱을 `build` 폴더에 빌드합니다.\
프로덕션 모드에서 React를 올바르게 번들하고 최상의 성능을 위해 빌드를 최적화합니다.

빌드가 축소되고 파일 이름에 해시가 포함됩니다.\
앱을 배포할 준비가 되었습니다!

자세한 내용은 [배포](https://facebook.github.io/create-react-app/docs/deployment) 섹션을 참조하세요.

### `npm run eject`

**참고: 이것은 단방향 작업입니다. 한 번 '꺼내기'하면 되돌릴 수 없습니다!**

빌드 도구 및 구성 선택에 만족하지 않으면 언제든지 '꺼낼' 수 있습니다. 이 명령은 프로젝트에서 단일 빌드 종속성을 제거합니다.

대신 모든 구성 파일과 전이적 종속성(webpack, Babel, ESLint 등)을 프로젝트에 복사하여 완전히 제어할 수 있습니다. '꺼내기'를 제외한 모든 명령은 계속 작동하지만 복사된 스크립트를 가리키므로 수정할 수 있습니다. 이 시점에서 당신은 혼자입니다.

'꺼내기'를 사용할 필요가 없습니다. 선별된 기능 세트는 중소 규모 배포에 적합하며 이 기능을 사용할 의무가 없습니다. 그러나 준비가 되었을 때 사용자 정의할 수 없다면 이 도구가 유용하지 않을 것이라는 점을 이해합니다.

## 더 알아보기

[React 앱 만들기 문서](https://facebook.github.io/create-react-app/docs/getting-started)에서 자세히 알아볼 수 있습니다.

React를 배우려면 [React 문서](https://reactjs.org/)를 확인하세요.
