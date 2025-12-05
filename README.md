# 더나은티앤씨 주식회사 홈페이지

> 친환경 바닥재 전문 기업 웹사이트

## 📋 프로젝트 개요

더나은티앤씨(주)와 (주)인팩토리의 공식 홈페이지입니다. 독일 KLB-KOTZTAL, 미국 LIFEFLOOR, 노르웨이 Weber의 한국 총괄 대리점으로서 친환경 바닥재 솔루션을 제공하는 기업의 온라인 플랫폼입니다.

### 주요 특징

- 🌱 **친환경 중심**: 솔벤트-ZERO, VOC-Free 제품 강조
- 🏭 **산업별 솔루션**: 물류, 주차장, HACCP, 의료, 수영장, 해양설비 등 9가지 카테고리
- 🌍 **글로벌 파트너십**: 독일, 미국, 노르웨이 선진 기술 제휴
- 📱 **반응형 디자인**: 모바일, 태블릿, 데스크톱 최적화
- ⚡ **현대적 UI/UX**: 부드러운 애니메이션과 인터랙티브 요소

## 🛠️ 기술 스택

### Frontend
- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - CSS Grid & Flexbox
  - CSS Variables (Custom Properties)
  - Responsive Design
  - Animations & Transitions
- **JavaScript (ES6+)**:
  - Vanilla JS (No Framework)
  - DOM Manipulation
  - Event Handling
  - Intersection Observer API

### 외부 라이브러리
- **AOS (Animate On Scroll)**: 스크롤 애니메이션
- **Font Awesome 6.4.0**: 아이콘
- **Google Fonts**: 
  - Noto Sans KR (한글)
  - Montserrat (영문)

## 📂 프로젝트 구조

```
webapp/
├── index.html              # 메인 HTML 파일
├── css/
│   └── style.css          # 메인 스타일시트
├── js/
│   └── main.js            # JavaScript 기능
├── images/                # 이미지 자산
├── assets/
│   └── icons/            # 아이콘 및 파비콘
└── README.md             # 프로젝트 문서
```

## 🎨 디자인 시스템

### 컬러 팔레트
- **Primary Color**: #0066cc (블루)
- **Secondary Color**: #00a651 (그린)
- **Accent Color**: #ff6b35 (오렌지)
- **Dark Color**: #1a1a1a (다크 그레이)
- **Light Color**: #f8f9fa (라이트 그레이)

### 타이포그래피
- **본문**: Noto Sans KR (300, 400, 500, 700, 900)
- **제목**: Montserrat + Noto Sans KR (300~800)
- **기본 크기**: 16px
- **줄간격**: 1.6

## 🌟 주요 기능

### 1. 헤더 네비게이션
- 고정 헤더 (스크롤 시 배경색 변경)
- 드롭다운 메뉴 (제품/서비스, 회사소개)
- 모바일 반응형 햄버거 메뉴
- 부드러운 스크롤 이동

### 2. 히어로 섹션
- 자동 슬라이더 (5초 간격)
- 3개의 메인 메시지 슬라이드
- 좌우 네비게이션 버튼
- 인디케이터 (현재 슬라이드 표시)

### 3. 제품 & 서비스
9가지 산업 분야별 바닥재 솔루션:
- 물류센터 바닥
- 주차장/방수 바닥
- HACCP/식품 바닥
- 의료시설 바닥
- 수영장/워터파크
- 해양설비 바닥
- 화학공장 바닥
- 실외/도로 바닥
- 논슬립 시스템

### 4. 시공사례 포트폴리오
- 필터링 기능 (전체/카테고리별)
- 프로젝트 상세 정보
- 호버 효과 (이미지 확대)
- 실적 통계 표시

### 5. 인증 & 품질
- 친환경 인증 (EMICODE EC1 PLUS)
- 안전 인증 (NSF, IMO, DIN EN)
- 품질 인증 (DNV-GL, MED-B)
- 성능 기준 표시

