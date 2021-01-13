# Desafio Toro Desenvolvedor Mobile

Bem-vindo ao desafio de programação Mobile da Toro Investimentos.

Nesta etapa queremos ver suas habilidades técnicas e sua colaboratividade em trabalhos em grupo.
Este desafio foi projetado para que ele aconteça em duas etapas, uma em casa e outra em conjunto com a equipe da Toro.

## Primeira etapa: Em casa :house_with_garden:

Este é o momento que você terá para pensar no problema a ser resolvido e em como você irá arquitetar seu app para isso. 

Algumas dúvidas que devem ser respondidas nesta etapa:
- Quais as camadas necessárias? 
- Como será a separação entre elas? 
- MVC? MVVM? Clean Code? etc...
- Quais as bibliotecas e frameworks a serem usados?
- Como você irá gerir o estado do seu app?
- E a gestão da qualidade?

E para ajudá-lo a respondê-las, é importante que você na segunda etapa com as seguintes features já desenvolvidas: 

- Tela de Splash
A sua Splash deve conter uma animação simples a sua escolha

- Telas de introdução ao aplicativo (Onboarding)
Você deverá ajudar o cliente a entender as funcionalidades do seu app. A quantidade de telas, design e interação entre as telas fica a sua escolha.

- Tela de login:
Trate tentativas de login com sucessso e erro, informando para o usuário de forma agradável: login e senha inválidos, campos não preenchidos e requisito de senha inválidos (mínimo 6 caracteres)

## Segunda Etapa: em conjunto :floppy_disk:

- Após login com sucesso, vamos criar a navegação para uma tela interna, apenas para clientes logados;
- Esta tela deverá exibir em tempo real, de forma organizada e agradável, preços das ações recebidas através de uma conexão websocket. 
- Vamos exibir pelo menos as 5 ações mais valorizadas e as 5 menos valorizadas em cards contendo o símbolo da ação, o preço atual e um gráfico que ilustre a evolução do preço.

Obs: As cotações devem ser recebidas a partir do nosso simulador de cotações que pode ser acessado usando docker com o seguinte comando: docker run -p 8080:8080 toroinvest/quotesmock. O fluxo de cotações está no endpoint /quotes.  Importante: este simulador de cotações não responde ao protocolo HTTP, apenas websocket.

## Requisitos

- Cumprimento da primeira etapa para evoluirmos para a segunda;
- O projeto deve ser publicado em um repositório público no github.com, bitbucket.org ou gitlab.com e compartilhado com o time da Toro;
- README com instruções de como instalar as dependências do projeto, de como rodar a aplicação e como rodar os testes automatizados;
- Deve ser desenvolvido em Flutter;


## Critérios de Avaliação

Os seguintes critérios serão usados para avaliar o seu código:
- Legibilidade;
- Cuprimento do escopo;
- Organização do código (camadas bem definidas. Ex: apresentação não deve conter regras de negócio);
- Padrões de projeto (IoC, DI);
- Existência e quantidade de bugs e gambiarras;
- Documentação;
- Responsividade e comportamento em diversas telas;
- Gestão de estado (BloC, Mobx, etc.)

### Bônus

- CI/CD
- Testes unitários;
- Contexto e cadência dos commits.
- Fazer efeitos de transição na tela de introdução

## Dúvidas

Em caso de dúvidas entre em contato conosco pelo nosso email: desafiotoro@toroinvestimentos.com.br
Sugestões de tela na pasta
