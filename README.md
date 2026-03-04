# 📅 OUR TIMELINE | 2026 Integrated Dashboard

> **흩어져 있는 활동 보고와 관리 서비스를 한곳에서 처리하는 웹 기반 통합 대시보드**

**OUR TIMELINE**은 개인의 비전 공유부터 활동 보고(MyMemo, IUBA, TS), 진리 발표 기록까지 하나의 화면에서 통합 관리하기 위해 만듦.

<br>

## ✨ 주요 기능 (Key Features)

### 1. 사용자 인증 & 보안 (Authentication)
- **Firebase Auth 연동:** 안전한 로그인을 위해 Firebase Authentication을 사용.
- **세션 관리:** 보안을 위해 페이지를 새로 열 때마다 세션을 초기화하고 재로그인을 유도.
- **간편 로그인:** 매번 긴 도메인을 입력할 필요 없이, 아이디만 입력해도 자동으로 로그인되도록 편의성을 높임.

### 2. 통합 서비스 내비게이션 (Service Integration)
- **Quick Links:** WAPLE, MEDIA CAST, 구글 캘린더 등 자주 가는 외부 사이트는 헤더에서 바로 이동 가능.
- **Service Modal:** MyMemo, IUBA, TS, 서신 올리기 등 매일 쓰는 기능들은 새 창이 아닌 모달(Modal) 형태로 직관적으로 연결.

### 3. 실시간 활동 기록 (Real-time Board)
- **진리발표 현황판:** Firestore(NoSQL)를 붙여서 실시간 게시판 기능을 구현.
- **CRUD 기능:** '진리발표'나 '오해와 진실' 실천 내용을 날짜/주제/대상자와 함께 기록할 수 있고, 작성한 내용은 실시간으로 저장, 조회, 삭제 가능.

### 4. 반응형 디자인 (Responsive Web)
- **Desktop:** PC 화면에서는 5열 그리드로 정보를 한눈에 넓게 보여줌.
- **Mobile:** 모바일에서는 자동으로 1열 카드 형태로 바뀌며, 버튼이나 폰트 크기도 터치 환경에 맞춰 최적화.

### 5. 동기부여 & 비전 (Vision & Motivation)
- **Mindset Slider:** 'MAIN WORDS'와 'MINDSET' 명언을 슬라이드 형식으로 넣어 비전을 계속 상기할 수 있음.
- **Goal Visualization:** 학기 목표(Semester Goals)와 주요 지표(Baptism, Fruit, Join)를 그래프 형태로 시각화.
