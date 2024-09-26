## Integrantes
- Guilherme Ferreira de Souza RA: 22.122.061-9
- Sérgio Martins de Oliveira Santos RA: 22.222.021-2
- Taina Cunha Bueno RA: 22.119.025-9

---

![](https://github.com/sergiomos/projeto-eng-software/blob/main/processo%20de%20venda%20faturamento%20e%20nps.png)


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
