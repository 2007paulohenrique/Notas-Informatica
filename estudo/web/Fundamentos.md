# Fundamentos da Web

A Web, ou World Wide Web (WWW), é um sistema de informação onde documentos e recursos são acessíveis pela internet. Ela é composta por uma rede de páginas interconectadas por links (hiperlinks), utilizando protocolos padrão, como HTTP. A Web permite que usuários acessem conteúdos multimídia, serviços e informações, usando navegadores que interpretam documentos em HTML.

## Site

Um site (ou website) é um conjunto de páginas web interligadas e acessíveis na internet, que podem conter texto, imagens, vídeos e outros tipos de mídia. Os sites são hospedados em servidores web e podem ser acessados por meio de navegadores usando URLs.

### Tipos de Sites

**Sites Estáticos**: Apresentam conteúdo fixo, que não muda com frequência. Geralmente, são feitos apenas com HTML e CSS.
**Sites Dinâmicos**: O conteúdo pode mudar com base em interações do usuário ou dados de um banco de dados.
**Blogs**: Um tipo de site que apresenta conteúdo em formato de postagens, geralmente organizadas em ordem cronológica.
**E-commerce**: Sites que permitem a compra e venda de produtos ou serviços online.
**Redes Sociais**: Plataformas que permitem a interação entre usuários.

## Arquitetura Cliente-Servidor

A arquitetura cliente-servidor é um modelo de comunicação onde duas partes se envolvem: o cliente, que é o navegador ou dispositivo do usuário, e o servidor, que armazena e processa os dados. O cliente envia uma requisição ao servidor, pedindo uma página ou recurso, e o servidor responde com o conteúdo solicitado (como uma página web ou dados de uma API). Esse modelo é amplamente utilizado na web para facilitar a distribuição e o acesso à informação.

## Domínios e DNS

Um domínio é o nome legível por humanos que identifica um site na internet (por exemplo, www.exemplo.com). Ele é uma forma mais amigável de acessar um endereço IP, que é a forma numérica de identificar servidores na rede.

O DNS (Domain Name System) é o sistema que traduz nomes de domínio em endereços IP. Quando você digita um domínio em um navegador, o DNS encontra o endereço IP correspondente ao servidor que hospeda o site, permitindo que o navegador se conecte a ele.

Esses quatro conceitos são fundamentais para entender como a web funciona e como as informações são transmitidas e acessadas na internet.

## Protocolo HTTP/HTTPS

O  HTTP (Hypertext Transfer Protocol) é o protocolo de comunicação utilizado pela web para transferir dados entre clientes e servidores. Ele é baseado em requisições e respostas: o cliente faz uma requisição HTTP, e o servidor retorna uma resposta (por exemplo, uma página HTML).

O HTTPS (HTTP Secure) é uma versão segura do HTTP, que usa criptografia SSL/TLS para proteger os dados transferidos entre o cliente e o servidor. Ele garante que as informações enviadas, como senhas ou dados pessoais, estejam seguras contra interceptações, oferecendo uma camada extra de proteção.

### Componentes de uma Requisição HTTP

- **Método HTTP**: Define a ação que o cliente deseja realizar. Os métodos mais comuns são:

**GET**: Solicita a recuperação de dados, como uma página web ou arquivo. É o método mais usado e não altera o estado do servidor.
**POST**: Envia dados ao servidor, como o preenchimento de um formulário. O POST pode alterar dados no servidor.
**PUT**: Atualiza um recurso existente no servidor.
**DELETE**: Remove um recurso do servidor.
**PATCH**: Faz uma atualização parcial de um recurso.

- **URL (Uniform Resource Locator)**: A URL especifica o endereço do recurso que o cliente quer acessar. Exemplo: https://www.exemplo.com/pagina.

- **Cabeçalhos (Headers)**: Contêm informações adicionais sobre a requisição, como o tipo de conteúdo aceito, informações de autenticação, cookies, e o agente de usuário (navegador). Exemplos de cabeçalhos:

**Content-Type**: Informa o tipo de conteúdo que está sendo enviado ou solicitado (ex: text/html, application/json).
**Authorization**: Carrega tokens ou credenciais de autenticação.
**Corpo da Requisição (Body)**: Presente principalmente em requisições como POST ou PUT, onde o cliente envia dados ao servidor, como em um envio de formulário. O corpo da requisição contém esses dados.

## URL

Uma URL (Uniform Resource Locator) é o endereço completo que especifica a localização de um recurso na web. Ela inclui não apenas o domínio, mas também o protocolo, o caminho e, opcionalmente, parâmetros de consulta. Por exemplo, na URL https://www.exemplo.com/pagina?param=valor, temos:

**Protocolo**: https
**Domínio**: www.exemplo.com
**Caminho**: /pagina
**Parâmetros de consulta**: ?param=valor