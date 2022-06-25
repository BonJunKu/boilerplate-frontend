# boilerplate-frontend

리액트-타입스크립트 기반으로 웹 프론트엔드 초기 세팅이 되어 있는 저장소입니다.
<br/>

## Usage

1. 터미널에서 아래 명령어로 파일을 복사합니다.

```
git clone https://github.com/BonJunKu/boilerplate-frontend.git
```

2. 원격 저장소와의 연결을 끊습니다.

```
git remote remove origin
```

3. `github`에서 새로운 저장소를 생성합니다.
4. 아래 명령어로 원격 저장소와 다시 연결합니다.

```
git remote add origin [저장소 주소]
```

5. 공동 작업일 경우 한 사람이 위 과정을 거치면 나머지 사람은 그 저장소에서 클론합니다.

## Settings

세팅되어 있는 목록은 아래와 같습니다.

- CRA template TypeScript
- `@sharedComponents`에 위치 잡기 위한 컴포넌트 작성
- craco 로 절대 경로 import 가 가능함
- `styled-components` 설치
- `GlobalStyle` 추가
- react-router-dom 추가
- 불필요한 파일 제거
