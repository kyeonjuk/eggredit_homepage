# QuestLearn - Landing Page

QuestLearn의 랜딩 페이지입니다. 학습을 모험으로 만드는 플랫폼!

## 🚀 Railway 배포 방법

### 1. Railway에 로그인
[Railway.app](https://railway.app)에 접속하여 GitHub 계정으로 로그인합니다.

### 2. 새 프로젝트 생성
1. Dashboard에서 "New Project" 클릭
2. "Deploy from GitHub repo" 선택
3. 이 리포지토리 선택

### 3. 자동 배포
Railway가 자동으로 다음을 감지하고 배포합니다:
- `package.json` - Node.js 프로젝트 인식
- `server.js` - Express 서버 실행
- PORT 환경 변수 자동 설정

### 4. 배포 완료
몇 분 후 Railway가 제공하는 URL로 사이트에 접속할 수 있습니다!

## 📁 프로젝트 구조

```
eggredit_homepage/
├── index.html          # 메인 랜딩 페이지
├── code.html           # 원본 HTML 파일
├── screen.png          # 스크린샷
├── server.js           # Express 웹 서버
├── package.json        # Node.js 의존성
├── .gitignore          # Git 제외 파일
└── README.md           # 프로젝트 문서
```

## 🛠️ 로컬 개발

### 설치
```bash
npm install
```

### 실행
```bash
npm start
```

서버가 `http://localhost:3000`에서 실행됩니다.

## 🎨 기술 스택

- **HTML5** - 마크업
- **Tailwind CSS** - 스타일링 (CDN)
- **Express.js** - 웹 서버
- **Railway** - 배포 플랫폼

## 📝 특징

- 반응형 디자인
- 다크 모드 지원
- Material Icons 사용
- Nunito 폰트
- 부드러운 애니메이션

## 📄 라이센스

MIT License

---

Made with ❤️ for QuestLearn
