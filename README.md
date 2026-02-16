# [Proje Adi] - Backend

[1-2 cumle aciklama]

## Gereksinimler

- Node.js 20+
- npm

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
Health check: GET http://localhost:5000/health

## Scriptler

| Komut | Aciklama |
|-------|----------|
| `npm run dev` | Development server (nodemon + ts-node) |
| `npm run build` | TypeScript build (dist/) |
| `npm start` | Production server |
| `npm run lint` | TypeScript tip kontrolu |

## Tech Stack

- **Runtime:** Node.js
- **Framework:** Express
- **Dil:** TypeScript
- **Hot Reload:** Nodemon

## Git Workflow

- `main` - Production (sadece PR ile merge)
- `develop` - Development
- `feature/xxx` - Yeni ozellik
- `fix/xxx` - Bug fix

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
