# telc Deutsch B2 디지털 시험 (digital.html)

- `data/mt1–4.json`: 문제 데이터 (PDF에서 옮긴 것, 정답은 Lösungsschlüssel S. 20과 대조). 형식은 `SCHEMA.md`.
- `template.html`: 시험 화면 (HTML/CSS/JS 한 파일). `build-digital.py`가 데이터·로고·글꼴을 넣어 저장소 루트에 `digital.html`을 만듭니다.
- 검사: `python3 digital-src/validate.py 1 2 3 4`
- 빌드: `python3 digital-src/build-digital.py`
- 글꼴(Pretendard, OFL)은 `make-font.py`로 부분 추출합니다.

공식 DIGItelc 화면의 복제가 아니라, 공개된 정보(좌우 분할, 컴퓨터 입력, 형광펜, 단어 수 표시 등)에 맞춘 연습용 화면입니다.
