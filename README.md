# 🎂 Aniversário do Fabio 42 Anos

Mini-game de confirmação de presença para o aniversário do Fabio.

## Como publicar no Vercel (passo a passo)

### 1. Criar repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"** (botão verde no canto superior direito)
3. Nome sugerido: `fabio42-birthday`
4. Deixe como **Public**
5. Clique em **"Create repository"**

### 2. Fazer upload dos arquivos

Na página do repositório recém-criado:

1. Clique em **"uploading an existing file"**
2. Arraste os dois arquivos:
   - `index.html`
   - `vercel.json`
3. Clique em **"Commit changes"**

### 3. Deploy no Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com sua conta GitHub
2. Clique em **"Add New → Project"**
3. Selecione o repositório `fabio42-birthday`
4. Clique em **"Deploy"** (sem precisar mudar nada)
5. Em ~30 segundos o site estará no ar!

### 4. Pegar o link

Após o deploy, o Vercel fornece um link no formato:
```
https://fabio42-birthday.vercel.app
```

Você pode personalizar o domínio nas configurações do projeto.

### 5. Compartilhar no WhatsApp

Copie o link e mande para seus convidados:
> *"Antes de confirmar presença, você precisa passar no meu teste de afinidade 😏 → [link]*"

---

## Personalizar as perguntas

Abra o `index.html` e edite o array `questions` no `<script>`:

```js
const questions = [
  {
    q: "Sua pergunta aqui?",
    opts: ["Opção A", "Opção B", "Opção C", "Opção D"],
    wrongs: [
      "Resposta errada para A",
      "Resposta errada para B",
      "Resposta errada para C",
      "Resposta errada para D"
    ]
  },
  // ... mais perguntas
];
```

Após editar, basta fazer commit no GitHub — o Vercel atualiza automaticamente!
