http://www.sitepoint.com/understanding-es6-modules/

소스코드 참고 부탁드립니다.

실행이 목적이기때문에 불친절한 설명은 너그러히 이해해 주시기 바랍니다..

1.node 4.1 버전이상 설치되어 있어야 합니다. 

2.npm install -g es6-module-transpiler   컴파일 모듈을 전역 설치 합니다.

3.node app.js 실행 합니다.

4.public 폴더상에서 compile-modules convert -I js -o out app.js utility.js --format commonjs 명령어 실행 합니다.

5.public/out 폴더에 컴파일된 결과물 확인하시면 됩니다.!