### 6. 글로벌 파트너
- 독일 KLB-KOTZTAL
- 미국 LIFEFLOOR
- 노르웨이 Weber Marine

### 7. 문의 폼
- 실시간 입력 검증
- 이메일/전화번호 형식 체크
- 개인정보 동의 체크박스
- 제출 성공 알림

### 8. 스크롤 투 탑 버튼
- 300px 이상 스크롤 시 표시
- 부드러운 상단 이동

## 🚀 설치 및 실행

### 로컬 개발 환경

1. **저장소 클론**
```bash
git clone <repository-url>
cd webapp
```

2. **로컬 서버 실행**

Python을 사용하는 경우:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Node.js를 사용하는 경우:
```bash
# http-server 설치 (전역)
npm install -g http-server

# 서버 실행
http-server -p 8000
```

VS Code Live Server를 사용하는 경우:
- VS Code에서 `index.html` 우클릭
- "Open with Live Server" 선택

3. **브라우저에서 접속**
```
http://localhost:8000
```

## 📱 반응형 디자인

### 브레이크포인트
- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

### 반응형 특징
- 모바일 햄버거 메뉴
- 그리드 레이아웃 자동 조정
- 이미지 최적화
- 터치 인터랙션 지원

## 🎯 SEO 최적화

- 시맨틱 HTML5 태그 사용
- Meta 태그 (description, keywords)
- Open Graph 태그 준비
- 이미지 alt 속성
- 구조화된 데이터 (JSON-LD) 준비

## ♿ 접근성 (Accessibility)

- ARIA 레이블
- 키보드 네비게이션 지원
- 포커스 인디케이터
- 색상 대비 비율 준수 (WCAG 2.1 AA)
- 스크린 리더 호환

## 🔧 커스터마이징

### 색상 변경
`css/style.css` 파일의 CSS Variables 수정:

```css
:root {
    --primary-color: #0066cc;
    --secondary-color: #00a651;
    --accent-color: #ff6b35;
    /* ... */
}
```

### 슬라이더 간격 조정
`js/main.js` 파일에서 `startSlideShow` 함수 수정:

```javascript
function startSlideShow() {
    slideInterval = setInterval(nextSlide, 5000); // 5000ms = 5초
}
```

### 섹션 추가
1. `index.html`에 새로운 `<section>` 추가
2. `css/style.css`에 스타일 정의
3. 필요한 경우 `js/main.js`에 인터랙션 추가

## 📞 연락처 정보

**더나은티앤씨 주식회사**
- **주소**: 경기도 용인시 기흥구 동백중앙로 16번길 16-4, 에이스 동백타워 1411, 1412, 1413
- **전화**: 1551-9904
- **이메일**: infactory-id@naver.com
- **운영시간**: 평일 09:00 - 18:00

## 📄 라이센스

Copyright © 2025 더나은티앤씨 주식회사 & (주)인팩토리. All rights reserved.

## 🤝 기여

이 프로젝트는 더나은티앤씨 주식회사의 공식 웹사이트입니다.

## 📝 변경 이력

### v1.0.0 (2025-01-XX)
- 초기 웹사이트 개발
- 9가지 제품/서비스 카테고리 구현
- 반응형 디자인 적용
- 시공사례 포트폴리오 구현
- 문의 폼 구현

## 🔮 향후 계획

- [ ] 다국어 지원 (영문, 중문)
- [ ] 제품 상세 페이지 추가
- [ ] 블로그/뉴스 섹션
- [ ] 고객 후기 시스템
- [ ] 온라인 견적 계산기
- [ ] 실시간 채팅 상담
- [ ] PWA (Progressive Web App) 변환
- [ ] 성능 최적화 (이미지 lazy loading, 코드 minify)

## 💡 기술 문의

웹사이트 관련 기술 문의는 다음으로 연락해주세요:
- 이메일: infactory-id@naver.com
- 전화: 1551-9904

---

**Built with ❤️ by 더나은티앤씨 웹 개발팀**
