# 🎨 우도 팝아트 쿠키팩토리
### Pop Art Cookie Factory — Exterior Painting Design

![thumbnail](https://raw.githubusercontent.com/partyok-create/udo/main/thumbnail.png)

---

## 📌 프로젝트 소개

제주 **우도 팝아트 쿠키팩토리** 건물 외관에 팝아트 + 멤피스 디자인 스타일을 적용하기 위한  
**3D 인터랙티브 채색 시뮬레이션** 및 **실제 페인팅 가이드** 프로젝트입니다.

> 3D simulation and painting guide for applying Pop Art + Memphis Design style  
> to the exterior of **Udo Pop Art Cookie Factory**, Jeju Island, Korea.

---

## 🗂️ 파일 구성

| 파일 | 설명 |
|------|------|
| `building3d_popart.html` | Three.js r128 기반 인터랙티브 3D 채색 시뮬레이션 |
| `design_guide.docx` | 실제 페인팅 적용을 위한 상세 디자인 가이드 문서 |
| `thumbnail.png` | 프로젝트 대표 이미지 |

---

## 🏗️ 건물 구성

```
[ 타워동 ]  [ 메인동 — 삼각지붕 3개 ]  [ 부속동 ]
    ▲              ▲   ▲   ▲               ▲
  단일 타워     2층+1층+테라스+파라펫     평지붕
```

- **총 채색 면**: 27개 (정면 14 · 좌측 4 · 후면 5 · 우측 4)
- **지붕**: 삼각지붕 4개 + 평지붕 1개

---

## 🎨 디자인 콘셉트

| 항목 | 내용 |
|------|------|
| 스타일 | 팝아트(Pop Art) + 멤피스(Memphis) 혼합 |
| 주요 색상 | 빨강 `#E31212` · 파랑 `#0044DD` · 노랑 `#FFE000` · 주황 `#FF6600` · 초록 `#00CC44` |
| 패턴 종류 | 대각선 줄무늬 · 체커보드 · 동심원 타깃 · 대형 타원 · 수직 줄무늬 · 격자 창문 · 삼각형 |
| 핵심 원칙 | 인접 면 색상 충돌 없음 · 4면 코너 연속성 유지 · 원색 최대 채도 |

### 컬러 팔레트

![#E31212](https://placehold.co/40x20/E31212/E31212)
![#FF6600](https://placehold.co/40x20/FF6600/FF6600)
![#FFE000](https://placehold.co/40x20/FFE000/FFE000)
![#00CC44](https://placehold.co/40x20/00CC44/00CC44)
![#CCFF00](https://placehold.co/40x20/CCFF00/CCFF00)
![#0044DD](https://placehold.co/40x20/0044DD/0044DD)
![#00CCCC](https://placehold.co/40x20/00CCCC/00CCCC)
![#FF3399](https://placehold.co/40x20/FF3399/FF3399)
![#7B5EA7](https://placehold.co/40x20/7B5EA7/7B5EA7)

---

## 🖥️ 3D 시뮬레이션 사용법

`building3d_popart.html` 파일을 브라우저에서 열면 바로 실행됩니다.

| 조작 | 동작 |
|------|------|
| 🖱️ 드래그 | 360° 회전 |
| 🖱️ 스크롤 | 줌 인/아웃 |
| 📱 터치/핀치 | 모바일 회전·줌 |
| 버튼 | 정면/좌측/후면/우측/상단/아이소 뷰 |

> **요구사항**: 모던 브라우저 (Chrome, Edge, Firefox, Safari) — 별도 설치 불필요

---

## 📄 디자인 가이드 주요 내용

`design_guide.docx` 문서에는 다음 내용이 포함됩니다:

1. **프로젝트 개요** — 콘셉트, 건물 구성
2. **색상 팔레트** — HEX 코드 견본, NCS/RAL 변환표
3. **패턴 정의 8종** — 시공 방법 및 치수 기준
4. **정면 채색 명세** — F1~F14 전 면 상세
5. **측면·후면 채색 명세** — LS/RS/RE 전 면
6. **시공 지침** — 7단계 순서, 재료 사양, 품질 체크리스트
7. **코너 연속성 검증표** — 충돌 0건 확인
8. **색상 코드 변환 참고표**

---

## 🛠️ 기술 스택

- **3D 엔진**: Three.js r128
- **텍스처**: HTML5 Canvas 2D API (프로그래밍 생성)
- **문서**: docx.js
- **시뮬레이션**: 단일 HTML 파일 (외부 의존성 없음)

---

## 📍 프로젝트 정보

- **위치**: 제주특별자치도 우도
- **운영**: AI마케팅랩 · 박영미 대표
- **버전**: v17 (2026.05)

---

<p align="center">
  <img src="https://img.shields.io/badge/Three.js-r128-black?logo=three.js" />
  <img src="https://img.shields.io/badge/Pop Art-Memphis Style-FF3399" />
  <img src="https://img.shields.io/badge/Jeju-Udo Island-00CC44" />
  <img src="https://img.shields.io/badge/Version-v17-0044DD" />
</p>
