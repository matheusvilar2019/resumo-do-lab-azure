# Resumo dos Labs DIO - Azure


## Localizando Serviços por Categoria 

### Personalizar Conta
* Menu e cores

### Categorias
* IA + Machine Learning
* Análises
* Computação (Area de trabalho virtual, chaves SSH, conjuntos de disponibilidade, contas de laboratório, imagens, maquinas virtuais, discos)
* Contêineres
* Bancos de dados
* DevOps
* Híbrido + multinuvem
* Redes (Bastions, End. IP, Gateway, Links, Zona de DNS, Firewall, Peering)
* Armazenamento (Discos, migração)



## Criando Máquinas Virtuais na Azure
Esta tabela mostra a relação entre diferentes níveis de SLA e o tempo máximo de inatividade permitido em diferentes períodos.

| SLA      | Tempo de inatividade por semana | Tempo de inatividade por mês | Tempo de inatividade por ano |
|----------|---------------------------------|------------------------------|------------------------------|
| 99%      | 1,68h                           | 7,2h                         | 3,65d                        |
| 99,9%    | 10m                             | 43,2m                        | 8,76h                        |
| 99,95%   | 5m                              | 21,6m                        | 4,38h                        |
| 99,99%   | 1,01m                           | 4,32m                        | 52,56m                       |
| 99,999%  | 6s                              | 25,9m                        | 5,26m                        |

### Como usar esta tabela

Essa tabela pode ser usada como referência para avaliar o impacto do SLA em um serviço e definir estratégias para minimizar o tempo de inatividade.



## Configurando uma Instância de Banco de Dados na Azure

* Ao selecionar a imagem da máquina, a responsabilidade passa a ser do seu TI
* Configurar:
  * Discos
  * Rede
  * Gerenciamento
  * Monitoramento
  
### Criando Banco de Dados no Azure:
1. Escolher o nome do BD
2. Selecionar servidor
3. Configurar redundância de armazenamento do backup:
	* Redundância local
	* Redundância de zona
	* Redundância geográfica

### Responsabilidade dos Modelos de Serviço
* Infraestrutura como serviço é o modelo que mais demanda responsabilidade da parte do nosso TI.
* Software como serviço é o que menos demanda responsabilidade.
