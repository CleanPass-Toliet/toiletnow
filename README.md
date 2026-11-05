# 화장실나우 웹사이트

화장실나우 앱의 소개·다운로드 페이지와 개인정보처리방침 · 이용약관입니다. (GitHub Pages로 게시)

- 홈페이지(앱 소개·다운로드): https://cleanpass-toliet.github.io/toiletnow/
- 개인정보처리방침: https://cleanpass-toliet.github.io/toiletnow/privacy.html
- 이용약관: https://cleanpass-toliet.github.io/toiletnow/terms.html
- APK 다운로드: https://github.com/CleanPass-Toliet/toiletnow/releases/latest/download/toiletnow.apk

## 수정 방법

이 저장소의 파일을 직접 고치지 마세요. 원본은 앱 저장소(TolietNow)의 `docs/` 폴더입니다.

- 약관 문구: TolietNow의 `src/data.ts` 수정 → `npm run build:policy` 실행
- 소개 페이지: TolietNow의 `docs/index.html`, `docs/img/` 수정

그다음 `docs/` 안의 파일을 이 저장소에 복사해서 커밋 · 푸시하세요.

## 새 APK 올리기

이 저장소의 Releases에 새 릴리스를 만들고, APK 파일 이름을 **`toiletnow.apk`**로 올리면
사이트의 다운로드 버튼이 자동으로 최신 릴리스를 가리킵니다.
