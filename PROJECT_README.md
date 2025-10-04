# 유지수 포트폴리오 웹사이트 🌊

바다 속으로 잠수하는 듯한 느낌을 주는 인터랙티브 포트폴리오 웹사이트입니다.

## 🎨 디자인 컨셉

- **테마**: 깊은 바다 속으로 잠수하는 경험
- **색상**: 깊은 블루, 시안, 화이트 그라데이션
- **효과**: 스크롤에 따른 수심 변화 효과, 기포 애니메이션, 물결 효과

## 📁 프로젝트 구조

```
master0419.github.io/
├── _config.yml              # Jekyll 설정 파일
├── Gemfile                  # Ruby 의존성 파일
├── index.md                 # 메인 페이지
├── _layouts/
│   └── default.html         # 기본 레이아웃 템플릿
├── _includes/
│   ├── header.html          # 재사용 가능한 헤더
│   └── footer.html          # 재사용 가능한 푸터
└── assets/
    ├── css/
    │   ├── base.css         # 전역 스타일
    │   ├── header.css       # 헤더 스타일
    │   ├── footer.css       # 푸터 스타일
    │   ├── hero.css         # Hero 컴포넌트 스타일
    │   ├── about.css        # About 컴포넌트 스타일
    │   └── tech-stack.css   # Tech Stack 컴포넌트 스타일
    └── images/
        └── README.md        # 이미지 파일 안내
```

## 🎯 주요 컴포넌트

### 1️⃣ Hero Component (첫 번째 섹션)
- **ID**: `#home`
- **높이**: 100vh (전체 화면)
- **특징**:
  - 큰 제목으로 이름 강조
  - AI/Data Scientist 소개
  - 프로필 이미지 영역
  - 떠다니는 기포 애니메이션
  - 스크롤 인디케이터

### 2️⃣ About Me Component (두 번째 섹션)
- **ID**: `#about`
- **높이**: 최소 100vh
- **특징**:
  - 4개의 카드형 섹션 (소개, 학력/경력, 관심분야, 가치관)
  - 호버 효과
  - 떠다니는 파티클 애니메이션
  - 반투명 글래스모피즘 디자인

### 3️⃣ Tech Stack Component (세 번째 섹션)
- **ID**: `#tech-stack`
- **높이**: 최소 100vh
- **특징**:
  - 6개의 기술 카테고리 카드
  - 주요 기술 아이콘 표시
  - 기술 뱃지
  - 빛줄기 애니메이션 효과

## 🚀 로컬 개발 환경 설정

### 필요 조건
- Ruby (2.7 이상)
- RubyGems
- Bundler

### 설치 및 실행

```bash
# 1. 의존성 설치
bundle install

# 2. 로컬 서버 실행
bundle exec jekyll serve

# 3. 브라우저에서 접속
# http://localhost:4000
```

### Windows에서 실행 시 주의사항

```bash
# tzinfo-data gem이 설치되어 있는지 확인
gem install tzinfo-data

# 또는 Gemfile에 이미 포함되어 있으므로
bundle install
```

## ✏️ 컨텐츠 수정 방법

### 1. 기본 정보 수정 (`_config.yml`)

```yaml
title: 유지수 | Python Developer
description: Python Developer passionate about software development and AI
author: 유지수
email: jsyoo@example.com
github_username: master0419
```

### 2. About Me 섹션 수정 (`index.md`)

`index.md` 파일에서 "About Me Component" 부분을 찾아 수정:

```html
<div class="about-section-text">
  <p>여기에 자신의 소개를 입력하세요</p>
</div>
```

### 3. Tech Stack 수정 (`index.md`)

각 tech-card의 내용을 수정:

```html
<div class="tech-card">
  <div class="tech-card-icon">💻</div>
  <h3 class="tech-card-title">카테고리 이름</h3>
  <p class="tech-card-description">설명</p>
  <ul class="tech-list">
    <li>기술 1</li>
    <li>기술 2</li>
  </ul>
</div>
```

