# easy-study 다운로드

강의 PDF를 슬라이드 단위로 LLM 튜터(Claude Code · Codex · Claude API · OpenAI API)와 함께 공부하는 데스크톱 앱이에요.
이 저장소에는 **설치 파일만** 있어요. 소스 코드는 비공개예요.

## 설치

[최신 릴리스](https://github.com/Wooangha/easy-study-releases/releases/latest)에서 내려받으세요.

| 운영체제 | 파일 |
|---|---|
| macOS (Apple Silicon) | `easy-study_<버전>_aarch64.dmg` |
| macOS (Intel) | `easy-study_<버전>_x64.dmg` |
| Windows (x64) | `easy-study_<버전>_x64-setup.exe` |
| Linux (Debian/Ubuntu) | `easy-study_<버전>_amd64.deb` / `_arm64.deb` |
| Linux (Fedora 등) | `easy-study-<버전>-1.x86_64.rpm` / `.aarch64.rpm` |
| Linux (AppImage) | `easy-study_<버전>_amd64.AppImage` / `_aarch64.AppImage` |
| Arch Linux | `easy-study-bin-<버전>-1-x86_64.pkg.tar.zst` (또는 `PKGBUILD`로 `makepkg -si`) |

### 처음 열 때

- **macOS:** 앱이 Apple 공증을 받지 않아서 "열지 않음" 창이 떠요. **시스템 설정 → 개인정보 보호 및 보안**에서 맨 아래 **그래도 열기**를 누르세요.
- **Windows:** SmartScreen 창이 뜨면 **추가 정보 → 실행**을 누르세요.

## 업데이트

0.5.0부터는 앱이 새 버전을 알려 줘요. **⚙ 설정**의 "업데이트" 버튼 한 번으로 설치돼요 (Linux의 deb/rpm/Arch 설치는 이 페이지에서 새 파일을 받아 주세요).
업데이트 파일은 서명돼 있어서 앱은 이 저장소의 진짜 파일만 설치해요.

## 라이선스 고지

앱에 들어 있는 FFmpeg(LGPL 2.1+)의 소스 코드는 각 릴리스에 `easy-study-ffmpeg-<버전>-source.tar`로 함께 올라가요. 그 밖의 고지는 앱의 `THIRD_PARTY_NOTICES.md`에 있어요.
