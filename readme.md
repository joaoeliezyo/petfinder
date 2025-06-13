# PetFinder - Demo de Aplicação Frontend

## Visão Geral

Este projeto é uma demonstração de frontend para o **PetFinder**, uma plataforma fictícia para ajudar a encontrar animais de estimação perdidos. A aplicação é construída como uma _Single Page Application (SPA)_, utilizando tecnologias web modernas para criar uma experiência de usuário interativa e responsiva. O backend é simulado através do `localStorage` do navegador para persistência de dados.

---

## Tecnologias Utilizadas

- **HTML5:** Para a estrutura semântica da aplicação.
- **Tailwind CSS:** Framework CSS utility-first para um design rápido e moderno, utilizado via CDN.
- **JavaScript (ES6+):** Linguagem principal para toda a lógica da aplicação, incluindo manipulação do DOM, interatividade do mapa e gerenciamento de estado.
- **Leaflet.js:** Biblioteca de mapas interativos de código aberto para exibir a localização dos pets.
- **Leaflet.markercluster:** Plugin para agrupar marcadores no mapa e melhorar a visualização.

---

## Funcionalidades Implementadas

- **Mapa Interativo:** Exibe pets perdidos com marcadores personalizados (🐕/🐈) e clusters para áreas com muitos registros.
- **Filtros Avançados:** Filtre pets por tipo (cão/gato), data de desaparecimento e busque por texto (nome/descrição).
- **Geolocalização:** Botão "Perto de mim" para centralizar o mapa na localização atual do usuário.
- **Cadastro de Pets:** Usuários logados podem cadastrar um pet perdido através de um formulário modal, incluindo upload de foto e seleção de localização no mapa.
- **Sistema de Autenticação:** Simulação completa de cadastro, login e logout de usuários. Os dados são salvos no `localStorage`.
- **Painel do Usuário:** Após o login, o cabeçalho exibe o nome do usuário e um menu com acesso à seção "Meus Pets" e a opção de "Sair".
- **Seção "Meus Pets":** Lista privada de pets cadastrados pelo usuário logado.
- **Chat Simulado:** Ao clicar em "Tenho Informações", um modal de chat é aberto com respostas automáticas para simular a comunicação.
- **Notificações Toast:** Sistema de notificação visual (toast) que aparece quando um novo pet é cadastrado.
- **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, desde dispositivos móveis até desktops.
- **Seções Informativas:** Inclui seções como "Como Funciona", estatísticas animadas e uma página "Sobre".

---

## Como Executar o Projeto

1.  **Baixe os arquivos:** Certifique-se de ter `index.html`, `style.css` e, opcionalmente, o `README.md`.
2.  **Abra o `index.html`:** Não é necessário um servidor web. Você pode abrir o arquivo `index.html` diretamente em um navegador moderno (como Chrome, Firefox, ou Edge).

A aplicação utilizará o `localStorage` do seu navegador para salvar usuários e pets cadastrados, então os dados persistirão mesmo que você feche a aba ou recarregue a página. Para limpar os dados, limpe o cache e os dados de site do seu navegador.