### 4. 프로필 이미지 추가

1. `assets/images/` 폴더에 이미지 업로드
2. `index.md`의 Hero 섹션에서 이모지를 이미지로 교체:

```html
<img src="{{ '/assets/images/profile.jpg' | relative_url }}"
     alt="유지수 프로필"
     class="hero-profile-image">
```

## 🎨 스타일 커스터마이징

### 색상 변경 (`assets/css/base.css`)

```css
:root {
  --ocean-deep: #051829;      /* 깊은 바다색 */
  --ocean-mid: #0d3454;        /* 중간 바다색 */
  --ocean-light: #115782;      /* 밝은 바다색 */
  --accent-blue: #64c8ff;      /* 강조 파란색 */
  --accent-dark-blue: #4a9fd8; /* 어두운 강조 파란색 */
}
```

### 애니메이션 속도 조정

각 CSS 파일에서 `animation-duration` 값을 조정:

```css
/* 기포 애니메이션 속도 */
.bubble {
  animation: rise 15s infinite ease-in; /* 15s를 원하는 값으로 변경 */
}
```

## 📱 반응형 디자인

모든 컴포넌트는 반응형으로 제작되었습니다:
- **Desktop**: 1200px 이상
- **Tablet**: 768px - 1199px
- **Mobile**: 767px 이하

## 🌐 GitHub Pages 배포

### 자동 배포
1. GitHub에 코드 푸시
2. Settings > Pages에서 소스를 `main` 브랜치로 설정
3. `https://master0419.github.io/`에서 자동으로 배포됨

### 수동 빌드

```bash
# 프로덕션 빌드
JEKYLL_ENV=production bundle exec jekyll build

# _site 폴더에 빌드된 파일 생성됨
```

## 🔧 주요 기능

### ✨ 인터랙티브 요소
- **고정 헤더**: 스크롤 시 배경 투명도 변경
- **깊이 인디케이터**: 현재 섹션 표시 (오른쪽 점)
- **Back to Top 버튼**: 스크롤 300px 이상 시 표시
- **부드러운 스크롤**: 모든 앵커 링크에 적용
- **Fade-in 애니메이션**: 스크롤 시 요소 표시

### 🎬 애니메이션
- 기포 애니메이션 (Hero 섹션)
- 떠다니는 파티클 (About 섹션)
- 빛줄기 효과 (Tech Stack 섹션)
- 호버 효과 (모든 카드)
- 글로우 효과 (제목)

## 🐛 문제 해결

### Jekyll 서버가 시작되지 않을 때

```bash
# Bundler 재설치
gem install bundler

# 의존성 재설치
bundle install

# 포트 변경
bundle exec jekyll serve --port 4001
```

### CSS가 적용되지 않을 때

1. 브라우저 캐시 삭제 (Ctrl + F5)
2. `_site` 폴더 삭제 후 재빌드
3. CSS 파일 경로 확인

## 📝 추가 작업 권장사항

### 즉시 수정이 필요한 부분
1. **이미지 추가**: `assets/images/ocean-surface.jpg` (배경 이미지)
2. **프로필 사진**: 개인 프로필 이미지로 교체
3. **About Me 내용**: 실제 경력 및 학력으로 수정
4. **이메일 주소**: 실제 이메일로 변경

### 추후 추가 가능한 기능
1. **Projects 섹션**: 포트폴리오 프로젝트 전시
2. **Blog 섹션**: 기술 블로그 포스트
3. **Contact Form**: 문의 양식
4. **다크모드**: 라이트/다크 테마 토글
5. **다국어 지원**: 한국어/영어 전환

## 📄 라이선스

이 프로젝트는 개인 포트폴리오 용도로 제작되었습니다.

## 👤 작성자

**유지수**
- GitHub: [@master0419](https://github.com/master0419)
- Email: jsyoo@example.com

---

Made with 💙 by diving into the deep ocean of code
