# Relatório de otimização

Projeto conceitual AN Advocacia, criado para portfólio e revisado em 12/08/2026.

> Atualização de prospecção: as fotografias foram removidas do layout e do pacote em 11/08/2026. As molduras foram preservadas para receber as imagens aprovadas pelo profissional.

## Resultado

- HTML semântico validado com `html-validate`.
- JavaScript validado sintaticamente e sem bibliotecas externas.
- Todas as referências locais verificadas; nenhum arquivo ausente.
- Monograma em WebP; fotografias removidas da versão de prospecção.
- Molduras mantidas com proporções definidas, evitando mudança de layout quando as fotos definitivas forem inseridas.
- Fontes externas removidas. O projeto usa duas famílias de sistema, sem bloqueio de renderização.
- Metadados completos: title, description, author, robots, canonical, Open Graph e Twitter Card.
- JSON-LD `LegalService`, favicons, manifest, robots.txt e sitemap.xml adicionados.
- Acessibilidade reforçada com link de salto, foco visível, landmarks, headings hierárquicos, textos alternativos, controles nomeados e redução de movimento.
- Links externos com `rel="noopener noreferrer"`.
- Cabeçalhos de segurança fornecidos no arquivo `_headers` para hosts compatíveis.
- Linguagem ética revisada, sem promessa de resultado ou garantia de retorno imediato.

## Comparativo das imagens antes da remoção

| Arquivo | Original | WebP | Redução |
|---|---:|---:|---:|
| Retrato do hero | 81.999 B | 15.704 B | 80,8% |
| Escritório | 244.898 B | 70.042 B | 71,4% |
| Foto de perfil | 375.647 B | 48.320 B | 87,1% |
| Monograma | 308.416 B | 9.724 B | 96,8% |

Os dados acima registram a otimização realizada antes da retirada das fotos. Os PNGs restantes são apenas os ícones exigidos por navegadores e dispositivos Apple; a marca usada no conteúdo está em WebP.

## Checklist final

- [x] Conteúdo raster do site em WebP
- [x] Referências de conteúdo apontando para `.webp`
- [x] Hero sem requisição de fotografia na versão de prospecção
- [x] Molduras com proporção fixa para evitar CLS
- [x] Dimensões explícitas nas imagens restantes
- [x] OG image WebP em 1200 × 630 px
- [x] No máximo duas famílias tipográficas
- [x] Nenhuma fonte ou biblioteca externa bloqueante
- [x] Animações contínuas em CSS
- [x] Preferência `prefers-reduced-motion` respeitada
- [x] `lang="pt-BR"`
- [x] Alt descritivo ou alt vazio para imagens decorativas
- [x] Contraste textual reforçado
- [x] Links e botões nomeados
- [x] Um H1 e hierarquia H2/H3 consistente
- [x] Title com 43 caracteres
- [x] Description com 127 caracteres
- [x] Canonical e robots
- [x] Open Graph e Twitter Card
- [x] JSON-LD `LegalService`
- [x] Favicons 16/32/48, apple-touch-icon e manifest
- [x] Links externos protegidos
- [x] Sem erros de validação HTML
- [x] Sem referências locais quebradas

## Observações de publicação

A prévia está configurada para `https://adolfo-nogueira-advocacia.vercel.app/`. Se a Vercel gerar uma URL diferente ou o cliente contratar um domínio próprio, substitua-a no canonical, Open Graph, JSON-LD, robots.txt e sitemap.xml antes da publicação definitiva.

A nota real do PageSpeed depende também da hospedagem: HTTPS, compressão Brotli/Gzip, HTTP/2 ou HTTP/3, cache e tempo de resposta do servidor. Após publicar, execute Lighthouse/PageSpeed em modo anônimo e sem extensões. O pacote foi preparado para eliminar os principais gargalos no front-end, mas nenhuma nota deve ser prometida antes do teste na URL de produção.
