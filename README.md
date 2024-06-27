Servidor HTTP Simulado em JavaScript

Este projeto é um exemplo simples de como simular um servidor HTTP usando JavaScript diretamente no navegador. Ele demonstra como criar rotas básicas e responder a diferentes solicitações HTTP com respostas simples.

Funcionalidades

Servidor HTTP Simulado: Capaz de lidar com requisições HTTP simuladas diretamente no navegador.
Roteamento Simulado: Define rotas simples como / e /contato.
Respostas Simuladas: Envia respostas de texto simples e JSON baseadas na URL da requisição.

Estrutura do Projeto

O projeto consiste em um único arquivo HTML (index.html) que contém o código JavaScript para simular o servidor HTTP. Não é necessário nenhum ambiente de servidor como Node.js; tudo é executado no navegador.

Ao executar este código no navegador e abrir as Ferramentas de Desenvolvedor (guia "Console"), deverá aparecer:

Status da Requisição: Para cada requisição simulada (/ e /contato), você verá o status da resposta (200, 404, etc.).
Cabeçalhos da Resposta: Os cabeçalhos HTTP configurados para cada resposta serão exibidos, mostrando o tipo de conteúdo (Content-Type).
Corpo da Resposta: O corpo da resposta enviado ao cliente, seja texto simples ou JSON, dependendo da rota acessada.
