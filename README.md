# 모듈스(Modules) — 영업 덱 / 사업제안서

총통합 모듈러 IoT 시스템 패키지 사업제안서 (HTML PPT, 21슬라이드).

## 사용법

```bash
open index.html
```

- **←/→/Space**: 슬라이드 이동
- **P**: 발표(풀스크린) 모드 토글
- **`?present=1`**: URL로 발표 모드 진입
- 우상단 **PDF 저장** 버튼 → 1슬라이드 = 1페이지(16:9) PDF

## 구성

- `index.html` — 단일 파일 덱 (CSS/JS inline)
- `모듈스영업덱 이미지/` — 슬라이드 이미지 폴더 (없으면 점선 플레이스홀더로 자동 fallback)

## 슬라이드 목록

1. 표지
2. Executive Summary
3. 문제 정의
4. 솔루션 개요
5. 자체 설계 통신보드
6. 모듈러 센서 라인업
7. 시뮬레이션 웹
8. 커스텀 관제 대시보드
9. 시스템 아키텍처
10. 차별점 / 경쟁 비교
11. 적용사례 (요약)
12. A사 건축현장 하중계
13. 건설현장 건물 경사계 구성도
14. 스마트 재난경보시스템
15. 상습침수지역 모터보드
16. 확장 가능 분야
17. 시장·정책
18. 비즈니스 모델·가격
19. 로드맵
20. 팀·추진체계
21. 재무·요청사항

## 이미지 파일명 규칙

| 슬라이드 | 파일명 |
| -------- | ------ |
| 3 | `03_fragmented_vs_unified.jpg` |
| 5 | `05_board_pcb.jpg` |
| 7 | `07_simulator_ui.jpg` |
| 8 | `08_dashboard.jpg` |
| 12 | `12_loadcell_site_a.png`, `12_loadcell_site_b.png` |
| 13 | `13_tilt_diagram.jpg` |
| 15 | `15_motorboard_diagram.jpg` |
| 17 | `17_market_chart.jpg` |
| 19 | `19_roadmap_gantt.jpg` |
| 20 | `team_ceo.jpg`, `team_cto.jpg`, `team_platform.jpg`, `team_biz.jpg` |

이미지는 `object-fit: contain`으로 **원본 비율 유지·잘림 없음** 으로 렌더링됩니다.

## CONFIDENTIAL

본 문서는 제안 검토 목적 외 사용을 금합니다.
