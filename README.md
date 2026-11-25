# 한가족 PC (Hangajok PC)

대규모 족보(가계도)를 PC에서 편집하는 프로그램입니다.
족보 파일(`.ftdb`)은 **한가족 모바일 앱과 같은 형식**이라, PC에서 만든 족보를 앱에서 열어 볼 수 있고 앱에서 내보낸 족보를 PC에서 편집할 수 있습니다.

- 로그인 없이 내 PC에서만 작동합니다. 족보는 지정한 폴더의 `.ftdb` 파일 하나로 저장됩니다.
- 공유는 파일을 USB·메일·구글 드라이브 등으로 전달하면 됩니다.
- 10개 언어 지원(한국어, English, 日本語, 中文, Español, Français, Deutsch, Português, العربية, हिन्दी)

## 내려받기

**[최신 버전 내려받기 → Releases](https://github.com/kwonchanghyug/hangajok-pc-download/releases/latest)**

| 파일 | 대상 | 설치 방법 |
|---|---|---|
| `hangajok-pc_<버전>_amd64.deb` | 우분투·하모니카·리눅스 민트·데비안 | 더블클릭해 설치 (추천) |
| `hangajok-pc-linux-<버전>.tar.gz` | 그 밖의 리눅스 | 압축을 풀고 실행 |

### 필요한 환경 (Linux)

- 64비트(x86_64) 리눅스, **우분투 22.04 / 하모니카 6 / 리눅스 민트 21 / 데비안 12 이상** (glibc 2.34 이상)
- 일반 데스크톱 환경(GTK 3 — 대부분 기본 설치되어 있음)

Windows·macOS 판은 준비 중입니다.

## 설치

### .deb (우분투·하모니카·민트·데비안)

1. `hangajok-pc_..._amd64.deb` 파일을 더블클릭해 소프트웨어 설치 창에서 **설치**를 누릅니다.
   터미널에서는: `sudo apt install ./hangajok-pc_*_amd64.deb`
2. 프로그램 메뉴에서 **한가족 PC**를 실행합니다.
3. 족보 파일(`.ftdb`)을 더블클릭해도 한가족 PC로 열립니다.

삭제: `sudo apt remove hangajok-pc` (저장한 족보 파일은 지워지지 않습니다)

### .tar.gz

```bash
tar -xzf hangajok-pc-linux-*.tar.gz
./hangajok-pc/familytree_pc
```

압축을 푼 `hangajok-pc` 폴더를 원하는 곳에 두고 그 안의 `familytree_pc`를 실행하면 됩니다.

## 족보 파일 위치

- 기본 저장 폴더: `문서/한가족PC` (시작 화면의 **폴더 변경**으로 바꿀 수 있습니다)
- 변경 내용은 바로 파일에 저장됩니다. `.ftdb` 파일 하나만 복사하면 다른 PC나 휴대폰으로 옮겨집니다.

## 모바일 앱

- 한가족 앱(Android·iOS·웹)의 **족보 파일 열기 (.ftdb)** 로 PC에서 만든 족보를 볼 수 있습니다(앱에서는 보기 전용).
- 앱의 **족보 파일로 내보내기 (.ftdb)** 로 받은 파일을 PC에서 열어 편집할 수 있습니다.

---

이 저장소는 설치 파일 배포용입니다.
