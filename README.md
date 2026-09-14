# 딥러닝 학습용 웹 교재

첨부된 PDF의 Chapter 3, **Probability and Information Theory**를 바탕으로 재구성한 한국어 학습 자료입니다. 원문을 단순 변환하지 않고 개념, 직관, 수식, 딥러닝에서의 의미를 중심으로 다시 썼습니다.

## 실행

`index.html`을 브라우저에서 열면 됩니다. MathJax는 CDN에서 로드되므로 수식 표시에는 인터넷 연결이 필요합니다.

## 구조

- `index.html`: 홈과 목차
- `chapters/chapter-03.html`: Chapter 3 본문
- `assets/css/textbook.css`: 반응형 레이아웃, 다크 모드, 학습 컴포넌트
- `assets/js/textbook.js`: 모바일 목차, 현재 section highlight, 다크 모드
- `assets/images/`: 교육용 그림
- `assets/image-prompts.json`: 생성 이미지의 목적과 prompt 기록

## 이미지와 수식

이미지는 기존 원서 그림을 복제하지 않고 개념을 새로 구성한 다이어그램입니다. 이미지가 없을 때도 레이아웃이 무너지지 않도록 `figure`에 배경과 캡션을 두었습니다. 수식은 MathJax용 LaTeX로 작성합니다.

## 새 Chapter 추가

`chapters/chapter-XX.html`을 만들고 공통 CSS/JS 경로를 맞춘 뒤, `index.html`의 chapter card와 각 페이지의 sidebar·하단 navigation을 연결합니다.
