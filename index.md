---
layout: default
title: Home
---

<!-- Hero Component - First Section -->
<section id="home" class="hero-component">
  <!-- Animated Bubbles -->
  <div class="bubbles">
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>
  </div>

  <div class="hero-content fade-in">
    <h1 class="hero-title">유지수</h1>
    <h2 class="hero-subtitle">AI / Data Scientist</h2>
    <p class="hero-description">
      데이터 속에서 인사이트를 발견하고, AI 기술로 고객을 위한 서비스를 설계하고 싶습니다.<br>
      깊은 바다처럼 끝없는 배움의 열정으로 성장하겠습니다.
    </p>

    <div class="hero-profile-container">
      <!-- Profile Image -->
      <img src="{{ '/assets/img/profile.jpg' | relative_url }}" alt="유지수 프로필 사진" class="hero-profile-image">

      <a href="#about" class="hero-cta">더 알아보기</a>
    </div>
  </div>

  <!-- Scroll Indicator -->
  <div class="scroll-indicator">
    <span>Scroll to dive deeper</span>
    <svg viewBox="0 0 24 24" fill="currentColor">
      <path d="M7.41 8.59L12 13.17l4.59-4.58L18 10l-6 6-6-6 1.41-1.41z"/>
    </svg>
  </div>
</section>

