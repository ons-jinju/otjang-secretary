# 앱 URL 깔끔하게 바꾸기

지금: `https://[github아이디].github.io/otjang-secretary/`
원하는 모습: github 흔적 없이 깔끔한 주소

---

## 🎯 3가지 옵션 (저렴한 순)

| 옵션 | URL 예시 | 비용 | 난이도 |
|------|---------|------|--------|
| **A. Netlify로 옮기기** | `otjang.netlify.app` | **무료** | ⭐ 쉬움 |
| **B. Vercel로 옮기기** | `otjang.vercel.app` | **무료** | ⭐ 쉬움 |
| **C. 도메인 사기** | `otjang.com` | 1~3만원/년 | ⭐⭐ 보통 |

---

## 🥇 옵션 A. Netlify로 옮기기 (가장 추천)

### 왜 추천?
- 완전 무료
- 회원가입 1분
- GitHub 연동하면 글 수정할 때마다 **자동 배포**
- URL 원하는 이름으로 바꿀 수 있음 (예: `otjang.netlify.app`)

### 단계별 안내

**1단계. Netlify 가입**

1. https://app.netlify.com/signup 접속
2. **"Sign up with GitHub"** 클릭 (이미 GitHub 계정 있으니까)
3. GitHub 로그인 정보 입력 → 권한 허용

**2단계. GitHub 저장소 연결**

1. 로그인 후 **"Add new site"** → **"Import an existing project"** 클릭
2. **"Deploy with GitHub"** 선택
3. 저장소 목록에서 `otjang-secretary` 찾아서 선택
4. 설정 화면이 나오면 그대로 두고 **"Deploy site"** 클릭
5. 30초~1분 기다리면 완료

**3단계. URL 예쁘게 바꾸기**

1. 사이트가 만들어지면 자동 URL이 나옴 (예: `random-bunny-12345.netlify.app`)
2. **"Site configuration"** 또는 **"Domain management"** 클릭
3. **"Change site name"** 클릭
4. 원하는 이름 입력:
   - `otjang` → `otjang.netlify.app`
   - `otjang-secretary` → `otjang-secretary.netlify.app`
   - `cloth-helper` 등 영문으로
5. 저장

**완료!** 새 URL로 접속해보세요.

> 💡 GitHub 저장소에 파일 수정해서 올리면 Netlify가 **자동으로 새 버전 배포**해요. 매번 수동 업로드 안 해도 돼요.

---

## 🥈 옵션 B. Vercel로 옮기기 (Netlify와 거의 동일)

### Netlify와 차이점
- 둘 다 무료, 무제한
- Netlify가 한국에서 더 빠른 편
- Vercel은 Next.js 만든 회사라 개발자 사이에서 더 핫함
- 어느 쪽이든 상관없어요

### 단계
1. https://vercel.com/signup 접속
2. **"Continue with GitHub"** 로 가입
3. **"Add New"** → **"Project"** → GitHub 저장소 선택
4. 그대로 **"Deploy"** 클릭
5. 완료 후 **Settings → Domains** 에서 이름 변경

URL: `otjang.vercel.app` 같은 형식

---

## 🥉 옵션 C. 진짜 도메인 사기 (10,000~30,000원/년)

블로그도 운영할 거고, 진지하게 갈 생각이면 추천.

### 어디서 사나?
| 사이트 | 가격 | 추천 |
|--------|------|------|
| **가비아** (한국) | .com 약 15,000원/년 | 한국어, 결제 편함 ⭐ |
| **Namecheap** (해외) | .com 약 $10/년 | 영어, 더 저렴 |
| **Cloudflare** | .com 약 $10/년 | 원가만 받음, 가장 저렴 |
| **호스팅케이알** | .kr 약 22,000원/년 | .kr 도메인 추천 |

### 추천 도메인 이름 예시
- `otjang.kr`
- `closet-helper.com`
- `otjang-app.com`
- (본인 닉네임).com

### 연결 방법
1. 도메인 구입
2. Netlify (또는 Vercel) 사이트의 **Domain settings** 에서 도메인 추가
3. 도메인 사이트의 DNS 설정에서 Netlify가 알려준 값 입력
4. 5분~몇 시간 후 적용

---

## 🎯 제가 추천하는 순서

**지금 당장**: 옵션 A (Netlify) — 무료, 1분 완료
**블로그 좀 키운 후**: 옵션 C (도메인 구입) — 진지한 느낌

옵션 A로 일단 가시고, 나중에 도메인 구입하면 그때 Netlify에 연결만 하면 돼요. 사용자들에게는 새 URL만 알려주면 되고요.

---

## ⚠️ 주의사항

### GitHub Pages 그대로 두기

Netlify로 옮겨도 **GitHub Pages는 그대로 두세요**. 백업이 되고, 두 URL 다 작동해요.

### 블로그에 쓸 URL은?

블로그 발행 전에 **Netlify URL** 만들고, 그걸 블로그 글에 넣으세요. 더 깔끔해 보여요.

---

## 🆘 막히는 부분 있으면

- Netlify 로그인 안 됨 → GitHub 권한 다시 허용
- 저장소가 안 보임 → 저장소가 **Public**인지 확인 (Private이면 안 보일 수 있음)
- 도메인 연결 헷갈림 → 사신 도메인 사이트에 1:1 문의 (한국 업체면 빠름)

진행하다가 막히면 화면 캡쳐해서 보여주세요!
