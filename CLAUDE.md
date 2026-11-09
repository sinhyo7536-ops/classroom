# 우리 반 도구 (classroom)

GitHub Pages로 배포되는 학급용 웹 도구 모음. 각 도구는 폴더 하나에 `index.html` 한 파일로 둔다.

- `checkboard/index.html` — 우리 반 체크판 (주소: https://sinhyo7536-ops.github.io/classroom/checkboard/)

## 규칙
- 답변과 주석은 한국어로 쓴다.
- **학생 실명을 코드에 넣지 않는다.** 공개 저장소다. 명단은 각 기기의 localStorage(⚙ 명단 설정)에만 저장한다. 기본값은 `1번`~`25번`처럼 둔다.
- **체크판을 고칠 때마다 `<meta name="build" content="...">` 값을 바꾼다** (예: `2026-11-09-2`). 이 값이 바뀌어야 교실에 켜진 화면이 새 버전을 알아채고 자동 새로고침한다.
- localStorage 키(`classcheck:*`)의 이름이나 형식을 바꾸면 기존 기록이 사라지니, 바꿔야 하면 옮겨 주는 코드를 함께 넣는다.
- `main`에 push하면 1~2분 안에 Pages에 반영된다.
- 휴대폰·태블릿·교실 PC 화면 모두에서 확인한다.
