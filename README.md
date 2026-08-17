# 🌳 Batalha da Aldeia — 10 Anos

**Um hub completo pra acompanhar os 30 MCs da Batalha da Aldeia 10 Anos — trios, estatísticas, conquistas e as batalhas de destaque de cada competidor, tudo numa página só, sem sair pra lugar nenhum.**

### 🔗 [jokfernandes.github.io/bda-10-anos](https://jokfernandes.github.io/bda-10-anos/)

![Cabeçalho do site](readme_shots/01_hero.png)

---

## Por que esse site existe

Acompanhar 10 (e contando) trios espalhados em posts, stories e planilhas é trabalhoso. Esse site junta tudo num lugar só: quem está em cada trio, quem manda mais no round de trio, quem é estreante, quem já é lenda — e ainda deixa você comparar dois MCs (ou dois trios inteiros) lado a lado, ou simplesmente sortear um confronto aleatório pra descobrir alguém novo.

Não é o site oficial do evento — é um projeto de fã, feito pra ser rápido, bonito e útil tanto pra quem já acompanha de perto quanto pra quem está chegando agora.

## O que você encontra

**Cards em formato de pódio** — o MC com melhor desempenho do trio aparece no meio, em destaque; os outros dois nas laterais. Cada card começa fechado (só foto, nome, estado e tags) e revela as estatísticas com um clique — com efeito de "impacto" ainda mais forte nos MVPs e lendas do evento.

**Cards lendários com tratamento especial** — MVPs de edições anteriores e campeões atuais ganham borda dourada, brilho pulsante e uma entrada mais dramática ao expandir.

**Hall da Fama** — Top 5 automático por categoria (mais títulos, mais participações, maior aproveitamento), recalculado sempre que os dados são atualizados.

**Comparação cara a cara** — escolha dois MCs (ou dois trios inteiros) e veja todas as estatísticas lado a lado. Sem ideia de quem comparar? O botão "Me surpreenda" gira uma roleta e sorteia um confronto pra você.

**E também:**
- Busca com filtros por tag e estado
- Vídeo do round de destaque de cada MC tocando direto na página
- Modo apresentação em tela cheia, ideal pra passar num telão
- Contagem regressiva pro dia do evento

## Como foi feito

Um único arquivo HTML, sem framework, sem build — só HTML, CSS e JavaScript direto ao ponto. Isso significa que o site abre instantaneamente e roda em qualquer lugar, do computador ao celular. Fotos e vídeos ficam num bucket separado e só carregam quando o card entra na tela, mantendo tudo leve mesmo com dezenas de MCs.

Os dados (participações, títulos, rounds, aproveitamento) são atualizados a partir de uma planilha de controle — conforme novos trios são anunciados e as estatísticas evoluem, o site é regenerado e tudo (ranking, comparação, modo apresentação) se ajusta sozinho.

---

*Projeto pessoal e não oficial, feito por um fã, sem fins comerciais. Todos os direitos do evento, marca e identidade visual pertencem à **Batalha da Aldeia**.*
