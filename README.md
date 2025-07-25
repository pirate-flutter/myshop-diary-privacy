# MyShop Diary 개인정보보호 및 고객지원 문서

MyShop Diary 앱의 개인정보보호 정책, 서비스 이용약관, 고객지원 관련 문서들을 포함한 웹사이트입니다.

## 📁 파일 구조

```
myshop-diary-privacy/
├── index.html              # 메인 홈페이지
├── privacy-policy.html      # 개인정보처리방침 (완전 개선됨)
├── terms-of-service.html    # 서비스 이용약관 (신규 작성)
├── delete-account.html      # 계정 삭제 안내 (플레이스토어 등록 URL, 완전 개선됨)
├── support.html            # 고객지원 및 FAQ (신규 작성)
└── README.md               # 이 파일
```

## 📋 문서 개요

### 1. 메인 홈페이지 (`index.html`)
- MyShop Diary 앱 소개
- 주요 기능 안내
- 모든 정책 문서로의 링크
- 연락처 정보
- 반응형 웹 디자인 적용

### 2. 개인정보처리방침 (`privacy-policy.html`)
**기존 대비 대폭 개선된 내용:**
- MyShop Diary 코드 분석을 통한 정확한 개인정보 수집 현황 반영
- Firebase 서비스 사용에 대한 상세 명시
- 13개 섹션으로 구성된 완전한 개인정보처리방침
- 법적 요구사항 완전 준수

**주요 개선사항:**
- 수집하는 개인정보 항목을 7개 카테고리로 상세 분류
- Firebase 위탁 처리 명시
- 개인정보 보유기간을 법령에 따라 정확히 명시
- 8단계 안전성 확보조치 상세 기술
- 정보주체의 권리 행사 방법 구체적 안내

### 3. 서비스 이용약관 (`terms-of-service.html`)
**신규 작성된 포괄적 약관:**
- 19개 조항으로 구성된 완전한 이용약관
- 앱 서비스 특성을 반영한 맞춤형 내용
- 무료 서비스 정책 명시
- 데이터 백업 및 손실에 대한 명확한 책임 규정
- 지적재산권 보호 조항

### 4. 계정 삭제 안내 (`delete-account.html`)
**기존 대비 대폭 확장된 내용:**
- 3가지 계정 삭제 방법 상세 안내
- 삭제되는 데이터 8개 카테고리 표로 정리
- 법정 보관 의무 데이터 별도 명시
- 부분 데이터 삭제 방법 안내
- 9개 FAQ로 구성된 자주 묻는 질문
- 삭제 유예 및 철회 절차 안내

### 5. 고객지원 (`support.html`)
**신규 작성된 종합 고객지원 센터:**
- 연락처별 응답 시간 명시
- 16개 FAQ로 구성된 자주 묻는 질문
- 문의 전 체크리스트 제공
- 기능 개선 제안 및 버그 신고 절차
- 보안 취약점 신고 체계

## 🔧 기술적 특징

### 반응형 디자인
- 모바일, 태블릿, 데스크톱 모든 기기 지원
- CSS Grid와 Flexbox 활용
- 터치 친화적 인터페이스

### 접근성
- 시맨틱 HTML 구조
- 명확한 헤딩 구조
- 적절한 색상 대비
- 읽기 쉬운 타이포그래피

### 사용자 경험
- 직관적인 네비게이션
- 카드 기반 레이아웃
- 호버 효과 및 애니메이션
- 빠른 링크 버튼

## 📊 개인정보 분석 결과

MyShop Diary 앱 코드 분석을 통해 확인된 개인정보 처리 현황:

### 수집되는 개인정보
1. **인증 정보**: 이메일 주소 (패스워드리스 인증)
2. **사업자 정보**: 사업체명, 사업자명, 주소, 전화번호 등
3. **고객 데이터**: 이름, 휴대폰번호, 생년월일, 메모
4. **예약 데이터**: 예약일시, 서비스 내용, 결제 정보
5. **매출 데이터**: 결제 금액, 결제 방법, 할인 정보
6. **멤버십 데이터**: 멤버십 타입, 구매/만료일, 사용 내역
7. **앱 사용 데이터**: 로그, 성능 데이터, 오류 리포트

### Firebase 서비스 사용
- **Firebase Authentication**: 패스워드리스 이메일 인증
- **Cloud Firestore**: 사용자별 격리된 데이터 저장
- **Firebase Performance**: 앱 성능 모니터링
- **Firebase Crashlytics**: 오류 추적 및 분석

## 🔗 URL 구조

프로덕션 환경에서는 다음과 같은 URL로 접근 가능:

```
https://myshop-diary-privacy.web.app/
├── index.html                    # 메인 페이지
├── privacy-policy.html           # 개인정보처리방침
├── terms-of-service.html         # 서비스 이용약관
├── delete-account.html           # 계정 삭제 안내
└── support.html                  # 고객지원
```

## 📧 연락처

각 문서에서 안내하는 연락처:

- **일반 문의**: myshopdiary.cs@gmail.com
- **개인정보 관련**: myshopdiary.cs@gmail.com
- **기능 제안**: myshopdiary.cs@gmail.com
- **버그 신고**: myshopdiary.cs@gmail.com
- **보안 취약점**: myshopdiary.cs@gmail.com
- **비즈니스 문의**: myshopdiary.cs@gmail.com

## ⚖️ 법적 준수사항

### 준수하는 법령
- 개인정보보호법
- 정보통신망 이용촉진 및 정보보호 등에 관한 법률
- 전자상거래 등에서의 소비자보호에 관한 법률
- 부가가치세법 (세무 관련 기록 보관)

### 보관 의무 기간
- 세무 관련 기록: 5년
- 전자상거래 기록: 5년
- 서비스 이용 기록: 3개월
- 부정이용 기록: 1년

## 🚀 배포 정보

- **최초 작성일**: 2025년 1월 23일
- **최종 수정일**: 2025년 1월 23일
- **버전**: 2.0.0 (완전 재작성)
- **개발**: MyShop Team

## 📝 변경 이력

### v2.0.0 (2025-01-23)
- 전체 문서 구조 완전 재설계
- MyShop Diary 앱 코드 분석 기반 개인정보처리방침 작성
- 서비스 이용약관 신규 작성
- 계정 삭제 안내 대폭 확장
- 고객지원 및 FAQ 신규 작성
- 반응형 웹 디자인 적용

### v1.0.0 (이전)
- 기본적인 개인정보처리방침
- 간단한 계정 삭제 안내

---

**참고**: 이 문서들은 MyShop Diary 앱의 실제 코드 분석을 바탕으로 작성되었으며, 개인정보보호법 및 관련 법령의 요구사항을 완전히 준수합니다.