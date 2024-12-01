# Link Tracker

## Descrição

O **Link Tracker** é uma extensão de navegador simples que permite aos usuários salvar links personalizados ou salvar o link da aba ativa diretamente no seu navegador. Ele também oferece a opção de excluir todos os links salvos com um simples clique. Os links são armazenados no `localStorage` do navegador para persistência, garantindo que os dados fiquem disponíveis mesmo após o fechamento do navegador.

A principal funcionalidade do **Link Tracker** é fornecer uma maneira prática de acompanhar e acessar links importantes ou frequentemente visitados diretamente da interface da extensão.

## Funcionalidades

- **Salvar Link Personalizado**: O usuário pode inserir um link manualmente e salvá-lo para referência futura.
- **Salvar Link da Aba Ativa**: O usuário pode clicar em um botão para salvar o link da aba ativa no navegador, facilitando o rastreamento rápido de páginas visitadas.
- **Excluir Todos os Links**: O usuário pode limpar todos os links salvos com um único clique.
- **Interface Simples e Responsiva**: O design da extensão é simples, com botões de fácil acesso para todas as funcionalidades principais.

## Como Funciona

### 1. Salvar Link Manualmente
Ao digitar um link no campo de entrada e clicar em **SAVE LINK**, o link será salvo no `localStorage` e exibido na lista abaixo do campo.

### 2. Salvar Link da Aba Ativa
Ao clicar em **SAVE TAB**, a extensão acessa a URL da aba ativa do navegador e a salva no `localStorage`.

### 3. Excluir Todos os Links
Ao clicar em **DELETE ALL**, todos os links armazenados serão apagados tanto da lista visível quanto do `localStorage`.

### 4. Exibição de Links
Todos os links salvos são exibidos em uma lista abaixo do campo de entrada, com cada item funcionando como um link clicável, abrindo o site em uma nova aba.

## Estrutura do Projeto

- **index.html**: Arquivo HTML principal que contém a interface do usuário (campo de entrada, botões e lista de links).
- **style.css**: Arquivo CSS que contém a estilização da interface, incluindo animações e efeitos de hover para os botões.
- **index.js**: Arquivo JavaScript que contém a lógica para salvar links, recuperar dados do `localStorage`, e gerenciar eventos de botão.
- **manifest.json**: Arquivo de manifesto para a extensão, especificando as permissões necessárias (acesso a abas do navegador) e configurando o popup padrão e o ícone da extensão.

## Instruções de Instalação

1. Faça o download ou clone este repositório em seu computador.
2. Abra o navegador e acesse `chrome://extensions/`.
3. Ative o **Modo de desenvolvedor**.
4. Clique em **Carregar sem compactação** e selecione a pasta do projeto.
5. A extensão estará disponível no seu navegador, e você poderá começar a usá-la imediatamente.

## Tecnologias Usadas

- **HTML**: Para estruturação da interface de usuário.
- **CSS**: Para a estilização e efeitos de hover nos botões.
- **JavaScript**: Para a lógica de salvamento e manipulação de dados.
- **Manifest V3**: Para criar a extensão do navegador, incluindo permissões para acessar as abas.

