Simulação de Servidor HTTP com JavaScript no Navegador


Motivação

Entender os conceitos básicos de servidores HTTP e como eles funcionam é fundamental para qualquer desenvolvedor web. Este projeto visa desmistificar o funcionamento interno dos servidores HTTP de uma maneira prática e interativa. Ao simular um servidor HTTP diretamente no navegador usando JavaScript, podemos focar nos conceitos fundamentais de roteamento e manipulação de requisições HTTP, sem a complexidade adicional de um servidor real ou Node.js.

Objetivo

O objetivo deste projeto é duplo:

Criar um servidor HTTP simulado que possa responder a diferentes tipos de solicitações, como texto simples e JSON.
Aprender sobre roteamento – a maneira como diferentes URLs são mapeadas para diferentes respostas no servidor.
Descrição do Experimento
Descrição
Este projeto consiste em um 'Servidor HTTP Simulado' utilizando JavaScript no navegador. O servidor simulado tem duas rotas principais:

Rota /: Responde com a mensagem "Olá Mundo!".
Rota /contato: Responde com um objeto JSON contendo informações de contato.
As respostas das requisições são exibidas no console do navegador. Além disso, utilizamos o Wireshark para capturar e analisar a troca de pacotes, oferecendo uma visão prática do tráfego de rede.


Conexão com a Disciplina de Redes

Roteamento: Entender como diferentes URLs são tratadas pelo servidor.
Protocolo HTTP: Estudar os métodos HTTP e cabeçalhos de resposta.
Análise de Pacotes: Utilizar o Wireshark para analisar o tráfego de rede gerado pelas requisições HTTP.
Pré-requisitos de Uso
Software Necessário
Navegador moderno (Google Chrome, Firefox, etc.)
Wireshark (para captura e análise de pacotes)
Ferramentas de Desenvolvedor do navegador (F12).

Componentes Principais

Função handleRequest: Define as respostas para diferentes URLs.
Função requestHandler: Processa as requisições e define os cabeçalhos e o corpo da resposta.
Simulação do Servidor: Objeto http simula a criação e escuta do servidor.
