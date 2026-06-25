# 에스제이(SJ)행사기획 홈페이지 + 관리자페이지

## 파일 구성
- `index.html` : 홈페이지
- `admin.html` : 관리자페이지
- `css/style.css` : 홈페이지 디자인
- `css/admin.css` : 관리자페이지 디자인
- `js/app.js` : 홈페이지 기능
- `js/admin.js` : 관리자 기능
- `js/firebase-config.js` : Firebase 설정 파일

## GitHub에 올릴 파일
이 폴더 안의 파일 전체를 그대로 업로드하세요.

## 관리자 로그인
Firebase 설정 전 데모 비밀번호: `admin1234`

## 주의
Firebase 설정 전에는 문의/상담/접속현황이 같은 브라우저의 데모 데이터로만 동작합니다.
실제 방문자 문의를 관리자페이지에서 보려면 Firebase 콘솔에서 프로젝트를 만들고 `js/firebase-config.js` 값을 입력하세요.

## Firebase에서 필요한 기능
- Firestore Database 생성
- 웹 앱 생성 후 firebaseConfig 복사
- Firestore 규칙은 운영 전 관리자 인증 기반으로 강화 필요

## Vercel 배포
1. GitHub 저장소 생성
2. 이 폴더 파일 전체 업로드
3. Vercel에서 해당 저장소 Import
4. 배포 후 `index.html`, `admin.html` 접속
