TakeBlip Avaliação - Fluxo e API
Este repositório contém a implementação de um fluxo interativo projetado para interagir com usuários externos, utilizando a plataforma TakeBlip. O fluxo é estruturado com validações de entrada, eventos personalizados para relatórios e integração com uma API externa. A seguir, são descritos os detalhes sobre a arquitetura do fluxo e da API.

Estrutura do Fluxo
O fluxo é composto por uma série de etapas organizadas de forma sequencial, que utilizam diversas funcionalidades para garantir uma interação rica e controlada. As etapas do fluxo são numeradas de acordo com o seu nível hierárquico, permitindo fácil navegação e compreensão.

Validação de Respostas: Cada resposta do usuário é validada por expressões regulares (REGEX), garantindo que entradas inesperadas ou incorretas sejam tratadas adequadamente.

Eventos Personalizados: O fluxo conta com eventos personalizados que geram relatórios detalhados sobre quais tópicos foram mais acessados pelos usuários. Também há um mecanismo para registrar quando o usuário participou ou não nos tópicos relacionados a C#.

Requisições HTTP: A integração com uma API externa é realizada por meio de requisições HTTP, permitindo a coleta e envio de dados em tempo real durante a interação com o usuário.

Fluxo de Interação
A ordem das etapas e os blocos do fluxo são organizados da seguinte forma:

Etapa 0 (0.0, 0.1, etc.): Primeira interação do fluxo, onde o sistema coleta as informações iniciais do usuário.
Etapa 1 (1.0, 1.1, etc.): Continuação do fluxo, onde o sistema valida as respostas e apresenta opções para o usuário.
Etapa 2, 3, ...: Etapas subsequentes que seguem a lógica do fluxo, com a validação de entradas e fornecimento de informações.
Cada etapa possui elementos interativos como:

Quick Replies: Botões rápidos para facilitar a escolha do usuário.
Carrossel: Exibição de uma série de opções ou informações de forma interativa e visual.
Sometext: Mensagens de texto simples para fornecer instruções ou informações adicionais.

API
A API foi desenvolvida com base no conhecimento adquirido durante a criação do fluxo. Seu propósito principal é efetuar a comunicação e coletar os dados necessários para apresentação dos tópicos. 
Fontes de Conhecimento: A construção da API se baseou em conteúdos de vídeos, tutoriais e tópicos disponíveis na internet sobre a construção de API em RestFul.

