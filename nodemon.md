##소스 수정시에 자동으로 서버 재시작하기.

javascript 파일의 수정될 경우 반영이 되지 않아 node 어플리케이션을 다시 수행해 주어야 한다.
nodemon은 폴더의 파일을 모터링 하다 변경된 내용이 있을 경우 서버를 재시작한다.

###설치
```sh
$ npm install -g nodemon
```

###실행
```sh
$ nodemon app.js
```

>재시작 하고 싶지 않은 파일이 있다면 `.nodemonignore`에 추가한다.
