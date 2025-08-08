 Visão Geral do Projeto (Abrir pacotes)

Este é um **site interativo em HTML, CSS e JavaScript** que simula a experiência de **abrir um pacote de cartas Pokémon**. O usuário pode revelar cartas aleatórias e salvá-las em sua coleção local.

Estrutura Principal

- **HTML** define a estrutura da página:
  - Um **menu de navegação** com links para outras páginas.
  - Um **título** e uma **área de exibição da carta**.
  - Três **botões**: Abrir Pacote, Revelar Próxima Carta e Salvar na Coleção.
  - Um **status** que mostra mensagens ao usuário.

- **CSS** estiliza a página com:
  - Um visual moderno e escuro.
  - Botões estilizados com efeitos de hover.
  - Layout centralizado e responsivo.

- **JavaScript** adiciona interatividade:
  - Busca cartas da API do Pokémon TCG.
  - Seleciona 6 cartas aleatórias para o pacote.
  - Permite revelar uma carta por vez.
  - Salva a carta revelada na coleção usando `localStorage`.

  Funcionalidades Básicas

**Abrir Pacote**: Carrega 6 cartas aleatórias.
  **Revelar Carta**: Mostra uma carta por vez com efeito de fade.
  **Salvar Carta**: Armazena a carta revelada na coleção local do navegador.
