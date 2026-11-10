# 🔤 Encoder & Decoder Studio

**Encoder & Decoder Studio**는 개발자와 디자이너, 일반 사용자들을 위한 올인원 웹 인코딩/디코딩 툴입니다. 
외부 서버와의 통신 없이 100% 사용자의 브라우저(Client-side) 내에서 안전하고 빠르게 동작합니다.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

---

## ✨ 주요 기능 (Key Features)

- 🔒 **100% 클라이언트 사이드 처리**: 입력한 모든 데이터는 외부 서버로 전송되지 않으며 브라우저 메모리상에서만 연산됩니다.
- ⚡ **실시간 즉시 변환**: 텍스트를 입력하는 순간 실시간으로 변환 결과가 출력됩니다.
- 🔄 **다양한 인코딩/디코딩 지원**:
  - **Base64**: UTF-8 유니코드(한글, 이모지 등) 완벽 지원
  - **URL Encoding**: URL 구성 요소 safe-encoding 및 파싱
  - **HTML Entity**: 태그 및 특수문자 이스케이프 처리 (`<`, `>`, `&` 등)
  - **Hexadecimal (16진수)**: 바이트 단위 16진수 상호 변환
  - **Binary (2진수)**: 8비트 단위 2진수 상호 변환
  - **JWT (JSON Web Token)**: Header, Payload, Signature 자동 분석 및 Formatting 뷰어
- 🌓 **다크 / 라이트 모드 지원**: 사용자 시스템 설정 자동 감지 및 수동 토글 기능
- 🔀 **입출력 맞바꾸기 (Swap)**: 클릭 한 번으로 결과값을 입력값으로 전환하여 역변환 수행
- 📊 **실시간 통계**: 글자 수 및 UTF-8 기준 바이트 크기 실시간 계산

---

## 🚀 GitHub Pages 배포 가이드

단일 HTML 파일 구조로 이루어져 있어 GitHub Pages를 통해 1분 만에 무료로 배포할 수 있습니다.

### 1단계: Repository 생성 및 파일 업로드
1. GitHub에서 새로운 public 저장소(`repository`)를 생성합니다.
2. 생성한 저장소에 `index.html` 파일(제공된 웹 앱 코드)과 이 `README.md` 파일을 올립니다.

### 2단계: GitHub Pages 설정
1. 저장소 상단의 **Settings** 탭을 클릭합니다.
2. 좌측 메뉴에서 **Pages**를 클릭합니다.
3. **Build and deployment** 섹션의 **Branch**를 `main` (또는 `master`)로 설정하고 `/ (root)` 폴더를 선택한 뒤 **Save**를 클릭합니다.
4. 약 1~2분 후 제공되는 URL (`https://<user-name>.github.io/<repo-name>/`)로 접속합니다.

---

## 🛠️ 기술 스택 (Tech Stack)

- **HTML5 & Vanilla JavaScript (ES6+)**
- **Tailwind CSS (CDN)** - 모던 뷰포트 레이아웃 및 다크 모드 스타일링
- **FontAwesome 6** - UI 아이콘

---

## 📄 라이선스 (License)

이 프로젝트는 [MIT License](./LICENSE)를 따릅니다. 자유롭게 수정 및 수정 재배포가 가능합니다.