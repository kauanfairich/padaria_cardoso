#  Padaria Cardoso - Site Vitrine

Site vitrine profissional e responsivo para a Padaria Cardoso, desenvolvido com HTML5, CSS3 e JavaScript puro.

##  Conteúdo do Projeto

- `index.html` - Estrutura principal do site
- `styles.css` - Estilos e design responsivo
- `script.js` - Interatividade e animações

##  Como Usar

### 1. Configuração Básica

1. Coloque todos os três arquivos (`index.html`, `styles.css`, `script.js`) na mesma pasta
2. Certifique-se de que as imagens estão no caminho correto
3. Abra o arquivo `index.html` em qualquer navegador moderno

### 2. Personalizar Números de WhatsApp

Procure por `5527XXXXXXXXXXX` no arquivo `index.html` e substitua pelos números reais:

```html
<!-- Exemplo de onde substituir -->
<a href="https://wa.me/5527XXXXXXXXXXX" target="_blank">

<!-- Substitua por algo como: -->
<a href="https://wa.me/5527999887766" target="_blank">
```

**Locais para substituir (total de 3 ocorrências):**
- Linha 47: Botão "Fazer Pedido" no Hero
- Linha 325: Botão "Fazer Pedido pelo WhatsApp" 
- Linha 395: Botão flutuante "Pedidos"
- Linha 403: Botão flutuante "Dúvidas"

### 3. Ajustar Imagens

As imagens atualmente estão referenciando o caminho `/mnt/project/`. Você tem duas opções:

#### Opção A: Criar pasta de imagens
```
seu-projeto/
  ├── index.html
  ├── styles.css
  ├── script.js
  └── imagens/
      ├── hero.jpg (imagem principal)
      ├── interior1.jpg
      ├── interior2.jpg
      ├── paes.jpg
      ├── pao-queijo.jpg
      ├── salgados.jpg
      ├── pizza.jpg
      ├── bolos.jpg
      ├── tortas.jpg
      ├── equipe.jpg
      └── ...
```

Depois, no HTML, altere os caminhos:
```html
<!-- De: -->
<img src="/mnt/project/imagem.jpg" alt="...">

<!-- Para: -->
<img src="imagens/imagem.jpg" alt="...">
```

#### Opção B: Usar URLs externas
Se as imagens estiverem hospedadas online:
```html
<img src="https://seusite.com/imagens/produto.jpg" alt="...">
```

### 4. Personalizar Cores

No arquivo `styles.css`, você pode alterar as cores principais editando as variáveis CSS:

```css
:root {
    --primary-color: #D4773C;      /* Cor principal (laranja) */
    --secondary-color: #8B4513;    /* Cor secundária (marrom) */
    --dark-brown: #5D3A1A;         /* Marrom escuro */
    --light-beige: #F5E6D3;        /* Bege claro */
    --cream: #FFF8DC;              /* Creme */
}
```

### 5. Atualizar Informações de Contato

No arquivo `index.html`, procure pela seção `<!-- Contato Section -->` e atualize:

- Endereço
- Telefone/WhatsApp
- Instagram
- Horário de funcionamento
- Link do Google Maps (substituir o iframe)

### 6. Modificar Produtos e Preços

Para adicionar, remover ou editar produtos:

1. Localize a seção `<!-- Produtos Section -->` no `index.html`
2. Cada produto está dentro de um `<div class="product-card">`
3. Copie e cole um card existente para adicionar novos produtos
4. Edite os textos, preços e caminhos das imagens

Exemplo de estrutura de produto:
```html
<div class="product-card">
    <div class="product-image-wrapper">
        <img src="caminho/da/imagem.jpg" alt="Nome do Produto" class="product-image">
    </div>
    <div class="product-info">
        <h4>Nome do Produto</h4>
        <p class="product-description">Descrição opcional</p>
        <p class="product-price">R$ 00,00</p>
    </div>
</div>
```

##  Recursos do Site

### Funcionalidades Implementadas

✅ Design responsivo (funciona em desktop, tablet e celular)
✅ Menu de navegação suave
✅ Animações ao scroll
✅ Botões flutuantes de WhatsApp
✅ Seções: Hero, Sobre, Produtos, Equipe, Contato
✅ Cards de produtos com hover effects
✅ Google Maps integrado
✅ Otimizado para SEO
✅ Performance otimizada

### Seções do Site

1. **Header** - Menu de navegação fixo
2. **Hero** - Banner principal com call-to-action
3. **Sobre** - História da padaria e diferenciais
4. **Produtos** - Catálogo organizado por categorias:
   - Pães
   - Salgados
   - Doces e Sobremesas
   - Tortas e Assados
5. **Equipe** - Foto da equipe
6. **Contato** - Informações e localização
7. **Footer** - Rodapé com links e informações
8. **Botões WhatsApp** - Flutuantes para fácil contato

##  Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge (versões recentes)
- ✅ Mobile (iOS e Android)
- ✅ Tablets
- ✅ Desktop (todas as resoluções)

##  Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Design moderno com Flexbox e Grid
- **JavaScript** - Interatividade e animações
- **Google Fonts** - Tipografia (Poppins e Playfair Display)

##  Hospedagem

Para colocar o site no ar, você pode usar:

### Opção 1: GitHub Pages (Grátis)
1. Crie uma conta no GitHub
2. Crie um repositório
3. Faça upload dos arquivos
4. Ative GitHub Pages nas configurações

### Opção 2: Netlify (Grátis)
1. Crie uma conta no Netlify
2. Arraste a pasta do projeto
3. Site publicado automaticamente

### Opção 3: Vercel (Grátis)
1. Crie uma conta no Vercel
2. Conecte seu repositório ou faça upload
3. Deploy automático

### Opção 4: Hospedagem tradicional
1. Contrate um plano de hospedagem
2. Use FTP para enviar os arquivos
3. Configure o domínio

##  Manutenção

### Para adicionar novos produtos:
1. Abra `index.html`
2. Localize a categoria desejada
3. Copie um card de produto existente
4. Cole e edite as informações

### Para mudar preços:
1. Procure pela classe `.product-price`
2. Atualize o valor

### Para adicionar novas seções:
1. Crie a estrutura HTML em `index.html`
2. Adicione estilos em `styles.css`
3. Se necessário, adicione interatividade em `script.js`

##  Suporte

Para dúvidas ou customizações adicionais, entre em contato:
- WhatsApp: (número a ser definido)
- Email: (email a ser definido)

## 📝 Observações Importantes

 **IMPORTANTE:** Lembre-se de substituir:
- [ ] Números de WhatsApp (todas as 4 ocorrências)
- [ ] Caminhos das imagens
- [ ] Link do Google Maps
- [ ] Informações de contato
- [ ] Horário de funcionamento (se necessário)

##  Próximos Passos Sugeridos

1. Substituir todos os números de WhatsApp
2. Organizar e otimizar as imagens
3. Testar em diferentes dispositivos
4. Configurar Google Analytics (opcional)
5. Adicionar meta tags para redes sociais
6. Testar performance com Lighthouse
7. Fazer backup dos arquivos
8. Escolher e configurar hospedagem

##  Licença

Este projeto foi desenvolvido especificamente para a Padaria Cardoso.
