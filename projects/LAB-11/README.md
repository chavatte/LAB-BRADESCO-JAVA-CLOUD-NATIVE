# LAB-11: Microsoft Azure - Configurando uma Instância de Banco de Dados

## Guia detalhado para criação de instâncias de banco de dados no Azure

<img align="center" src="./assets/logo.png" />

### Descrição

Este projeto detalha o processo de criação de instâncias de banco de dados no Microsoft Azure, um passo crucial para o armazenamento e gerenciamento de dados em aplicações e serviços em nuvem. Abordaremos desde a configuração inicial do ambiente até a implantação e gerenciamento da instância de banco de dados, fornecendo um guia passo a passo para profissionais de TI e entusiastas da computação em nuvem.

### Conceitos Fundamentais

Antes de iniciar o processo de criação, é crucial compreender alguns conceitos chave do Azure:

* **Tipos de Banco de Dados:** O Azure oferece diversas opções, como SQL Database, MySQL, PostgreSQL e Cosmos DB, cada uma com suas características e casos de uso específicos.
* **Camadas de Serviço:** As camadas de serviço (Basic, Standard, Premium) definem o desempenho e os recursos disponíveis para a instância de banco de dados.
* **Grupos de Recursos:** Contêineres lógicos que agrupam recursos do Azure, facilitando o gerenciamento e a organização.
* **Servidores Lógicos:** Infraestruturas que hospedam e gerenciam as instâncias de banco de dados.

### Acessando o Portal do Azure

O primeiro passo é acessar o portal do Azure em [https://portal.azure.com](https://portal.azure.com) e fazer login com suas credenciais. Para novos usuários, é possível criar uma conta gratuita para explorar os serviços básicos do Azure.

### Criando uma Instância de Banco de Dados

O processo de criação de uma instância de banco de dados no Azure envolve os seguintes passos:

#### Acessar a Seção de Bancos de Dados:

* No painel de navegação à esquerda, clique em "Todos os Serviços" e procure pelo tipo de banco de dados desejado (ex: "SQL Databases").
* Selecione a opção desejada em "Bancos de Dados" e clique em "Adicionar" ou "Criar".

#### Configurações Básicas:

* Selecione a assinatura e o grupo de recursos desejados.
* Insira o nome do banco de dados e escolha a região onde ele será hospedado.
* Selecione ou crie um novo servidor lógico, fornecendo um nome de servidor, um nome de administrador e uma senha.
* Selecione a versão do banco de dados desejada.

#### Tamanho e Desempenho:

* Escolha a camada de serviço com base nos requisitos de desempenho e custo da sua aplicação.
* Ajuste o tamanho do computador (DTUs ou vCores) e a capacidade de armazenamento.

#### Configurações de Rede:

* Escolha a rede virtual e sub-rede desejadas.
* Configure as regras do Firewall para permitir o acesso ao banco de dados de endereços IP específicos.

#### Configurações de Segurança:

* Configure a autenticação do banco de dados (SQL ou Azure AD).
* Configure as opções de backup e restauração.

#### Revisão e Criação:

* Revise todas as configurações e clique em "Revisar + criar" e, em seguida, em "Criar".

### Gerenciando a Instância de Banco de Dados

Após a criação, é possível acessar a instância de banco de dados usando ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio. Recomenda-se monitorar o desempenho da instância e ajustar as configurações conforme necessário.

### Considerações sobre disponibilidade e redundância

Para garantir alta disponibilidade, considere as seguintes práticas:

* Utilizar zonas de disponibilidade para proteger contra falhas de datacenter.
* Configurar backups regulares e a redundancia de armazenamento desejada para a aplicação.

### Conclusão

A criação de instâncias de banco de dados no Azure é um processo flexível e personalizável, que permite o armazenamento e gerenciamento de dados em nuvem de forma eficiente. Ao seguir as melhores práticas e considerar os conceitos de disponibilidade e redundância, é possível garantir o desempenho e a confiabilidade das aplicações em ambiente Azure.

### Recursos Adicionais

* Portal do Microsoft Azure: [https://azure.microsoft.com/](https://azure.microsoft.com/)
* Documentação do Azure: [https://learn.microsoft.com/pt-br/azure/](https://learn.microsoft.com/pt-br/azure/)