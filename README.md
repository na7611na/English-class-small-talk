# English Warm-Up Time! 🎬

초등 영어 TV 수업용 워밍업(Small Talk) 보드입니다. 데이터베이스나 서버 없이 순수 HTML/CSS/JS로 동작하는 정적 웹페이지 한 장으로 구성되어 있어, 파일을 열거나 정적 호스팅에 올리기만 하면 바로 사용할 수 있습니다.

## 구성

- `index.html` — 전체 앱 (마크업 + 스타일 + 로직이 한 파일에 포함)
  - Slide 1: 날짜 (요일 / 월 / 일)
  - Slide 2: 날씨 (16개 단어, 4개 카테고리)
  - Slide 3: 감정 (인사이드 아웃 캐릭터 기반 21개 단어)
  - 브라우저 내장 Web Speech API를 사용한 영어 발음(TTS) 재생
  - `canvas-confetti`를 이용한 감정 선택 시 컨페티 효과

외부 리소스는 CDN(Tailwind CSS, canvas-confetti, Google Fonts)만 사용하며, 별도의 백엔드/데이터베이스/빌드 과정이 필요 없습니다.

## 로컬에서 열기

`index.html` 파일을 더블클릭하거나 브라우저 주소창에 파일 경로를 입력해서 바로 열면 됩니다.

```bash
open index.html   # macOS
# 또는
xdg-open index.html   # Linux
```

## GitHub Pages로 배포하기

1. GitHub 저장소의 **Settings → Pages**로 이동합니다.
2. **Source**를 `Deploy from a branch`로 설정합니다.
3. Branch를 `main` (또는 배포하려는 브랜치), 폴더를 `/ (root)`로 선택 후 저장합니다.
4. 잠시 후 `https://<사용자명>.github.io/<저장소명>/` 주소에서 바로 접속할 수 있습니다.

## 사용 팁 (교실 TV용)

- 우측 상단 **전체화면** 버튼으로 TV에 꽉 차게 표시할 수 있습니다.
- **발음 ON/OFF** 버튼으로 클릭 시 자동 음성 재생 여부를 설정할 수 있습니다.
- 화면 하단 **Read Aloud!** 버튼을 누르면 완성된 문장을 다시 들을 수 있습니다.
- 키보드 방향키(← →)로 슬라이드를 이동할 수 있습니다.
