# Segurança Web

A segurança web é essencial para proteger aplicações e dados contra ataques maliciosos.

## Tipos Comuns de Vulnerabilidades

- **XSS (Cross-Site Scripting)**: É uma vulnerabilidade que permite que atacantes injetem scripts maliciosos em páginas web. Quando um usuário visita uma página comprometida, o script pode roubar cookies, dados de sessão ou realizar ações em nome do usuário sem o seu consentimento.

- **Prevenção de XSS**

    - **Escapar entradas de usuário**: Sempre escape caracteres especiais (processo de transformar caracteres que têm significados especiais em strings de texto) nas entradas do usuário antes de exibi-las em HTML.
    - **Usar Content Security Policy (CSP)**: Implemente CSP para limitar as fontes de scripts que podem ser executados em sua página.
    - **Validar e sanitizar entradas**: Verifique e limpe as entradas do usuário para garantir que não contenham scripts maliciosos.

- **CSRF (Cross-Site Request Forgery)**: É um ataque que força um usuário autenticado a executar ações indesejadas em uma aplicação web. Se um usuário estiver logado e visitar um site malicioso, esse site pode enviar requisições para a aplicação web legítima, agindo como o usuário.

- **Prevenção de CSRF**

    - **Tokens de verificação**: Utilize tokens CSRF únicos e aleatórios em formulários e requisições para verificar a autenticidade das requisições.
    - **Métodos HTTP apropriados**: Limite ações sensíveis a métodos HTTP como POST, que exigem mais que uma simples requisição GET.
    - **Verificação de referer**: Verifique o cabeçalho referer para garantir que a requisição está vindo de uma origem legítima.

- **SQL Injection**: É uma técnica de ataque onde um invasor insere código SQL malicioso em campos de entrada de uma aplicação. Isso pode permitir o acesso não autorizado a dados do banco de dados, permitindo que o invasor visualize, modifique ou exclua dados.

- **Prevenção de SQL Injection**

    - **Prepared Statements**: Use consultas parametrizadas (prepared statements) em vez de concatenar strings SQL com entradas do usuário.
    - **Validação de entradas**: Valide e sanitize todas as entradas de dados, limitando o que pode ser inserido em campos de entrada.
    - **Privilégios limitados**: Conceda o menor nível de privilégios necessário ao banco de dados, reduzindo o impacto de uma possível injeção.

## HTTPS

HTTPS (Hypertext Transfer Protocol Secure) é uma extensão do HTTP que utiliza criptografia para proteger a comunicação entre o navegador do usuário e o servidor web.

- **Criptografia**: HTTPS usa o protocolo TLS (Transport Layer Security) para criptografar dados, garantindo que informações sensíveis (como senhas e dados de cartão de crédito) não possam ser interceptadas por terceiros.

- **Autenticação**: O HTTPS também autentica o servidor, assegurando que os usuários estejam se conectando ao site correto, não a uma versão falsa ou maliciosa.

- **Importância**: Usar HTTPS é fundamental para proteger a privacidade dos usuários, aumentar a confiança e melhorar a classificação nos motores de busca.