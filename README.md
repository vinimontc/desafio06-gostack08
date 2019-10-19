# Aplicação com React Native

Aplicação utilizando React Native e a API de usuários do GitHub onde o desafio proposto após o desenvolvimento da aplicação em si foi a implementação das funcionalidades abaixo:

## Funcionalidades

### Loading de repositórios

Indicator de loading utilizando `<ActivityIndicator />` antes de carregar a lista de repositórios favoritados na tela de detalhes do Usuário.

### Scroll infinito

Funcionalidade de scroll infinito na lista de repositórios favoritados. Assim que o usuário chegar nos **20%** do final de lista, busque pelos items na próxima página e adicione na lista. 

### Pull to Refresh

Funcionalidade para quando o usuário arrastar a listagem de repositórios favoritados pra baixo atualize a lista resetando o estado, ou seja, volte o estado da paginação para a página 1 exibindo apenas os 30 primeiros itens.

### WebView

Página na aplicação que é acessada quando o usuário clica em um repositório favoritado, essa página contém apenas o Header da aplicação. O conteúdo da página é uma WebView, ou seja, um browser integrado que exibe o atributo `html_url` presente no objeto do repositório que vem da API do Github.

## Observação

- Aplicação feita com base nas aulas sobre React Native e React do bootcamp GoStack 8.0 da RocketSeat.
