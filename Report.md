# 📑 과제 B1-2 결과 보고서: AERION 브랜드 광고 제작 프로젝트
> **과제명**: AI로 글·그림·영상 만들어 나만의 광고 만들기  
> **과정명**: AI 네이티브 — 1. AI 도구학습  
> **프로젝트명**: AERION Future Mobility Campaign  
> **작성 기준 문서**: `보고서 작성/` 폴더 내 스토리보드, 영상 프롬프트, 이미지 프롬프트 명세서

---

## 1. 브랜드 기획 및 캠페인 정의 (Brand Identity)

### 1) 브랜드 및 캠페인 개요
* **프로젝트명**: AERION Future Mobility Campaign
* **브랜드명**: **AERION (에어리온)**
* **핵심 타겟층**: 출퇴근길 극심한 도심 정체에 피로감을 느끼며 혁신 기술과 스마트 라이프스타일에 관심이 높은 20~40대 전문직 및 프리미엄 모빌리티 소비자
* **톤앤매너**: 미래지향적(Futuristic), 럭셔리(Luxury), 시네마틱(Cinematic), 미니멀(Minimal)
* **차별점(USP)**: 도로의 물리적 한계를 극복하고 도심 하늘로 이동 영역을 확장하는 차세대 개인용 전기 수직이착륙 플라잉카(eVTOL, electric Vertical Take-Off and Landing)
* **핵심 메시지(슬로건)**:
  > **“길이 끝나는 순간, 새로운 이동이 시작됩니다. 이제 하늘이 우리의 도로입니다.”**  
  > *"Next Mobility, Beyond Roads — Reserve Your Future"*
* **광고 목적**: 혁신 기술에 대한 직관적 기대감 고조 및 미래 프리미엄 모빌리티 시장 선도 브랜드로서의 인지도 구축

---

## 2. 멀티모달 도구 선정 및 파이프라인 (Multi-modal Tools)

각 제작 단계별 최적의 결과물을 도출하기 위해 생성형 AI 도구들의 장점을 결합한 파이프라인을 구축했습니다.

| 미디어 타입 | 주 사용 도구 | 대체/보조 도구 | 선정 및 활용 이유 |
|:---:|:---:|:---:|:---|
| **이미지 생성** | **ChatGPT (DALL-E 3)** | Gemini (Nano Banana) | 브랜드 컨셉(Apple·Genesis 감성)에 가장 부합하는 정밀한 고해상도 차량 렌더링 |
| **비디오 모션** | **미리캔버스 (Miricanvas)** | CapCut, InVideo | 원본 이미지 구도를 유지하면서도 부드러운 패닝 및 수직 상승 모션 구현 탁월 |
| **오디오(VO)** | **Vrew (AI 음성)** | ElevenLabs | 신뢰감 있고 차분한 톤의 보이스 제어 및 문장 단위 호흡·속도 미세 조율 |
| **오디오(BGM)** | **Suno AI** | 미리캔버스 오디오 | 미래지향적 일렉트로닉 신스 비트와 앰비언트 사운드스케이프를 씬 길이에 맞춰 생성 |
| **통합 편집** | **Vrew** | - | 영상, BGM, 자막, 보이스오버의 정밀한 타임라인 싱크 및 멀티 포맷 렌더링 |

---

## 3. 스토리보드 상세 명세 (Storyboard Specification)

### [메인 영상: 16초 와이드 버전 (16:9)]

| 씬 | 타임라인 | 목표 메시지 | 화면 구성 및 연출 | 나레이션 (VO) | 제작 프롬프트 및 파일 |
|:---:|:---:|:---|:---|:---|:---|
| **Scene 1** | 0.00s ~ 3.91s | **현재의 한계** | 석양의 도심 정체 도로, 붉은 브레이크 등이 가득한 차량들 중앙에 정지해 있는 AERION 후면 클로즈업. 차체 하부 미세 진동 및 청색 조명 점멸 | *"아직도 꽉 막힌 도로 위에 있으신가요?"* | **Prompt**: `Ultra realistic traffic jam in a futuristic megacity at sunset...`<br/>**파일**: `Scene1_현재의한계_F.png`<br/>`Scene1_MC.mp4` |
| **Scene 2** | 3.92s ~ 7.94s | **혁신의 시작** | 정체 차량들 사이에서 AERION 차체 하단으로 푸른색 플라즈마 에너지 필드를 형성하며 1m 수직 이륙 개시 | *"길이 끝나는 순간, 새로운 이동이 시작됩니다."* | **Prompt**: `Luxury futuristic flying car activating blue energy core, preparing for vertical takeoff...`<br/>**파일**: `Scene2_혁신의시작_F.png`<br/>`Scene2_MC.mp4` |
| **Scene 3** | 7.95s ~ 11.90s | **새로운 경험** | 도심 빌딩 숲과 강 위를 가로지르며 부드럽고 역동적으로 고속 비행하여 구름 위로 상승하는 카메라 추적 샷 | *"이제, 하늘이 우리의 도로입니다."* | **Prompt**: `Futuristic luxury flying sedan soaring above traffic, cinematic motion...`<br/>**파일**: `Scene3_하늘을 가르다.png`<br/>`Scene3_MC.mp4` |
| **Scene 4** | 11.91s ~ 15.93s | **브랜드 각인** | 일출의 구름 위를 평화롭게 비행하는 AERION 히어로 샷과 좌측 타이포그래피(브랜드명/슬로건/CTA) | *"AERION! 미래는 이미 시작되었습니다."* | **Prompt**: `Premium flying sedan above bright clouds at sunrise, luxury commercial style...`<br/>**파일**: `Scene4_브랜드엔딩_카피-F.png`<br/>`Scene4_MC.mp4` |

