# MoaWing 편집기 내려받기

![모아윙 MoaWing 편집기](moawing-editor.png)

MoaWing 편집기는 한국어 영상 편집기입니다. 이 저장소는 Windows용 프로그램을 배포하는 곳입니다(소스 코드는 없습니다).

## 내려받기

**[최신 버전 내려받기](https://github.com/cnswk/moawing-editor-download/releases/latest)** — `MoaWingEditor-<버전>-windows-x64.zip`

설치 없이 웹에서 바로 쓰기: https://moawing-editor.pages.dev

## 실행 방법 (Windows 10·11, 64비트)

1. 내려받은 zip 파일을 마우스 오른쪽 버튼으로 누르고 **[모두 압축 풀기]** 를 고릅니다.
2. 압축을 푼 폴더에서 `MoaWingEditor.exe`를 실행합니다.
3. "Windows의 PC 보호" 창이 뜨면 **[추가 정보]** 를 누른 뒤 **[실행]** 을 누릅니다.
   아직 코드 서명 인증서가 없는 프로그램이라 나오는 안내입니다.

설정과 복구용 자동 저장 파일은 `%APPDATA%\MoaWing Editor` 폴더에 저장됩니다. 새 버전으로 바꿔도 설정은 그대로 남습니다.

## 자동 업데이트 (0.12.0부터)

편집기가 새 버전을 스스로 받아 같은 폴더에 설치합니다. 위쪽의 **[새 버전 · 다시 시작]** 을 누르거나 다음에 켤 때 새 버전으로 켜집니다.
**[도움말] > [자동 업데이트]** 로 끄고 켭니다. 각 릴리스의 `update.json`(버전 · 크기 · SHA-256 · 서명)을 확인한 뒤에만 설치합니다.
0.11.2 이하를 쓰고 있다면 최신 버전을 한 번만 직접 받아 주세요.

## 라이선스

MoaWing 편집기는 ArtCraft 팀의 [FilmCraft](https://github.com/storytold/filmcraft)(MIT 또는 Apache-2.0 라이선스)를 바탕으로 만들었습니다.
라이선스 원문(`LICENSE-MIT`, `LICENSE-APACHE`, `NOTICE`, `ATTRIBUTION.md`)과 글꼴 Pretendard의 라이선스(SIL Open Font License 1.1)는 zip 안에 들어 있습니다.
