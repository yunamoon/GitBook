# NPM (Node Package Manager)

### npm이란?

npm은 Node Package Manager 이름 그대로 node package를 관리하기 위한 시스템으로 다양한 패키지들을 설치, 업데이트, 삭제 등의 도움을 주는 툴입니다. 이때 npm에서 node는 javascript runtime을 의미하며 대부분의 javascript 프로그램은 패키지로 묶여 npm 안에 등록되어 있기 때문에 npm을 사용해 설치가 가능하고, 이따 npm에 업로드 되어 있는 node modules을 패키지라고 부릅니다.

npm을 사용하면 보다 효율적으로 node 서버를 구축할 수 있습니다. 문제는 npm 사용시 패키지들이 서로 의존성을 가지고 있어 하나의 패키지에 문제가 생가면 연쇄적으로 기능을 하지 않을 수 있다는 단점이 있는데 이를 관리하기 위해 [package.json](package.json-package-lock.json.md)이 존재합니다.

### npm 사용 방식

```
// npm 사용이 가능한 초기 환경 설정

npm init

// npm을 이용한 패키지 설치
npm install '패키지 이름'

// 개발용으로만 사용한 패키지를 설치할 경우.
npm install -D '패키지 이름'

// 패키지를 공통적으로 모두 설치할 경우.
npm install -g '패키지 이름'
```
