# 📋 Guia do Vendedor - Marina Premium

Este documento explica como usar e personalizar o site mostruário para apresentações a clientes.

---

## 🚀 Como Usar

### Visualização Local
1. Abra a pasta `marina-premium`
2. Dê duplo-clique no arquivo `index.html`
3. O site abrirá no navegador

### Hospedagem Online (Recomendado)
Para demonstrações profissionais, hospede o site gratuitamente:

**Opção 1 - Vercel:**
1. Acesse [vercel.com](https://vercel.com)
2. Faça login com sua conta GitHub
3. Clique em "Import Project"
4. Selecione o repositório `marinas`
5. Clique em "Deploy"

**Opção 2 - Netlify:**
1. Acesse [netlify.com](https://netlify.com)
2. Arraste a pasta `marina-premium` para a área de upload
3. O site será publicado automaticamente

---

## ✏️ Como Personalizar

### Informações a Alterar para Cada Cliente

| O que alterar | Arquivo | Localização |
|---------------|---------|-------------|
| Nome da Marina | Todos os `.html` | Tag `<title>` e logo no header |
| Telefone WhatsApp | Todos os `.html` | Link do botão flutuante (buscar `5541999999999`) |
| Endereço | `contato.html` | Seção de informações de contato |
| E-mail | `contato.html` | Seção de informações de contato |
| Horários | `contato.html` | Seção de horários de funcionamento |
| Mapa Google | `contato.html` | iframe do Google Maps |
| Preços | `servicos.html` | Cards de cada serviço |
| CNPJ/Razão Social | Páginas legais | Política de Privacidade e Termos |

### Alterando o Nome da Marina

1. Abra todos os arquivos `.html` no editor de texto
2. Use **Ctrl+H** (Localizar e Substituir)
3. Substitua `Marina Premium` pelo nome do cliente
4. Salve todos os arquivos

### Alterando o WhatsApp

1. Busque em todos os arquivos: `5541999999999`
2. Substitua pelo número do cliente (formato: código do país + DDD + número)
3. Exemplo: `5547912345678`

### Alterando Imagens

As imagens estão na pasta `img/` e também referenciadas via URLs externas no CSS.

Para usar fotos reais do cliente:
1. Coloque as imagens na pasta `img/`
2. Edite `css/styles.css`
3. Substitua as URLs nas classes:
   - `.hero-bg` - Imagem principal do topo
   - `.dest-img-1` - Imagem de destino (praia)
   - `.dest-img-2` - Imagem de destino (golfinhos)
   - `.service-img-*` - Imagens dos serviços

### Alterando o Mapa

1. Abra [Google Maps](https://maps.google.com)
2. Pesquise o endereço do cliente
3. Clique em "Compartilhar" → "Incorporar um mapa"
4. Copie o código `<iframe>`
5. Cole em `contato.html` no lugar do iframe existente

---

## 📱 Páginas do Site

| Página | Arquivo | Conteúdo |
|--------|---------|----------|
| Inicial | `index.html` | Hero, serviços em destaque, destinos |
| Serviços | `servicos.html` | Detalhes dos 5 serviços principais |
| A Marina | `sobre.html` | História, valores e infraestrutura |
| Galeria | `galeria.html` | Fotos da marina |
| Contato | `contato.html` | Formulário, mapa e informações |
| Privacidade | `privacidade.html` | Política de Privacidade (LGPD) |
| Termos | `termos.html` | Termos de Serviço |
| Transparência | `transparencia.html` | Política de Transparência |
| Mapa do Site | `mapa-do-site.html` | Links organizados |

---

## 🎨 Cores e Estilo

O tema usa as seguintes cores (editáveis em `css/styles.css`):

- **Azul escuro (fundo):** `#081E2B`
- **Dourado (destaques):** `#C9A55C`
- **Texto claro:** `#F5F5F5`

---

## ⚠️ Checklist Antes da Apresentação

- [ ] Nome da marina alterado
- [ ] Telefone/WhatsApp atualizado
- [ ] Endereço e mapa corretos
- [ ] E-mail de contato atualizado
- [ ] Horários de funcionamento definidos
- [ ] Preços dos serviços atualizados (se aplicável)
- [ ] CNPJ nas páginas legais atualizado
- [ ] Testado em celular e computador

---

## 💡 Dicas de Apresentação

1. **Use o celular** - Demonstre a responsividade do site
2. **Clique no WhatsApp** - Mostre que o botão funciona
3. **Navegue por todas as páginas** - Mostra profissionalismo
4. **Destaque as páginas legais** - Transmite credibilidade
5. **Mostre a galeria** - O lightbox impressiona

---

## 📞 Suporte

Repositório GitHub: https://github.com/ndrd79/marinas

---

*Documento atualizado em Janeiro/2026*
