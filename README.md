# 🚀 실전 AI 활용 올인원 마스터 클래스

> 9개 실전 프로젝트로 완성하는 AI 활용 능력  
> 영상 생성부터 자동화, Agent까지 난이도 순서로 학습

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://tygwan.github.io/ai-master-class/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 📌 소개

이 커리큘럼은 최신 AI 도구들을 실전에서 활용할 수 있도록 체계적으로 구성된 학습 가이드입니다.

### ✨ 주요 특징

- **📊 진행률 추적**: LocalStorage 기반으로 학습 진행률 자동 저장
- **📱 반응형 디자인**: 모바일/태블릿/데스크톱 모두 지원
- **📖 상세 가이드**: Part별 Step-by-Step 학습 가이드 제공
- **🎯 프로젝트 중심**: 각 Part마다 실전 프로젝트 포함

## 📚 커리큘럼 구성

| Part | 제목 | 난이도 | 학습시간 |
|------|------|--------|----------|
| 01 | 개발자 브랜딩 & 문서화 | ★☆☆☆☆ | 약 3시간 |
| 02 | AI 이미지 & 영상 생성 파이프라인 | ★★☆☆☆ | 약 5시간 |
| 03 | n8n 자동화 워크플로우 | ★★☆☆☆ | 약 6시간 |
| 04 | Wan Move 모션 그래픽 | ★★★☆☆ | 약 4시간 |
| 05 | LangExtract 정보 추출 | ★★★☆☆ | 약 4시간 |
| 06 | AI Agent 실전 활용 | ★★★☆☆ | 약 6시간 |
| 07 | AI 트레이딩 자동화 | ★★★★☆ | 약 5시간 |
| 08 | Computer Vision 실전 프로젝트 | ★★★★☆ | 약 7시간 |
| 09 | Palantir Foundry 기초 | ★★★★★ | 약 8시간 |

**총 77개 강의 / 약 48시간**

## 🛠️ 사용 기술

- HTML5 / CSS3 / Vanilla JavaScript
- LocalStorage (진행률 저장)
- Lucide Icons
- Google Fonts (Noto Sans KR)

## 🚀 배포 방법

### GitHub Pages

1. 이 저장소를 Fork하거나 Clone
2. Settings → Pages
3. Source: `main` branch, `/ (root)` 선택
4. Save 후 몇 분 대기
5. `https://tygwan.github.io/ai-master-class/` 접속

### 로컬 실행

```bash
# 저장소 클론
git clone https://github.com/tygwan/ai-master-class.git
cd ai-master-class

# 로컬 서버 실행 (Python)
python -m http.server 8000

# 또는 VS Code Live Server 사용
```

## 📁 프로젝트 구조

```
ai-curriculum/
├── index.html      # 메인 페이지 (단일 파일)
├── README.md       # 프로젝트 설명
└── LICENSE         # 라이선스
```

## 🔧 커스터마이징

### 커리큘럼 수정

`index.html` 파일 내 `curriculumData` 배열을 수정하세요:

```javascript
const curriculumData = [
  {
    id: 1,
    title: "Part 제목",
    subtitle: "부제목",
    difficulty: 1,  // 1-5
    duration: "약 3시간",
    icon: "✨",
    color: "#10B981",
    chapters: [...]
  },
  // ...
];
```

### 상세 가이드 수정

`detailedGuides` 객체를 수정하세요:

```javascript
const detailedGuides = {
  1: {
    objectives: [...],
    prerequisites: [...],
    steps: [...],
    project: {...},
    resources: [...],
    tips: [...]
  },
  // ...
};
```

## 📄 라이선스

MIT License - 자유롭게 사용, 수정, 배포 가능

## 🤝 기여

이슈나 PR은 언제나 환영합니다!

---

Made with ❤️ for AI Education
