# Guide Website

본 저장소는 다양한 사용자 가이드를 웹으로 제공하기 위한 **가이드 웹사이트**의 소스 코드를 관리합니다.  
문서/가이드/사용 매뉴얼을 웹 형태로 쉽고 명확하게 전달하는 것을 목표로 합니다.

---

## 🚀 프로젝트 소개

가이드 웹사이트는 다음을 목표로 합니다:

- 업무 매뉴얼, 지침, 개발 가이드, 운영 문서를 **웹 기반으로 쉽게 접근**  
- 검색과 탐색이 편리한 **문서 허브(Documentation Hub)** 구축  
- 버전 관리 및 변경 이력 추적 가능  
- 협업자가 문서를 쉽게 수정하고 배포할 수 있는 구조 제공

---

## 🏗️ 기술 스택

(필요한 항목만 선택하여 유지하세요.)

- **Frontend:** React / Next.js / Vue / Svelte / HTML 기반 정적 사이트  
- **Docs Framework:** Docusaurus / MkDocs / VitePress / GitBook 스타일  
- **Styling:** Tailwind CSS / Styled Components / SCSS  
- **Deployment:** GitHub Pages / Vercel / Netlify / 내부 서버  
- **CI/CD:** GitHub Actions 기반 자동 빌드 & 배포  

---

## 📂 디렉토리 구조 (예시)

```bash
├── docs/              # 문서/가이드 원본 파일
├── public/            # 정적 리소스 (이미지, 아이콘 등)
├── src/               # 웹사이트 소스 코드
│   ├── components/    # 공통 UI 컴포넌트
│   └── pages/         # 라우트 페이지
├── scripts/           # 빌드/배포 스크립트
└── README.md          # 프로젝트 설명 문서

commit

fix
