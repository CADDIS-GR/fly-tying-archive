# 🎣 Fly Tying Archive

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://caddis-gr.github.io/fly-tying-archive/)
[![Patterns](https://img.shields.io/badge/Patterns-7-blue)]()
[![Categories](https://img.shields.io/badge/Categories-2-purple)]()

관리형 낚시터(저수지) 플라이 낚시를 위한 타잉 패턴 아카이브입니다.

## 🌟 프로젝트 소개

이 프로젝트는 관리형 저수지에서 사용하는 플라이 타잉 패턴을 체계적으로 정리하고 공유하기 위해 만들어졌습니다. 각 패턴은 실전 경험을 바탕으로 상세한 재료 정보, 타잉 방법, 그리고 사용 조건을 포함하고 있습니다.

**🔗 라이브 사이트:** [https://caddis-gr.github.io/fly-tying-archive/](https://caddis-gr.github.io/fly-tying-archive/)

## 📚 등록된 패턴 (7개)

### 🦟 Chironomid (3개)

#### 1. Zucchini Chironomid Pupa
- **Hook:** #14
- **특징:** Dark Zucchini 베이스 + Red Ribbing
- **마무리:** Thin UV + Varnish

#### 2. 2026 Chironomid Pupa
- **Hook:** #12
- **특징:** Deepness 컬러 아키텍처, VEEVUS BQ5 + Under-Layer 밸런스
- **컨셉:** 밑실 톤으로 완전히 다른 생명체 구현

#### 3. White Pupa, Pink Larva Collection ⭐ NEW!
- **Hook:** #14 (DAIICHI 1760)
- **구성:** 3종 프리미엄 컬렉션
  - **Pink Larva 3D** - 입체적 반사, 한겨울 맑은 날 특화
  - **Pink Larva 2D** - 슬림한 실루엣, 예민한 입질 대응
  - **White Pupa** - 순수 화이트, 저광도 상황 특화
- **코어 기술:** Bubble Dot (바니시 방울로 공기 방울 재현)
- **특징:** Tailwind CSS 기반 프리미엄 상세 페이지, 이미지 확대 기능

### 🐟 Streamer (4개)

#### 4. 화이트 버전 리치
- **Hook:** #16
- **특징:** Special White + Tan Dubbing 블렌딩
- **시즌:** 동절기 저수지 필살기

#### 5. Glow Bead Marabou Leech
- **Hook:** #12
- **특징:** Black & Purple 마라부 믹스, 야광 텅스텐 비드
- **용도:** 저광량 공략, 바닥 걸림 최소화

#### 6. White Zonker Collection
- **Hook:** #16
- **특징:** Opal Tinsel + Red Thread 포인트
- **전략:** 6미터 수심 전용, 3가지 컬러 로테이션

#### 7. Black Torpedo Leech
- **Hook:** #12
- **특징:** 빠른 침강 + 은밀한 실루엣, Light Blue 버블 트리거
- **시즌:** Nov-Mar 동절기 특화

## ✨ 주요 기능

### 메인 아카이브 페이지
- 🔍 **실시간 검색** - 패턴명, 설명 기반 필터링
- 🏷️ **카테고리 필터** - Chironomid, Streamer, Nymph, Dry Fly, Emerger
- 📱 **반응형 디자인** - 모바일/태블릿/데스크톱 지원
- 📊 **통계 대시보드** - 패턴 수, 카테고리 수 실시간 표시
- 🎨 **모던 UI** - 보라색 그라디언트 + Glassmorphism

### White Pupa, Pink Larva Collection 페이지
- 🎭 **프리미엄 디자인** - Tailwind CSS 기반 고급 UI
- 🔬 **Master's Touch** - 상세 스펙 섹션
- 💎 **Bubble Dot 기술** - 코어 기술 하이라이트
- 📝 **Field Note** - 실전 활용 팁 (Sizing/Depth/Action)
- 🖼️ **이미지 확대** - 클릭 시 모달로 고화질 이미지 확대
- ⌨️ **키보드 지원** - ESC 키로 모달 닫기

## 🛠️ 기술 스택

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Framework:** Tailwind CSS 3.x (프리미엄 페이지)
- **Icons:** Font Awesome 6.5.1
- **Fonts:** Inter, Noto Sans KR (Google Fonts)
- **Hosting:** GitHub Pages
- **Design:** Glassmorphism, Gradient, Modern Card UI

## 📂 프로젝트 구조

```
fly-tying-archive/
├── index.html                          # 메인 아카이브 페이지
├── README.md                           # 프로젝트 문서
├── flies/
│   ├── chironomid/
│   │   ├── zucchini-pupa/
│   │   │   ├── index.html
│   │   │   └── zucchini-pupa.jpg
│   │   ├── 2026-chironomid-pupa/
│   │   │   ├── index.html
│   │   │   └── olive-chironomid.jpg
│   │   └── white-pupa-pink-larva/     # ⭐ NEW!
│   │       └── index.html              # 프리미엄 컬렉션 페이지
│   └── streamer/
│       ├── white-version-leech/
│       ├── glow-bead-marabou-leech/
│       ├── white-zonker-collection/
│       └── black-torpedo-leech/
└── images/
    ├── PinkLarvar_3D.jpg               # ⭐ NEW!
    ├── PinkLarva_2D.jpg                # ⭐ NEW!
    ├── WhitePupa.jpg                   # ⭐ NEW!
    ├── Olive_chironomid.jpg
    └── ...
```

## 🚀 로컬 실행 방법

```bash
# 1. 저장소 클론
git clone https://github.com/CADDIS-GR/fly-tying-archive.git

# 2. 프로젝트 디렉토리로 이동
cd fly-tying-archive

# 3. 로컬 서버 실행 (Python 3)
python -m http.server 8000

# 4. 브라우저에서 접속
# http://localhost:8000
```

## 📝 새 패턴 추가하기

### 1. 패턴 폴더 생성
```bash
mkdir -p flies/카테고리명/패턴명/
```

### 2. index.html 작성
각 패턴의 상세 페이지를 작성합니다.

### 3. 메인 index.html 수정
`patterns` 배열에 새 패턴 추가:

```javascript
{
  id: 8,
  name: '패턴 이름',
  category: 'chironomid', // 또는 streamer, nymph, dry-fly, emerger
  description: '패턴 설명',
  hook: '#14',
  image: 'flies/카테고리명/패턴명/이미지.jpg',
  date: '2025-01-26',
  url: 'flies/카테고리명/패턴명/index.html'
}
```

### 4. 이미지 추가
- 패턴 이미지를 `images/` 폴더에 업로드
- 또는 패턴 폴더 내에 직접 저장

### 5. Git 커밋 & 푸시
```bash
git add .
git commit -m "Add new pattern: 패턴명"
git push origin main
```

## 🎨 디자인 가이드

### 컬러 팔레트
- **Primary:** `#667eea` → `#764ba2` (보라색 그라디언트)
- **Secondary:** `#9333ea` → `#4f46e5` (퍼플-인디고)
- **Accent:** `#ddd6fe` (라이트 퍼플)
- **Text:** `#1e293b` (슬레이트 다크)

### 타이포그래피
- **제목:** 800-900 weight, tracking-tight
- **본문:** 400-500 weight, leading-relaxed
- **강조:** 700 weight, uppercase

### 카드 스타일
- **Border Radius:** 1-2rem (둥근 모서리)
- **Shadow:** 0 4px 6px rgba(0,0,0,0.1)
- **Hover:** translateY(-5px) + shadow 확대

## 📅 업데이트 로그

### 2025-01-26
- ⭐ **White Pupa, Pink Larva Collection** 추가
  - 3종 프리미엄 컬렉션 (Pink Larva 3D/2D, White Pupa)
  - Tailwind CSS 기반 고급 디자인 페이지
  - Bubble Dot 코어 기술 소개
  - 이미지 확대(줌) 기능 구현
  - Master's Field Note 섹션 추가

### 2025-01-23
- 🎉 프로젝트 시작
- 기본 구조 구축
- 6개 패턴 등록 (Chironomid 2개, Streamer 4개)

## 🎯 향후 계획

- [ ] Nymph 카테고리 활성화 및 패턴 추가
- [ ] Dry Fly 카테고리 활성화 및 패턴 추가
- [ ] Emerger 카테고리 활성화 및 패턴 추가
- [ ] 기존 패턴 프리미엄 디자인으로 업그레이드
- [ ] 계절별/수심별 필터 기능
- [ ] 패턴 비교 기능
- [ ] 타잉 동영상 임베드
- [ ] 커뮤니티 댓글 기능 (Disqus 또는 GitHub Discussions)

## 👨‍💻 기여하기

이 프로젝트는 플라이 낚시를 사랑하는 모든 분들의 기여를 환영합니다!

1. 이 저장소를 Fork 합니다
2. 새 브랜치를 생성합니다 (`git checkout -b feature/new-pattern`)
3. 변경사항을 커밋합니다 (`git commit -m 'Add new pattern'`)
4. 브랜치에 Push 합니다 (`git push origin feature/new-pattern`)
5. Pull Request를 생성합니다

## 📄 라이선스

이 프로젝트는 개인 학습 및 비상업적 용도로 자유롭게 사용할 수 있습니다.

## 📧 문의

프로젝트에 대한 문의사항이나 제안사항은 GitHub Issues를 통해 남겨주세요.

---

**Made with ❤️ by Jeff | 2026 Season**

*"입질은 우연이 아니라, 완벽하게 설계된 '뉴앙스'의 결과다."*
