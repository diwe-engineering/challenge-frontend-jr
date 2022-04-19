

# Desafio Técnico - Pessoa desenvolvedora Front-end Junior
Na DIWE, atualmente trabalhamos preferencialmente com VUEJS e para processamento de estilos utilizamos SASS, mas fique à vontade para escolher a tecnologia que mais se adéque ao seu projeto.
# Objetivo do teste
O candidato(a) deverá desenvolver um crud de contatos (agenda) com autenticação, utilizando VUEJS (SPA com VUEX), SASS e consumindo uma API básica que disponibilizaremos neste documento.

# Design da Aplicação 
A interface do sistema deverá ser desenvolvida as bases do layout (figma), levando em consideração todos os componentes "protótipados" e seu comportamento quanto a responsividade.

Abaixo o link do layout :

**[https://www.figma.com/file/MlDF7BP1BgodRv0BO4EQ4C/Desafio?node-id=2%3A1694](https://www.figma.com/file/MlDF7BP1BgodRv0BO4EQ4C/Desafio?node-id=2%3A1694)**
  
# Requisitos
O sistema deverá conter as seguintes rotas/páginas :
 - Login (aberta), ou seja, não é necessário autenticação para acessá-la;
 - Home (protegida por autenticação JWT), nesta página deverá ser exibido a listagem de contatos;
 - Cadastro de contato (protegida por autenticação JWT), nesta página deverá ser exibido o formulário de cadastro de novo contato;
 - Edição de contato (protegida por autenticação JWT), nesta página deverá ser exibido o formulário de edição de contato;

O sistema também deverá fazer as seguintes validações :
  - O campo de nome completo deverá obrigatório, deverá conter ao menos 2 palavras e não conter caracteres especiais ou numéricos;
  - O campo de email deverá obrigatório e deverá nao ser um email válido (utiliza o próprio validador de input type['email'] do HTML5);
  - O campo de celular deverá ser obrigatário e apenas conter números;


# API para integração





# Entrega do Teste
Ao fim do teste, crie um repositório aberto no github e o compartilhe com os seguintes emails:
-   vinicius.silva@diwe.com.br
-   maicon.passos@diwe.com.br
-   vinicius.bassalobre@diwe.com.br.

Boa sorte e obrigado por participar do nosso processo seletivo!