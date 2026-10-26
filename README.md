# Hun Proto (`hun-proto`)

VS Code extension for **Protocol Buffers (`.proto`)** syntax highlighting.

Protocol Buffers 파일(`.proto`)을 위한 깔끔하고 가벼운 VS Code 구문 강조(Syntax Highlighting) 확장입니다.

---

## ✨ Key Features (주요 기능)

* **Lightweight & Fast**: TextMate 기반의 가볍고 빠른 구문 강조
* **Auto Theme Compatibility**: 사용 중인 VS Code 테마(Dark/Light 등)의 색상 팔레트에 100% 자동 매핑
* **Essential Keywords Support**: Protobuf `syntax`, `package`, `message`, `enum`, `service`, `rpc` 및 데이터 타입 지원

---

## 🚀 Quick Start (사용 방법)

1. 확장을 설치합니다.
2. `.proto` 확장자를 가진 파일(예: `service.proto`)을 엽니다.
3. 현재 설정된 VS Code 테마에 맞추어 자동으로 강조되는 구문을 확인합니다.

```protobuf
syntax = "proto3";

package hun.example;

message UserRequest {
  string user_id = 1;
  int32 age = 2;
}

service UserService {
  rpc GetUser (UserRequest) returns (UserResponse);
}
