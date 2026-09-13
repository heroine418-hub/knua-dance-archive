# 무용원 30주년 디지털 아카이브 — 정보구조 프로토타입

한국예술종합학교 무용원 30주년 디지털 아카이브 웹사이트의 정보구조(IA) 프로토타입입니다.
Google Arts & Culture의 카테고리 구조를 참고해 좌측 사이드바를 구성했고, 컬렉션 · 인물 · 연혁·이벤트 · 사료매체 · 분야 · 기관 · 공간 · 타임캡슐 8개 레이어가 서로 클릭으로 연결됩니다.

## 미리보기

`index.html`을 브라우저로 열거나, 아래 GitHub Pages 배포 후 링크로 확인하세요.

## 사용 데이터

자료 분류표 · 분류 해제표 · 콩쿨·대회 · 장소 · 행위자 · 인물이력관리 · 수상사건 시트에서 발췌한 실제 값 기반 샘플입니다. 전체 수량이 아닌 프로토타입용 발췌본입니다.

## 로컬 실행

별도 빌드 과정 없이 정적 HTML 한 파일입니다.

```bash
git clone <이 저장소 URL>
cd knua-dance-archive
open index.html   # macOS
# 또는 브라우저에서 index.html을 직접 드래그해서 열기
```

## GitHub Pages 배포

1. 저장소 Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main` / `/ (root)` 선택 후 저장
4. 몇 분 후 `https://<사용자명>.github.io/<저장소명>/` 에서 접속 가능
