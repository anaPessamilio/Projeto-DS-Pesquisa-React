# Solução de Pesquisa de Jogos

## Descrição

A **Solução de Pesquisa de Jogos** é um sistema completo para coletar, gerenciar e analisar preferências de jogos dos usuários. O sistema é composto por um aplicativo móvel que coleta feedback dos usuários e uma API backend para gerenciar e fornecer esses dados. Este projeto é ideal para empresas e desenvolvedores que desejam entender melhor as preferências dos jogadores e otimizar suas ofertas com base em dados reais.

## Funcionalidades

### Frontend

- **Interface Intuitiva**: Tela inicial com uma imagem de destaque e uma chamada para ação.
- **Coleta de Dados**: Permite aos usuários indicar seu jogo favorito.
- **Integração com Backend**: Envia os dados coletados para a API backend para processamento.

### Backend

- **API RESTful**: Endpoint para recuperação de dados sobre jogos.
- **Gerenciamento de Jogos**: Manipulação e fornecimento de dados relacionados aos jogos.
- **Escalabilidade**: Projeto configurado para expansão e integração com outros serviços.

## Tecnologias

- **Frontend**: React Native, Expo, FontAwesome
- **Backend**: Spring Boot, Java
- **Banco de Dados**: H2 Database (ou substitua conforme a necessidade)

## Estrutura do Projeto

### Frontend

- **`/src/components/Home.js`**: Componente principal do aplicativo que exibe a tela inicial para coleta de dados de jogos.
- **`/assets/gamer.png`**: Imagem exibida na tela inicial.

#### Dependências

- `react-native`
- `@expo/vector-icons`
- `react-native-gesture-handler`

### Backend

- **`/src/main/java/com/devsuperior/dspesquisa/resources/GameResource.java`**: Controlador REST que fornece a lista de jogos.
- **`/src/main/java/com/devsuperior/dspesquisa/services/GameService.java`**: Serviço que lida com a lógica de negócios relacionada aos jogos.

#### Dependências

- `spring-boot-starter-web`
- `spring-boot-starter-data-jpa`
- `h2`
