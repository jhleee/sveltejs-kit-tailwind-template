# SvelteKit + Tailwind CSS 프로젝트

이 프로젝트는 [SvelteKit](https://kit.svelte.dev/)과 [Tailwind CSS](https://tailwindcss.com/)를 사용하여 구축된 웹 애플리케이션입니다.


## 시작하기

### 필요 조건

- Node.js (버전 14 이상)
- npm 또는 yarn

### 설치

1. 이 저장소를 클론합니다:
   ```
   git clone https://github.com/jhleee/sveltejs-kit-tailwind-template.git
   ```

2. 프로젝트 디렉토리로 이동합니다:
   ```
   cd sveltejs-kit-tailwind-template
   ```

3. 의존성을 설치합니다:
   ```
   npm install
   ```
   또는
   ```
   yarn install
   ```

### 개발 서버 실행

개발 서버를 시작하려면 다음 명령어를 실행하세요:

```
npm run dev
```

또는

```
yarn dev
```

이제 `http://localhost:5173`에서 애플리케이션에 접속할 수 있습니다.

## 빌드

프로덕션용 빌드를 생성하려면 다음 명령어를 실행하세요:

```
npm run build
```

또는

```
yarn build
```

## 프로젝트 구조

```
your-project-name/
├── src/
│   ├── lib/
│   │   ├── components/
│   ├── routes/
│   └── app.html
├── static/
├── postcss.config.cjs
├── svelte.config.js
├── tailwind.config.js
├── tsconfig.json
└── package.json
```

- `src/`: 소스 코드
  - `lib/`: 재사용 가능한 Svelte 컴포넌트 및 유틸리티 함수
  - `routes/`: SvelteKit 라우트 (페이지)
- `static/`: 정적 파일 (이미지, 폰트 등)
- `postcss.config.cjs`: PostCSS 설정
- `svelte.config.js`: SvelteKit 설정
- `tailwind.config.js`: Tailwind CSS 설정
- `tsconfig.json`: TypeScript 설정

## 커스터마이징

- Tailwind 설정을 수정하려면 `tailwind.config.js` 파일을 편집하세요.
- 전역 스타일은 `src/app.css`에 추가할 수 있습니다.
- 새로운 라우트를 추가하려면 `src/routes` 디렉토리에 새 파일이나 디렉토리를 생성하세요.

## 기여하기

프로젝트에 기여하고 싶으시다면 풀 리퀘스트를 보내주세요. 주요 변경사항의 경우, 먼저 이슈를 열어 논의해 주시기 바랍니다.

## 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.