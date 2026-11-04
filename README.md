# Acupoint US Interactive Atlas (경혈-초음파 인터랙티브 아틀라스)

[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Online-emerald?style=flat&logo=github)](https://jaehyokim-sketch.github.io/Acupoint_US/)
[![WebGL](https://img.shields.io/badge/3D-WebGL_Canvas-blue?style=flat)](https://jaehyokim-sketch.github.io/Acupoint_US/)

한의학 경혈학(Acupoint Anatomy)과 현대 근골격계·신경 초음파(Sonoanatomy)를 융합하여, 3D 공간 해부 구조와 실시간 단면 초음파 영상을 직관적으로 학습할 수 있는 인터랙티브 웹 아틀라스 모음입니다.

---

## 🌐 웹 접속 주소 (Live Demo)

- **공식 포털 (메인 허브)**: [https://jaehyokim-sketch.github.io/Acupoint_US/](https://jaehyokim-sketch.github.io/Acupoint_US/)
- **목 부위 초음파 인터랙티브 아틀라스**: [Neck_US_Interactive_Atlas.html](https://jaehyokim-sketch.github.io/Acupoint_US/Neck_US_Interactive_Atlas.html)
- **L5-S1 초음파 인터랙티브 아틀라스**: [L5S1_Interactive_Atlas.html](https://jaehyokim-sketch.github.io/Acupoint_US/L5S1_Interactive_Atlas.html)
- **목 부위 초음파 자침 시뮬레이터**: [Neck_US_Interactive_simulator.html](https://jaehyokim-sketch.github.io/Acupoint_US/Neck_US_Interactive_simulator.html)
- **L5-S1 초음파 유도 침도 시뮬레이터**: [L5S1_Interactive_simulator.html](https://jaehyokim-sketch.github.io/Acupoint_US/L5S1_Interactive_simulator.html)

---

## 📚 주요 아틀라스 소개

### 1. 목 부위 초음파 인터랙티브 아틀라스 (`Neck_US_Interactive_Atlas.html`)
- **대상 부위**: 경부(Cervical region) 및 후두하부
- **핵심 경혈**: 천정(LI17), 부돌(LI18), 천창(SI16), 천용(SI17), 인영(ST9), 아문(GV15), 풍지(GB20) 등
- **해부학적 위험 구조 및 지표**:
  - 총경동맥(Common carotid artery), 내경정맥(Internal jugular vein), 척추동맥(Vertebral artery)
  - 미주신경(Vagus nerve), 횡격신경(Phrenic nerve), 완신경총(Brachial plexus), 대후두신경(Greater occipital nerve)
- **주요 기능**:
  - 3D 경부 골격·혈관·신경 모델 회전 및 투시
  - 프로브 초음파 빔 평면 가상 투사
  - 5대 스캔 뷰(악하부, 경동맥 삼각, 쇄골상와, 후경부, 후두하부) 및 sonoanatomy 비교
  - 5단계 인터랙티브 학습 워크스페이스 및 실습 저널 기록

### 2. L5-S1 초음파 인터랙티브 아틀라스 (`L5S1_Interactive_Atlas.html`)
- **대상 부위**: 요천추 연접부(Lumbosacral junction, L5-S1) 및 천골
- **핵심 경혈**: 대장유(BL25), 관원유(BL26), 소장유(BL27), 방광유(BL28), 상료(BL31), 차료(BL32), 요양관(GV3) 등
- **해부학적 위험 구조 및 지표**:
  - L5 극돌기, 후관절(Facet joint), 천골릉(Median sacral crest), 후천골공(Posterior sacral foramina)
  - 황색인대(Ligamentum flavum), 경막외강(Epidural space), 마미신경 및 척수강
- **주요 기능**:
  - 3D 척추 모델과 초음파 스캔 플레인의 동적 연동
  - 정중 종단 스캔(Median sagittal), 부정중 사위 스캔(Paramedian sagittal oblique), 축성 횡단 스캔(Axial transverse) 지원
  - 초음파 침투 심도 및 각도에 따른 sonoanatomy 분석

### 3. L5-S1 초음파 유도 침도 시뮬레이터 (`L5S1_Interactive_simulator.html`)
- L5-S1 아틀라스에 도침 연습 화면을 더한 판
- **경혈 찾기** (상단 `경혈 찾기` 버튼): 경혈학 상용경혈 필수·우선순위 표기본 가운데 3D 모델 범위(L3·L4·L5·천골·관골, 재구성 피부면)에 定位 기준이 있는 15혈
  - 命门·腰阳关, 肾俞·气海俞·大肠俞·关元俞·小肠俞·膀胱俞·白环俞, 上髎·次髎, 志室·秩边, 夹脊(L2–L5), 腰眼
  - 검색·필수/우선순위 필터 결과가 3D 해부 이미지의 피부면 표식으로 바로 반영되고, 경혈을 고르면 강조·라벨·피부→골 기준점 선과 함께 카메라가 이동
  - 위치는 《针灸腧穴通考》 部位 문구대로 모델의 극돌기·극간·후천골공(S1–S4)·정중천골릉에서 측정, 외측 거리는 1寸 = 23 mm 환산 (L2는 모델에 없어 L2–L3 극간은 추정)
  - 경혈마다 《针灸腧穴通考》의 部位·取穴·针刺操作·별명, 역대 문헌 定位 인용(현대 통편 교재 이전까지), 원서 책·쪽수

### 4. 목 부위 초음파 자침 시뮬레이터 (`Neck_US_Interactive_simulator.html`)
- 목 부위 아틀라스에 L5-S1 시뮬레이터와 같은 방식의 연습·발표 기능을 더한 판 (`neck_atlas_src/build_simulator.py`로 아틀라스에서 생성)
- **자침 연습** (작업 화면 줄의 `자침 연습` 버튼 → 학습 모드 연동 해부 단면)
  - 연습 니들 배치(단계 가이드 그림의 바늘 방향), 전진·후퇴 ±1 mm, 면내 각도 ±5°, 주사면 수직 이동 ±1 mm, 단면을 클릭·드래그해 끝 이동
  - 끝 위치 판독: 주사면 두께 안/밖, 탐촉자 면에서의 깊이, 끝이 놓인 모델 구조, 몸통이 지나는 구조, 골·공기 음영 여부
  - 초음파형 단면에 니들 몸통·끝의 합성 반사(빔에 수직일수록 밝음, 반향 꼬리, 음영 뒤에서는 억제)
  - 도침용 날 회전은 넣지 않음(목 부위 실습은 침 자침)
- **해부 정답 겹치기**: 초음파형에서는 윤곽·라벨을 한 토글로 묶어 B-mode형 화면을 먼저 보고 정답을 확인, 교차 구조 목록은 접어 둠
- **발표 장면**: 대표 장면 7개(C6·C7 횡단, C4 분지, 갑상샘, 사각근 간구, 관절기둥·가시돌기 종단), 내 장면 저장·복원(최대 30개, HTML 저장에 포함), PPT용 1920×1080 PNG(3D·단면·나란히)
- **경혈 찾기**: 필수·우선순위 14혈(CV22·CV23·GV14·GV15·GV16·LI18·ST9·ST10·ST11·ST12·BL10·TE17·GB20·GB21) 검색·필터, 3D 표식·라벨·카메라 이동, 관련 스캔 단계 바로 열기, 《针灸腧穴通考》 部位·取穴·针刺操作·별명·역대 문헌 定位 (EX-HN11 안면은 《通考》에 조목이 없어 제외)

---

## 🛠️ 기술 사양
- **Frontend**: Single-file Standalone HTML5 / CSS3 / JavaScript (ES6+)
- **3D Graphics**: WebGL / Canvas API
- **Hosting**: GitHub Pages

---

## ⚠️ 저작권 및 이용 규정 (All Rights Reserved)
- 본 사이트 및 리포지토리의 모든 3D 그래픽 모델, 해부학적 구조 데이터, 초음파 Sonoanatomy 영상 및 인터랙티브 소프트웨어는 개인 교육 및 학술 연구 목적으로 제작된 저작물입니다.
- **저작권자의 사전 서면 허락 없는 무단 전재, 소스 코드 복제, 재배포, 크롤링 및 영리 목적의 상업적 이용을 엄격히 금합니다.**
- 본 아틀라스는 교육 보조 자료이며, 실제 임상 진단 및 중재시술 시에는 반드시 표준 의학 교과서와 공인된 학술 가이드라인을 준수하시기 바랍니다.

