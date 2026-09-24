# Página de vendas — Pack Educação Infantil Completa

Página estática, sem build e sem servidor. Sobe em qualquer hospedagem.

| Arquivo | Para quê |
|---|---|
| `index.html` | **O que é publicado.** 48 KB, mais 276 KB em `img/`. |
| `preview-unico.html` | Arquivo único com as imagens embutidas, para mandar por WhatsApp. Não publique este. |
| `img/` | Oito páginas reais do material, em WebP a 680px. |

## Publicar no GitHub Pages

1. Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **main**, pasta **/ (root)** → Save

A página fica em `https://caio28193k.github.io/packs/` em um ou dois minutos.

## Antes de vender, trocar

1. Os dois `href="https://pay.SUA-PLATAFORMA.com.br/SEU-LINK"` pelo link real do checkout.
2. O bloco "Quem fez este material" pelos seus dados.
3. CNPJ e e-mail de suporte no rodapé.
4. Se usar domínio próprio, as tags `og:` no `<head>` (elas definem o que aparece quando o link é mandado no WhatsApp).

## Notas técnicas

- Preto e branco é decisão de produto: o material foi desenhado para a impressora da escola.
- A página trava `color-scheme: light`. Sem isso, o modo escuro do navegador inverte as cores sozinho.
- Verificada em 320px, 375px e em paisagem, sem rolagem lateral, com barra de compra fixa no celular.
- As imagens foram geradas no tamanho real de exibição. Não troque por PNG grande: o peso sobe cinco vezes.
