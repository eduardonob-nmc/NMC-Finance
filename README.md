# NMC Finance — PWA

**Nobrega Mall Consultant — Sistema de Gestão Financeira**

## Deploy no Vercel (passo a passo)

### 1. Faça upload para o GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **New repository**
3. Nome: `nmc-finance`
4. Deixe como **Public** (necessário para o Vercel gratuito)
5. Clique em **Create repository**
6. Na tela seguinte, clique em **uploading an existing file**
7. Arraste **todos os arquivos deste ZIP** para a área de upload
8. Clique em **Commit changes**

### 2. Deploy no Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com sua conta GitHub
2. Clique em **Add New → Project**
3. Selecione o repositório `nmc-finance`
4. Clique em **Deploy** (sem alterar nada)
5. Aguarde ~30 segundos
6. Seu app estará disponível em: `https://nmc-finance.vercel.app`

### 3. Instalar no celular como app

**Android (Chrome):**
1. Abra o link no Chrome
2. Toque no menu ⋮ (três pontos)
3. Toque em **"Adicionar à tela inicial"**
4. Confirme — o app aparece como ícone nativo

**iPhone (Safari):**
1. Abra o link no Safari
2. Toque no botão de compartilhar ↑
3. Role e toque em **"Adicionar à Tela de Início"**
4. Confirme — o app aparece como ícone nativo

---

## Estrutura dos arquivos

```
nmc-finance/
├── index.html        ← Sistema completo
├── manifest.json     ← Configuração do PWA
├── sw.js             ← Service Worker (offline)
├── favicon.ico       ← Ícone do navegador
├── vercel.json       ← Configuração do Vercel
└── icons/            ← Ícones em vários tamanhos
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    ├── icon-512x512.png
    └── apple-touch-icon.png
```

## Funcionalidades

- ✅ Funciona 100% offline após primeira abertura
- ✅ Dados salvos localmente no dispositivo
- ✅ Ícone na tela inicial (Android e iOS)
- ✅ Tela cheia sem barra do navegador
- ✅ Tema escuro nativo
- ✅ Responsivo para celular e tablet

---

*NMC Finance v18 — Nobrega Mall Consultant*
