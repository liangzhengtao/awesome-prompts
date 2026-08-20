[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# 🚀 Awesome Prompts

**개발자, 창작자, 전문가를 위한 150개 이상의 검증된 AI 프롬프트. 복사, 붙여넣기, 결과 확인.**

---

<p align="center">
  <img src="https://img.shields.io/badge/prompts-150+-blue" alt="150+ Prompts">
  <img src="https://img.shields.io/badge/categories-5-green" alt="5 Categories">
  <img src="https://img.shields.io/badge/language-bilingual-yellow" alt="Bilingual">
  <img src="https://img.shields.io/badge/license-MIT-red" alt="MIT License">
</p>

---



## 🤔 왜 Awesome Prompts인가?

### 이전 (모호한 프롬프트) ❌

```
코드 리뷰를 작성해줘
```

### 이후 (정확한 프롬프트) ✅

```
당신은 시니어 보안 엔지니어입니다. 다음 코드에 대해 OWASP Top 10 보안 감사를 수행하세요.

언어: Python
프레임워크: Django
코드:
[코드를 붙여넣으세요]

다음 형식으로 출력하세요:
1. 🔴 심각한 취약점 (Critical)
2. 🟠 높은 취약점 (High)
3. 🟡 중간 취약점 (Medium)
4. 🔵 낮은 취약점 (Low)

각 문제에는 다음을 포함하세요: 문제 설명, 위험 수준, 공격 시나리오, 수정 제안 (코드 예시 포함)
```

**결과: 매번 10배 더 나은 출력.**

---

## 📂 카테고리

<table>
<tr>
<td width="50%">

### 💻 프로그래밍 개발
| 프롬프트 파일 | 프롬프트 |
|-------------|---------|
| [코드 리뷰](prompts/编程开发/code-review.md) | 보안 감사, 성능, 가독성, 아키텍처 |
| [디버깅](prompts/编程开发/debugging.md) | 오류 분석, 스택 트레이스, 근본 원인 분석 |
| [리팩토링](prompts/编程开发/refactoring.md) | 메서드 추출, 조건 단순화, 네이밍 최적화 |
| [문서화](prompts/编程开发/documentation.md) | README, API 문서, 코드 주석 |

</td>
<td width="50%">

### ✍️ 콘텐츠 창작
| 프롬프트 파일 | 프롬프트 |
|-------------|---------|
| [블로그 글쓰기](prompts/内容创作/blog-writing.md) | 개요, 훅, SEO, 결론 |
| [소셜 미디어](prompts/内容创作/social-media.md) | Twitter, LinkedIn, Instagram, TikTok |
| [이메일 시퀀스](prompts/内容创作/email-sequences.md) | 환영 시퀀스, 육성, 판매, 재활성화 |

</td>
</tr>
<tr>
<td width="50%">

### 💼 비즈니스 사무
| 프롬프트 파일 | 프롬프트 |
|-------------|---------|
| [비즈니스 전략](prompts/商业办公/business-strategy.md) | SWOT, 경쟁 분석, 시장 조사 |
| [프레젠테이션](prompts/商业办公/presentation.md) | 슬라이드, 발표 노트, Q&A |
| [프로젝트 관리](prompts/商业办公/project-management.md) | 요구사항, 리스크, 보고서, 회고 |

</td>
<td width="50%">

### 📚 교육 학습
| 프롬프트 파일 | 프롬프트 |
|-------------|---------|
| [학습 도우미](prompts/学习教育/study-assistant.md) | 개념 설명, 플래시카드, 퀴즈, 학습 계획 |
| [교육](prompts/学习教育/teaching.md) | 수업 계획, 평가 기준, 학생 피드백 |
| [연구](prompts/学习教育/research.md) | 문헌 리뷰, 가설, 연구 설계 |

</td>
</tr>
<tr>
<td colspan="2">

### 🎨 창의적 디자인
| 프롬프트 파일 | 프롬프트 |
|-------------|---------|
| [이미지 생성](prompts/创意设计/image-generation.md) | 스타일 수정, 구도, 품질 향상, 네거티브 프롬프트 (20+ 템플릿) |
| [창의적 글쓰기](prompts/创意设计/creative-writing.md) | 이야기 시작, 캐릭터 생성, 세계 구축, 대화 (15+ 템플릿) |

</td>
</tr>
</table>

---

## 🚀 빠른 시작

### 1. 탐색

위의 카테고리를 선택하고 필요한 프롬프트를 찾으세요.

### 2. 복사

프롬프트 템플릿을 복사하고 `[VARIABLES]`를 구체적인 정보로 교체하세요.

### 3. 붙여넣기 & 결과 확인

좋아하는 AI 도구(ChatGPT, Claude, Gemini 등)에 붙여넣고 고품질 결과를 얻으세요.

---

## 📖 사용법

### 변수

모든 프롬프트는 교체해야 하는 `[VARIABLES]`를 사용합니다:

```
[TOPIC]       → 구체적인 주제
[LANGUAGE]    → 프로그래밍 언어
[AUDIENCE]    → 대상 독자
[CODE]        → 실제 코드
```

### 팁

1. **구체적으로**:提供更多 컨텍스트를 제공할수록 결과가 더 좋습니다.

2. **반복하기**: 첫 번째 출력을 시작점으로 사용하고 개선하세요.

3. **조합하기**: 복잡한 작업을 위해 다른 카테고리의 프롬프트를 혼합하세요.

4. **커스터마이징**: 워크플로우와 스타일에 맞게 프롬프트를 수정하세요.

---

## 🤝 기여

기여를 환영합니다! [기여 가이드](CONTRIBUTING.md)를 먼저 읽어주세요.

### 기여 방법

- 🆕 새 프롬프트 추가
- ✏️ 기존 프롬프트 개선
- 🐛 오류나 오타 수정
- 🌍 번역 추가
- ⭐ 다른 사람과 공유

---

## 📊 통계

| 카테고리 | 파일 | 프롬프트 |
|----------------|-------------|-----------------|
| 💻 프로그래밍 개발 | 4 | 64 |
| ✍️ 콘텐츠 창작 | 3 | 50+ |
| 💼 비즈니스 사무 | 3 | 48+ |
| 📚 교육 학습 | 3 | 50+ |
| 🎨 창의적 디자인 | 2 | 35+ |
| **합계** | **15** | **247+** |

---

## 📜 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다 — 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

---

## ⭐ 스타 히스토리

도움이 되셨다면 스타를 눌러주세요! ⭐

---

## 📬 연락처

- **이슈**: [GitHub Issues](https://github.com/liangzhengtao/awesome-prompts/issues)
- **토론**: [GitHub Discussions](https://github.com/liangzhengtao/awesome-prompts/discussions)

---

<p align="center">
  커뮤니티가 ❤️으로 만들었습니다<br>
  <a href="#top">맨 위로 ↑</a>
</p>

---
