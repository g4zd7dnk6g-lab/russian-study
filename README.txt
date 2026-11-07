러시아어 첫걸음 PWA
===================

파일
- index.html: 화면 구조
- style.css: 디자인
- script.js: 학습/퀴즈/진도/음성 기능
- manifest.json: 홈 화면 설치 정보
- sw.js: 오프라인 캐시
- icon.svg: 앱 아이콘

Acode에서 실행
1. ZIP 압축을 풀고 폴더 전체를 Acode에서 엽니다.
2. index.html을 미리보기로 실행해 기본 동작을 확인합니다.
3. 홈 화면 설치(PWA)를 하려면 HTTPS 주소로 웹에 올려야 합니다.
   Acode 미리보기의 file:// 주소만으로는 설치가 되지 않을 수 있습니다.
4. iPad/iPhone은 Safari로 HTTPS 주소를 열고 공유 버튼 > 홈 화면에 추가를 선택합니다.
   Android는 Chrome 메뉴 > 앱 설치 또는 홈 화면에 추가를 선택합니다.

주의
- 음성은 기기에 설치된 러시아어 TTS 음성에 따라 달라집니다.
- 진도와 오답 기록은 현재 브라우저의 localStorage에 저장됩니다.
- 이 버전은 PWA 웹앱이며 네이티브 APK가 아닙니다.
