# 📅 OUR TIMELINE | 2026 Integrated Dashboard

> **다양한 활동 보고 및 관리 서비스를 하나의 화면에서 효율적으로 접근하고 관리하는 웹 기반 통합 대시보드**

**OUR TIMELINE**은 개인의 비전 공유, 활동 보고(MyMemo, IUBA, TS), 그리고 진리 발표 기록을 통합보고 및 관리하여 상호 간의 목표 달성을 돕기 위함.

<br>

## ✨ 주요 기능 (Key Features)

### 1. 🔐 사용자 인증 & 보안 (Authentication)
- **Firebase Authentication**을 이용한 안전한 로그인 시스템.
- **세션 보안:** 페이지 로드 시 보안을 위해 세션을 초기화하고 재로그인을 유도.
- **간편 아이디 처리:** 도메인 입력을 생략하고 아이디만으로 로그인할 수 있도록 자동 처리 로직이 적용.

### 2. 🔗 통합 서비스 내비게이션 (Service Integration)
- **Quick Links:** WAPLE, MEDIA CAST, Google Calendar 등 주요 외부 서비스로 즉시 이동할 수 있는 헤더 메뉴를 제공.
- **Service Modal:** MyMemo, IUBA, TS, 서신 올리기 등 자주 사용하는 서비스들을 모달(Modal) 형태로 직관적으로 안내하고 연결.

### 3. 📝 실시간 활동 기록 (Real-time Board)
- **진리발표 현황판:** Firebase Firestore(NoSQL DB)와 연동된 게시판 기능.
- **CRUD 구현:** '진리발표' 및 '오해와 진실' 실천 내용을 날짜, 주제, 대상자와 함께 **작성(Create), 조회(Read), 삭제(Delete)** 할 수 있으며, 데이터는 실시간으로 반영됨.

### 4. 📱 반응형 디자인 (Responsive Web)
- **Desktop:** 넓은 화면을 활용한 5열 그리드 레이아웃과 여유로운 UI.
- **Mobile:** 스마트폰 환경에 맞춰 1열 카드 레이아웃으로 자동 전환되며, 터치 인터페이스에 최적화된 버튼과 폰트 사이즈를 제공.

### 5. 🎯 동기부여 & 비전 (Vision & Motivation)
- **Mindset Slider:** 'MAIN WORDS'와 'MINDSET' 명언을 슬라이드 형태로 제공하여 비전을 공유.
- **Goal Visualization:** 학기 목표(Semester Goals) 및 주요 지표(Baptism, Fruit, Join)를 시각화하여 보여줌.
