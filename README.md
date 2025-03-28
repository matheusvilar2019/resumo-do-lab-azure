# Resumo dos Labs DIO - Azure


## Lab 1 - Localizando Serviços por Categoria 

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



## Lab 2 - Criando Máquinas Virtuais no Azure
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



## Lab 3 - Configurando uma Instância de Banco de Dados no Azure

* Ao selecionar a imagem da máquina, a responsabilidade passa a ser do seu TI
* Configurar
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



## Lab 4 - Construíndo Arquiteturas no Azure

### Azure Tour: Ilustra o funcionamento dos datacenters do Azure
* Centro de Operações
* Sala de Servidores
* Área externa
* Centro Circular	

### Criando Grupo de Recursos
* Log de atividades: armazena os registros de criação, alteração e exclusão das configurações do Azure
* __IAM:__ controle de permissão do TI
* __Bloqueios:__ possibilita restringir alterações e exclusões realizadas pelo TI
* __Visualizador de Recursos:__ exibe os recursos (exemplo: rede virtual criada abaixo)
* __Eventos:__ possibilita a criação de eventos automatizados

### Criando Rede Virtual
* __Escolher:__
	* Grupo de Recursos
	* Nome da Rede Virtual
	* Região (Brazil South)
* O objetivo ao criar a VNET é realizar o endereçamento de rede
