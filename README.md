#Sistema de Gestão de Ordens de Serviço – Oficina Mecânica#
Descrição do projeto:
Este projeto consiste na modelagem conceitual de um banco de dados para um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica.
O modelo foi desenvolvido com o objetivo de representar, de forma estruturada, os principais elementos envolvidos no processo de atendimento ao cliente, diagnóstico, execução e finalização de serviços automotivos.
Contexto:
Clientes levam seus veículos até a oficina para realização de consertos ou revisões periódicas. A partir disso, é gerada uma ordem de serviço (OS), contendo todas as informações necessárias para execução do trabalho.
Cada veículo é associado a uma equipe de mecânicos responsável por avaliar, planejar e executar os serviços. A ordem de serviço reúne dados como descrição do problema, serviços a serem realizados, possíveis peças utilizadas, valores, datas e status do atendimento.

Regras de Negócio:

Um cliente pode possuir um ou mais veículos.
Um veículo pode gerar uma ou mais ordens de serviço.
Cada ordem de serviço está associada a um único cliente.
Cada ordem de serviço é atribuída a uma equipe de mecânicos.
Uma equipe pode ser responsável por várias ordens de serviço.
Os mecânicos pertencem a uma equipe.
Uma ordem de serviço pode conter um ou mais serviços.
Um serviço pode estar presente em várias ordens de serviço
Nem toda ordem de serviço possui itens (peças).
Itens de OS existem apenas quando há necessidade de utilização de peças.
O valor total da OS é composto pelos serviços realizados e pelas peças utilizadas.
O cliente deve autorizar a execução dos serviços.
A equipe designada é responsável pela execução dos serviços.

Entidades do Modelo:
Clientes
Veículos
Mecânico
Equipe de Mecânicos
Ordem de Serviço
Item OS
Serviço

Observações:
A entidade Item OS é opcional e depende da existência de uma Ordem de Serviço, sendo utilizada apenas quando há necessidade de registrar peças utilizadas no serviço.
A relação entre Ordem de Serviço e Serviço é do tipo n:m
Os valores monetários foram modelados utilizando o tipo DECIMAL.

Objetivo:
Desenvolver um modelo conceitual fiel ao cenário real de uma oficina mecânica, garantindo organização, consistência dos dados e clareza nas relações entre as entidades.

Sistema de Gestão de Ordens de Serviço – Oficina Mecânica
Descrição do projeto:
Este projeto consiste na modelagem conceitual de um banco de dados para um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica.
O modelo foi desenvolvido com o objetivo de representar, de forma estruturada, os principais elementos envolvidos no processo de atendimento ao cliente, diagnóstico, execução e finalização de serviços automotivos.
Contexto:
Clientes levam seus veículos até a oficina para realização de consertos ou revisões periódicas. A partir disso, é gerada uma ordem de serviço (OS), contendo todas as informações necessárias para execução do trabalho.
Cada veículo é associado a uma equipe de mecânicos responsável por avaliar, planejar e executar os serviços. A ordem de serviço reúne dados como descrição do problema, serviços a serem realizados, possíveis peças utilizadas, valores, datas e status do atendimento.
Regras de negócio:
Um cliente pode possuir um ou mais veículos.
Um veículo pode gerar uma ou mais ordens de serviço.
Cada ordem de serviço está associada a um único cliente.
Cada ordem de serviço é atribuída a uma equipe de mecânicos.
Uma equipe pode ser responsável por várias ordens de serviço.
Os mecânicos pertencem a uma equipe.
Uma ordem de serviço pode conter um ou mais serviços.
Um serviço pode estar presente em várias ordens de serviço.
Nem toda ordem de serviço possui itens (peças).
Itens de OS existem apenas quando há necessidade de utilização de peças.
O valor total da OS é composto pelos serviços realizados e pelas peças utilizadas.
O cliente deve autorizar a execução dos serviços.
A equipe designada é responsável pela execução dos serviços.
Entidades do modelo:
Clientes
Veículos
Mecânico
Equipe de mecânicos
Ordem de serviço
Item OS
Serviço
Observações:
A entidade Item OS é opcional e depende da existência de uma ordem de serviço, sendo utilizada apenas quando há necessidade de registrar peças utilizadas no serviço.
A relação entre ordem de serviço e serviço é do tipo N:M.
Os valores monetários foram modelados utilizando o tipo DECIMAL.
Objetivo:
Desenvolver um modelo conceitual fiel ao cenário real de uma oficina mecânica, garantindo organização, consistência dos dados e clareza nas relações entre as entidades.

