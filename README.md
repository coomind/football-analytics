# ⚽ Football Analytics

축구 데이터 분석 학습 기록. StatsBomb Open Data를 활용해 경기를 분석합니다.

## 🎯 목표
축구 전력분석가를 목표로, 데이터 기반 경기 분석 역량을 쌓아갑니다.

## 📊 분석 목록

### 01. 대한민국 vs 포르투갈 슈팅맵 (2022 카타르 월드컵)
- **경기**: 2022 W컵 조별리그 H조, 대한민국 2-1 포르투갈 (알라이얀의 기적)
- **내용**: 한국의 슈팅 위치를 xG(기대득점) 기반으로 시각화
- **사용**: `statsbombpy`, `mplsoccer`, `pandas`, `matplotlib`
- **결과물**: [노트북](01_shotmap.ipynb) · [슈팅맵 이미지](korea_portugal_xg_shotmap.png)

![슈팅맵](korea_portugal_xg_shotmap.png)

**주요 인사이트**
- 총 12회 슈팅, 총 xG 1.4 (StatsBomb 모델 기준)
- 두 골(김영권 0.62, 황희찬 0.42)이 전체 xG의 약 74%를 차지 — 양질의 기회에서 득점
- 나머지 10회 슈팅은 대부분 박스 외곽의 낮은 xG 시도

## 🛠️ 환경
- Python 3.11
- statsbombpy, mplsoccer, pandas, matplotlib

## 📝 블로그
분석 과정은 [벨로그](https://velog.io/@coomind)에 기록합니다.
