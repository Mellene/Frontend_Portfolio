# 프로젝트 이미지 넣는 곳

아래 파일명 그대로 이 폴더에 이미지를 넣으면, 해당 프로젝트 모달의 "화면 미리보기" 영역에 자동으로 표시됩니다.
권장 비율 16:10, 권장 폭 1200px 이상.

| 파일명 | 들어갈 이미지 |
| --- | --- |
| jobtam-01.png | JobTam — 직무 적합도 진단 결과 화면 |
| jobtam-02.png | JobTam — 채용공고 매칭 분석 화면 |
| jobtam-03.png | JobTam — 커리어 준비 로드맵 화면 |
| lfp-01.png | Life Financial Platform — 메인 대시보드 |
| lfp-02.png | Life Financial Platform — 단계별 입력 창 |
| encar-02.png | SK엔카 — 차량 비교 프로토타입 화면 |
| ar-01.png | Face the Truth — AR 필터 적용 전후 |
| ar-02.png | Face the Truth — IGC 2023 발표 포스터 |

사진이 아직 없는 항목(Relationship Analysis Platform, 학부 조교, LAMBDA, STEAM 멘토, SK엔카 기존/개선 비교 컷)은 화면 미리보기 영역 자체를 뺐습니다. 나중에 사진이 생기면 `index.html`의 `projectData` 안 해당 프로젝트 `images` 배열에 `{ src: "assets/projects/파일명", caption: { ko: "...", en: "..." } }` 형태로 추가하면 됩니다.

파일명이나 캡션을 바꾸려면 `index.html`의 `projectData` 안 `images` 배열을 수정하세요.
