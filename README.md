# 성도용 AI 활용 준비도 체크리스트

교회 성도들의 AI 기술 활용 준비 상태를 평가하고 개선 방향을 제시하는 인터랙티브 웹 애플리케이션입니다.

## 🎯 프로젝트 소개

이 체크리스트는 교회 성도들이 AI 기술을 신앙생활과 일상에서 효과적으로 활용할 수 있는 준비 상태를 점검하기 위해 개발되었습니다. 개인의 디지털 역량과 AI에 대한 이해도를 파악하여 보다 나은 활용 방향을 제시하는 것이 목표입니다.

## ✨ 주요 기능

- **6개 영역의 종합 평가**
  - AI에 대한 기본 이해도
  - 디지털 기기 활용 능력
  - 신앙생활에서의 AI 활용 의지
  - AI의 신앙적 가치 인식
  - 학습 및 적응 의지
  - AI 윤리 및 안전 의식

- **개인 맞춤형 피드백**
  - 실시간 진행률 표시
  - 즉시 점수 계산
  - 개인 수준에 맞는 학습 방향 제시

- **사용자 친화적 설계**
  - 모바일, 태블릿, 데스크톱 지원
  - 직관적이고 접근하기 쉬운 인터페이스
  - 연령대를 고려한 친근한 문항 구성

## 🚀 데모

[Live Demo](https://takwhankim.github.io/christian-church-ai-readiness-checklist)

## 📊 평가 기준

| 점수 범위 | 등급 | 설명 |
|-----------|------|------|
| 40-50점 | AI 활용 준비 완료 | AI를 효과적으로 활용할 준비가 잘 되어 있음 |
| 30-39점 | 기본 준비 완료 | 추가 학습을 통해 더 나은 활용 가능 |
| 20-29점 | 학습 필요 | 기초적인 학습과 연습이 필요한 상태 |
| 19점 이하 | 단계적 접근 권장 | 디지털 기초부터 차근차근 시작 |

## 💻 설치 및 사용법

### GitHub Pages로 배포하기

1. 이 저장소를 fork 하거나 다운로드
2. GitHub 저장소 설정에서 Pages 활성화
3. `main` 브랜치의 루트 디렉토리를 소스로 설정
4. 생성된 URL로 접속하여 사용

### 로컬에서 실행하기

```bash
# 저장소 클론
git clone https://github.com/takwhankim/christian-church-ai-readiness-checklist.git

# 디렉토리 이동
cd christian-church-ai-readiness-checklist

# 웹 서버 실행 (Python 3 사용 예시)
python -m http.server 8000

# 브라우저에서 http://localhost:8000 접속
```

## 📁 프로젝트 구조

```
christian-church-ai-readiness-checklist/
├── index.html          # 메인 HTML 파일
├── README.md           # 프로젝트 문서
├── LICENSE            # 라이선스 파일
└── assets/
    ├── images/        # 이미지 파일들 (스크린샷 등)
    └── docs/          # 추가 문서들
```

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: CSS Grid, Flexbox, CSS Animations
- **Responsive**: Mobile-first 반응형 디자인
- **Accessibility**: 연령대를 고려한 사용자 친화적 인터페이스

## 👥 대상 사용자

- **교회 성도들**: 모든 연령대의 교회 구성원
- **목회자**: 성도들의 AI 활용 수준 파악을 원하는 분
- **교회 교육팀**: 디지털 교육 계획 수립을 위한 기초 자료 필요
- **소그룹 리더**: 소그룹 내 AI 활용 교육 계획

## 📈 활용 방안

### 개인 활용
- 본인의 AI 활용 준비도 점검
- 개인 학습 계획 수립
- 신앙생활에서의 AI 활용 방향 모색

### 교회 활용
- 성도들의 전체적인 디지털 역량 파악
- 교육 프로그램 기획을 위한 기초 데이터
- 세대별, 그룹별 특성에 맞는 교육 계획 수립

### 소그룹 활용
- 소그룹 모임에서 함께 진단하고 결과 나누기
- 서로 돕는 학습 파트너 찾기
- 디지털 세대와 시니어 세대 간의 소통 도구

## 🤝 기여하기

1. 이 저장소를 Fork
2. 새로운 브랜치 생성 (`git checkout -b feature/새기능`)
3. 변경사항 커밋 (`git commit -am '새기능 추가'`)
4. 브랜치에 Push (`git push origin feature/새기능`)
5. Pull Request 생성

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

## 📞 문의

프로젝트에 대한 질문이나 제안사항이 있으시면 언제든 연락주세요!

- 이슈 트래커: [GitHub Issues](https://github.com/takwhankim/christian-church-ai-readiness-checklist/issues)
- 제작자: onmam

## 🔗 관련 프로젝트

- [목회자 및 사역자용 AI 도입 체크리스트](https://github.com/takwhankim/church-ai-readiness-checklist)

## 🏷️ 버전 히스토리

### v1.0.0 (2025-07-22)
- 초기 릴리스
- 10개 질문으로 구성된 성도용 체크리스트
- 6개 평가 영역 구성
- 반응형 웹 디자인 적용
- 실시간 점수 계산 및 개인 맞춤형 결과 제공

---

⭐ 이 프로젝트가 도움이 되셨다면 별표를 눌러주세요!

**Made by onmam** 💙
