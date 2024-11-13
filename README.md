## Integrantes
- Guilherme Ferreira de Souza RA: 22.122.061-9
- Sérgio Martins de Oliveira Santos RA: 22.222.021-2
- Taina Cunha Bueno RA: 22.119.025-9

---

![image](https://github.com/user-attachments/assets/11f29bd8-23c6-4c62-96cd-abbd2b63a6ca)
![image](https://github.com/user-attachments/assets/1fb245a2-00f8-4bb7-b789-fe9c18f2d6d7)
![image](https://github.com/user-attachments/assets/308ee1f9-2951-47e0-9d87-ec9d97ff5540)


## Modelo de Processo de Software

O Scrum será a metodologia adotada para o desenvolvimento do nosso e-commerce. Essa escolha se justifica pela necessidade de flexibilidade para acompanhar as rápidas mudanças do mercado e entregar valor continuamente aos nossos clientes. Além disso, o Scrum promove a colaboração entre o time, a gestão de riscos e a adaptação a novas demandas, garantindo que nosso e-commerce esteja sempre alinhado com as expectativas do mercado.

## Detalhamento dos Processos
![image](https://github.com/user-attachments/assets/d397a895-2613-495e-82a5-e2b631c6e226)
![image](https://github.com/user-attachments/assets/104c2e76-35fa-4657-8549-adabf9d9849f)
![image](https://github.com/user-attachments/assets/63e2bb9d-3369-4c20-9fd7-d563ab7cecd7)
![image](https://github.com/user-attachments/assets/3f9f51ba-3819-4559-bf43-1ad288707e0b)
![image](https://github.com/user-attachments/assets/5c81b416-92f1-4964-b556-df6d1be509ee)
![image](https://github.com/user-attachments/assets/659dd98e-6dfc-4e3f-a58c-fd525cbfbffd)
![image](https://github.com/user-attachments/assets/b52eb792-0788-4540-9c2e-64a8ac74d0d6)
![image](https://github.com/user-attachments/assets/b07ae4d3-af46-495e-9064-597713a1e4bb)
![image](https://github.com/user-attachments/assets/a616a519-ab59-4a57-b40f-00146b0128d0)

![image](https://github.com/user-attachments/assets/fdb43edd-1962-4b20-96d1-a53e3c7e3c0d)



## Stakeholders do Software 

•  Clientes: Indivíduos que compram as artes.

•  Vendedores: Artistas que cadastram e vendem suas obras no e-commerce.

•  Equipe de Desenvolvimento: Profissionais responsáveis pela construção do software.

•  Equipe de Marketing: Responsável pela promoção do e-commerce.

•  Equipe de Suporte: Responsável por atender aos clientes e vendedores.

•  Gestão: Responsável pela tomada de decisões estratégicas e pela gestão do projeto.

## Técnica de Coleta de Requisitos 

Entrevistas: Com os vendedores e clientes para entender suas necessidades e expectativas.

Brainstorm: Para reunir os stakeholders e definir os requisitos de forma colaborativa.

Documentação existente: Análise de e-commerces similares para identificar funcionalidades comuns e melhores práticas.

## Requisitos do Software

### Requisitos Funcionais:

RF01: Cadastrar usuário

RF02: Cadastrar vendedor

RF03: Buscar por produtos

RF04: Cadastrar produto

RF05: Adicionar ao carrinho

RF06: Calcular frete

RF07: Realizar pagamento

RF08: Acompanhar pedido

RF09: Gerar relatórios

### Requisitos Não funcionais:

RNF01: Uso de múltiplos threads

RNF02: O sistema deve ter uma taxa de disponibilidade de 99,99%

RNF03: Uso de criptografia ponta a ponta

RNF04: O usuário deverá ser capaz de realizar tarefas simples em até 2 minutos e tarefas complexas em até 6 minutos

RNF05: O sistema deve ter 20% de recursos a mais do que a capacidade ocupada

### Regras de negócio:

RDN01: Todo cliente deve ter um CPF

RDN02: Todo vendedor deve ter um CPF ou CNPJ

RDN03: Cada vendedor pode gerenciar apenas sua própria página

RDN04: Os vendedores não podem ter acesso ao histórico de pedidos do cliente

RDN05: O vendedor não pode ter acesso às informações de pagamento do cliente

RDN06: O pagamento só é repassado para o vendedor somente quando confirmado o recebimento do produto pelo cliente

RDN07: Clientes têm até 7 dias após o recebimento para solicitar devolução sem justificativa

## Histórias de Usuário e Critérios de Aceitação

História de Usuário 1: Cadastro de Usuário

Como um amante de arte,
Quero me cadastrar na plataforma,
Para que eu possa comprar produtos artísticos.

Critérios de Aceitação:

O sistema deve permitir que o usuário forneça CPF.
O cadastro deve incluir nome, e-mail e senha.
O usuário deve receber um e-mail de confirmação após o cadastro.

História de Usuário 2: Cadastro de Vendedor

Como um artista,
Quero me cadastrar como vendedor,
Para que eu possa vender meus produtos artísticos.

Critérios de Aceitação:

O sistema deve permitir que o vendedor forneça CPF ou CNPJ.
O cadastro deve incluir nome, e-mail, senha e informações da loja.
O vendedor deve receber um e-mail de confirmação após o cadastro.

História de Usuário 3: Busca por Produtos

Como um amante de arte,
Quero buscar por produtos,
Para que eu possa encontrar obras de arte que me interessem.

Critérios de Aceitação:

O sistema deve permitir busca por nome, categoria ou artista.
Os resultados devem ser exibidos de forma clara, com imagem e preço.
História de Usuário 4: Cadastro de Produto
Como um vendedor,
Quero cadastrar meus produtos,
Para que os amantes de arte possam comprá-los.

Critérios de Aceitação:

O sistema deve permitir que o vendedor adicione título, descrição, preço e imagens do produto.
O vendedor deve receber uma confirmação após o cadastro do produto.

História de Usuário 5: Adicionar ao Carrinho

Como um amante de arte,
Quero adicionar produtos ao meu carrinho,
Para que eu possa revisar antes de finalizar a compra.

Critérios de Aceitação:

O sistema deve permitir que o usuário adicione múltiplos produtos ao carrinho.
O usuário deve ver um resumo dos itens no carrinho a qualquer momento.

História de Usuário 6: Calcular Frete

Como um amante de arte,
Quero calcular o frete dos produtos no meu carrinho,
Para que eu saiba o custo total da compra.

Critérios de Aceitação:

O sistema deve calcular o frete com base no endereço informado pelo usuário.
O frete deve ser exibido claramente antes da finalização da compra.

História de Usuário 7: Realizar Pagamento

Como um amante de arte,
Quero realizar o pagamento da minha compra,
Para que eu possa adquirir os produtos desejados.

Critérios de Aceitação:

O sistema deve aceitar múltiplas formas de pagamento (cartão de crédito, boleto, etc.).
O pagamento deve ser processado de forma segura e confirmar a transação ao usuário.

História de Usuário 8: Acompanhar Pedido

Como um amante de arte,
Quero acompanhar o status do meu pedido,
Para que eu saiba quando meus produtos chegarão.

Critérios de Aceitação:

O sistema deve permitir que o usuário veja o status do pedido (processando, enviado, entregue).
O usuário deve receber notificações por e-mail sobre atualizações do pedido.

História de Usuário 9: Gerar Relatórios

Como um vendedor,
Quero gerar relatórios de vendas,
Para que eu possa analisar meu desempenho.

Critérios de Aceitação:

O sistema deve permitir a geração de relatórios com vendas por período, produtos mais vendidos e receita total.
Os relatórios devem estar disponíveis para download em formato PDF.

## Protótipos

![image](https://github.com/user-attachments/assets/1b544ded-61a2-4a04-bb14-6ad0b7b625c2)

![image](https://github.com/user-attachments/assets/ada804c8-6c0b-4433-98c4-869c337dbb4b)


![image](https://github.com/user-attachments/assets/60ede6e5-d585-4ae8-a11a-ec4ef5ec30d9)

![image](https://github.com/user-attachments/assets/7b758771-f199-483a-b64b-280b50b03b10)

![image](https://github.com/user-attachments/assets/deeb875b-b743-46cd-a871-9ba5f764f3dd)

## Diagrama de Casos de Uso

![image](https://github.com/user-attachments/assets/ce7666be-4d1e-49a2-8c91-07c4df862daa)

## Diagrama de Domínio

![image](https://github.com/user-attachments/assets/9b9616ed-24cd-4da3-b921-4b511ddcd598)

## Projeto de Arquitetura
Para o e-commerce focado em arte, a arquitetura do sistema deve suportar uma experiência rica e visual, otimizar o desempenho para grandes volumes de imagens e integrar funcionalidades voltadas para a comercialização de obras de arte. Abaixo segue uma proposta detalhada com a estrutura, componentes e propriedades do sistema.

### Organização Geral do Sistema
O sistema será dividido em camadas para organizar as funcionalidades e facilitar a manutenção. Proponho as seguintes camadas:

- Camada de Apresentação (Frontend): Interface do usuário, responsiva e otimizada para dispositivos móveis.
- Camada de Aplicação (Backend): Gerenciamento de lógica de negócios, processamento de pedidos, e integração com APIs.
- Camada de Persistência de Dados (Banco de Dados): Armazenamento de informações de usuários, produtos, pedidos e transações.
- Camada de Infraestrutura: Rede, servidores, e outros recursos de suporte.

### Estrutura Geral do Sistema
A estrutura inclui três partes principais:

- Frontend (Aplicativo Web e Mobile): Frameworks como React para web e React Native para mobile, com interfaces intuitivas que priorizam o carregamento rápido de imagens.
- Backend (APIs e Lógica de Negócio): Servidores em Node.js com Express.js ou em Python com Django, expostos por meio de APIs REST ou GraphQL.
- Banco de Dados e Armazenamento:
  -   Banco de dados relacional, como PostgreSQL, para manter informações estruturadas.
  -   Banco de dados NoSQL, como MongoDB, para dados mais flexíveis.
  -   Armazenamento em nuvem, como AWS S3, para arquivos de imagem.
 
### Componentes Estruturais Principais
- Interface do Usuário: Acesso a catálogo de artes, filtros por estilo, artista e preço, além de uma galeria para apresentação detalhada.
- Carrinho de Compras: Persistente e conectado a um sistema de pagamentos seguro.
- Sistema de Pagamento: Integração com provedores como Stripe ou PayPal.
- Gerenciamento de Conteúdo (CMS): Um painel para artistas e administradores publicarem obras.
- Motor de Busca e Filtragem: Sistema de pesquisa avançado e filtros de categoria.
- Painel do Artista: Área restrita para que artistas acompanhem vendas e status de pedidos.
- Painel do Administrador: Gerenciamento de catálogo, análises de desempenho e controle de usuários.

### Padrões Reutilizáveis (Famílias de Sistemas)
Para acelerar o desenvolvimento e garantir boas práticas, sugiro o uso dos seguintes padrões:

- Model-View-Controller (MVC) para organização do backend.
- Padrão de Microserviços para escalabilidade e modularidade.
- Design de Interface Responsivo para compatibilidade com diferentes dispositivos.
- Patters de Segurança (ex., proteção contra CSRF e XSS) para garantir a proteção dos dados do usuário.







