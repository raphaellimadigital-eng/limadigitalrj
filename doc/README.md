# Documentação do site Lima Digital

Pasta de anotações internas do projeto **limadigitalrj.com.br**.
O site não mostra estes arquivos: o `_redirects` na raiz bloqueia `/doc/` para quem tenta abrir pelo navegador.

| Arquivo | Para que serve |
|---|---|
| [pendencias.md](pendencias.md) | O que falta fazer agora, em ordem de prioridade. Marque com `[x]` quando concluir. |
| [melhorias-futuras.md](melhorias-futuras.md) | Ideias para depois, com o motivo de cada uma. |
| [guia-tecnico.md](guia-tecnico.md) | Como o site é organizado e como fazer as alterações mais comuns. |

## Histórico

### 19/10/2026: tema claro opcional
- Botão de sol/lua no topo. O site abre escuro e o visitante pode trocar para o claro; a escolha fica salva no navegador.
- O menu passa a virar "hambúrguer" a partir de 920 px de largura (antes, 820 px).
- As páginas "mensagem enviada" e 404 continuam só no escuro.

### 19/10/2026: refinamento profissional
- Imagem de compartilhamento (`img/compartilhar.jpg`, 1200×630) e metatags completas.
- Fotos convertidas para WebP em vários tamanhos. Página inicial: de ~1,8 MB para ~0,6 MB (computador) e ~0,75 MB (celular).
- Grade de serviços sem buraco e um botão "Pedir orçamento" em cada serviço, com mensagem pronta no WhatsApp.
- Clientes em seção própria, com as logos reais (CTI CrossBox, Torcida Fla São José, Ele Reina).
- SEO: dados estruturados de empresa local (JSON-LD), `robots.txt`, `sitemap.xml` e página `404.html`.
- Rodapé completo com navegação e contatos.
- CSS com variáveis de cor e de cantos arredondados; efeito ao passar o mouse igual em todos os cartões.
- Menu do celular fecha com Esc e ao tocar fora.
- Página "mensagem enviada" (`obrigado.html`) refeita.
- Exemplo de retiro de igreja com fotos de culto.

### Antes disso
- Site novo no Netlify (saiu da Vercel), domínio `limadigitalrj.com.br` registrado no Registro.br.
- Duas landing pages de exemplo: imobiliária (`exemplos/imobiliaria.html`) e retiro de igreja (`exemplos/conferencia.html`).
- Formulário de contato com Netlify Forms.
