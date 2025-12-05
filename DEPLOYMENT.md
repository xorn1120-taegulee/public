# 더나은티앤씨 웹사이트 배포 가이드

## 🚀 GitHub Pages 배포

### 1단계: GitHub 저장소 생성
1. GitHub에 로그인
2. 새 저장소 생성: `thenaeuntnc-website`
3. Public 또는 Private 선택 (GitHub Pages는 둘 다 지원)

### 2단계: 코드 푸시
```bash
cd /home/user/webapp
git remote add origin https://github.com/YOUR_USERNAME/thenaeuntnc-website.git
git branch -M main
git push -u origin main
```

### 3단계: GitHub Pages 활성화
1. 저장소 Settings → Pages 메뉴
2. Source: **GitHub Actions** 선택
3. 자동으로 배포 시작

### 4단계: 접속
- URL: `https://YOUR_USERNAME.github.io/thenaeuntnc-website/`
- 배포 완료까지 1-2분 소요

---

## 🌐 다른 배포 옵션

### Netlify (무료, 간편)
1. [Netlify](https://netlify.com) 회원가입
2. "Add new site" → "Import an existing project"
3. GitHub 저장소 연결
4. Build settings:
   - Build command: (비워두기)
   - Publish directory: `/`
5. Deploy 버튼 클릭

**장점:**
- 무료 HTTPS
- 자동 배포
- 커스텀 도메인 무료
- 빠른 글로벌 CDN

### Vercel (무료, 고성능)
1. [Vercel](https://vercel.com) 회원가입
2. "Add New Project"
3. GitHub 저장소 import
4. 자동 감지 및 배포

**장점:**
- 최고 성능의 CDN
- 자동 HTTPS
- 프리뷰 배포
- 커스텀 도메인

### Cloudflare Pages (무료, 빠름)
1. [Cloudflare Pages](https://pages.cloudflare.com) 가입
2. "Create a project"
3. GitHub 연결
4. Build settings:
   - Framework preset: None
   - Build command: (비워두기)
   - Build output directory: `/`

**장점:**
- Cloudflare CDN
- 무제한 대역폭
- 무료 DDoS 보호

---

## 📝 커스텀 도메인 설정

### GitHub Pages
1. Settings → Pages → Custom domain
2. 도메인 입력: `www.thenaeuntnc.com`
3. DNS 설정:
   ```
   CNAME  www  YOUR_USERNAME.github.io
   ```

### Netlify/Vercel/Cloudflare
1. 사이트 설정 → Domains
2. "Add custom domain"
3. DNS 설정 안내 따라하기

---

## 🔧 배포 후 확인사항

- [ ] 모든 페이지 정상 작동
- [ ] 반응형 디자인 테스트 (모바일/태블릿)
- [ ] 이미지 로딩 확인
- [ ] 문의 폼 작동 확인
- [ ] 메타 태그 및 SEO 확인
- [ ] 성능 최적화 (Google PageSpeed Insights)

---

## 📞 문의

**더나은티앤씨 주식회사**
- 전화: 1551-9904
- 이메일: thenaeuntnc@naver.com
