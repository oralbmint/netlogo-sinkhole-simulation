# 도심 지반침하 시뮬레이션 (Urban Sinkhole Formation Simulation)

NetLogo를 활용한 도심 지반침하 현상의 교육용 시뮬레이션입니다.

## 👨‍🏫 개발자
**박홍준 | Park, Hongjoon**  

## 📋 프로젝트 소개

이 시뮬레이션은 도심 지역의 지반침하 발생 메커니즘을 이해하기 위한 교육용 도구입니다.

![인포그래픽](images/040%20anatomy%202_eng.png)

### 주요 기능
- 관로 누수에 의한 토양 침식 시뮬레이션
- 지하수 흐름과 공동 형성 과정 시각화
- 굴착공사가 지반에 미치는 영향 분석
- Punching형과 Trough형 붕괴 유형 구현

## 🎥 빠른 시작

### 소개 자료
- **슬라이드** : [050_Slide_Sinkhole_Mechanism_Simulation.pdf](docs/050%20Slide_Sinkhole_Mechanism_Simulation.pdf)
-  **소개영상** : [060_video_싱크홀_시뮬레이션.mp4](https://drive.google.com/file/d/1YMZXXZWMzlxCW1r_0OmElG6bDIvV-pjT/view?usp=sharing)
-  **팟캐스트** : [070_podcast_싱크홀_붕괴를_부르는_지하의_연쇄_반응.m4a]([media/podcast.m4a](https://drive.google.com/file/d/1nWRs424oPW9Hix95Z2lRwkS37xSzMvp1/view?usp=sharing))

### 기술 문서
- [시뮬레이션 아키텍처](docs/030%20아키텍처_보완.pdf) - 변수들 간의 관계도
- [개요 인포그래픽](images/040%20anatomy%202_eng.png) - 시각적 개요

## 🚀 설치 및 실행

### 필요한 프로그램
1. **NetLogo 7.x 이상** 다운로드: [ccl.northwestern.edu/netlogo](https://www.netlogo.org/)

### 실행 방법
1. 이 저장소를 다운로드 (Code → Download ZIP)
2. ZIP 파일 압축 해제
3. `src/sinkhole-simulation_xxx.nlogo` 파일을 NetLogo로 실행
4. 인터페이스에서 파라미터 조정
5. **Setup** 버튼 → **Go** 버튼 클릭

## 🎓 교육 활용

### 학습 목표
- 복잡계 이론의 이해
- 지질학적 현상의 에이전트 기반 모델링
- 도시 인프라 안전 관리의 중요성 인식
- 다양한 환경 요인의 상호작용 분석

### 주요 파라미터
- `rainfall-intensity`: 강우 강도 (0-50)
- `groundwater-change-rate`: 지하수 변화율 (0-30)
- `excavation-depth`: 굴착 깊이 (0-25m)
- `pipe-condition`: 관로 상태 (0-100)
- `compaction-degree`: 다짐도 (0-100)
- `surface-load`: 지표 하중 (0-100)

### 적용 가능한 교과목
- 과학교육 (지질학, 환경과학)
- 복잡계 및 시뮬레이션 과목

## 📊 시뮬레이션 특징

### 구현된 물리 현상
1. **관로 누수 침식**: 다중 요인 기반 침식 확률 계산
2. **지하수 흐름**: 포화도 차이에 따른 확산
3. **공동 성장**: 비선형 성장 모델 적용
4. **붕괴 메커니즘**: Punching형/Trough형 자동 판별

### 시각화 요소
- 실시간 공동 크기 표시
- 지하수 흐름 방향 표시 (화살표)
- 위험 지수 모니터링
- 붕괴 발생 시 색상 변화

## 📄 라이선스
- **소스코드** (`src/`): MIT License - 자유로운 사용, 수정, 배포 가능
- **교육 자료** (`docs/`, `media/`): CC BY-NC-SA 4.0 - 비영리 목적, 저작자 표시 필수

### ✅ 허용되는 사용
- 교육 목적의 수정 및 재배포
- 학술 연구 및 논문 작성
- 수업 자료로 활용
- 비영리 교육 프로그램

### ⚠️ 제한 사항
- 교육 자료의 상업적 판매 금지
- 저작자 표시 의무

## 🔖 버전 정보

- **현재 버전**: v7.7
- **개발 기간**: 2025-2026
- **최종 업데이트**: 2026년 1월
