# Mala Feita

Organizador de malas para viagens curtas ou longas. Abre o `index.html` no navegador (funciona offline, no telemóvel e no computador).

- **Viagem**: destino, datas, transporte (avião, carro ou comboio), clima, atividades, lavandaria e tipo de bagagem.
- **Hábitos**: questionário único (pijamas por semana, trocas de roupa por dia, margem de segurança, etc.) que serve para todas as viagens.
- **Mala**: lista gerada por secções com quantidades calculadas, checklist, itens próprios e atribuição de cada item a uma mala ou mochila (vista por secção ou por mala).
- **Outfits**: guarda-roupa da viagem, montagem e sugestão de combinações, plano por dia. As peças do plano entram na lista da mala.

**Fotografias**: cada peça pode ter fotografia (câmara ou galeria), reduzida no próprio aparelho antes de ser guardada.

**Sessão e sincronização**: na versão publicada no claude.ai a sessão é a conta Claude. O estado fica num documento privado por utilizador e as fotografias no armazenamento do artefacto, por isso o telemóvel e o computador veem os mesmos dados. Aberto como ficheiro local, o `index.html` funciona sem conta: guarda tudo no `localStorage` (fotografias em miniatura) e tem cópia/restauro por texto.
