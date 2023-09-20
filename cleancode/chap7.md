# Error Handling

## Exception > Return Code
- Return Code 보다 Exception 이 핸들링 구조를 좀 더 명확하게 만들 수 있음
	- 서비스 로직과 에러 핸들링 로직 분리
- Return Value 는 소중하다

## Try-Catch-Finally
- Try: service logic
- Catch: Exception handling
- Finally: Cleanup

## Exception Type
- Application level/logic exception 에는 새 타입을 만들어 사용

## NULL
- null 을 구분할 수 없다면, null 을 함수 인자나 리턴값으로 사용하지 않는 것이 좋다

## Provide context in exception

## Exception 무시는 좋지않다
- unchecked exception 이 낫다
- 그냥 throw 하는 것이 낫다.

## logger 사용
