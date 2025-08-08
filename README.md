## Visão Geral do Projeto (Abrir pacotes)

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


## Visão Geral (TCG Dex)

Este é um **site em HTML, CSS e JavaScript** que funciona como uma **Pokédex para cartas Pokémon TCG**. Ele permite ao usuário **buscar cartas pelo nome** e exibe os resultados com informações detalhadas.


Estrutura da Página

- **Barra de navegação (navbar)** com links para outras seções do site.
- **Cabeçalho** com título e instruções.
- **Caixa de busca** onde o usuário digita o nome da carta.
- **Área de resultados** que mostra as cartas encontradas.

Estilo Visual (CSS)

- Tema escuro com gradiente de fundo.
- Layout centralizado e responsivo.
- Cartas exibidas em blocos com sombra, bordas arredondadas e efeito de zoom ao passar o mouse.
- Botões estilizados com cores vibrantes e efeitos de hover.

Funcionalidade (JavaScript)

- Quando o usuário digita um nome e clica em "Buscar":
  - O site faz uma requisição à **API do Pokémon TCG**.
  - Busca até 12 cartas que tenham o nome informado.
  - Exibe cada carta com:
    - Imagem
    - Nome
    - HP
    - Tipos
    - Raridade
    - Artista

- Se não encontrar nenhuma carta, exibe uma mensagem informando isso.
- Se houver erro na busca, mostra uma mensagem de erro.
