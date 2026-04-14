# BellaMolina Modas - Site Estático de Catálogo

Site estático de catálogo de roupas com design moderno, cores vibrantes femininas e tema de resiliência. O cliente entra em contato via WhatsApp para fazer orçamentos.

## 🎨 Características

- **Design moderno** com cores vibrantes femininas (rosa, coral, lilás, dourado)
- **Tema de resiliência** na apresentação da marca
- **Catálogo visual** de produtos com filtros por categoria
- **Contato direto** via WhatsApp para orçamentos
- **Responsivo** - funciona em desktop, tablet e mobile
- **100% gratuito** no Render

## 📁 Estrutura do Projeto

```
.
├── index.html          # Página inicial com banner e seção de resiliência
├── catalogo.html       # Catálogo de produtos com filtros
├── sobre.html          # Página sobre com tema de resiliência
├── contato.html        # Página de contato com link WhatsApp
├── styles.css          # CSS com cores vibrantes e design responsivo
└── README.md           # Este arquivo
```

## 🚀 Como Fazer Deploy no Render (Gratuito)

### Passo 1: Preparar o Repositório

1. Crie uma conta no [GitHub](https://github.com) (se ainda não tiver)
2. Crie um novo repositório para o projeto
3. Faça upload dos arquivos do projeto para o repositório

### Passo 2: Criar Conta no Render

1. Acesse [render.com](https://render.com)
2. Clique em "Sign Up" para criar uma conta gratuita
3. Conecte sua conta do GitHub ao Render

### Passo 3: Fazer Deploy do Site

1. No dashboard do Render, clique em **"New +"** → **"Static Site"**
2. Preencha as informações:
   - **Name**: `bellamolina-modas` (ou o nome que preferir)
   - **Branch**: `main` (ou `master`)
   - **Build Command**: deixe vazio (não precisa de build)
   - **Publish Directory**: `.` (ponto, indica a raiz do repositório)
3. Clique em **"Create Static Site"**

### Passo 4: Aguardar Deploy

O Render irá automaticamente:
- Clonar seu repositório do GitHub
- Detectar os arquivos HTML/CSS
- Fazer o deploy do site
- Fornecer uma URL HTTPS gratuita (ex: `https://bellamolina-modas.onrender.com`)

### Passo 5: Configurar Domínio Personalizado (Opcional)

Se quiser usar um domínio próprio:
1. Nas configurações do site no Render, vá em **"Custom Domains"**
2. Adicione seu domínio (ex: `bellamolina.com.br`)
3. Siga as instruções para configurar o DNS

## ⚙️ Personalização

### Alterar Número do WhatsApp

No arquivo `contato.html`, procure por:
```javascript
const whatsappNumber = '5511999999999';
```

Substitua `5511999999999` pelo número real do WhatsApp (formato: código do país + DDD + número, sem espaços ou traços).

### Alterar Link do Instagram

No arquivo `contato.html`, procure por:
```html
<a href="https://instagram.com/bellamolina" target="_blank">
```

Substitua `bellamolina` pelo nome de usuário real do Instagram.

### Alterar E-mail

No arquivo `contato.html`, procure por:
```html
<a href="mailto:contato@bellamolina.com.br">
```

Substitua pelo e-mail real.

### Alterar Imagens dos Produtos

No arquivo `catalogo.html`, substitua as URLs das imagens do Unsplash pelas imagens reais dos produtos. Você pode:
- Hospedar as imagens em um serviço como Imgur, Cloudinary ou AWS S3
- Usar imagens do próprio catálogo da loja

### Alterar Preços e Descrições

No arquivo `catalogo.html`, edite os preços e descrições dos produtos diretamente no HTML.

## 🎨 Cores Utilizadas

O site usa uma paleta de cores vibrantes femininas:

- **Primária**: Rosa (#E91E63)
- **Secundária**: Roxo (#9C27B0)
- **Accent**: Laranja (#FF6F00)
- **Dourado**: #FFD700
- **Coral**: #FF6B6B
- **Lilás**: #C8A2C8
- **Rose**: #F7CAC9

Para alterar as cores, edite as variáveis CSS no arquivo `styles.css` na seção `:root`.

## 📱 Responsividade

O site é totalmente responsivo e funciona em:
- Desktop (1920px+)
- Laptop (1366px - 1920px)
- Tablet (768px - 1366px)
- Mobile (320px - 768px)

## 🔧 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização com variáveis CSS e Flexbox/Grid
- **JavaScript** - Menu mobile e filtros de produtos
- **Google Fonts** - Poppins e Playfair Display
- **Unsplash** - Imagens de exemplo (substituir por imagens reais)

## 💡 Dicas de Uso

1. **Atualize o catálogo regularmente** - Mantenha os produtos e preços atualizados
2. **Use fotos de alta qualidade** - Imagens melhores aumentam as conversões
3. **Responda rápido no WhatsApp** - Clientes apreciam respostas rápidas
4. **Adicione novos produtos** - Expanda o catálogo conforme necessário
5. **Monitore o desempenho** - Use Google Analytics para entender o comportamento dos visitantes

## 📄 Licença

Este projeto foi criado para uso pessoal e comercial. Sinta-se livre para modificar e usar conforme necessário.

## 🆘 Suporte

Se precisar de ajuda com o deploy ou personalização, entre em contato através do WhatsApp ou e-mail informados no site.

---

**Desenvolvido com ❤️ para BellaMolina Modas**
