# Fluxogramas - Nexray

Fluxogramas de processo (Abertura de O.S. e Venda de Equipamentos) — Futuremed & Hexamedical.

## Deploy no Vercel

Este é um site estático (HTML puro, sem build). Para publicar:

1. Suba estes arquivos para a raiz do seu repositório no GitHub.
2. No [Vercel](https://vercel.com/new), clique em **Add New Project**.
3. Selecione o repositório `Fluxogramas - Nexray`.
4. Em **Framework Preset**, escolha **Other** (não precisa de build).
5. Deixe **Build Command** e **Output Directory** em branco.
6. Clique em **Deploy**.

O Vercel vai servir automaticamente o `index.html` na raiz do domínio.

## Estrutura

```
.
├── index.html      # página principal (fluxogramas)
├── vercel.json     # configuração de URLs limpas
└── README.md
```
