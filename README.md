# 🚀 InstaPro.ai — Guia Completo de Deploy

## O que é o InstaPro.ai?
Plataforma SaaS que usa IA para ajudar profissionais liberais (advogados, dentistas, psicólogos...) a crescer no Instagram com diagnóstico de perfil, geração de posts, sistema de missões e dicas de SEO.

---

## 📁 Arquivos do projeto
```
instapro-ai/
├── index.html      ← O app completo
├── vercel.json     ← Configuração do Vercel
└── README.md       ← Este guia
```

---

## 🌐 PASSO A PASSO: Colocar no ar (sem linha de comando!)

### PARTE 1 — Criar conta no GitHub

1. Acesse **github.com** e clique em **Sign up**
2. Crie uma conta com seu e-mail
3. Confirme o e-mail e entre na plataforma

### PARTE 2 — Criar o repositório no GitHub

1. Na tela inicial do GitHub, clique no botão verde **"New"** (canto superior esquerdo)
2. Em **Repository name**, digite: `instapro-ai`
3. Deixe como **Public**
4. Marque a caixinha **"Add a README file"**
5. Clique em **"Create repository"**

### PARTE 3 — Fazer upload dos arquivos

1. Dentro do repositório criado, clique em **"Add file"** → **"Upload files"**
2. Arraste os 3 arquivos para a área de upload:
   - `index.html`
   - `vercel.json`
   - `README.md` (substitua o que foi criado)
3. Na parte de baixo, clique em **"Commit changes"**
4. Pronto — seus arquivos estão no GitHub!

### PARTE 4 — Criar conta no Vercel

1. Acesse **vercel.com**
2. Clique em **"Sign Up"**
3. Escolha **"Continue with GitHub"** (isso conecta os dois automaticamente)
4. Autorize o acesso

### PARTE 5 — Fazer o deploy

1. No Vercel, clique em **"Add New Project"**
2. Na lista de repositórios, encontre **"instapro-ai"** e clique em **"Import"**
3. Na tela de configuração, não precisa mudar nada — clique em **"Deploy"**
4. Aguarde 1-2 minutos
5. 🎉 Seu site está no ar! O Vercel vai mostrar um link tipo: `instapro-ai.vercel.app`

---

## 🔑 Ativar a IA (OpenAI)

Para que o app gere posts reais com IA:

1. Acesse **platform.openai.com** e crie uma conta
2. Vá em **API Keys** → **Create new secret key**
3. Copie a chave (começa com `sk-...`)
4. No InstaPro.ai, vá na aba **⚙️ Chave de API** e cole a chave
5. Salve — a IA estará ativa!

> 💡 Custo estimado: ~R$ 0,05 por post gerado (muito barato)

---

## 🌍 Colocar seu domínio próprio (ex: instapro.com.br)

1. Compre um domínio no **registro.br** ou **GoDaddy**
2. No Vercel, vá em seu projeto → **Settings** → **Domains**
3. Clique em **"Add"** e digite seu domínio
4. O Vercel vai mostrar os DNS para configurar no seu provedor
5. Em até 48h o domínio estará funcionando

---

## 💰 Modelo de Negócio Sugerido

| Plano | Preço | O que inclui |
|-------|-------|-------------|
| Essencial | R$ 97/mês | 1 profissão, 12 posts/mês, diagnóstico, ranking |
| Pro | R$ 197/mês | Tudo ilimitado + tendências + suporte WhatsApp |

Para cobrar assinaturas, integre o **Stripe** (stripe.com) ou o **Hotmart**.

---

## 📦 Próximas funcionalidades para adicionar

- [ ] Login com Google (Firebase Auth)
- [ ] Histórico de posts gerados
- [ ] Análise de concorrentes via API
- [ ] Integração Stripe para assinaturas
- [ ] Painel de admin para ver usuários
- [ ] Notificações de missões por e-mail

---

## ❓ Dúvidas?

Se algo não funcionar, verifique:
- O arquivo `vercel.json` está na pasta raiz
- O arquivo `index.html` está na pasta raiz (não dentro de subpasta)
- A conta GitHub está conectada ao Vercel

---

Construído com ❤️ usando HTML/CSS/JS puro — zero dependências, zero servidor, funciona em qualquer lugar.
