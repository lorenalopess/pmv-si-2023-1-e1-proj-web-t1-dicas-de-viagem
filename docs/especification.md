# Especificações do Projeto

## Personas

### Primeiro público-alvo

1. Senhora Inês tem 60 anos, é aposentada, possui renda extra com serviços que faz de costura, é formada em Design de Moda e reside em Santos/SP. Durante a pandemia de covid-19, ficou viúva do seu marido após um casamento de 30 anos por complicações da doença. Na tentativa de manter sua saúde mental e emocional, decidiu adotar a cadelinha Nala para ter uma companhia em casa. Sempre gostou muito de viajar com seu marido e, devido à perda, está procurando opções de destinos em Minas Gerais que sejam *pet friendly* para que Nala seja sua companheira de viagem. Inês desconhece as regras de viagem de avião para embarcar com Nala e tem encontrado dificuldades em localizar hospedagens e estabelecimentos que aceitem a cadelinha.

2. Leandro Silva tem 45 anos e é marceneiro. Ele trabalha em uma fábrica de móveis planejados e mora no interior de São Paulo com seu cachorro Thor, um vira-lata brincalhão que adotou há 7 anos. Solteiro, é uma pessoa tranquila e dedicada, que gosta de passar seu tempo livre tocando violão ou fazendo caminhadas com Thor. Leandro tem muita vontade de viajar para conhecer algumas cachoeiras em Minas Gerais e não abre mão da companhia de seu melhor amigo nessa aventura. No entanto, ele não possui carteira de motorista e tem muito medo de voar de avião, o que o leva a considerar a opção de viajar de ônibus, Leandro está com dificuldades para acessar informações e regras para viajar de ônibus com seu cachorro. Além disso, ele gostaria de ter acesso ao feedback de outros hóspedes para garantir que fez uma boa escolha de acomodação pet friendly.


3.



### Segundo público-alvo


1.


2.


## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Tutor de pet | Ter acesso às regras de viagem de avião com pet | Viajar de avião com meu pet |
|Tutor de pet | Localizar hospedagens *pet friendly* em Minas Gerais | Vijar com meu pet para destinos mineiros |
|Tutor de pet | Conhecer estabelecimentos comerciais privados em Minas Gerais que sejam *pet friendly* | Conseguir passear com meu pet durante a viagem |
|Tutor de pet        |Acessar regras de viagens de ônibus com pet | Viajar de ônibus com meu pet |
|Viajante        | Acessar feedback de hospedes | Me basear e escolher uma acomodação pet friendly |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Disponibilizar área com informações com regras de viagem de avião com pet | ALTA |  
|RF-002| Disponibilizar área com informações com regras de viagem de trem com pet | ALTA |  
|RF-003| Disponibilizar área com informações com regras de viagens de ônibus com pet, como limites de tamanho, tarifas e documentos necessários | ALTA | | 
|RF-004| Disponibilizar área com informações com regras de viagem de ônibus com pet | ALTA |  
|RF-005| Disponibilizar área com informações com regras de viagem de carro com pet | ALTA |  
|RF-006| Disponibilizar área com informações de hospedagens *pet friendly* em Minas Gerais | ALTA |  
|RF-007| Disponibilizar área com informações de estabelecimentos comerciais privados *pet friendly* em Minas Gerais | ALTA | 
|RF-008| Disponibilizar página em que o usuário poderá inserir e consultar depoimentos/feedback sobre as hospedagens *pet friendly* em Minas Gerais | ALTA | 
|RF-009| Disponibilizar funcionalidade que permita pesquisar hospedagens *pet friendly* em Minas Gerais | MÉDIA |  
|RF-010| Disponibilizar funcionalidade que permita pesquisar estabelecimentos comerciais privados *pet friendly* em Minas Gerais | MÉDIA |  
|RF-011| Disponibilizar página em que o usuário poderá inserir depoimentos sobre os estabelecimentos comerciais privados *pet friendly* em Minas Gerais | BAIXA |
|RF-012| Disponibilizar funcionalidade que permita definir perfil de usuário anônimo ou identificado para depoimentos | BAIXA |  
|RF-013|Criar funcionalidade para curtir e comentar os depoimentos	| BAIXA |  


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Interface responsiva adaptável a qualquer interface utilizada - Browser, Smartphone ou Tablet	 | ALTA | 
|RNF-002| Disponibilidade de adaptação da interface pró acessibilidade	| MÉDIA | 
|RNF-003| A página deverá ter disponibilidade em 90% do tempo	 |  BAIXA | 
|RNF-004| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre, não podendo extrapolar a data de 12/07/2023 |
|02| Não pode ser desenvolvido um módulo de BackEnd        |
|03| A abrangência do projeto limita-se à Minas Gerais     |
|04| FrontEnd desenvolvido em HTML, CSS e JavaScript       |
