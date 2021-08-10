# 타입스크립트 입문 - 기초부터 실전까지
: 자바스크립트로 제작된 COVID-19 세계 현황판을 타입스크립트로 변환

## 정의
타입스크립트는 자바스크립트의 확장된 언어로 타입스크립트는 자바스크립트와 다른게 브라우저에서 실행하기 위해 파일을 한번 변환(컴파일;Compile)해주어야 한다.

## 컴파일(compile) : ts 파일을 js 파일로 변환하는 작업
```
 #node 버전 확인
 node -v 

 # NPM을 통한 타입스크립트 전역 설치
 npm i typescript -g

 # (참고)
 # 1. NPM(Node Package Manager)
 # 명령어로 자바스크립트 라이브러리를 설치하고 관리할 수 있는 패키지 매니저

 # 2. NPM 전역 설치
 # 시스템 레벨에서 사용할 자바스크립트 라이브러리를 설치할 때 사용
 # 라이브러리가 설치되고 나면 이제 명령어 실행 창에 해당 라이브러리 이름을 입력했을 때 명령어를 인식
```

## 장점
1. JS를 이용하여 에러 사전방지
2. 코드 가이드 및 자동완성(개발 생산성 향상)


## Reference
- [공식문서](https://www.typescriptlang.org/)
- [타입스크립트 핸드북](https://joshua1988.github.io/ts/intro.html)

## 개발 환경

- [Chrome](https://www.google.com/intl/ko/chrome/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js LTS 버전(v10.x 이상)](https://nodejs.org/ko/)
- [Git](https://git-scm.com/downloads)

## VSCode 플러그인 목록
- 문법 검사 : ESLint, [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
- 기타
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) 등


> 강의
인프런의 [타입스크립트 입문 - 기초부터 실전까지](https://www.inflearn.com/course/%ED%83%80%EC%9E%85%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EC%9E%85%EB%AC%B8?inst=f1ae9299&utm_source=blog&utm_medium=githubio&utm_campaign=captianpangyo&utm_term=banner) 온라인 강의 리포지토리입니다.

[![typescript-beginner](https://joshua1988.github.io/images/posts/web/inflearn/typescript-beginner-kor.png)](https://www.inflearn.com/course/%ED%83%80%EC%9E%85%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EC%9E%85%EB%AC%B8?inst=f1ae9299&utm_source=blog&utm_medium=githubio&utm_campaign=captianpangyo&utm_term=banner)