---

### [숏폼 영상: 12초 버티컬 버전 (9:16)]
* **씬 1 (꽉 막힌 도심의 일상)**: 석양의 젖은 아스팔트 위 붉은 테일램프 반사, AERION 차체 하단 파란색 조명 점멸.
* **씬 2 (수직 이륙의 순간)**: 강렬한 파란 입자 에너지 빔 방출, 정지된 주변 차들과 대비되는 수직 상승 미디엄 샷.
* **씬 3 (빌딩숲 사이의 질주)**: 은색 차체가 도시 조명을 반사하며 마천루 사이를 날렵하게 통과하는 측면 패닝 샷.
* **씬 4 (미래의 완성)**: 황금빛 구름 위 정면 3/4 쿼터 뷰 조망 하이앵글 + 고정된 브랜드 슬로건 텍스트.

---

## 4. 프롬프트 엔지니어링 명세서 (Prompt Specification)

### 1) 마스터 디자인 레퍼런스 프롬프트 (Visual DNA)
차량의 고유 디자인과 아이덴티티를 유지하기 위한 기준 프롬프트입니다.
```text
[Positive Prompt]
AERION master vehicle design sheet, futuristic luxury flying sports sedan, 
metallic silver body, ultra aerodynamic design, hidden integrated micro-thrusters, 
no visible propellers, no helicopter blades, no wings, panoramic black glass canopy, 
ultra thin LED headlights, premium concept car, front view, side view, rear view, 
3/4 perspective, industrial design presentation board, white studio background, 
photorealistic, Apple industrial design language, 8K, HDR

[Negative Prompt]
large propellers, drone, helicopter, airplane, robot, cartoon, toy, 
mechanical arms, multiple rotors, oversized engines, text, watermark
```

### 2) 씬별 핵심 생성 프롬프트
* **공통 베이스 (Common Vehicle Prompt)**:
  `AERION futuristic luxury flying sports sedan, metallic silver body, ultra aerodynamic body, hidden integrated micro-thrusters, no visible propellers, no helicopter blades, no airplane wings, panoramic black glass canopy, ultra-thin LED headlights, minimal luxury design, Apple industrial design language, Genesis luxury concept, BMW Vision Next inspiration, photorealistic, premium automotive commercial, 8K, HDR, physically accurate materials`
* **Scene 1 (정체 도로)**:
  `The AERION is completely trapped inside an extremely dense multi-lane traffic jam in a futuristic megacity during golden hour. Hundreds of premium luxury sedans and SUVs completely surround the AERION in every direction... Wet asphalt reflecting sunset, glowing brake lights everywhere, cinematic volumetric lighting...`
* **Scene 2 (수직 이륙)**:
  `The AERION is lifting vertically from the center of a completely gridlocked multi-lane highway inside a futuristic smart megacity... Soft blue anti-gravity energy beams project downward beneath the vehicle, forming a circular holographic energy field on the asphalt. Hidden micro-thrusters emit subtle blue plasma glow...`
* **Scene 3 (도심 비행)**:
  `AERION flying at high speed between futuristic skyscrapers, dynamic banking turn, motion blur, energy trails, bright futuristic city, golden hour, volumetric sunlight, cinematic aerial tracking shot, luxury automotive commercial, Top Gun Maverick atmosphere...`
* **Scene 4 (브랜드 엔딩 & 카피)**:
  `Hero shot, vehicle floating peacefully above bright white clouds, golden sunrise, warm orange sunlight, clean blue sky... Typography layout: Large premium white typography placed on the left side. Top: "AERION", Middle: "Next Mobility, Beyond Roads", Bottom: "Reserve Your Future"...`

---

## 5. 제작 전략 및 개선 이력 (Refinements & Strategy)

1. **외형 왜곡 억제 (Negative Prompt 보강)**:
   - 초기 생성 단계에서 비행체 키워드로 인해 드론 프로펠러나 비행기 날개가 생성되는 문제 발생.
   - `no visible propellers, no helicopter blades, no airplane wings, hidden micro-thrusters`를 명시하여 고급 세단 실루엣 보존.
2. **타이포그래피 위계 설정 (Scene 4 레이아웃)**:
   - 로고와 텍스트의 크기 및 위치 불일치 문제를 해결하기 위해 프롬프트 내에 비율 수치 지정:
     - `AERION`: 대형 메인 타이틀 (Apple 산세리프 스타일)
     - `Next Mobility, Beyond Roads`: 브랜드명의 60~70% 크기
     - `Reserve Your Future`: 브랜드명의 40~45% 크기 (미니멀 라이트 폰트)
3. **일관성 유지 전략 (Consistency Strategy)**:
   - 단일 마스터 디자인 시트를 먼저 확정한 후, 각 씬 프롬프트 생성 시 해당 시트의 형태적 특징을 지속적으로 주입하여 4컷 전반의 차량 연속성을 성공적으로 유지함.

---

## 6. 최종 산출물 사양 (Technical Specifications)

* **최종 마스터 영상**: `AERION_Brand_Commercial.mp4`
* **재생 시간**: 메인 영상 16초 / 숏폼 12초
* **비디오 해상도**:
  * 16:9 가로형: 1280 × 720 (30fps)
  * 1:1 정방형: 1080 × 1080 (30fps)
  * 9:16 숏폼: 720 × 1280 (30fps)
* **인코딩 포맷**: H.264 / AAC Stereo
