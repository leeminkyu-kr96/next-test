## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

---

## 진행 현황: 챕터 9까지

- Next.js App Router 기반 대시보드 프로젝트 진행
- 챕터 9까지의 주요 구현 내용:
  - 서버 컴포넌트와 클라이언트 컴포넌트 분리
  - 카드, 차트, 최근 인보이스 등 대시보드 UI 구현
  - Suspense와 Skeleton 컴포넌트로 로딩 UX 개선
  - 데이터 패칭 로직 서버 컴포넌트에서 처리, 클라이언트 컴포넌트에는 props로 전달
  - 서버 전용 라이브러리(postgres 등)는 서버 컴포넌트/route에서만 사용
- 최신 코드 및 구조는 [next-test 레포지토리](https://github.com/leeminkyu-kr96/next-test)에서 확인 가능

### 폴더 구조 예시
```
app/
  dashboard/
    (overview)/page.tsx  # 대시보드 메인
    ...
  ui/
    dashboard/
      cards.tsx          # 카드 컴포넌트 (use client)
      revenue-chart.tsx  # 차트 컴포넌트
      latest-invoices.tsx# 최근 인보이스
    skeletons.tsx        # 로딩 스켈레톤
  lib/
    data.ts              # 데이터 패칭 함수
```

---
