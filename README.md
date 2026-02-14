# [Proje Adi] - Backend

[1-2 cumle aciklama]

## Gereksinimler

- Node.js 20+
- npm veya yarn
- PostgreSQL (veya MongoDB)

## Kurulum

```bash
git clone https://github.com/sunstech/[REPO_ADI].git
cd [REPO_ADI]
npm install
cp .env.example .env
# .env dosyasini duzenle (DB bilgileri, JWT secret vb.)
npm run dev
```

API http://localhost:5000 adresinde calisir.

## Scriptler

| Komut | Aciklama |
|-------|----------|
| npm run dev | Development server (nodemon) |
| npm run build | Production build |
| npm start | Production server |
| npm run lint | Lint kontrolu |
| npm test | Testleri calistir |
| npm run migrate | Migration calistir |

## API Dokumantasyon

Swagger: http://localhost:5000/api-docs (eger kurulduysa)

## Git Workflow

- main - Production (sadece PR ile merge)
- develop - Development
- feature/xxx - Yeni ozellik
- fix/xxx - Bug fix

### Commit Formati
```
feat(kapsam): yeni ozellik
fix(kapsam): hata duzeltme
docs(kapsam): dokumantasyon
refactor(kapsam): kod duzenleme
test(kapsam): test ekleme
```

## Ekip

| Rol | Kisi |
|-----|------|
| Backend Lead | [Ad] |

## Linkler

- Frontend repo: [Link]
- Trello: [Board linki]
- Slack: #proje-[ad]
