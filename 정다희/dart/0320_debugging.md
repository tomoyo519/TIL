# 디버깅

## 디버깅 종류

- 로깅: Print찍기
- 브레이크포인트 : 디버깅모드에서 빨간점
- 디버거 : 디버깅모드
- 스택 추적 : 디버깅 모드에서 지원. 어디서 오류가 낫는지 추적할 수 있음

# 람다식과 함수

## 1급 객체

- 변수에 대입가능한 객체
- ex ) 값, 인스턴스, 함수

## 옵션 파라미더

### []를 사용해서 위치를 지정하는 옵션 파라미터를 사용할 수 있음

```dart

void say(String from, String msg, [String? device]) {}
```

# 함수형 프로그래밍

dart 는 객체지향 프로그래밍과 함수형 프로그래밍 특징을 모두 제공하는 멀티패러다임 언어

## 고계함수

- where : 조건필터링
- map : 변환
- forEach : 루프
- reduce : 한단계씩
- fold : 하나씩 접기
- any : 있는지없는지 확인