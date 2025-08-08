# Quero ser MB

Somos a maior plataforma de negociação de criptomoedas e ativos alternativos da América Latina, criada para elevar a experiência de quem vivencia essa revolução, entregando o melhor serviço de negociação de ativos alternativos, com liberdade, segurança e liquidez. Sendo assim, nós existimos para mudar a maneira como as pessoas lidam com o dinheiro através da tecnologia.

### Objetivo

O objetivo deste desafio é entender seus conhecimentos, estilo de programação e como você resolve desafios técnicos.

### Projeto
Criar um aplicativo para consultar a [coinmarketcap](https://coinmarketcap.com/api/documentation/v1/#operation/getV1ExchangeInfo) e trazer as exchanges em forma de lista e suas moedas.


### Credencial da API
Será necessária uma [API_KEY](https://pro.coinmarketcap.com/api/v1) para utilizar a API.


### Features
-   **Tela de listagem:**
    - Exibir, pelo menos, os campos: `logo`, `name`, `spot_volume_usd` e `date_launched`
    - Ao tocar em um item deve ser exibida a tela de detalhes.
-   **Tela de detalhe:**
    - Exibe os detalhes da exchange com os campos: `logo`, `name`, `id`, `description`, `url do website`, `maker_fee`, `taker_fee` e `date_launched`;
    - E a [Listagem das moedas](https://coinmarketcap.com/api/documentation/v1/#operation/getV1ExchangeAssets) com os campos: `currency.name` e `currency.price_usd`
    
### Requisitos Técnicos
|      Android       |     iOS            |     Flutter        |
| ------------------ | ------------------ | ------------------ |
| Kotlin             |  Swift 5+          | Dart               |
| Compose            |  View Code         | Flutter Widgets    |
| Testes unitários   |  Testes unitários  | Testes unitários   |
| Testes de UI       |  Testes de UI      | Testes de UI       |

#### Arquitetura

Sinta-se à vontade para utilizar a arquitetura que melhor atender o projeto proposto. Aqui no Mercado Bitcoin utilizamos 

|      Android       |     iOS            |     Flutter            |
| ------------------ | ------------------ | ---------------------- |
| MVVM com Clean     |  MVVM-C e VIP-C    | Flutter_Bloc com Clean |

### Requisitos não funcionais

- UI e UX fluída seguindo os padrões da plataforma.
- A aplicação deve ser resiliente, tratamento de erros são bem-vindos.
- Considerar escalabilidade.

### Prazo
A partir do envio do desafio ao candidato por e-mail, o prazo de retorno é de 7 dias corridos.

### Processo de Submissão
O candidato deverá criar um novo repositório no Github, público ou privado, para realização do teste.

Caso opte pelo repositório privado, adicionar como **ADMIN** os usuários abaixo:

|      Android       |     iOS             |    Flutter          |
| ------------------ | ------------------- |-------------------- |
| gabrielprado-mb    | guilhermemachado-mb | gabrielprado-mb     |
| luiztorres-mb      | alexandremarconi-mb | guilhermemachado-mb |

### IMPORTANTE
Esse código não será usado em nenhuma hipótese para qualquer fim a não ser o de avaliação de conhecimentos técnicos.
