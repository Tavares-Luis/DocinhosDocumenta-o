# Principais Recursos e Funcionalidades

**Pedidos:** O sistema permitirá que o cliente realize os pedidos, e o enviará ao proprietário para a fabricação.

**Publicações:** O sistema permitirá que o proprietário e o colaborador realizem postagens a respeito da confeitaria.

**Relatório de Vendas:** O sistema irá emitir relatório de vendas da confeitaria. 

**Frete:** O sistema deve calcular o valor do frete, adicionando ao valor final do pedido.

**Login:** O sistema será acessado a partir do login do cliente e proprietário.

**Cadastro:** O cliente irá fazer um cadastro no sistema, assim, terá seu histórico de pedidos e poderá acompanhar seu pedido atual. 

**Avaliação do cliente:** Ao final do seu pedido, o cliente poderá avaliar o serviço da padaria. 

## Requisitos Funcionais

**RF01 - Registro de Pedidos:** O sistema deve permitir que clientes registrem pedidos de produtos disponíveis no cardápio. O processo de registro de pedido deve incluir a seleção dos produtos, especificação de quantidade, e escolha da forma de pagamento. O sistema deve confirmar o pedido com um número de referência e fornecer um resumo para o cliente;

**RF02 - Cadastro de Cliente:** O sistema deve permitir que novos clientes se cadastrem fornecendo as seguintes informações: nome completo, CPF, telefone, endereço e senha. O sistema deve validar o CPF para garantir que ele esteja em um formato válido e não esteja já registrado. O endereço deve incluir campos para rua, número, complemento, bairro, cidade e CEP;

**RF03 - Avaliação do Cliente:** O sistema deve permitir que clientes avaliem produtos ou serviços com uma nota (de 1 a 5 estrelas) e um comentário opcional. As avaliações devem ser associadas aos produtos específicos e armazenadas no sistema para futuras referências e relatórios;

**RF04 - Relatório de Vendas:** O sistema deve gerar relatórios detalhados de vendas com filtros por data, produto, categoria, e forma de pagamento. O relatório deve incluir informações como quantidade vendida, receita gerada e outros indicadores de desempenho;

**RF05 - Postagens**

O sistema deve permitir que a confeitaria faça postagens de atualizações, promoções ou notícias no site. As postagens devem incluir título, conteúdo, data e hora de publicação, e podem incluir imagens;

**RF06 - Cadastro de Produtos:** O sistema deve permitir que a confeitaria cadastre novos produtos no cardápio, incluindo informações como nome do produto, descrição, preço, categoria e imagens. A interface para cadastro deve permitir a edição e exclusão de produtos existentes;

**RF07 - Formas de Pagamento:** O sistema deve permitir que o cliente escolha entre as formas de pagamento aceitas: pix, dinheiro, cartão de débito e cartão de crédito. Deve haver uma integração segura para processar pagamentos com cartões de crédito e débito;

**RF08 - Manipulação do Cardápio:** O sistema deve permitir a manipulação do cardápio, incluindo adicionar, editar e remover produtos. As alterações devem ser refletidas em tempo real para os clientes;

**RF09 - Área Administrativa:** O sistema deve ter uma área administrativa acessível apenas por funcionários autorizados. Esta área deve permitir gerenciar pedidos, clientes, avaliações, postagens, produtos e gerar relatórios. O acesso deve ser protegido por autenticação e autorização;

**RF10 - Cálculo do Frete:** O sistema deve calcular o valor do frete com base no endereço de entrega e nas políticas de frete definidas (por exemplo, faixa de preço, peso do pedido, distância). O valor do frete deve ser apresentado ao cliente antes da finalização do pedido;

**RF11 - Edição das Informações Pessoais:** O sistema deve permitir que os usuários editem suas informações pessoais, como telefone, endereço e senha. As alterações devem ser salvas de forma segura e o usuário deve receber uma confirmação de que as informações foram atualizadas;

**RF12 - Recuperação de Senha:** O sistema deve permitir que os usuários recuperem suas senhas em caso de esquecimento, por meio de um processo seguro de redefinição de senha que envolva verificação via e-mail ou SMS;

**RF13 - Notificações por E-mail/SMS:** O sistema deve enviar notificações por e-mail ou SMS para confirmar pedidos, atualizações de status, e outras comunicações importantes. As notificações devem ser configuráveis para atender às preferências do usuário;

**RF14 - Segurança de Dados:** O sistema deve implementar medidas de segurança para proteger os dados dos usuários e transações financeiras, incluindo criptografia de dados sensíveis e proteção contra ataques de segurança;

**RF15 - Feedback de Usuário:** O sistema deve permitir que os usuários forneçam feedback sobre sua experiência, o que pode ajudar na melhoria contínua do sistema e na identificação de problemas;

**RF16 - Acessibilidade:** O sistema deve ser projetado para ser acessível a pessoas com deficiências, atendendo aos padrões de acessibilidade web, como a WCAG (Web Content Accessibility Guidelines).

## Requisitos Não Funcionais

**RNF 01 - Funcionamento em Websites:** O sistema deve ser compatível com os principais navegadores web, como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge. Deve ter uma interface responsiva que se adapte a diferentes tamanhos de tela;

**RNF 02 - Compatibilidade com Ambientes Móveis:** O sistema deve ser compatível com sistemas operacionais móveis iOS e Android, oferecendo uma experiência de usuário consistente em dispositivos móveis, seja por meio de um site responsivo ou um aplicativo dedicado;

**RNF 03 - Interface de Login:** O sistema deve ter uma interface de login segura para clientes e funcionários. O login deve ser feito com e-mail/CPF e senha, e o sistema deve implementar políticas de segurança como bloqueio de conta após múltiplas tentativas de login falhadas;

**RNF 04 - Suporte a 100 Usuários Simultâneos:** O sistema deve ser capaz de suportar pelo menos 100 usuários ativos simultaneamente sem degradação significativa de desempenho;

**RNF 05 - Interatividade e Facilidade de Uso:** O sistema deve ser projetado para ser intuitivo e de fácil entendimento, com uma interface gráfica que facilite a navegação e a realização das tarefas comuns. Deve incluir instruções claras e suporte em caso de dúvidas;

**RNF 06 - Funcionamento em Servidores Online:** O sistema deve ser hospedado em servidores online confiáveis e seguros, com alta disponibilidade e backup regular para garantir que os dados não sejam perdidos;

**RNF 07 - Diferença de Letras Maiúsculas e Minúsculas:** O sistema deve distinguir entre letras maiúsculas e minúsculas em campos sensíveis, como senhas e CPF, para garantir a precisão e segurança;

**RNF 08 - Geração de Logs de Atividades:** O sistema deve gerar logs detalhados de atividades do usuário e do sistema, incluindo ações de login, alterações de dados e eventos críticos. Esses logs devem ser armazenados em um banco de dados seguro e acessíveis apenas por administradores autorizados.

