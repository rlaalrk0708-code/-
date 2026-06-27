# 매장재고파악 앱

## 🚀 배포 방법 (Vercel — 무료, 5분)

### 1단계 — GitHub에 올리기
1. https://github.com 회원가입 (무료)
2. 우측 상단 **+** → **New repository**
3. Repository name: `매장재고파악`
4. **Create repository** 클릭
5. 이 폴더의 파일들을 모두 업로드

### 2단계 — Vercel로 배포
1. https://vercel.com 회원가입 (GitHub 계정으로 로그인)
2. **Add New Project** → GitHub의 `매장재고파악` 선택
3. **Deploy** 클릭
4. 1~2분 후 주소 발급: `매장재고파악.vercel.app`

### 3단계 — 핸드폰에 앱으로 설치
**안드로이드 (크롬):**
- 발급된 주소 접속 → 점 3개 메뉴 → "홈 화면에 추가"

**아이폰 (사파리):**
- 발급된 주소 접속 → 하단 공유 버튼(□↑) → "홈 화면에 추가"

설치하면 홈 화면에 노란 MJ 아이콘이 생겨요! 📱

## ⚠️ 중요: Anthropic API 키 설정
카메라 스캔 기능은 Anthropic API를 사용해요.
Vercel 배포 후 **Environment Variables**에 추가:
- Key: `VITE_ANTHROPIC_API_KEY`
- Value: 본인의 API 키

API 키 발급: https://console.anthropic.com
