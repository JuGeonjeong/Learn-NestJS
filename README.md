<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

<details>
  <summary>...</summary>
  
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

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

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
  
</details>

## Nest JS란 
#### Nest JS는 효율적이고 확장 가능한 Node.js 서버 측 애플리케이션을 구축하기 위한 프레임 워크입니다. Javascript를 사용하고 Typescript로 빌드되고 완벽하게 지원하며 OOP(Object Orientied Programming, FP(Functional Reactive Programming)요소를 사용.
## Nest JS의 내부 구성
#### 내부적으로는 Nest는 Express 와 같은 강력한 HTTP서버 프레임 워크를 사용하며 선택적으로 Fastify를 사용하도록 구성 할 수도 있음.   Nest는 이러한 공통 Node.js 프레임 워크 (Express/Fastify) 위에 추상화 수준을 제공하지만 API를 개발자에게 직접 노출합니다. 이를 통해 개발자는 기본 플렛폼에서 사용할 수 있는 수많은 타사 모듈을 자유롭게 사용할 수 있습니다.
## Nest JS 의 철학
#### Node(및 서버 측 Javascript)를 위한 훌륭한 라이브러리, 도우미 및 도구가 많이 존재하지만 이들 중 어느 것도 아키텍쳐의 주요 문제를 효과적으로 해결하지 못함.   Nest는 개발자와 팀이 고도로 테스트 가능하고 확장 가능한 애플리케이션 아키텍쳐를 제공합니다. 이 아키텍쳐는 Angular에서 크게 영감을 받음.
## 개발자와 팀이 고도로 테스트 가능! 테스트코드(TDD)의 장점이 강함!

#### 실행과정
```bash
$ npm i -g @nestjs/cli   
$ nest new project-name
```
#### NestCLI로 생성한 기본구조
* eslintrc.js - 개발자들이 특정한 규칙을 가지고 코드를 깔끔하게 짜도록 도와주는 라이브러리, 타입스크립트를 쓰는 가이드 라인 제시, 문법에 오류가 나면 알려주는 역할 등등..
* prettierrc - 주로 코드 형식을 맞추는데 사용합니다. 작은따옴표(')를 사용할지 큰따옴표(")를 사용할지, Indent 값을 2로 줄지 4로 줄지 등등, 에러 찾는 것이 아닌 코드 포멧터 역할.
* nest-cli.json - nest 프로젝트를 위해 특정한 설정을 할 수 있는 json파일.
* tsconfig.json - 어떻게 타입스크립트를 컴파일 할지 설정.
* tsconfig.build.json - tsconfig.json의 연장선상 파일이며 .build를 할때 필요한 설정들 "excludes"에서는 빌드할때 필요없는 파일들 명시
* package.json - build : 운영환경을 위한 필드, format : 린트에러가 났을지 수정, start : 앱시작   
* src폴더 - (대부분의 비즈니스 로직) - main.ts(앱을 생성하고 실행, 앱의 시작점) - app.module.ts(앱 모듈을 정의?)

<details>
  
![스크린샷 2021-10-27 오후 4 01 45](https://user-images.githubusercontent.com/81910342/139016162-bda908d5-0c31-495f-8c23-6bb6105fc715.png)   
![스크린샷 2021-10-27 오후 4 06 23](https://user-images.githubusercontent.com/81910342/139016800-cdafefed-f148-4400-a51a-1dc2814760a4.png)

</details>











