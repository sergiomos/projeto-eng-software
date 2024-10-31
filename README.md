## Integrantes
- Guilherme Ferreira de Souza RA: 22.122.061-9
- Sérgio Martins de Oliveira Santos RA: 22.222.021-2
- Taina Cunha Bueno RA: 22.119.025-9

---

![](https://github.com/sergiomos/projeto-eng-software/blob/main/processo%20de%20venda%20faturamento%20e%20nps.png)

## Modelo de Processo de Software

O Scrum será a metodologia adotada para o desenvolvimento do nosso e-commerce. Essa escolha se justifica pela necessidade de flexibilidade para acompanhar as rápidas mudanças do mercado e entregar valor continuamente aos nossos clientes. Além disso, o Scrum promove a colaboração entre o time, a gestão de riscos e a adaptação a novas demandas, garantindo que nosso e-commerce esteja sempre alinhado com as expectativas do mercado.

## Stakeholders do Software 

•  Clientes: Indivíduos que compram as artes.
•  Vendedores: Artistas que cadastram e vendem suas obras no e-commerce.
•  Equipe de Desenvolvimento: Profissionais responsáveis pela construção do software.
•  Equipe de Marketing: Responsável pela promoção do e-commerce.
•  Equipe de Suporte: Responsável por atender aos clientes e vendedores.
•  Gestão: Responsável pela tomada de decisões estratégicas e pela gestão do projeto.

##Técnica de Coleta de Requisitos 
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

## Histórias de Usuário

Histórias de Usuário e Critérios de Aceitação
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

