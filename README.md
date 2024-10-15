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

## Aprendizados
Ao longo do desenvolvimento deste projeto, foram aprofundados os conhecimentos em:  
#### HTML:  
- Tabelas: Organização dos dados dos participantes em uma table.  
- Forms: Criação de formulários para coleta de dados do usuário.  
#### CSS:  
- Seletores: "**>`" seleciona elementos filhos diretos; "," combina múltiplos seletores.  
- :hover: Aplica estilos quando é passado o mouse por cima do elemento.  
- Animações: Criação de animações personalizadas utilizando @keyframes.  
#### JavaScript:  
- Variáveis: Armazenamento de dados como nome, e-mail, data e outros.  
- querySelector: Seleção de elementos HTML para manipulação.  
- innerHTML: Atualização do conteúdo HTML de um elemento.  
- return: Encerramento de uma função e retorno de um valor.  
- Objetos: Representação de entidades como um participante, com propriedades como nome e e-mail.  
- Arrays: Coleção de elementos, como a lista de participantes.  
- Listas: Criação de listas não ordenadas ou ordenadas para exibir informações.  
- new Date: Criação de objetos de data para registrar a data de inscrição.  
- Laços de repetição: Iteração sobre elementos de um array, como para adicionar cada participante à lista.  
- Day.js: Biblioteca para formatação e manipulação de datas, facilitando a exibição do tempo relativo.  
- CDN: Utilização de um Content Delivery Network para incluir a biblioteca Day.js no projeto.  
- onsubmit: Escuta o evento de envio de um formulário.  
- .target: Acessa o elemento que disparou um evento.  
