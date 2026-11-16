# VeriMod · User-Verifiable AI Moderation Protocol

[← 프로필로](../README.md) · [원본 저장소](https://github.com/k0ng-min/2026_blockchain)


## 프로젝트 소개

AI 콘텐츠 판정 뒤에 Decision Receipt를 발급하고, Merkle proof와 공개 Epoch 기준점을 통해 사용자가 기록의 사후 무결성을 확인하도록 돕는 프로토콜입니다.

<a id="evaluation"></a>
## 평가 설계와 결과

AI 추론·정책 결정·영수증 발급·블록체인 앵커·브라우저 검증을 분리합니다. 따라서 “모델 판정이 옳다”는 주장과 “발급된 기록이 바뀌지 않았다”는 검증을 같은 것으로 취급하지 않습니다.

<a id="contribution"></a>
## 내 기여와 팀 구현

**근거 수준: 높음.** 공개 커밋 기준 `k0ng-min` 계정이 52건을 기여했습니다. 기본 사용자 앱 통합, 댓글 기반 Receipt 흐름, 자동 앵커 상태와 UX를 연결한 제품화 기여가 확인됩니다.

## 대표 기여 사례

- [기본 사용자 앱 통합](https://github.com/k0ng-min/2026_blockchain/commit/91477e8): 설경민 데모를 기본 앱으로 가져와 백엔드·프로토콜 계층과 연결했습니다.
- [YouTube 댓글 Receipt 흐름](https://github.com/k0ng-min/2026_blockchain/commit/3c81893): 실제 사용자 입력 맥락에서 Receipt를 다루는 진입 흐름을 추가했습니다.
- [로컬 Base Sepolia 자동 앵커](https://github.com/k0ng-min/2026_blockchain/commit/39d677e): 검증 가능한 기록을 실제 앵커 과정과 연결했습니다.

## 포트폴리오에서 보여줄 역량

복잡한 검증 프로토콜을 사용자가 이해할 수 있는 화면·상태·안내로 바꾸고, 보안 경계를 과장하지 않는 제품 설계를 보여줍니다.

<a id="failure"></a>
## 실패 사례와 한계

Receipt가 존재해도 AI 판정의 정답성·공정성까지 증명하지는 않습니다. 또한 앵커 전 상태는 최종 블록체인 증명처럼 보이면 안 됩니다. 그래서 화면은 모델 결과와 무결성 검증, 대기·실패 상태를 분리해 보여 주는지로 평가합니다.
