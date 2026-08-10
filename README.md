# Adolfo Nogueira Advocacia

Landing page estática preparada para apresentação comercial e publicação na Vercel.

## Estrutura

- `index.html`: página completa.
- `assets/`: fotos, monograma e ícones otimizados.
- `og-image.webp`: imagem de compartilhamento 1200 × 630 px.
- `robots.txt` e `sitemap.xml`: indexação.
- `site.webmanifest` e favicons: identidade no navegador e celular.
- `vercel.json`: headers de segurança e cache dos arquivos estáticos.

## Publicar pelo GitHub e Vercel

1. Crie um repositório no GitHub chamado `adolfonogueira-advocacia`.
2. Envie **o conteúdo desta pasta para a raiz** do repositório. O arquivo `index.html` não pode ficar dentro de outra subpasta.
3. Na Vercel, selecione **Add New > Project** e importe o repositório.
4. Em **Framework Preset**, selecione `Other`.
5. Não preencha Build Command. Mantenha a raiz do projeto como `./` e publique.
6. Use `adolfo-nogueira-advocacia` como nome do projeto para obter, se disponível, a URL esperada:
   `https://adolfo-nogueira-advocacia.vercel.app/`

## Conferência após o primeiro deploy

Se a Vercel gerar uma URL diferente, substitua a URL esperada nestes arquivos antes do deploy final:

- `index.html`: canonical, Open Graph, Twitter e JSON-LD.
- `robots.txt`: endereço do sitemap.
- `sitemap.xml`: URL principal.

Depois, confirme:

- Página inicial e todas as imagens carregando.
- Botões do WhatsApp abrindo o número correto.
- Layout no computador e no celular.
- `robots.txt`, `sitemap.xml` e `og-image.webp` acessíveis pela URL pública.

## Dados utilizados

- WhatsApp: (88) 9 9916-0853.
- OAB/CE 30.698.
- Sede: Rua Presidente Vargas, 86, José Aurélio Câmara, Quixeramobim–CE.
- E-mail: adolfonogueiraadv@hotmail.com.

Este site apresenta informações institucionais e não contém promessa de resultado jurídico.
