# Batalha da Aldeia — 10 Anos

Site não oficial, feito por um fã, com o painel completo dos MCs da **Batalha da Aldeia 10 Anos** — trios, estatísticas, conquistas e as batalhas de destaque de cada competidor, tudo numa página só.

🔗 **Site ao vivo:** _https://jokfernandes.github.io/bda-10-anos/_

---

## O que tem no site

- **Cards por trio**, organizados em "pódio" (o MC com melhor desempenho aparece no meio, os outros dois nas laterais), com foto, tags (Estreante, Campeão, MVP), estado e estatísticas — colapsados por padrão, revelados com um clique.
- **Win rate combinado do trio**, com selo automático de "Trio em Ascensão" ou "Trio Dominante", e um painel expansível com radar comparativo + placar dos 3 integrantes.
- **Hall da Fama** — Top 5 por categoria (mais títulos, mais participações, maior aproveitamento em trio e individual), com critério de desempate.
- **Comparação** — MC vs MC ou Trio vs Trio lado a lado, incluindo uma "roleta de confronto" que sorteia dois nomes aleatórios.
- **Busca com filtros** — por nome, tags e estado.
- **Modo apresentação** — tela cheia, avança automaticamente entre trios (ou entre MCs individuais no celular), pensado pra exibição em telão/projetor.
- **Vídeos** de cada MC tocando direto na página (sem redirecionar pro YouTube), com preview mudo ao passar o mouse.
- Contagem regressiva para o evento, partículas, efeitos de flutuação e outros detalhes visuais.

## Tecnologia

Um único arquivo HTML autocontido (`index.html`) — sem build, sem dependências externas de framework. HTML + CSS + JavaScript puro. As fotos dos MCs e as fotos de trio ficam hospedadas separadamente (ver abaixo); o restante (logo, emblema, fundo do cabeçalho) está embutido no próprio arquivo.

## Hospedagem de mídia

- **Vídeos e fotos**: hospedados num bucket Cloudflare R2, carregados sob demanda (lazy load) conforme o card entra na tela.
- **Padrão de nome de arquivo**: `NomeDoMC.png` para fotos individuais, `Trio NomeDoRepresentante.png` para fotos de trio (ex: `Sid.png`, `Trio Sid.png`). Nomes com espaço ou acento são automaticamente codificados na URL.

## Atualizando os dados

Os dados de cada MC (participações, títulos, rounds, aproveitamento, tags especiais) vêm de uma planilha de controle. Pra adicionar um trio novo ou atualizar estatísticas, edite a planilha e gere um novo `index.html` a partir dela — o layout, ranking, comparação e modo apresentação se ajustam automaticamente à quantidade de trios/MCs.

## Publicando no GitHub Pages

1. Suba o arquivo `index.html` (e `og-image.jpg`, se for usar preview de compartilhamento) pra raiz do repositório.
2. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`.
3. Aguarde a publicação — o link fica em `https://seu-usuario.github.io/nome-do-repositorio/`.

## Aviso

Este é um projeto pessoal e não oficial, feito por um fã, sem fins comerciais. Todos os direitos do evento, marca e identidade visual pertencem à **Batalha da Aldeia**.
