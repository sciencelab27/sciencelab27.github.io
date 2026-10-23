QuizClass 2.0 — Firebase 실시간 버전

사용 순서
1. 이 폴더의 모든 파일을 GitHub 저장소의 같은 위치에 업로드합니다.
2. GitHub Pages를 켭니다.
3. 배포된 index.html을 엽니다.
4. 교사 화면에서 '새 방 만들기'를 눌러 6자리 PIN을 만듭니다.
5. 학생은 student.html 주소로 접속하여 PIN과 이름/번호를 입력합니다.
6. 교사가 문제를 선택하고 '문제 시작'을 누르면 학생이 답을 제출합니다.

포함 기능
- 기존 과학수업 Firebase 프로젝트(sciencelab27-5b82f)의 Cloud Firestore 사용
- 데이터 경로를 quizclass_v2로 분리
- 실시간 학생 입장/응답
- 응답 막대그래프
- 기본 퀴즈
- 스피드 퀴즈(남은 시간 보너스)
- 골든벨(오답 즉시 탈락)
- 서바이벌(생명 3개)
- 익명 형성평가(교사 화면 이름/순위 비표시)
- 정답 공개/해설
- 문제 추가/삭제
- 반응형 학생 화면

주의
- 기존 Firestore 보안 규칙은 수정하지 않았습니다.
- 현재 프로젝트 규칙이 quizclass_v2 경로의 읽기/쓰기를 허용해야 실제 접속이 됩니다.
- 규칙 때문에 'Missing or insufficient permissions' 오류가 나오면 기존 규칙을 확인해야 합니다.
- 학생 QR 이미지는 아직 자동 생성하지 않았습니다. GitHub Pages의 student.html 주소를 QR로 만들면 바로 참여할 수 있습니다.
