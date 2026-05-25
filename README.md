# skn_calenda

React(Vite) + TypeScript 캘린더 일정관리 프로젝트.

## 로컬 실행

```bash
cd C:\Users\son\projects\skn_calenda
npm install
npm run dev
```

http://localhost:5173

## Vercel 배포

1. GitHub에 저장소 push
2. Vercel → **Add New Project** → `skn_calenda` Import
3. Framework: **Vite** (자동 감지)
4. Build Command: `npm run build`
5. Output Directory: `dist`

### CLI

```bash
npm i -g vercel
vercel login
vercel
```
