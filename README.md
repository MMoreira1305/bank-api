# Requisitos Funcionais:
#1 - Autenticação e Autorização:
- Os usuários devem poder se registrar, fazer login e sair do sistema.
- Apenas usuários autenticados devem ter acesso às funcionalidades da API.
- Deve haver diferentes níveis de acesso para usuários normais e administradores.

#2 - Gestão de Contas:
- Os usuários devem poder criar contas bancárias.
- Eles devem ser capazes de ver o saldo da conta e o histórico de transações.

#3 - Transações Financeiras:
- Os usuários devem poder realizar transações financeiras, como PIX, TED e transferências bancárias entre contas.
- As transações devem ser seguras e refletir corretamente no saldo das contas envolvidas.

#4 - Notificações:
- Os usuários devem receber notificações sobre transações bem-sucedidas, falhas de transações e outras atividades importantes em suas contas.

#5 - Segurança:
- Todas as transações devem ser protegidas por medidas de segurança adequadas, como autenticação de dois fatores, se necessário.
- As senhas dos usuários devem ser armazenadas de forma segura, utilizando técnicas de hash e salt.

Passo a Passo:
1. Configuração do Ambiente de Desenvolvimento:
Instalar o Java JDK.
Configurar o ambiente de desenvolvimento Spring Boot.
Configurar e instalar o MySQL Server.
Configurar o ambiente de desenvolvimento Angular, se necessário.
2. Estrutura do Projeto:
Criar um novo projeto Spring Boot.
Definir a estrutura de pacotes.
Configurar a conexão com o banco de dados MySQL.
3. Implementação da Autenticação e Autorização:
Implementar a autenticação com Spring Security.
Criar serviços para registro de usuários e login.
Definir roles (níveis de acesso) para usuários.
4. Desenvolvimento das Funcionalidades da Conta Bancária:
Implementar serviços para criação de contas bancárias.
Desenvolver endpoints para visualização de saldo e histórico de transações.
5. Implementação das Transações Financeiras:
Desenvolver serviços para realização de transações financeiras, como PIX, TED e transferências bancárias.
Garantir que as transações sejam atomicamente seguras e atualizem corretamente os saldos das contas envolvidas.
6. Implementação das Notificações:
Criar um sistema de notificações para informar os usuários sobre atividades importantes em suas contas.
Configurar notificações por e-mail, SMS ou outros meios, conforme necessário.
7. Refatoração e Testes:
Refatorar o código para garantir qualidade e legibilidade.
Escrever testes automatizados para as funcionalidades principais.
Testar a integração entre a API e o frontend Angular.
8. Implantação e Monitoramento:
Implantação da API em um ambiente de produção.
Configuração de monitoramento para acompanhar o desempenho e a disponibilidade do sistema.
Realizar testes de carga para garantir a escalabilidade do sistema.
