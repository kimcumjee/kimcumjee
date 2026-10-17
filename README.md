# 한승재 · iOS Developer

Swift로 앱의 기반을 만들고, 여러 앱이 함께 쓰는 프레임워크와 빌드·배포 환경까지 설계하는 모바일 개발자입니다.
iOS · Android · Flutter 환경에서 5년간 제품을 만들어 왔고, 지금은 iOS Native에 집중하고 있습니다.

## 지금까지 한 일

**Flutter WebView 앱 → Swift·Kotlin 하이브리드 전환** · 인티그레이션, 2024–2025
모든 화면을 다시 만드는 대신 하단 탭·라우팅·로그인·결제·사진 뷰어 등 앱 기반부터 Native로 전환하고 Flutter·Dart 의존성을 제거했습니다.
- iOS 홈 콘텐츠 표시 시간 **10.40s → 5.33s** (약 49% 단축, 메디스트림 3.2.8 → 4.0.0 동일 단말 비교)
- Android 신규 설치 크기 **43.7MB → 8.42MB** (80.7% 감소, Google Play Console 기준)

**SuperAppFramework · 공통 하이브리드 프레임워크 설계**
서비스마다 달랐던 30여 개 네이티브↔웹 브릿지의 이름·입력·응답 규격을 하나의 계약으로 통일하고, 라우팅·결제·소셜 로그인·미디어·권한·로깅을 공통 모듈로 묶었습니다. iOS는 SPM, Android는 AAR로 배포해 **5개 서비스(iOS·Android 10개 앱)** 에 적용했습니다.

**Tuist 기반 iOS 멀티 앱 프로젝트 코드화**
5개 iOS 앱의 `.xcodeproj`를 `Project.swift`로 대체하고, dev·stg·prod 타깃·Bundle ID·앱 아이콘·FCM 설정이 환경별로 자동 분기되게 했습니다.

**태그 기반 배포 파이프라인**
`Git Tag → GitHub Actions → 전용 빌드머신(Fastlane) → 배포 채널 → Slack`. versionCode 자동 산정, 채널별 분기, 빌드머신 장애 시 Claude Code 로컬 배포로 전환되는 폴백까지 구성했습니다.

**Firebase AI(Gemini) 기반 식단 분석** · 린다이어트, MAU 2만
음식 사진 분석 결과를 JSON Schema로 구조화해 받고, 신뢰도 80% 이상만 자동 반영하고 나머지는 사용자가 확인·수정하는 흐름으로 설계했습니다. 사진+텍스트 식단 기록 비중 **23% → 54%** (Segment 기준).

## 기술 스택

| 영역 | 사용 |
|---|---|
| **iOS** | Swift, UIKit, SnapKit, Combine, WebKit, SPM, Tuist |
| **Android** | Kotlin, WebView, AAR |
| **Cross-platform** | Flutter, Dart, Riverpod |
| **Architecture** | MVVM, Clean Architecture, Hybrid WebView, Native↔Web Bridge |
| **Build / Deploy** | Fastlane, GitHub Actions, Firebase App Distribution |
| **AI / Data** | Firebase AI(Gemini), JSON Schema, Segment, Claude Code |

## 경력

| 회사 | 역할 | 기간 | 주요 업무 |
|---|---|---|---|
| 인티그레이션 (메디스트림 · 린다이어트) | Mobile Developer | 2023.04 – 현재 | 하이브리드 앱 Native 전환, 공통 프레임워크, 빌드·배포 환경, AI 제품 기능 |
| 샵라이브 | iOS Developer | 2022.04 – 2023.04 | 라이브 커머스 송출 앱·Player SDK, SnapKit Code-based UI + MVVM |
| 스파이더크래프트 | Android Developer | 2021.07 – 2021.12 | 배달대행 라이더 앱 (실시간 채팅, 분할결제, Push) |

## 글

- [JS로 슈퍼앱 만들기 with Flutter a.k.a. 모바일 MSA 아키텍처](https://velog.io/@medistream/JS-%EB%A1%9C-%EC%8A%88%ED%8D%BC%EC%95%B1-%EB%A7%8C%EB%93%A4%EA%B8%B0-with-Flutter-a.k.a.-%EB%AA%A8%EB%B0%94%EC%9D%BC-MSA-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98)
- ["배포해 줘"로 끝내는 Fastlane 자동화](https://velog.io/@medistream/Mobile-%EB%B0%B0%ED%8F%AC%ED%95%B4-%EC%A4%98%EB%A1%9C-%EB%81%9D%EB%82%B4%EB%8A%94-Fastlane-%EC%9E%90%EB%8F%99%ED%99%94)
- [태그 하나로 끝내는 배포 파이프라인](https://velog.io/@medistream/%ED%83%9C%EA%B7%B8-%ED%95%98%EB%82%98%EB%A1%9C-%EB%81%9D%EB%82%B4%EB%8A%94-%EB%B0%B0%ED%8F%AC-%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8)
- [개발자 3명, 디자이너 1명 — AI로 디자인 병목을 해소한 이야기](https://velog.io/@medistream/%EA%B0%9C%EB%B0%9C%EC%9E%90-3%EB%AA%85-%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88-1%EB%AA%85-AI%EB%A1%9C-%EB%94%94%EC%9E%90%EC%9D%B8-%EB%B3%91%EB%AA%A9%EC%9D%84-%ED%95%B4%EC%86%8C%ED%95%9C-%EC%9D%B4%EC%95%BC%EA%B8%B0)

## 만든 앱

- [App Store · Medistream Corp.](https://apps.apple.com/kr/developer/medistream-corp/id1573511491) · [Google Play · MEDISTREAM](https://play.google.com/store/apps/developer?id=MEDISTREAM)
- [린다이어트 · App Store](https://apps.apple.com/kr/app/id6444097742)

## 연락

- 📧 sheep103132@naver.com
- 📄 [포트폴리오 (Notion)](https://hsj2003.notion.site/f13079b9c690498a8939a6a0a10d2edd)
