# 온라인 교육 서비스 이탈 분석

🔗 [Tableau 대시보드 바로가기](https://public.tableau.com/app/profile/jiwoo.lee8788/viz/_17788274740880/sheet0#)

## 개요
- 목표: 63.7% 이탈 → 리뷰 노출 개선 가설
- 기간: 2026.04.20 ~ 2026.05.18
- 데이터: 2022.01 ~ 2023.12

## 분석 과정
1. AARRR 퍼널 분석 (5단계)
2. 이탈 시점별 행동 분석
3. A/B 테스트 설계 (표본 2,540명/그룹)

## 주요 발견
- 가입 후 30일 이후 이탈자 중 68%가 리뷰 확인 직후 이탈
- A/B 테스트: 리뷰 노출 순서 "최신" → "베스트"

## 사용 기술
- MySQL, Python (Pandas), Tableau

## 프로젝트 구조
```
.
├── docs/                          # 보고서·기획안 문서
│   ├── 1. AARRR 보고서.pdf
│   ├── 2. 리뷰 정렬방식 변경 AB테스트 기획안.pdf
│   ├── 3. 온라인 교육 서비스 사용자 이탈 분석 보고서.pdf
│   └── 4. 온라인 교육 서비스 사용자 이탈 핵심 보고서_요약본.pdf
├── notebooks/
│   ├── 01_funnel_analysis.ipynb   # AARRR 퍼널 분석 (SQL 세부 분석 포함)
│   └── 02_churn_behavior.ipynb    # 이탈 시점별 행동 분석
├── output/
    └── churn_dashboard.png
```