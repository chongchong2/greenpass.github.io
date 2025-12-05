# 몇초남았지 - GitHub Pages

> "보지 않고도 알 수 있는 내 손안의 실시간 신호등"

이 저장소는 "몇초남았지" 앱의 공식 웹사이트입니다.

## 🌐 웹사이트 주소

https://chongchong2.github.io/greenpass.github.io/

## 📄 페이지 구성

- **index.html** - 메인 페이지 (앱 소개, 기능, 다운로드)
- **how-to-use.html** - 사용방법 안내
- **privacy-policy.html** - 개인정보처리방침
- **styles.css** - 스타일시트

## 🚀 GitHub Pages 배포 방법

### 1. Repository 설정

1. GitHub에서 이 저장소로 이동
2. **Settings** → **Pages** 클릭
3. **Source** 섹션에서:
   - **Branch**: `main` 선택
   - **Folder**: `/ (root)` 선택
4. **Save** 버튼 클릭

### 2. 배포 확인

- 설정 후 몇 분 내에 자동으로 배포됩니다
- **Actions** 탭에서 배포 진행 상황을 확인할 수 있습니다
- 배포 완료 후 웹사이트 주소가 표시됩니다

### 3. 업데이트

파일을 수정하고 push하면 자동으로 재배포됩니다:

```bash
git add .
git commit -m "Update website content"
git push origin main
```

## 📸 스크린샷 추가 방법

앱 스크린샷을 추가하려면 `docs/screenshots/` 폴더에 이미지를 넣어주세요:

```
docs/screenshots/
├── 01_splash.png
├── 02_map_green.png
├── 03_map_red.png
└── 04_settings.png
```

## 🛠️ 로컬에서 미리보기

```bash
# Python 3가 설치되어 있다면
python -m http.server 8000

# 또는 다른 방법
npx serve .
```

그런 다음 브라우저에서 `http://localhost:8000`으로 접속

## 📝 수정 가능한 내용

- **앱 다운로드 링크**: `index.html`의 다운로드 섹션에서 App Store/Google Play 링크 업데이트
- **연락처 정보**: 이메일 주소 등 변경
- **스크린샷**: `docs/screenshots/` 폴더의 이미지 교체
- **디자인**: `styles.css`에서 색상, 폰트 등 커스터마이징

## 📧 문의

- Email: techt8127@gmail.com
- GitHub Issues: https://github.com/chongchong2/greenpass.github.io/issues

## 📄 라이선스

MIT License
greenpass 블로그
