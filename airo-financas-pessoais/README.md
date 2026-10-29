# Airo Finanças Pessoais

Organize sua renda, despesas, dívidas e metas com o Método C.A.P. (Consciência, Ação, Planejamento) — grátis, sem cadastro, dados salvos só no celular.

Publicado em: https://airo-financas-pessoais.web.app

Usado como app de apoio na palestra ["O salário sumiu. E agora?"](https://github.com/prof-arijunior/Palestras), inclusive para as enquetes ao vivo (`hosting/public/ao-vivo/`).

## Estrutura

- `hosting/public/` — app principal (estático, sem build)
- `hosting/public/ao-vivo/` — página do participante para as enquetes ao vivo da palestra
- `firebase.json`, `.firebaserc`, `firestore.rules`, `firestore.indexes.json` — configuração do projeto Firebase (`airo-financas-pessoais`)

## Deploy

```
firebase deploy
```
