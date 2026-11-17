# VT Gastronomia

Projeto demonstrativo e reutilizável da VT Sites para estabelecimentos do setor gastronômico.

A proposta é reunir, em uma experiência digital adaptável, informações e caminhos de atendimento de restaurantes, pizzarias, hamburguerias, lancherias, cafeterias, confeitarias e outros negócios de alimentação. O cardápio e o fluxo de pedidos são funcionalidades do projeto — não o nome ou o limite do produto.

## Publicar na Vercel
1. Importe este repositório na Vercel.
2. Framework Preset: **Other**.
3. Build Command: deixe vazio.
4. Output Directory: `.`.
5. Deploy.

## Antes de adaptar para um estabelecimento
- Produtos, descrições, imagens e preços atuais são ilustrativos.
- Substitua pelos dados, identidade visual e fotos autorizados pelo estabelecimento.
- Configure no objeto `CONFIG`, no fim de `index.html`, os canais oficiais:
  - `whatsapp`: número com código do país e DDD, somente dígitos.
  - `deliveryUrl`: link do delivery próprio, se houver.
  - `ifoodUrl`: link da loja no iFood, se houver.
  - `locationUrl`: link da localização.
- Confirme todos os links e teste o fluxo antes de apresentar como versão final.

## Recursos demonstrativos
- Layout responsivo.
- Categorias e apresentação de produtos.
- Carrinho com quantidades e total.
- Resumo do pedido com nome e observações.
- Atalhos para os canais de atendimento configurados.

Feito pela **VT Sites**.
