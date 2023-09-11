### Meaningful Names

## 1. 이름에 의도가 드러나야 함 
구현 디테일을 보지 않고도 의미를 알 수 있어야 한다. 긴 이름이라도 분명하다면 상관없음.
```
int a # bad
int memberCount # good

```

## 2. 이름이 검색하기 쉽고, 해석하기 쉬워야 함(영어 문법적으로 의미가 있으면 좋다)

## 3. 타입에서 추론할 수 있는 정보를 이름에 포함하지 말아야 한다.
```
Person Person_Customer # bad
Person Customer # good
```

## 4. Class -> noun, Method -> verb

## 5. Naming Consistency
프로젝트 또는 자신의 코드에 통일성이 있으면 좋을 것 같다.

## 6. 코드 읽으면서 치환시켜야 하는 이름은 피하기
ex) 루프에서 i, j, k 같은 변수의 경우, 작은 코드에서는 괜찮지만 루프 내부가 복잡해지면, 내부의 코드를 읽을 때마다 i, j, k의 의미를 계속 떠올려야 하기 때문에 좋지 않다.

## 7. 이름이 존재하는 context 에서 정보를 유추할 수 있는 것이 좋다.
```
class Person
{
	string PersonName # bad
	string Name # good
}
```

## 8. 비슷한 컨셉의 이름이 여러 개 있을 경우, 이름에서 다른 점을 나타내야 함

## extra: 이름으로 장난치지 않기?
이름을 너무 추론하기 어렵게 짓거나 이름으로 장난치면 귀찮아짐.
