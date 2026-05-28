# Arquivos de Imagem Pública - Basefort

## Arquivos Disponíveis

### og-image.svg
- **Uso:** Compartilhamento em redes sociais (Facebook, LinkedIn, Twitter)
- **Dimensões:** 1200x630px (ideal para OpenGraph)
- **Formato:** SVG (vetorial, escalável)
- **Descrição:** Logo Basefort com texto "BASEFORT CONSTRUÇÕES" e "Sistema de Gestão"

### favicon.svg
- **Uso:** Ícone da aba do navegador
- **Dimensões:** 180x180px
- **Formato:** SVG

### apple-touch-icon.svg
- **Uso:** Ícone iOS quando adicionado à tela inicial
- **Dimensões:** 180x180px
- **Formato:** SVG com cantos arredondados

## Como Usar a Logomarca Real

Se você quiser usar a logomarca JPEG/PNG real (a imagem que enviou no WhatsApp):

### Opção 1: Converter para PNG otimizado
1. Abra sua imagem (logomarca)
2. Redimensione para 1200x630px
3. Exporte como PNG otimizado
4. Salve como `og-image.png` neste diretório
5. Atualize `index.html`:
   ```html
   <meta property="og:image" content="/og-image.png" />
   <meta property="og:image:type" content="image/png" />
   ```

### Opção 2: Usar versão JPG
1. Salve sua logomarca como `og-image.jpg` (1200x630px)
2. Atualize `index.html`:
   ```html
   <meta property="og:image" content="/og-image.jpg" />
   <meta property="og:image:type" content="image/jpeg" />
   ```

### Opção 3: Integrar com design
1. Abra `og-image.svg` em um editor (Adobe Illustrator, Figma, Inkscape)
2. Importe/coloque sua logomarca real
3. Mantenha o layout com o texto "BASEFORT CONSTRUÇÕES"
4. Exporte como SVG ou PNG

## Recomendação

**SVG Atual:** Mantém qualidade em qualquer tamanho, menor arquivo
**PNG Real:** Mais profissional se sua logomarca tiver detalhes

Se quiser usar a imagem real:
1. Coloque a imagem PNG/JPG neste diretório (`public/`)
2. Atualize o caminho no `index.html`
3. Não esqueça de otimizar o tamanho (máximo 2MB)

## Plataformas

A imagem em `og:image` aparece em:
- Facebook
- Instagram  
- LinkedIn
- Twitter/X
- Pinterest
- WhatsApp Web
- Telegram
- Discord
- Slack

## Teste

Use estas ferramentas para verificar:
- https://www.heymeta.com/
- https://developers.facebook.com/tools/debug/sharing
- https://cards-dev.twitter.com/validator

## Caminho do Arquivo

Todos os arquivos públicos estão em: `/public/`

No HTML, referencie como: `/og-image.svg` ou `/og-image.png`
