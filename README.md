# Press-Ticket

<p align="center">
  <a href="https://www.codefactor.io/repository/github/rtenorioh/press-ticket"><img src="https://www.codefactor.io/repository/github/rtenorioh/press-ticket/badge" alt="CodeFactor" /></a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rtenorioh/Press-Ticket">

  <a href="https://github.com/rtenorioh/Press-Ticket/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rtenorioh/Press-Ticket">
  </a>
      
   <a href="https://github.com/rtenorioh/Press-Ticket/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rtenorioh/Press-Ticket">
  </a>

  <a href="https://github.com/rtenorioh/Press-Ticket/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/rtenorioh/Press-Ticket">
  </a>

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/rtenorioh/Press-Ticket">

  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/rtenorioh/Press-Ticket">

  <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/rtenorioh/Press-Ticket">
</p>

## Manual de Instalação
- [INSTALL.md](https://github.com/rtenorioh/Press-Ticket/blob/main/INSTALL.md)

## Changelog

### 17/03/2022
- [Correções](https://github.com/rtenorioh/Press-Ticket/commit/a6a148f6bf5bde061c314c619bba127ad374d98f).

### 16/03/2022
- [Remover o Header da Swagger](https://github.com/rtenorioh/Press-Ticket/commit/c8290bc9286e9974bf443cb0117104c2fa4c3adc);
- [Limitação de usuários e conexões pelo .env](https://github.com/rtenorioh/Press-Ticket/commit/a40e6c34d2fbb1d71f19216f97f0486c2101757d); e
- [Correções no layout das conexões.](https://github.com/rtenorioh/Press-Ticket/commit/dd1a9bad3875b9e33971d96b24820c92ce4e233f).

### 15/03/2022
- [Add Página de Documentação da API](https://github.com/rtenorioh/Press-Ticket/commit/d9ee5505d90c36f176a75db44153faf1742cc237); e
- [Add Página de Uso da API](https://github.com/rtenorioh/Press-Ticket/commit/5404c22a7aed614af2eca3adf81f461dfcd5bd65).

### 14/03/2022
- Add CodeFactor; e
- Correções.

### 13/03/2022
- [Implementado autorização para o User poder trocar de senha](https://github.com/rtenorioh/Press-Ticket/commit/6fab280989f3ba5e2ada91380ad0db285b90d7ba);
- Removido o caption que era enviado junto com a imagem;
- Ignorar mensagens de grupos [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('CheckMsgIsGroup', 'enabled', '2022-03-02 17:17:00.000000', '2022-03-02 17:17:00.000000');``` ];
- Customização da página de configurações (trocando select por swicher); e
- Ignorando chamadas de vídeo/áudio [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('call', 'disabled', '2022-03-13 18:00:00.000000', '2022-03-13 18:00:00.000000');``` ].

### 12/03/2022

- Sistema base;
- Habilitado para MD;
- Usando MySql ao invés de Docker;
- Implementado função de aparecer ```digitando...``` antes de enviar a lista de setores;
- Implentado a inclusão do nome do usuário na msg de boas vindas;
- Criado uma variável no arquivo de tradução para alterar o nome Press Ticket;
- Na página de contatos o botão importar contatos está disponível apenas para Admin; e
- Conexões foi movido para a área administrativa.