## Rustlings

Rustlings는 Rust 프로그래밍 언어를 배우기 위한 작은 연습문제들의 모음입니다. 이 과정은 Rust의 문법과 개념을 실습을 통해 학습할 수 있도록 설계되었습니다.

### 주요 특징

- 단계별로 구성된 연습문제
- 즉각적인 피드백을 제공하는 자동 테스트
- Rust의 핵심 개념들을 실전적으로 학습
- 컴파일러 메시지를 통한 학습

### 실행 방법

1. **설치**

```bash
# rustling CLI 를 설치하기 위한 cargo install 명령어
cargo install rustlings
```

```bash
git clone https://github.com/juhyeonni/rustlings
cd rustlings
cargo install
```

2. **실행**

```bash
rustlings
```

### 문제 구성

- 변수와 기본 타입
- 함수
- if문
- 소유권과 참조
- 구조체
- 열거형
- 모듈
- 컬렉션
- 에러 처리
- 제네릭과 트레이트
- 테스트
- 클로저

각 연습문제는 `exercises` 디렉토리 내에 주제별로 정리되어 있습니다.

### 도움말

- `rustlings list` - 모든 연습문제 목록 보기
- `rustlings run 문제이름` - 특정 문제만 실행
- `rustlings hint 문제이름` - 특정 문제의 힌트 보기
