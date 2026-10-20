# Pendências

Atualizado em 19/10/2026. Marque `[x]` quando concluir.

## Alta prioridade: colocar o site no ar com o domínio

- [ ] **Trocar os servidores DNS no Registro.br.** Use os 4 servidores que o Netlify mostra em *Domains → limadigitalrj.com.br → Name servers*. Caminho no Registro.br: quadro **DNS → Alterar servidores DNS**. Não use a opção "Provedor de serviços".
- [ ] **Ligar o HTTPS (cadeado).** Quando sumir o aviso "Netlify DNS propagating...", vá em *Domain management → HTTPS → Verify DNS configuration*.
- [ ] **Testar os dois endereços:** `limadigitalrj.com.br` e `www.limadigitalrj.com.br`.
- [ ] **Ativar o aviso por e-mail do formulário.** Netlify → *Forms* → *Enable form detection* (se aparecer) → aba *Submission notifications* → *Email notification* → formulário **contato**. Depois envie um teste pelo site e confira também a caixa de spam.
- [ ] **Desligar o site antigo na Vercel** (`lima-digital-seven.vercel.app`), para não existirem dois sites iguais no Google.

## Média prioridade: depende de dados seus

- [ ] **CNPJ no rodapé.** No `index.html`, procure `CNPJ 00.000.000/0001-00`, troque pelo número real e apague as marcas de comentário (`<!--` e `-->`) daquela linha.
- [ ] **Estatísticas de visitas (Cloudflare Web Analytics, grátis e sem cookies).** Crie a conta em dash.cloudflare.com → *Web Analytics* → *Add a site* → copie o token. No fim do `index.html`, troque `SEU_TOKEN` e apague as marcas de comentário.
- [ ] **Google Search Console.** Cadastre `limadigitalrj.com.br` e envie `https://limadigitalrj.com.br/sitemap.xml`.
- [ ] **Depoimentos reais.** Peça uma frase a cada cliente (CTI CrossBox, Torcida Fla São José, Ele Reina), com nome e autorização para publicar.
- [ ] **Definir preços** de gestão de Instagram, tráfego pago, fotografia, drone e criativos. Os de site já estão definidos: R$ 500 a 1.500, mais R$ 50 a 150 por mês de manutenção.

## Adiado (não agora)

- [ ] **E-mail profissional** (`contato@limadigitalrj.com.br`). Por enquanto fica o Gmail. Quando for criar, a opção grátis é o Zoho Mail; depois troque o Gmail no `index.html` (contato, rodapé e dados estruturados).
- [ ] **CNAE do MEI.** Foto (7420-0/01), drone (7420-0/02) e vídeo (5912-0/99) cabem no MEI. Sites, gestão de Instagram e tráfego pago não têm ocupação de MEI. Ver com contador ou Sebrae quando for formalizar esses serviços.

## Autorizações de imagem

- [ ] **Fotos do exemplo de retiro** (`exemplos/img/culto-*.jpg`). Se não forem suas, confirme a licença. A foto da roda de violão mostra rostos, então peça autorização a quem aparece ou troque a foto.
- [ ] **Casa do exemplo da imobiliária.** É uma casa real fotografada com drone num anúncio fictício. Confirme que o dono autoriza.

## Conteúdo que ainda falta

- [ ] **Fotos de eventos** (corporativos e de igreja) para a página inicial, quando tiver os primeiros trabalhos.
- [ ] **Portfólio de fotografia**, porque hoje só há trabalhos com drone.
- [x] **Perfil da Empresa no Google** virou serviço ativo em 20/10 (site, posts e catálogo do WhatsApp).
- [ ] **Criar e verificar o Perfil da Empresa no Google da própria Lima Digital** (business.google.com, área de atendimento sem mostrar endereço, verificação por vídeo).
