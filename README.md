# Karisma Pedidos

Sistema interno da Karisma Uniformes, em Novo Horizonte/SP, para lançar pedido, acompanhar a produção e controlar o material.

A página inicial é a vitrine da loja. O acesso da equipe fica em `/login`.

## Como rodar

```bash
npm install
npm run dev
```

## Publicar

O site sobe na Vercel (preset TanStack Start). O banco é Postgres. Na Vercel, crie a variável `DATABASE_URL` com a connection string do Neon.
