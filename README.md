# 토익 특강 솔루션 (TOEIC SNIPER SOLUTION) 랜딩페이지

별도 설치 없이 GitHub Pages에 올리면 바로 열리는 정적 웹사이트입니다.

## 폴더 구성

```
index.html                       랜딩페이지 본문 (HTML, CSS, JavaScript 한 파일)
assets/images/photo-instructor.jpg   솔루션 섹션 사진
assets/images/photo-classroom.jpg    강의실 전경 사진
assets/images/photo-owner-tv.jpg     수익 구조 섹션 사진 (TV 화면 그래프는 코드로 덮음)
assets/audio/winter-skys-light.mp3   상단 "토익 특강 솔루션" 클릭 시 재생되는 음원
assets/video/toeic-sniper-intro.mp4 소개 영상 (3분, 1080p 30fps, 웹용으로 압축)
assets/video/intro-poster.jpg       영상 재생 전 보이는 첫 화면
README.md                        이 안내서
```

폰트(Pretendard)는 jsDelivr에서 불러옵니다. 인터넷이 연결된 상태라면 따로 넣을 필요가 없습니다.

## GitHub Pages에 올리는 방법

1. GitHub에 로그인한 뒤 오른쪽 위 `+` → `New repository`를 누릅니다.
2. 저장소 이름을 정하고(예: `toeic-sniper`) `Public`으로 만든 뒤 `Create repository`를 누릅니다.
3. 새 저장소 화면에서 `uploading an existing file`을 누르고, 압축을 푼 폴더 안의 파일과 `assets` 폴더를 통째로 끌어다 놓습니다. `index.html`이 저장소 맨 위에 있어야 합니다.
4. `Commit changes`를 누릅니다.
5. 저장소의 `Settings` → 왼쪽 `Pages`로 갑니다.
6. `Build and deployment`에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 고르고 `Save`를 누릅니다.
7. 1~2분 뒤 같은 화면 위쪽에 사이트 주소가 나타납니다. 보통 `https://<GitHub 아이디>.github.io/<저장소 이름>/` 형태입니다.

내용을 고친 뒤에는 바뀐 파일만 같은 방법으로 다시 올리면 몇 분 안에 사이트에 반영됩니다.

## 알아 둘 점

- **시연 문의 창**: 방문자가 작성한 내용으로 noveljny@gmail.com 앞으로 보낼 메일을 방문자의 메일 앱에 미리 채워 줍니다. 방문자가 메일 앱에서 보내기를 눌러야 전달되고, 메일 앱이 없는 방문자를 위해 내용 복사와 주소 복사 버튼이 있습니다. 문의가 메일함으로 자동 도착하게 하려면 Formspree 같은 문의 수신 서비스에 가입한 뒤 `index.html`의 문의 처리 부분을 그 서비스 주소로 연결하면 됩니다.
- **음악**: 브라우저 정책상 페이지가 열리자마자 소리를 낼 수 없습니다. 상단 "토익 특강 솔루션"이나 옆의 물결을 눌러야 재생되고, 다시 누르면 멈춥니다.
- **비어 있는 자리**: 연락처(`[전화번호] · [이메일]`)는 아직 자리 표시만 되어 있습니다. `index.html`에서 해당 문구를 찾아 바꾸면 됩니다.
- **스크롤 등장 효과**: 섹션이 흐림에서 선명하게 떠오르는 효과는 크롬과 엣지에서 보이고, 사파리에서는 처음부터 선명한 상태로 보입니다.
- **사진과 음원 권리**: 사용하는 사진과 음원은 게시 권한이 있는 파일이어야 합니다.
