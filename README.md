# ttakkku
딱구를 위해 만들어진 난해한 프로그래밍 언어입니다.

이 언어는 BrainFuck의 파생어입니다.

## 설명

`딱`  포인터 증가

`구`  포인터 감소

`t`  포인터가 가리키는 바이트의 값을 증가

`a`  포인터가 가리키는 바이트의 값을 감소

`u`  포인터가 가리키는 바이트 값을 아스키 코드 문자로 출력한다.

`#`  포인터가 가리키는 바이트에 아스키 코드 값을 입력한다.

`6`  포인터가 가리키는 바이트의 값이 0이 되면 짝이 되는 1로 이동한다.

`1`  포인터가 가리키는 바이트의 값이 0이 아니면 짝이 되는 6로 이동한다.


## 예제

### Hello, World

```t
t
t
t
t
t
t
t
t
t
6
딱
t
t
t
t
t
t
t
딱
t
t
t
t
t
t
t
t
t
t
딱
t
t
t
딱
t
구
구
구
구
a
1
딱
t
t
u
딱
t
u
t
t
t
t
t
t
t
u
u
t
t
t
u
딱
t
t
u
구
구
t
t
t
t
t
t
t
t
t
t
t
t
t
t
t
u
딱
u
t
t
t
u
a
a
a
a
a
a
u
a
a
a
a
a
a
a
a
u
딱
t
u
딱
u```
