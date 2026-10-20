# Guia técnico

## Estrutura

```
limadigitalrj/
├── index.html            página principal
├── obrigado.html         depois de enviar o formulário
├── 404.html              página de erro (endereço não encontrado)
├── css/style.css         estilos da página principal, obrigado e 404
├── img/                  fotos e logos do site
├── exemplos/             landing pages de demonstração (cada uma tem o próprio estilo)
│   └── img/
├── marca/                arquivos da marca (logo em PNG/SVG)
├── doc/                  esta documentação (bloqueada no site)
├── robots.txt / sitemap.xml   para o Google
├── _redirects            regras do Netlify (bloqueia /doc/)
└── favicon-32.png, favicon.svg, apple-touch-icon.png
```

Hospedagem: **Netlify**, publicado a partir do GitHub (`raphaellimadigital-eng/limadigitalrj`, branch `main`).
Não tem build: o Netlify publica os arquivos como estão. Fluxo: **editar → commit → push**, e em ~1 minuto o site atualiza.

## Cores e medidas (variáveis em `css/style.css`)

| Variável | Valor | Uso |
|---|---|---|
| `--preto` | #0F0F10 | fundo |
| `--grafite` | #19191B | fundo de seções alternadas e cartões |
| `--laranja` | #FE6A00 | cor da marca, botões e destaques |
| `--gelo` | #F3F1EC | texto principal |
| `--texto-2` | #CFCDC8 | texto de apoio |
| `--cinza` | #A3A3A8 | legendas |
| `--raio-p` / `--raio` / `--raio-g` | 4 / 6 / 10 px | cantos arredondados |

**Tema claro:** as cores ligadas ao tema são `--cor-fundo`, `--cor-superficie`, `--cor-texto` e `--cor-link`, além dos tons de texto e de borda. O bloco `:root[data-tema="claro"]`, no começo do `style.css`, troca só esses valores. Uma cor nova que precise mudar com o tema deve virar variável nos dois blocos. Texto sobre o laranja usa sempre `--tinta` (escuro).

Fontes: **Barlow Condensed** (títulos) e **Barlow** (texto), pelo Google Fonts.

## Tarefas comuns

### Trocar o número do WhatsApp
Busque `5521982232973` em `index.html`, `obrigado.html` e `404.html` e troque em todos. O número também aparece escrito como texto `(21) 98223-2973` e no bloco de dados estruturados (`"telephone"`).

### Adicionar um cliente
1. Salve a logo quadrada (240×240) como `img/cliente-NOME.webp`.
2. No `index.html`, na seção `id="clientes"`, copie um bloco `<li>…</li>` e troque o link do Instagram, as iniciais, o nome, o ramo e o @.

### Adicionar ou trocar uma foto da galeria
1. Exporte a foto em .jpg (lado maior com ~1500 px) para `img/`.
2. Gere versões WebP de 700, 1000 e 1400–1500 px de largura. Pode usar squoosh.app, que é grátis e roda no navegador.
3. No `index.html`, copie um bloco `<figure class="foto">` da galeria e troque os nomes dos arquivos e o texto `alt` (descrição da foto).

### Ativar o CNPJ e as estatísticas
Veja `pendencias.md`. As duas linhas já estão prontas no `index.html`, só que desativadas.

## Cuidados

- **Feche e abra de novo os arquivos no editor antes de fazer o commit.** Já aconteceu de o editor salvar por cima uma versão antiga.
- Toda foto nova precisa de texto `alt` (acessibilidade e Google).
- Ao mudar o site, atualize a data em `sitemap.xml` (`<lastmod>`).
