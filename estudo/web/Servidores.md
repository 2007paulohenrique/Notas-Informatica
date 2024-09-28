# Servidores Web

Um servidor web é um software ou hardware que armazena, processa e entrega conteúdos e recursos dos sites aos usuários. Quando um navegador (cliente) solicita uma página, o servidor web responde enviando o conteúdo dessa página. 

## Principais Componentes de um Servidor Web 

**Software**: Servidores como Apache, Nginx, Microsoft Internet Information Services (IIS) que gerenciam as requisições HTTP e servem o conteúdo.
**Hardware**: A infraestrutura física que hospeda o software do servidor, incluindo a capacidade de armazenamento, processamento e conectividade à internet.
**Funções**: Os servidores web processam requisições, armazenam arquivos, gerenciam conexões de rede e podem executar scripts e aplicações dinâmicas.

## Web Hosting (Serviços de Hospedagem)

Web Hosting refere-se ao serviço que permite que indivíduos e organizações publiquem seus sites na internet. Quando você contrata um serviço de hospedagem, você está alugando espaço em um servidor para armazenar seus arquivos web. 

### Tipos de Serviços de Hospedagem

**Hospedagem Compartilhada**: Vários sites compartilham os mesmos recursos de um único servidor. É a opção mais econômica, ideal para sites pequenos ou pessoais.
**Hospedagem VPS (Virtual Private Server)**: Um servidor é dividido em várias partes virtuais, oferecendo mais recursos e controle do que a hospedagem compartilhada, sem o custo de um servidor dedicado.
**Hospedagem Dedicada**: Um servidor inteiro é dedicado a um único site ou cliente, oferecendo total controle e recursos. É adequado para sites de alto tráfego ou que precisam de mais personalização.
**Hospedagem em Nuvem**: Os sites são hospedados em uma rede de servidores virtuais que podem se expandir ou contrair conforme necessário, proporcionando escalabilidade e flexibilidade.

## Sessões

Uma sessão é uma maneira de armazenar informações do usuário durante a interação com um site. Ao contrário dos cookies, que podem ser armazenados no cliente, os dados da sessão geralmente são mantidos no servidor. Cada sessão é identificada por um ID exclusivo que é enviado ao cliente como um cookie. As sessões são úteis para armazenar dados temporários e garantir que o usuário permaneça autenticado durante a navegação.

## Cookies

Cookies São pequenos arquivos de texto armazenados no navegador do usuário. Eles são usados para guardar informações sobre a sessão do usuário, como preferências, itens no carrinho de compras e dados de autenticação. Os cookies têm um tempo de expiração e podem ser acessados pelo servidor e pelo cliente.

## WebSockets

Os WebSockets são uma tecnologia que permite a comunicação bidirecional em tempo real entre um cliente (geralmente um navegador) e um servidor. Diferentemente do modelo tradicional de requisição-resposta HTTP, onde o cliente envia uma requisição e aguarda uma resposta, os WebSockets permitem que ambos os lados enviem dados a qualquer momento.

### Características

- **Conexão Persistente**: Uma vez estabelecida, a conexão WebSocket permanece aberta, permitindo comunicação contínua.
- **Baixa Latência**: As mensagens podem ser trocadas rapidamente, tornando os WebSockets ideais para aplicações que exigem interatividade em tempo real, como chats, jogos online e notificações.