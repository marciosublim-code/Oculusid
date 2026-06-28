# ÓculosID — PWA de medidas de óculos com IA

App para identificar medidas de óculos de grau via foto (IA) ou digitação manual.

## Como publicar no GitHub Pages (grátis)

### 1. Crie um repositório no GitHub
- Acesse github.com e crie um repositório público
- Sugestão de nome: `oculosid`

### 2. Suba os arquivos
```bash
git init
git add .
git commit -m "ÓculosID PWA"
git remote add origin https://github.com/SEU_USUARIO/oculosid.git
git push -u origin main
```

### 3. Ative o GitHub Pages
- No repositório, vá em **Settings → Pages**
- Em "Source", selecione **"Deploy from a branch"**
- Branch: **main**, pasta: **/ (root)**
- Clique em **Save**

### 4. Acesse o app
Após alguns minutos, o app estará em:
```
https://SEU_USUARIO.github.io/oculosid/
```

### 5. Configure a chave da API
- Abra o app no celular
- Vá na aba ⚙️ **Config**
- Insira sua chave da API da Anthropic (console.anthropic.com)

### 6. Instale no celular
**Android (Chrome):** Menu ⋮ → "Adicionar à tela inicial"  
**iPhone (Safari):** Botão compartilhar → "Adicionar à Tela de Início"

---

## Arquivos do projeto

```
oculosid/
├── index.html      # App principal
├── manifest.json   # Configuração PWA
├── sw.js           # Service Worker (cache offline)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## Funcionalidades
- 📷 **Foto**: Tira foto da haste do óculos e a IA identifica os números
- ⌨️ **Manual**: Digite os números diretamente
- 📖 **Guia**: Explicação de cada medida
- 📊 **Compatibilidade**: Indica para qual tipo de rosto as medidas são ideais
- 📲 **Instalável**: Funciona como app nativo no celular
