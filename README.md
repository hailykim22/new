# 여행 정산 MVP - 베타테스트 사전 신청

현금 위주 해외여행에서도 영수증 촬영만으로 실시간 정산과 갈등 없는 여행을 완성하는 서비스의 베타테스트 사전 신청 페이지입니다.

## 🚀 배포 방법

### 1. GitHub에 업로드
```bash
# Git이 설치되어 있다면
git init
git add .
git commit -m "Initial commit: Travel expense splitting landing page"
git branch -M main
git remote add origin https://github.com/hailykim22/new.git
git push -u origin main
```

### 2. Vercel로 배포
1. [Vercel](https://vercel.com)에 접속하여 GitHub 계정으로 로그인
2. "New Project" 클릭
3. GitHub 저장소 `hailykim22/new` 선택
4. "Deploy" 클릭
5. 자동으로 배포 완료!

### 3. Formspree 설정
- Formspree 엔드포인트: `https://formspree.io/f/xovkvyyj`
- 이메일 수집이 자동으로 시작됩니다
- Formspree 대시보드에서 제출된 이메일 확인 가능

## 📁 파일 구조
```
├── index.html          # 메인 랜딩 페이지
└── README.md          # 프로젝트 설명서
```

## 🎨 기능
- ✅ 반응형 디자인 (모바일/데스크톱)
- ✅ SEO 최적화
- ✅ 접근성 고려 (ARIA 라벨)
- ✅ 이메일 수집 폼 (Formspree 연동)
- ✅ FAQ 섹션
- ✅ 사용자 테스티모니얼
- ✅ 통계 데이터 표시

## 🔧 커스터마이징
- 색상: CSS 변수로 쉽게 변경 가능
- 폰트: Pretendard (한국어 최적화)
- 폼: Formspree 엔드포인트 변경 가능

## 📱 미리보기
로컬에서 미리보기:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .

# 또는 브라우저에서 직접 index.html 열기
```

## 📧 문의
베타테스트 관련 문의는 Formspree를 통해 수집된 이메일로 연락드리겠습니다.
