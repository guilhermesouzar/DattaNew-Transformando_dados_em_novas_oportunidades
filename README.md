## Bem-vindo ao repositório público de apresentação do **DattaNew** – uma plataforma desenvolvida para **concessionárias** que utiliza análise inteligente de dados para aprimorar o relacionamento com os clientes.

> Este repositório não contém o código-fonte do sistema devido a questões de marca e propriedade intelectual.

##  Sobre a solução

O **DattaNew** analisa o banco de dados da concessionária para compreender o comportamento de compra e interação dos clientes,
gerando eventos que permitem aos vendedores se conectar e fortalecer os vínculos com os clientes que já conhecem e confiam na marca.

### Principais Funcionalidades:

- **Insights Valiosos**: Geração de eventos que possibilitam contatos estratégicos com os clientes, onde os vendedores operam e registram a interação com o cliente.
- **Análise Única**: Avaliação personalizada do comportamento de cada cliente, identificando sua posição no funil de vendas e direcionando o cliente ao vendedor que já o atende.
- **Contato Assertivo**: Eliminação de campanhas genéricas, oferecendo ao cliente exatamente o que ele necessita no momento certo, prevendo necessidades e antecipando contatos.
- **Controle de distribuição**: Gestores controlam e visualizam a interatividade de seu time de vendas, podendo direcionar eventos e ativar/desativar a distruibuição para vendedores específicos.
- **Loop de oportunidades**: Realiza a distribuição de eventos de forma equilibrada entre os vendedores da marca, de maneira que todos possam ser beneficiados.
- **Relatórios de desempenho**: Visualização de rankings da marca, interações dos usuários por tipos de evento, tempo de contato, sucesso, perdas, entre outros.

![image](https://github.com/user-attachments/assets/e6b07af7-7989-4d23-9f08-5244a9dee3aa)


## Entendendo a ferramenta

-  **Site Oficial**: [https://www.dattanew.com.br](https://www.dattanew.com.br)

-  ![image](https://github.com/user-attachments/assets/ef17fa90-6767-4f47-9047-3b5b0eed39a6)

-  **Imagens da Plataforma**: interface vendedor

-  ![image](https://github.com/user-attachments/assets/a3219ea2-9eee-402c-930c-6dd0f9fa7a28)


## Arquitetura do Sistema

**Backend:** Web application ASP.NET MVC com separação por camadas (Model, View, Controller); Entity Framework 6 (Code First + Migrations); ASP.NET Identity (autenticação por claims/roles).

**Banco de Dados:** SQL Server com modelo relacional normalizado.

**Frontend:** Bootstrap para layout responsivo; jQuery para manipulação de DOM e interatividade.

**Automatizações:** Quartz.NET para agendamento de tarefas recorrentes (ex: envio de alertas, geração e distribuição de eventos, limpeza de dados).

**ETL:** Pipeline customizado para extração, transformação e carga de dados analíticos.

## Feedbacks
![image](https://github.com/user-attachments/assets/30e5a88b-9a5a-4dcf-83dd-da2af676403e)


---

*Este repositório é destinado apenas para fins de apresentação. O código-fonte permanece confidencial e não está disponível publicamente.*
