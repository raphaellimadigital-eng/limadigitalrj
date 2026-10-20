# Melhorias futuras

Ideias para depois. Nenhuma é urgente. Cada uma explica o que ganha.

## Conversão e confiança

| Ideia | Benefício | Esforço |
|---|---|---|
| Seção de **depoimentos** depois de "Clientes" | Prova social real perto do contato | Baixo (quando tiver as frases) |
| **Política de privacidade** (LGPD), com link no formulário | O formulário coleta nome e WhatsApp; a página mostra seriedade e cumpre a lei | Baixo |
| **Portfólio de fotografia** e de **eventos** | Mostra os serviços que hoje só aparecem em texto | Médio (depende das fotos) |
| Faixa de **números** (ex.: "X perfis atendidos", "X voos") | Credibilidade rápida | Baixo, mas só com números reais |
| Botão "Quero ser avisado" no cartão do **Perfil da Empresa no Google** | Já captura interessados antes do lançamento | Baixo |

## SEO (aparecer no Google)

| Ideia | Benefício | Esforço |
|---|---|---|
| **Uma página por serviço** (ex.: `/drone-imoveis`, `/criacao-de-sites`) | Aparecer em buscas específicas, como "drone imóvel Nova Iguaçu" | Médio |
| **Perfil da Empresa no Google** da própria Lima Digital | Aparecer no Google Maps da Baixada | Baixo |
| Imagem de compartilhamento própria para cada exemplo | Prévia certa quando mandar o link de um exemplo | Baixo |
| Atualizar a data no `sitemap.xml` sempre que mudar o site | O Google volta a visitar mais rápido | Muito baixo |

## Design e experiência

| Ideia | Benefício | Esforço |
|---|---|---|
| Link **"Clientes" no menu** | Acesso direto à prova social. Hoje não cabe entre 820 e 900 px de largura, então precisa ajustar onde o menu vira "hambúrguer" | Baixo |
| **Indicar no menu a seção atual** enquanto a página rola | Orientação em página longa | Baixo |
| **Alinhar "Perguntas frequentes" à esquerda**, como as outras seções | Alinhamento uniforme | Muito baixo |
| **Novos exemplos** de landing page (restaurante, salão, academia) | Mais nichos se veem no site | Médio por exemplo |
| Animação discreta de entrada nas seções (com respeito a "reduzir movimento") | Sensação mais polida | Baixo |

## Técnico e performance

| Ideia | Benefício | Esforço |
|---|---|---|
| Converter as fotos das **páginas de exemplo** para WebP (como a página inicial) | Exemplos abrem mais rápido. Hoje a imobiliária carrega ~1,4 MB | Baixo |
| Arquivo `netlify.toml` com **cabeçalhos de cache e segurança** | Visitas repetidas mais rápidas e proteção básica | Baixo |
| Formatar o **WhatsApp automaticamente** no formulário: (21) 9 0000-0000 | Menos números digitados errado | Baixo |
| Tirar a pasta `marca/` do site publicado (ou bloquear no `_redirects`) | Os arquivos de marca não ficam públicos | Muito baixo |

## Já avaliado e mantido de propósito

- **Sem framework** (React, Next etc.). HTML, CSS e JavaScript simples são mais rápidos, mais baratos e mais fáceis de manter para este site.
- **Identidade preto + laranja (#FE6A00)** e títulos em Barlow Condensed.
- **WhatsApp como canal principal**, com mensagem pronta em cada botão.
