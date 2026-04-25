# IT Manager — Frontend

## Como hospedar no GitHub Pages (grátis)

### 1. Criar repositório no GitHub
- Acesse github.com
- Clique em "New repository"
- Nome: `it-manager-frontend`
- Visibilidade: **Public** (obrigatório para GitHub Pages grátis)
- Clique em "Create repository"

### 2. Enviar arquivos via Git Bash
```bash
cd "CAMINHO_DA_PASTA_it-manager-frontend"
git init
git add .
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/it-manager-frontend.git
git push -u origin main
```

### 3. Ativar GitHub Pages
- No repositório, clique em "Settings"
- No menu lateral, clique em "Pages"
- Em "Source", selecione "Deploy from a branch"
- Em "Branch", selecione "main" e pasta "/ (root)"
- Clique em "Save"

### 4. Acessar o sistema
Após 1-2 minutos, seu sistema estará disponível em:
https://SEU_USUARIO.github.io/it-manager-frontend

Login: admin / Suport3mcrs
