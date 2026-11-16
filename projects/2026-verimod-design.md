# 설계 · VeriMod

[개요](2026-verimod.md) · [내 기여](2026-verimod-contribution.md) · [사례](2026-verimod-cases.md)

## 문제

AI가 콘텐츠를 제한했을 때 사용자는 판정 이유와 기록이 나중에 바뀌지 않았는지 확인하기 어렵습니다. VeriMod는 이 두 문제를 분리합니다.

## 흐름

`입력 → AI 분류 → 정책 결정 → Decision Receipt → Merkle proof → 공개 Epoch 기준점 → 브라우저 검증` 순서입니다. Receipt는 판정 기록의 요약본이고, Merkle proof는 그 요약이 공개된 묶음에 포함됐음을 대조하는 방법입니다.

## 중요한 한계

기록 무결성 검증은 “기록이 바뀌었는가”를 다룹니다. AI 판정이 공정하거나 항상 정확하다는 보장은 아닙니다. 그래서 화면도 AI 결과와 검증 결과를 별도의 상태로 보여 주도록 설계했습니다.