<!-- About Me Component - Second Section -->
<section id="about" class="about-component">
  <!-- Floating Particles -->
  <div class="about-particles">
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
  </div>

  <div class="about-container fade-in">
    <div class="about-header">
      <h2 class="about-title">About Me</h2>
      <p class="about-subtitle">저를 소개합니다</p>
    </div>

    <div class="about-content">
      <div class="about-section">
        <h3 class="about-section-title">
          <span class="about-section-icon">👋</span>
          소개
        </h3>
        <div class="about-section-text">
          <p>
            안녕하세요!!
          </p>
          <p>
            복잡한 데이터 속에서 의미 있는 패턴을 찾아내고,
            AI 기술을 활용하여 실질적인 가치를 창출하는 AI 데이터분석가 유지수입니다.
          </p>
          <p>
            끊임없이 배우고 성장하는 것을 즐기며,
            새로운 기술과 도전을 두려워하지 않고 도전하겠습니다.
          </p>
        </div>
      </div>

      <div class="about-section">
        <h3 class="about-section-title">
          <span class="about-section-icon">🎓</span>
          학력 및 경력
        </h3>
        <div class="about-section-text">
          <ul class="about-list">
            <li>2020 한국외국어대학교 국제금융학과</li>
            <li>2022 경희대학교 지속가능 빅데이터 신산업 선도인력 교육연구단</li>
            <li>2024 경희대학교 일반대학원 빅데이터응용학과 공학(졸)</li>
            <li>2025 (주)데이터사이언스랩 AI 데이터분석가 직무</li>
          </ul>
        </div>
      </div>

      <div class="about-section">
        <h3 class="about-section-title">
          <span class="about-section-icon">💡</span>
          관심 분야
        </h3>
        <div class="about-section-text">
          <ul class="about-list">
            <li>Machine Learning & Deep Learning</li>
            <li>Natural Language Processing</li>
            <li>RAG</li>
            <li>Data Analysis & Visualization</li>
            <li>Big Data Processing</li>
          </ul>
        </div>
      </div>

      <div class="about-section">
        <h3 class="about-section-title">
          <span class="about-section-icon">🌟</span>
          논문 및 수상
        </h3>
        <div class="about-section-text">
          <p>
            <strong>2023</strong>
            대학(원)생 ERP 아이디어 공모전 1위 대상 수상 (한국경영정보학회)
          </p>
          <p>
            <strong>2023</strong>
            빅콘테스트 빅데이터플랫폼 활용분야 1위 최우수상 수상 (과학기술정보통신부)
          </p>
          <p>
            <strong>2023</strong>
            건강추천시스템(HRS) 연구 동향: 인용네트워크 분석과 GraphSAGE를 활용하여 (지능정보연구 게재)
          </p>
          <p>
            <strong>2024</strong>
            Leveraging stock discussion room posts for stock price predictions: A focus on the secondary battery sector (IEEE Access 개제)
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Tech Stack Component - Third Section -->
<section id="tech-stack" class="tech-stack-component">
  <!-- Light Rays Effect -->
  <div class="light-rays">
    <div class="light-ray"></div>
    <div class="light-ray"></div>
    <div class="light-ray"></div>
    <div class="light-ray"></div>
    <div class="light-ray"></div>
  </div>

  <!-- Swimming Fish - 10 Scenarios (3 will be randomly selected by JavaScript) -->
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-1" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-2" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-3" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-4" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-5" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-6" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-7" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-8" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-9" style="display: none;">
  <img src="{{ '/assets/img/bone_fish.png' | relative_url }}" alt="Fish" class="swimming-fish fish-scenario-10" style="display: none;">

  <div class="tech-stack-container fade-in">
    <div class="tech-stack-header">
      <h2 class="tech-stack-title">Tech Stack</h2>
      <p class="tech-stack-subtitle">보유하고 있는 기술 스택을 소개합니다</p>
    </div>

    <div class="tech-stack-grid">
      <!-- Programming Languages -->
      <div class="tech-card">
        <div class="tech-card-icon">💻</div>
        <h3 class="tech-card-title">Programming Languages</h3>
        <p class="tech-card-description">
          주요 프로그래밍 언어 및 활용 능력
        </p>
        <ul class="tech-list">
          <li>Python (Advanced)</li>
          <li>R (Intermediate)</li>
          <li>SQL (Advanced)</li>
          <li>JavaScript (Intermediate)</li>
        </ul>
      </div>

      <!-- Machine Learning & AI -->
      <div class="tech-card">
        <div class="tech-card-icon">🤖</div>
        <h3 class="tech-card-title">Machine Learning & AI</h3>
        <p class="tech-card-description">
          머신러닝 및 딥러닝 프레임워크
        </p>
        <ul class="tech-list">
          <li>TensorFlow</li>
          <li>PyTorch</li>
          <li>Scikit-learn</li>
          <li>Keras</li>
        </ul>
      </div>

      <!-- Data Processing -->
      <div class="tech-card">
        <div class="tech-card-icon">📊</div>
        <h3 class="tech-card-title">Data Processing</h3>
        <p class="tech-card-description">
          데이터 분석 및 처리 도구
        </p>
        <ul class="tech-list">
          <li>Pandas / NumPy</li>
          <li>Matplotlib / Seaborn</li>
          <li>Plotly</li>
          <li>Pydeck</li>
        </ul>
      </div>

      <!-- Database & Storage -->
      <div class="tech-card">
        <div class="tech-card-icon">🗄️</div>
        <h3 class="tech-card-title">Database & Storage</h3>
        <p class="tech-card-description">
          데이터베이스 관리 및 저장 시스템
        </p>
        <ul class="tech-list">
          <li>GraphQL</li>
          <li>MySQL</li>
          <li>Weaviate DB</li>
          <li>Chroma</li>
        </ul>
      </div>

      <!-- Web Development -->
      <div class="tech-card">
        <div class="tech-card-icon">🌐</div>
        <h3 class="tech-card-title">Web Development</h3>
        <p class="tech-card-description">
          웹 개발 프레임워크 및 도구
        </p>
        <ul class="tech-list">
          <li>Django</li>
          <li>FastAPI</li>
          <li>REST API</li>
          <li>HTML / JavaScript</li>
        </ul>
      </div>

      <!-- DevOps & Tools -->
      <div class="tech-card">
        <div class="tech-card-icon">⚙️</div>
        <h3 class="tech-card-title">DevOps & Tools</h3>
        <p class="tech-card-description">
          개발 운영 및 협업 도구
        </p>
        <ul class="tech-list">
          <li>Docker / Kubernetes</li>
          <li>Git / GitHub</li>
          <li>CI / CD</li>
          <li>AWS</li>
        </ul>
      </div>
    </div>

    <!-- Featured Technologies -->
    <div class="featured-tech">
      <h3 class="featured-tech-title">주요 사용 기술</h3>
      <div class="featured-tech-icons">
        <div class="tech-icon" title="Python">🐍</div>
        <div class="tech-icon" title="TensorFlow">🧠</div>
        <div class="tech-icon" title="PyTorch">🔥</div>
        <div class="tech-icon" title="Pandas">🐼</div>
        <div class="tech-icon" title="Docker">🐳</div>
        <div class="tech-icon" title="Git">📚</div>
        <div class="tech-icon" title="Cloud">☁️</div>
        <div class="tech-icon" title="Database">💾</div>
      </div>
      <div class="tech-badges">
        <span class="tech-badge">Data Science</span>
        <span class="tech-badge">Machine Learning</span>
        <span class="tech-badge">Deep Learning</span>
        <span class="tech-badge">NLP</span>
        <span class="tech-badge">Computer Vision</span>
        <span class="tech-badge">Big Data</span>
        <span class="tech-badge">Web Development</span>
        <span class="tech-badge">Cloud Computing</span>
      </div>
    </div>
  </div>
</section>
