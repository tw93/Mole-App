# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · 한국어 · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

**Mole for Mac**과 **Mole for Windows**의 공식 문서와 커뮤니티 지원을 모아 둔 저장소입니다.

Mac과 Windows 앱은 유료 네이티브 데스크톱 앱이며, 라이선스 구매는 개발과 업데이트를 지원합니다. 이 저장소는 문서, 질문, 피드백을 위한 곳이라 앱 소스 코드는 들어 있지 않습니다. [Mole CLI](https://github.com/tw93/Mole)는 계속 무료 오픈 소스입니다.

## Mole 받기

| 앱 | 요구 사항 | 다운로드 | 사용 가이드 |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 이상, Apple Silicon 또는 Intel | [Mac 웹사이트](https://mole.fit/ko/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Mac 도움말](https://mole.fit/ko/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 또는 Windows 11, x64 또는 ARM64 | [Windows 웹사이트](https://mole.fit/ko/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Windows 도움말](https://mole.fit/ko/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

두 앱 모두 정리, 앱 관리, 유지 관리, 디스크 분석, 실시간 시스템 상태를 하나의 화면에서 제공합니다.

### Mole for Mac

Mole for Mac은 [Tw93](https://github.com/tw93)가 만들고 관리하는 네이티브 SwiftUI 앱이며, 메뉴 막대에서도 자주 쓰는 도구를 바로 열 수 있습니다.

![Mole for Mac 정리 화면](https://mole.fit/img/ko/clean.jpg)

| 도구 | 할 수 있는 일 | 가이드 |
| --- | --- | --- |
| 정리 | 앱과 브라우저 캐시, 로그, 개발 빌드 파일을 먼저 확인한 뒤 삭제할 항목을 선택합니다 | [Mac 정리](https://mole.fit/ko/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 앱 | 앱을 제거하고 남은 파일을 검토하며, 업데이트를 확인하고 시작 항목을 관리합니다 | [앱 관리](https://mole.fit/ko/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 최적화 | macOS 유지 관리를 실행하고, 화면 닦기나 화면 켜기 유지를 사용합니다 | [Mac 유지 관리](https://mole.fit/ko/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 분석 | 디스크 트리맵으로 큰 파일과 폴더를 찾고, Finder에서 보거나 선택한 항목을 휴지통으로 이동합니다 | [디스크 분석](https://mole.fit/ko/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 상태 | CPU, 메모리, 저장 공간, 네트워크, 온도를 확인하고, 선택한 지표는 메뉴 막대에 표시할 수 있습니다 | [시스템 모니터](https://mole.fit/ko/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### AI 정리 · 베타

베타 버전에는 정리 안에 AI 도구 정리 및 관리가 추가됩니다. Claude Code, Codex, Cursor 등 AI 도구가 남긴 캐시, 이전 버전, 오래된 채팅, 정리할 수 있는 worktree, 사용하지 않는 명령줄 도구를 확인합니다. 캐시는 기본으로 선택되고, 채팅과 도구는 직접 검토해야 합니다. 메모리, 계획, 스킬 파일은 대상에서 제외됩니다. 로컬 모델은 한 달 넘게 쓰지 않은 Ollama 모델만 목록에 나오며, 직접 선택해 Ollama로 삭제합니다. 자세한 내용은 [AI 정리 가이드](https://mole.fit/ko/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai)를 참고하세요.

### Mac에서 시작하기

1. 위의 Mac 웹사이트에서 DMG를 내려받아 Mole을 응용 프로그램 폴더로 옮긴 뒤 실행합니다. Homebrew를 이미 쓰고 있다면 `brew install --cask mole-app`으로 Mac 앱을 설치할 수도 있습니다.
2. 스캔한 뒤 결과를 확인하고 삭제할 항목을 정합니다. 디스크 접근 권한이 없다고 나오면 아래 권한 가이드대로 설정하고 Mole을 다시 실행하세요.
3. 구매 후 `Cmd + Shift + L`로 라이선스 패널을 열고, Dodo Payments 메일에 있는 키를 붙여 넣은 다음 활성화를 누릅니다.

[Mac 글](https://mole.fit/ko/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Mac 릴리스 노트](https://mole.fit/ko/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### 추천 Mac 가이드

- [Mole CLI와 Mac 앱의 차이](https://mole.fit/ko/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 무료 터미널 도구와 유료 네이티브 앱이 각각 무엇을 하는지 알아봅니다.
- [Mole은 Mac에서 안전한가요?](https://mole.fit/ko/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 무엇이 휴지통으로 가고, 무엇이 영구 삭제되며, 무엇이 보호되는지 설명합니다.
- [Mac의 시스템 데이터란?](https://mole.fit/ko/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 삭제하기 전에 무엇이 공간을 차지하는지 먼저 찾아봅니다.
- [Mac 제거 후 남은 파일 검토하기](https://mole.fit/ko/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 삭제 전에 파일의 소유 앱과 공유 데이터를 확인합니다.
- [Ollama와 LM Studio 모델 삭제하기](https://mole.fit/ko/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 내려받은 모델, 캐시, 개인 데이터를 구분합니다.
- [Mole을 위한 Mac 앱 테스트](https://mole.fit/ko/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 실제로 설치하고 제거해 보면 무엇이 남는지 살펴봅니다.

### Mole for Windows

Windows 앱은 릴리스마다 계속 개선되고 있습니다.

![Mole for Windows 정리 화면](https://mole.fit/img/windows-ko/clean.jpg)

[Windows 글](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Windows 릴리스 노트](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## 피드백

- [Mac 앱 버그 신고](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Windows 앱 버그 신고](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [기능 제안](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [질문하거나 토론에 참여하기](https://github.com/tw93/Mole-App/discussions)

이슈와 토론은 공개됩니다. 구매, 활성화, 환불 문의는 [hi@mole.fit](mailto:hi@mole.fit)으로 메일을 보내 주세요. 보안 문제는 [비공개 신고 채널](.github/SECURITY.md)로 보내 주세요.

Mac 진단이 필요하면 Mole 로고 메뉴에서 Doctor 실행을 선택하세요. 보고서를 앱 버전, 겪은 상황과 함께 [hi@mole.fit](mailto:hi@mole.fit)으로 비공개로 보내 주시면 됩니다.

CLI 버그와 기능 요청은 [tw93/Mole](https://github.com/tw93/Mole/issues)에 남겨 주세요.

## FAQ

### GitHub 저장소가 공개라면 앱도 오픈 소스인가요?

이 저장소에는 문서와 커뮤니티 피드백만 있습니다. Mac과 Windows 앱의 소스 코드는 비공개입니다. [Mole CLI](https://github.com/tw93/Mole)는 무료 오픈 소스입니다.

### 앱을 쓰려면 CLI를 설치해야 하나요?

아니요. Mole for Mac과 Mole for Windows는 독립 실행형 데스크톱 앱입니다. CLI를 설치해도 두 앱이 설치되지는 않습니다.

### 앱은 무료인가요?

앱은 일회성 라이선스 방식입니다. Mole for Mac은 **Mac 두 대에 $19 USD**이며, 구독 없이 메이저 버전을 포함한 업데이트가 무료입니다. 현재 조건은 [공식 가격 페이지](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에서 확인할 수 있습니다. Windows의 가격과 제공 여부는 해당 제품 웹사이트에 있습니다. 오픈 소스 CLI는 무료입니다.

### 구매하기 전에 Mac 앱을 써 볼 수 있나요?

스캔은 무료이고, 유료 도구마다 두 번씩 체험할 수 있습니다. 디스크 분석과 시스템 상태는 라이선스 없이도 볼 수 있습니다. 내려받기, 체험, 활성화 방법은 [Mac 도움말 센터](https://mole.fit/ko/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에 있습니다.

### Mac 라이선스를 새 컴퓨터로 옮길 수 있나요?

이전 Mac에서 `Cmd + Shift + L`로 라이선스 패널을 열어 비활성화한 다음, 같은 키를 새 Mac에서 활성화하세요. 이전 Mac을 쓸 수 없다면 구매 이메일로 [Dodo Payments 고객 포털](https://customer.dodopayments.com/)에 로그인해 그곳에서 비활성화할 수 있습니다. 사용 가능한 기기 수는 구매한 라이선스에 따라 다르며, 현재 판매 중인 버전은 Mac 두 대를 지원합니다.

### 라이선스 키와 영수증은 어디에서 볼 수 있나요?

받은 편지함과 스팸 메일함에서 Dodo Payments를 검색하거나, 결제 때 쓴 이메일로 [Dodo Payments 고객 포털](https://customer.dodopayments.com/)에 로그인하면 키, 주문, 영수증을 확인할 수 있습니다. 그래도 찾지 못했다면 구매 이메일이나 Payment ID를 [hi@mole.fit](mailto:hi@mole.fit)으로 보내 주세요. 이 정보는 공개 이슈에 올리지 마세요.

### Mac 앱이 저와 맞지 않으면 어떻게 하나요?

구매 후 14일 이내에 Payment ID나 구매 이메일과 함께 [hi@mole.fit](mailto:hi@mole.fit)으로 메일을 보내 주세요. 전체 조건은 [환불 정책](https://mole.fit/ko/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에 있습니다.

### Mac 앱이 내 파일이나 스캔 결과를 업로드하나요?

스캔과 정리는 모두 Mac 안에서 이루어집니다. Mole은 파일 내용, 파일 이름, 스캔 결과를 업로드하지 않으며, 로컬 작업 로그도 자동으로 업로드되지 않습니다. 라이선스 활성화, 업데이트 등 온라인 서비스에 연결되는 기능은 [개인정보 처리방침](https://mole.fit/ko/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에서 설명합니다.

### Mole은 왜 디스크 접근 권한을 요청하나요?

macOS는 일부 앱 데이터의 접근을 제한합니다. 디스크 접근 권한을 허용하면 Mole이 그 위치를 살펴볼 수 있습니다. 보호된 경로와 사용자의 허용 목록은 그대로 적용되므로, 권한을 허용해도 모든 파일이 정리 대상이 되지는 않습니다. [권한 가이드](https://mole.fit/ko/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda)를 참고하세요.

### Mac 정리 후에 파일을 복원할 수 있나요?

제거한 앱과 선택한 남은 파일은 휴지통으로 이동하며, 휴지통에 있는 동안에는 복원할 수 있습니다. 캐시 정리는 기본적으로 영구 삭제이고, 설정에서 휴지통으로 이동하도록 바꿀 수 있습니다. 일부 유지 관리 작업은 데이터를 바로 삭제하므로 되돌릴 수 없습니다. 작업별 차이는 [안전 가이드](https://mole.fit/ko/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에서 설명합니다.

### Mac 업데이트와 베타 기능은 어떻게 동작하나요?

Mole에는 앱 내 업데이트 기능이 있으며, 릴리스마다 달라진 점은 [공식 릴리스 노트](https://mole.fit/ko/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에서 볼 수 있습니다. 문서에서 베타로 표시된 기능은 정식 버전에 포함되기 전까지 베타 버전에서만 쓸 수 있습니다.

### 키보드나 VoiceOver로도 쓸 수 있나요?

Mole은 키보드 탐색과 VoiceOver를 지원합니다. 트리맵은 시각 자료이며, 같은 파일을 큰 파일 목록에서 키보드나 VoiceOver로 둘러볼 수 있습니다. 자세한 내용과 현재의 한계는 [손쉬운 사용 가이드](https://mole.fit/ko/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)를 참고하세요.

### 공식 웹사이트는 어디인가요?

앱의 공식 웹사이트는 **mole.fit**입니다. 최신 설치 파일은 위의 다운로드 링크에서 받으세요. 무료 CLI는 [tw93/Mole](https://github.com/tw93/Mole)에 있습니다.

### 자세한 안내는 어디에서 볼 수 있나요?

[Mac 문서](https://mole.fit/ko/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에서 각 도구와 안전 규칙을 설명합니다. [테스트한 앱 목록](https://mole.fit/ko/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에는 개별 앱의 설치, 제거, 남은 파일 정보가 있습니다. 설정, 활성화, 문제 해결은 [Mac 도움말 센터](https://mole.fit/ko/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) 또는 [Windows 도움말 센터](https://mole.fit/ko/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)를 참고하세요. 라이선스 조건은 [이용약관](https://mole.fit/ko/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)에 있습니다.
