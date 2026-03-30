# 소프트 보이스 프로그램 — Netlify 배포 가이드

## 📦 이 폴더 안의 파일
- `index.html` — 메인 페이지
- `netlify.toml` — Netlify 설정 (캐시, 보안 헤더)

---

## 🚀 배포 방법 (3단계, 5분)

### 방법 1 — Netlify Drop (가장 빠름)
1. **netlify.com/drop** 접속
2. 이 폴더 전체를 드래그해서 페이지에 드롭
3. 자동으로 URL 생성됨 (예: `https://random-name.netlify.app`)
4. Site settings → Domain management에서 이름 변경 가능

### 방법 2 — Netlify 계정 연결 (URL 고정)
1. netlify.com 회원가입 (무료)
2. "Add new site" → "Deploy manually"
3. 폴더 드래그 업로드
4. Site settings → Change site name → `momesori-voice` 등으로 변경
5. 최종 URL: `https://momesori-voice.netlify.app`

---

## 🔗 공유 방법
- 생성된 URL을 카카오톡, 문자, 인스타 등으로 공유
- 스마트폰으로 열어도 PC와 동일하게 표시됨
- 인터넷만 되면 어디서든 정상 작동

---

## 🔄 수정 후 재배포
파일 수정 후 동일한 방법으로 다시 드래그하면 자동 업데이트됩니다.
