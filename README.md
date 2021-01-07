# Desafio Toro Desenvolvedor Mobile

Bem-vindo ao desafio de programação Mobile da Toro Investimentos.

## Problema

Crie um app mobile que:
- Tela de Splash
Tela de Splash deve conter uma animação simples a sua escolha

- Telas de introdução ao aplicativo
A introdução deve ser feita do zero, sem utilização de qualquer pacote existente.

- Exiba uma tela de login inicial:
Trate tentativas de login com sucessso e erro, informando para o usuário de forma agradável: login e senha inválidos, campos não preenchidos e requisito de senha inválidos (minimo 6 caracteres)

## Problema para ser resolvido em conjunto

- Após login com sucesso, navege para uma tela que exiba em tempo real, de forma organizada e agradável, preços de ações recebidas através de uma conexão websocket. 
É preciso exibir pelo menos as 5 ações mais valorizadas e as 5 menos valorizadas em cards contendo o símbolo da ação, o preço atual e um gráfico que ilustre a evolução do preço.
As cotações devem ser recebidas a partir do nosso simulador de cotações que pode ser acessado usando docker com o seguinte comando: docker run -p 8080:8080 toroinvest/quotesmock. O fluxo de cotações está no endpoint /quotes. 
Obs: este simulador de cotações não responde ao protocolo HTTP, apenas websocket.

## Requisitos

- O projeto deve ser publicado em um repositório público no github.com, bitbucket.org ou gitlab.com
- README com instruções de como instalar as dependências do projeto, de como rodar a aplicação e como rodar os testes automatizados
- Deve ser desenvolvido em Flutter


## Critérios de Avaliação

Os seguintes critérios serão usados para avaliar o seu código:
- Legibilidade;
- Escopo;
- Organização do código (camadas bem definidas. Ex: apresentação não deve conter regras de negócio);
- Padrões de projeto (IoC, DI);
- Existência e quantidade de bugs e gambiarras;
- Documentação;
- Responsividade e comportamento em diversas telas
- Gestão de estado (BloC, Mobx, etc.)

### Bônus

- CI/CD
- Testes unitários;
- Contexto e cadência dos commits.
- Fazer efeitos de transição na tela de introdução
## Dúvidas

Em caso de dúvidas entre em contato conosco pelo nosso email: desafiotoro@toroinvestimentos.com.br
Sugestões de tela na pasta
