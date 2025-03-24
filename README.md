# Resumo-Prova Computação em Nuvem I

### O que é computação em nuvem?
> Computação em Nuvem: A computação em nuvem é a entrega de serviços de computação pela Internet. Os serviços de computação incluem infraestrutura de TI comum, como máquinas virtuais, armazenamento, bancos de dados e rede

## Modelo de Responsabilidade Compartilhada: 
> Define quem é responsável pelo quê na nuvem:

- IaaS: A IaaS coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade

- PaaS: A PaaS, sendo um meio termo entre IaaS e SaaS, situa-se no meio desses dois cenários e distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

- SaaS: o SaaS coloca a maior parte da responsabilidade no provedor de nuvem

## Modelos de Nuvem:

- Privada: Uso exclusivo de uma empresa, maior controle e custos.

- Pública: Acessível a qualquer um, mantida por terceiros.

- Híbrida: Mistura das duas, combinando segurança e escalabilidade.

## Modelo Baseado em Consumo:

> OpEx (Despesas Operacionais): Pagamento contínuo pelo uso (ex: assinar serviços de nuvem).

- Nuvem = OpEx: Paga apenas pelo que usar, sem custos fixos de infraestrutura.

> CapEx (Despesas de Capital): Gastos grandes e únicos (ex: construir um datacenter).

## Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem

### Alta Disponibilidade:

> Garante que os serviços estejam sempre ativos, independentemente de falhas ou eventos inesperados. No Azure, isso é garantido pelos SLAs (Contratos de Nível de Serviço).

### Escalabilidade: 
> Ajusta os recursos conforme a demanda, evitando desperdício e garantindo desempenho. Dois tipos:

- Escala Vertical: Aumenta ou reduz capacidade de um recurso (mais CPU/RAM).

- Escala Horizontal: Adiciona ou remove recursos (mais máquinas virtuais/contêineres).

# Questões AZ-900T00-A

> 1. O que é a computação em nuvem?
- Entrega de serviços de computação pela Internet.

> 2. Qual modelo de nuvem usa alguns datacenters focados em fornecer serviços de nuvem para quem quiser e alguns data centers que estão focados em um único cliente?
- Nuvem híbrida.

> 3. De acordo com o modelo de responsabilidade compartilhada, qual tipo de serviço de nuvem coloca a maior responsabilidade sobre o cliente?
- IaaS (infraestrutura como serviço)

> 4. Qual tipo de expansão envolve adicionar ou remover recursos (como máquinas virtuais ou contêineres) para atender à demanda? 
- Dimensionamento horizontal

> 5. O que é caracterizado como a capacidade de um sistema de se recuperar de falhas e continuar funcionando? 
- Confiabilidade
  
> 6. Qual tipo de serviço de nuvem é mais adequado para uma migração lift-and-shift de um datacenter local para uma implantação de nuvem?
- IaaS (infraestrutura como serviço)

> 7. Em que tipo de serviço de nuvem geralmente estaria uma solução de controle de finanças e despesas?
- SaaS (software como serviço)

> 8. Qual ferramenta mantém automaticamente os arquivos atualizados entre um servidor Windows local e um ambiente de nuvem do Azure? 
- Sincronização de Arquivos do Azure 

> 9. Qual opção de redundância de armazenamento fornece o maior grau de durabilidade, com 16 noves de durabilidade?
- Armazenamento com redundância geográfica 

> 10. Qual serviço de Armazenamento do Azure dá suporte à análise de Big Data, bem como à manipulação de tipos de dados de texto e binários? 
- Blobs do Azure 

> 11. Qual recurso do Azure pode ajudar a manter a organização e acompanhar o uso com base nos metadados associados aos recursos?
- Marcações

> 12. Qual é o melhor método para estimar o custo de migração para a nuvem com custos mínimos?
- Use a calculadora Custo Total de Propriedade para estimar os custos esperados.

> 13. Como você pode evitar a criação de recursos fora de conformidade, sem precisar avaliar manualmente cada recurso?

- Azure Policy

> 14. Qual é a melhor maneira de evitar a exclusão inadvertida de um recurso?
- Bloqueios de recursos do Azure

# Questões DP-900T00-A

> 1. Como os dados são organizados em uma tabela relacional? 
- Linhas e colunas

> 2. Qual das alternativas a seguir é um exemplo de dados não estruturados? 
- Arquivos de áudio e vídeo

> 3. O que é um data warehouse? 
- Um banco de dados relacional otimizado para operações de leitura

> 4. Qual das seguintes tarefas é responsabilidade de um administrador de banco de dados? 
- Fazer backup e restaurar bancos de dados

> 5. Qual função é mais provável de usar o Azure Data Factory para definir um pipeline de dados para um processo de ETL? 

- Engenheiro de dados

> 6. Quais serviços você usaria como uma solução SaaS para análise de dados? 

- Microsoft Fabric

> 7. Qual das afirmações a seguir é uma característica dos bancos de dados relacionais? 

- Uma linha em uma tabela representa uma única instância de uma entidade.

> 8. Qual instrução SQL é usada para consultar tabelas e retornar dados? 

- SELECT

> 9. O que é um índice? 

- Uma estrutura que permite que consultas localizem linhas em uma tabela rapidamente

> 10. Qual opção de implantação oferece a melhor compatibilidade ao migrar uma solução local existente do SQL Server? 

- Instância Gerenciada do Azure SQL

> 11. Qual afirmação a seguir sobre o Banco de Dados SQL do Azure é verdadeira? 

- A maioria das tarefas de manutenção de banco de dados é automatizada

> 12. Qual serviço de banco de dados é a opção mais simples para migrar um aplicativo LAMP para o Azure? 

- Banco de Dados do Azure para MySQL

> 13. Quais são os elementos de uma chave do Armazenamento de tabelas do Azure? 

- Chave de partição e chave de linha

> 14. O que você deve fazer com um locatário existente do Microsoft Fabric para dar suporte a um data lake? 

- Nenhuma ação é necessária

> 15. Por que você pode usar o Armazenamento de arquivos do Azure? 

- Para permitir que usuários em sites diferentes compartilhem arquivos. 

> 16. Qual API você deve usar para armazenar e consultar documentos JSON no Azure Cosmos DB?

- Azure Cosmos DB para NoSQL

> 17.Qual API do Azure Cosmos DB deve ser usada para trabalhar com aqueles dados nos quais as entidades e as relações entre elas são representadas em um grafo usando vértices e bordas? 

- Azure Cosmos DB for Apache Gremlin

> 18. Como você pode permitir que usuários distribuídos globalmente trabalhem com uma réplica local própria de um banco de dados do Cosmos DB?

- Habilite gravações de várias regiões e adicione as regiões onde você tem usuários.