# Visual Studio - Estúdio Digital 🚀

Bem-vindo ao repositório do site oficial da Visual Studio!

## 📋 Sobre

Este é um site empresarial completo para um estúdio digital que oferece:

- **Desenvolvimento de Sites e Apps**
- **Lojas Online (E-commerce)**
- **Landing Pages para Vendas**
- **Marketing Digital & Social Media**
- **Plataforma de Templates**
- **Estúdio Criativo Multimídia**
- **Consultoria de Imagem para Negócios**

## 🎨 Diferenciais

- Design profissional e elegante
- Funcionalidade perfeita em todos os dispositivos
- Foco em resultados reais
- Tecnologia de ponta

## 📁 Estrutura do Projeto

```
visualstudio.com.br/
├── index.html          # Página principal (Home)
├── styles.css          # Estilos principais
├── script.js           # Interatividade e funcionalidades
├── README.md           # Este arquivo
└── favicon.ico         # Ícone do site (a ser adicionado)
```

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Criar o Repositório no GitHub

1. Acesse [github.com](https://github.com)
2. Clique no botão **+** no canto superior direito e selecione **New repository**
3. Preencha:
   - **Repository name**: `visualstudio.com.br`
   - **Description**: `Site oficial da Visual Studio - Estúdio Digital`
   - Marque **Public**
   - Clique em **Create repository**

### Passo 2: Enviar o Site para o GitHub

**Opção A: Via Terminal (Recomendado)**

```bash
# Clone este repositório ou crie um novo
cd /home/rodrigo/.openclaw/workspace

# Inicialize o git se ainda não tiver
git init

# Adicione os arquivos
git add visualstudio.com.br/

# Commit das mudanças
git commit -m "Inicial: Site completo da Visual Studio"

# Adicione o remote (substitua SEU-USUARIO pelo seu usuário do GitHub)
git remote add origin https://github.com/SEU-USUARIO/visualstudio.com.br.git

# Envie para o GitHub
git branch -M main
git push -u origin main
```

**Opção B: Via GitHub UI**

1. No seu repositório GitHub, clique em **add file** → **upload files**
2. Arraste os arquivos `index.html`, `styles.css`, `script.js` e `README.md`
3. Faça commit das mudanças

### Passo 3: Habilitar GitHub Pages

1. Acesse o repositório no GitHub
2. Clique em **Settings** (ícone de engrenagem)
3. No menu lateral, clique em **Pages**
4. Em **Source**, selecione:
   - **main** branch
   - **/ (root)** folder
5. Clique em **Save**

### Passo 4: Configurar DNS Customizado (Opcional)

Se quiser usar o domínio `visualstudio.com.br`:

1. No GitHub Pages, anote o endereço fornecido (ex: `SEU-USUARIO.github.io/visualstudio.com.br`)
2. No seu provedor de domínio, crie um record **CNAME**:
   - **Name**: `www` (ou deixe em branco para o domínio raiz)
   - **Target**: `SEU-USUARIO.github.io`
3. Aguarde a propagação (pode levar alguns minutos a algumas horas)

### Passo 5: Verificar o Site

Após alguns minutos, seu site estará disponível em:
- **URL padrão**: `https://SEU-USUARIO.github.io/visualstudio.com.br/`
- **Custom domain**: `https://www.visualstudio.com.br/` (se configurado)

## 🛠️ Personalização

### Cor da Tema
Edite as variáveis em `styles.css`:
```css
--primary-color: #00d2ff;
--secondary-color: #7b2cbf;
```

### Content
- Edite `index.html` para alterar textos, serviços e portfólio
- Atualize as informações de contato no formulário

### Imagens
- Substitua os placeholders (`📷 Projeto X`) por imagens reais
- Adicione a pasta `images/` e atualize os links no HTML

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:
- ✅ Desktop (computadores)
- ✅ Tablet (iPad, Android tablets)
- ✅ Mobile (smartphones)

## 🌐 Navegadores Suportados

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 📝 Próximos Passos (Opcional)

- [ ] Adicionar formulário funcional (use um serviço como Formspree, Netlify Forms, ou crie seu próprio backend)
- [ ] Integrar com Google Analytics
- [ ] Adicionar SEO avançado (meta tags, sitemap.xml, robots.txt)
- [ ] Criar área de blog
- [ ] Integrar com CRM/Email marketing
- [ ] Adicionar área de login para clientes

## 🤝 Contribuições

Este projeto é mantido pela equipe Visual Studio.

## 📄 Licença

© 2026 Visual Studio. Todos os direitos reservados.

---

**Feito com ❤️ pela Visual Studio - Estúdio Digital**
