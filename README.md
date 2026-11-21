# 우리집 학습관리 v2

## 포함 기능
- 첫째/둘째 아이 이름 설정 및 개별 학습 기록
- 흘려듣기, 집중듣기, 한글책, 영어책, 수학, 기타 기록
- 일별/주간/월간 통계 및 월간 캘린더
- 영어책·한글책 권수/쪽수 비율과 책 종류별 통계
- 독서 목표 및 A4 상장 인쇄/PDF 저장
- JSON 데이터 백업/복원
- PWA 홈 화면 설치 지원

## GitHub Pages 배포
1. GitHub에서 새 저장소를 만드세요. 예: `my-learning-app-v2` (기존 `my-learning-app` 저장소는 수정하지 마세요).
2. 이 ZIP의 압축을 풀고 파일 4개(index.html, manifest.webmanifest, service-worker.js, icon.svg)와 README.md를 새 저장소 루트에 업로드합니다.
3. 저장소 Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save를 선택합니다.
4. 몇 분 후 `https://계정이름.github.io/my-learning-app-v2/` 주소로 접속합니다.
5. 휴대폰 Chrome 메뉴에서 '홈 화면에 추가' 또는 '앱 설치'를 선택합니다.

## 중요
- 이 버전은 기존 앱과 다른 저장 키(`family_learning_v3`)를 사용합니다.
- 데이터는 현재 브라우저에 저장됩니다. 기기 변경이나 브라우저 데이터 삭제 전에 설정 메뉴에서 백업하세요.
- A4 상장 화면에서 인쇄를 누른 뒤 프린터 선택에서 'PDF로 저장'을 선택할 수 있습니다.
