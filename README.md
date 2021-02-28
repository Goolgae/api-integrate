## API 연동 기초 공부하는곳

```sh
yarn add axios
```

연습용 데이터는 json [placeholder](https://jsonplaceholder.typicode.com/)에서 가져오도록 한다.

이곳에 POST나 DELETE를 해도 서버의 값은 변하지 않으므로 GET을 써볼떄 유용하게 쓸 수 있다. user/를 사용한다.

api를 사용할땐 3가지의 상태를 관리하게 된다.

1. 요청의 결과
2. 로딩 상태
3. 에러
