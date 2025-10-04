# Assets 폴더 안내

이 폴더에는 웹사이트에서 사용되는 이미지 파일들이 저장됩니다.

## 필요한 이미지 파일

### 1. 배경 이미지
- **파일명**: `ocean-surface.jpg`
- **용도**: Hero 섹션의 배경 이미지
- **권장 크기**: 1920x1080px 이상
- **설명**: 제공하신 바다 수면 이미지를 이 이름으로 저장하세요

### 2. 프로필 이미지 (선택사항)
- **파일명**: `profile.jpg` 또는 `profile.png`
- **용도**: Hero 섹션의 프로필 사진
- **권장 크기**: 400x400px (정사각형)
- **설명**: 현재는 이모지(👩‍💻)로 대체되어 있습니다

### 3. 파비콘 (선택사항)
- **파일명**: `favicon.ico`
- **용도**: 브라우저 탭 아이콘
- **권장 크기**: 32x32px 또는 16x16px

## 이미지 추가 방법

1. 이미지 파일을 이 폴더(`assets/images/`)에 저장
2. Hero 섹션에서 프로필 이미지를 사용하려면 `index.md` 파일에서 다음 부분을 수정:

```html
<!-- 현재 코드 (이모지) -->
<div style="...">👩‍💻</div>

<!-- 변경 후 (이미지 사용) -->
<img src="{{ '/assets/images/profile.jpg' | relative_url }}" 
     alt="유지수 프로필" 
     class="hero-profile-image">
```

## 라이선스 및 저작권

웹사이트에 사용되는 모든 이미지는 적절한 사용 권한이 있는지 확인하세요.
- 직접 촬영한 사진
- 무료 이미지 사이트 (Unsplash, Pexels 등)
- 라이선스를 구매한 이미지

## 권장 무료 이미지 사이트

- [Unsplash](https://unsplash.com/) - 고품질 무료 이미지
- [Pexels](https://www.pexels.com/) - 무료 스톡 사진
- [Pixabay](https://pixabay.com/) - 무료 이미지 및 비디오

바다/해양 테마 이미지 검색 키워드:
- ocean surface
- underwater
- deep sea
- blue water
- ocean waves
