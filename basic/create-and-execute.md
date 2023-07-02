# 만들고 실행하기

## 만들기

- 확장자 : `sh`  
- 셸스크립트는 항상`#!bin/bash` 로 시작하기
- (터미널 이용시) 생성하기 `vi 파일명`
- (터미널 이용시) 저장하고 닫기 `:wq!`

[터미널이용시 명령어들은 vi 명령어로 여기를 참고](../appendix/vi.md)  
[First example : first.sh](./first.sh)

## 실행하기

### `sh` 명령어 이용
```shell
sh first.sh
```

### `chmod` 명령어 이용
```shell
chmod +x first.sh
./first.sh
```

## 변수

[거두절미 예제로 보기](./variable.sh)

```shell
#!/bin/bash

name="Den"

echo "My name is $name"
```