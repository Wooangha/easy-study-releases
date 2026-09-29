# easy-study

강의 PDF를 한 장씩 넘기면서, 옆 창의 AI 튜터에게 바로 물어보는 공부 앱이에요.
지금 보고 있는 슬라이드를 AI가 같이 보면서 설명해 주고, 질문과 답은 슬라이드별로 정리돼요.
강의를 녹음하면 받아쓴 내용이 슬라이드에 맞춰 붙어요.

## 준비물

- **AI 계정 하나:** Claude Code 구독, Codex(ChatGPT) 구독, 또는 Anthropic/OpenAI API 키.
  앱은 여러분의 계정으로 AI를 불러요. 따로 결제할 건 없어요.
- **컴퓨터:** macOS 13.5 이상, Windows 10/11, 또는 Linux(Ubuntu 22.04 이상 등).

## 설치하기

1. **[최신 버전 받기](https://github.com/Wooangha/easy-study-releases/releases/latest)** 페이지를 열어요.
2. 내 컴퓨터에 맞는 파일을 받아요.

   | 컴퓨터 | 받을 파일 |
   |---|---|
   | Mac (M1 · M2 · M3 · M4) | `easy-study_…_aarch64.dmg` |
   | Mac (Intel) | `easy-study_…_x64.dmg` |
   | Windows | `easy-study_…_x64-setup.exe` |
   | Ubuntu · Debian | `easy-study_…_amd64.deb` (ARM 컴퓨터는 `_arm64.deb`) |
   | Fedora 등 | `easy-study-…x86_64.rpm` |
   | 그 밖의 Linux | `easy-study_…AppImage` (실행 권한을 주고 바로 실행) |
   | Arch Linux | `easy-study-bin-…pkg.tar.zst` → `sudo pacman -U 파일이름` |

3. 설치하고 실행해요. Mac은 dmg를 열고 앱을 **응용 프로그램** 폴더로 끌어다 놓으세요.

## 처음 열 때 "열 수 없다"고 나오면

개인이 만든 앱이라 Apple · Microsoft 인증서가 없어서 나오는 안내예요. 아래처럼 한 번만 허용하면 돼요.

- **Mac:** "열지 않음" 창에서 **완료** → **시스템 설정 → 개인정보 보호 및 보안** → 맨 아래 **그래도 열기** → 암호 입력.
- **Windows:** "Windows의 PC 보호" 창에서 **추가 정보 → 실행**.

## 처음 실행하면

1. **이 컴퓨터에서 실행**을 누르세요. (다른 컴퓨터에서 켜 둔 easy-study에 접속할 수도 있어요.)
2. 강의 PDF를 창에 끌어다 놓으면 슬라이드가 준비돼요.
3. 오른쪽 위에서 어떤 AI를 쓸지 고르고, 슬라이드에 대해 물어보세요.

## 업데이트

새 버전이 나오면 앱이 알려 줘요. **⚙ 설정 → 업데이트** 버튼 한 번이면 끝이에요.
(Linux에서 deb · rpm · Arch 패키지로 설치했다면 이 페이지에서 새 파일을 받아 주세요.)

## 자주 묻는 질문

- **내 자료가 어딘가로 올라가나요?**
  아니요. 강의 자료, 노트, 녹음은 내 컴퓨터에만 있어요. AI에게 물어볼 때만 그 슬라이드가 여러분의 AI 계정으로 전달돼요.
- **소스 코드는 어디 있나요?**
  비공개예요. 이 저장소에는 설치 파일만 있어요.
- **문제가 생겼어요.**
  [Issues](https://github.com/Wooangha/easy-study-releases/issues)에 남겨 주세요.

## 라이선스 고지

앱에 들어 있는 FFmpeg(LGPL 2.1+)의 소스 코드는 각 릴리스에 `easy-study-ffmpeg-…-source.tar`로 함께 올라가요.
그 밖의 고지는 앱 안의 `THIRD_PARTY_NOTICES.md`에 있어요.
