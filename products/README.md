# 📷 OSMP Reference Image Library

**용도**: AI 이미지 생성 시 제품 형태/색상/로고가 변형되지 않도록 **reference image로 첨부**하는 정본 사진 모음.

**원칙**:
1. AI(Nano Banana Pro·ChatGPT 4o·Krea Edit)에 prompt + 이 폴더의 사진을 reference로 첨부
2. Prompt 자동 prefix: *"USE PROVIDED PRODUCT REFERENCE — do not redraw product, only background/lighting/context"*
3. **카피 텍스트는 절대 AI에 박지 말 것** → Canva·Photoshop에서 직접 입력 (AI는 한글·영문 텍스트 자주 틀림. 정본 첨부 이미지의 "Jewellce" 오타 사례 참조)

---

## 폴더 구조

```
products/
├── duomaker/             ← DuoMaker 메이커 케이스 (3컬러)
├── ablr/                 ← ablr 텀블러 (6컬러)
├── ablr-zero/            ← ablr zero 텀블러 (1컬러·투명 Tritan)
├── ice-molds/            ← 얼음 몰드 옵션 (아이스볼·큐브·스피어다이아·롱스틱·미니스틱)
└── _원본_2026-05-19_charles첨부/   ← Charles 첨부 원본 보존
```

---

## 📦 현재 보유 사진 (자동 복사 완료)

### ablr/ (4컬러)
- `ablr-white.jpg` — 화이트 정면
- `ablr-black.jpg` — 블랙 정면
- `ablr-silver.jpg` — 실버 정면
- `ablr-new-colors-teal-coral.png` — 신규 2컬러 (티얼·코랄) 런칭 컷

### ablr-zero/ (4장)
- `ablr-zero-01.jpg` ~ `03.jpg` — 텀블러 본체·뚜껑·전체
- `ablr-zero-규격.jpg` — 8.7×7×16.1cm 규격 도면

---

## 📋 Charles 직접 저장 필요 (Drive 동기화 후)

`02_상품기획/` 하위 PDF/카탈로그에서 추출하거나 별도 촬영본 필요:

### duomaker/ (필요 사진)
- [ ] `duomaker-white.jpg` — 화이트 케이스 정면 (H 17cm 손잡이 포함)
- [ ] `duomaker-black.jpg` — 블랙 케이스 정면
- [ ] `duomaker-blue.jpg` — 블루 케이스 정면
- [ ] `duomaker-size-spec.jpg` — H 14.32cm·W 18.16cm·D 10.5cm 규격 도면

### ice-molds/ (필요 사진)
- [ ] `mold-ball-64mm.jpg` — 아이스볼 옵션 (실리콘 몰드 + 64mm 결과 얼음, 137ml)
- [ ] `mold-cube-50mm-diag-75mm.jpg` — 큐브 (50mm·대각선 75mm·125ml)
- [ ] `mold-sphere-diamond-64mm.jpg` — 스피어다이아몬드 (64mm·114ml·다면체)
- [ ] `mold-stick-long-35x35x120mm.jpg` — 롱스틱 (정사각 단면 35×35×120mm·하이볼 전용)
- [ ] `mold-stick-mini-92x40mm.jpg` — 미니스틱 (직사각 92×40mm·flat block)

### ablr/ (신규 정제본 — 선택)
- [ ] `ablr-blue.jpg` — 블루 컬러 (현재 누락)
- [ ] `ablr-new-cafe-scene.jpg` — 카페 골든아워 씬 (티얼·코랄 2024년 5/19 첨부본 — 별도 저장)

---

## 🎯 사용 워크플로우 (팀원용)

### 1. 대시보드 → 카드 클릭 → 프롬프트 카피
   - 자동으로 *"USE PROVIDED PRODUCT REFERENCE..."* prefix 포함됨

### 2. AI 도구 열기 (택 1)
   - **Nano Banana Pro** (Higgsfield) — 무제한 토글 ON
   - **ChatGPT 4o image edit** — 첨부 후 prompt 붙여넣기
   - **Krea Edit** / **Reve** — image-to-image 모드

### 3. Reference 첨부
   - 이 폴더의 해당 제품 사진 (예: `ablr/ablr-black.jpg`) 첨부
   - prompt 붙여넣기 → 생성

### 4. Canva에서 카피 얹기
   - AI가 생성한 배경/씬 이미지 → Canva 캔버스로 업로드
   - 카피 텍스트 (한글 카피 + JewelIce 로고)는 **Canva에서 직접 입력**
   - 인스타 9:16 / 카드뉴스 4:5 템플릿 활용

### 5. 발행 → 1주 후 KPI 입력 (자기학습 HARNESS)

---

## ⚠️ 보안

- 신규 미공개 컬러 (teal·coral) 사진은 **출시 전 외부 공개 금지**
- 본 폴더는 **Drive 내부용** — GitHub Pages 공개 repo에는 사진 자체 commit 안 함
- 팀원 권한: 권나경 과장·권수지 대리·이한수에게 본 폴더 Drive 공유 권한 부여 필요 (Charles 액션)

---

*최종 갱신: 2026-05-19 / OSMP v1.1 — Reference Image 모드 추가*
