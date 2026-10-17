## 경력

### [인티그레이션](https://medistream.co.kr/) Mobile Engineer
*2023.04 - 현재*
- 메디스트림·모어덴·치즈톡·치크루팅·업스트림 5개 서비스의 iOS·Android 앱과 Flutter 다이어트 앱 린다이어트(MAU 2만)를 개발합니다.
- Flutter WebView 앱의 Swift·Kotlin 전환, 공통 하이브리드 프레임워크, Tuist 프로젝트 코드화, 태그 기반 배포 파이프라인을 설계·구축했습니다.

### [샵라이브](https://www.shoplive.cloud/) iOS Engineer
*2022.04 - 2023.04*
- 라이브 커머스 솔루션 샵라이브에서 iOS 송출 앱과 Player SDK를 개발했습니다.
- SnapKit Code-based UI와 MVVM을 도입하고, 방송 중 가로·세로 동적 전환 Player UI를 구현했습니다.

### 스파이더크래프트 Android Engineer
*2021.07 - 2021.12*
- 배달대행 라이더 전용 Android 앱의 실시간 채팅, 분할결제, 공지 Push 알림을 개발했습니다.

<br>

## 주요 프로젝트

### Flutter WebView → Swift·Kotlin Native 전환
*2024.01 - 2025.05*
- 하단 탭·라우팅·로그인·결제·사진 뷰어를 Native로 전환하고 Flutter·Dart 의존성 제거
- iOS 홈 콘텐츠 표시 **10.40s → 5.33s** · Android 설치 크기 **43.7MB → 8.42MB**

### SuperAppFramework · 하이브리드 앱 공통 프레임워크
*2024.01 - 현재*
- 30여 개 네이티브↔웹 브릿지 규격 통일, iOS SPM · Android AAR 배포, 5개 서비스 10개 앱 적용
- 글: [JS로 슈퍼앱 만들기 with Flutter a.k.a. 모바일 MSA 아키텍처](https://velog.io/@medistream/JS-%EB%A1%9C-%EC%8A%88%ED%8D%BC%EC%95%B1-%EB%A7%8C%EB%93%A4%EA%B8%B0-with-Flutter-a.k.a.-%EB%AA%A8%EB%B0%94%EC%9D%BC-MSA-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98)

### Tuist 기반 iOS 멀티 앱 프로젝트 코드화
*2024.06 - 2024.08*
- 5개 iOS 앱의 `.xcodeproj`를 `Project.swift`로 대체, dev·stg·prod 타깃·Bundle ID·FCM 자동 분기

### 태그 기반 배포 파이프라인
*2026.02 - 2026.06*
- `Git Tag → GitHub Actions → 빌드머신(Fastlane) → 배포 채널 → Slack`, 빌드머신 장애 시 Claude Code 폴백
- 글: [태그 하나로 끝내는 배포 파이프라인](https://velog.io/@medistream/%ED%83%9C%EA%B7%B8-%ED%95%98%EB%82%98%EB%A1%9C-%EB%81%9D%EB%82%B4%EB%8A%94-%EB%B0%B0%ED%8F%AC-%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8) · ["배포해 줘"로 끝내는 Fastlane 자동화](https://velog.io/@medistream/Mobile-%EB%B0%B0%ED%8F%AC%ED%95%B4-%EC%A4%98%EB%A1%9C-%EB%81%9D%EB%82%B4%EB%8A%94-Fastlane-%EC%9E%90%EB%8F%99%ED%99%94)

### Firebase AI(Gemini) 식단 분석 · 린다이어트
*2025.09 - 현재*
- 음식 사진 → JSON Schema 구조화 응답, 신뢰도 80% 이상만 자동 반영 · 사진+텍스트 기록 비중 **23% → 54%**
- 글: [개발자 3명, 디자이너 1명 — AI로 디자인 병목을 해소한 이야기](https://velog.io/@medistream/%EA%B0%9C%EB%B0%9C%EC%9E%90-3%EB%AA%85-%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88-1%EB%AA%85-AI%EB%A1%9C-%EB%94%94%EC%9E%90%EC%9D%B8-%EB%B3%91%EB%AA%A9%EC%9D%84-%ED%95%B4%EC%86%8C%ED%95%9C-%EC%9D%B4%EC%95%BC%EA%B8%B0)

<br>

## 기술 스택

### iOS

![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=for-the-badge&logo=apple&logoColor=white)
![WKWebView](https://img.shields.io/badge/WKWebView-1A1A1A?style=for-the-badge&logo=apple&logoColor=white)
![SnapKit](https://img.shields.io/badge/SnapKit-2C7BE5?style=for-the-badge)
![SPM](https://img.shields.io/badge/SPM-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Tuist](https://img.shields.io/badge/Tuist-6236FF?style=for-the-badge)

### Flutter

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-1E88E5?style=for-the-badge)
![go_router](https://img.shields.io/badge/go__router-02569B?style=for-the-badge&logo=flutter&logoColor=white)

### Build · Deploy

![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=for-the-badge&logo=fastlane&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

### AI

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=for-the-badge)

<br>

## 앱

[![App Store](https://img.shields.io/badge/App_Store-Medistream_Corp.-0D96F6?style=for-the-badge&logo=appstore&logoColor=white)](https://apps.apple.com/kr/developer/medistream-corp/id1573511491)
[![Google Play](https://img.shields.io/badge/Google_Play-MEDISTREAM-414141?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/developer?id=MEDISTREAM)
[![린다이어트](https://img.shields.io/badge/App_Store-린다이어트-0D96F6?style=for-the-badge&logo=appstore&logoColor=white)](https://apps.apple.com/kr/app/id6444097742)

<br>

## 학력

- **서울사이버대학교 컴퓨터공학과**<br>
*2025.03 - 재학중*

- **대구소프트웨어마이스터고등학교**<br>
*2019.03 - 2022.02*

<br>

## 연락처

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kimcumjee)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://hsj2003.notion.site/f13079b9c690498a8939a6a0a10d2edd)
[![Email](https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:sheep103132@naver.com)
