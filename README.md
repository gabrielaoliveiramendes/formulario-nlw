# Introdução
Este projeto é um sistema de inscrição simples com funcionalidade de check-in, construído utilizando HTML, CSS e JavaScript.

## Funcionalidades
- Formulário de inscrição para captura de nome e e-mail do participante.
- Lista de participantes inscritos, exibindo nome, e-mail, data de inscrição e data de check-in (se realizado).
- Botão de "Confirmar check-in" para participantes ainda não confirmados (utilizando JavaScript).
- Validação de e-mail duplicado na inscrição (evitando cadastro repetido).
- Formatação da data de inscrição utilizando a biblioteca Day.js (exibindo o tempo relativo, como "há 2 horas").

## Tecnologias utilizadas
- HTML: Estrutura básica da página web.
- CSS: Estilização da página.
- JavaScript: Funcionalidades interativas e lógica do sistema.
    - Day.js: Biblioteca para formatação e manipulação de datas (exibição do tempo relativo na inscrição).
    - DOM manipulation: Atualização da lista de participantes de forma dinâmica.
    - Form validation: Validação do e-mail duplicado na inscrição.
    - Event listeners: Captura de eventos como submit do formulário e clique no botão de check-in.
