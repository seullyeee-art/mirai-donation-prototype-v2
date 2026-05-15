# MIRAI Chat

> 디자인 시스템·토큰은 [`../shared/CLAUDE.md`](../shared/CLAUDE.md) 참조.

## 페이지

| 파일 | 설명 |
|---|---|
| `chat-prototype.html` | 채팅 — 풀스크린 (사이드바·바텀네비 없음) |

## 특이사항

- **풀스크린**: `.app` grid 구조를 쓰지 않음. `<mirai-sidebar>`, `<mirai-bottom-nav>` 모두 제외.
- **shared 토큰만 참조**: `<link rel="stylesheet" href="../shared/styles.css">`. letter-spacing / font-feature-settings는 채팅 자체 설정(`normal`)로 override.

## 이미지 에셋

`./images/` 하위 — `char-full.webp`, `char-profile.png`, `rank-*.png/webp` 등.
