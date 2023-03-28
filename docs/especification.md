# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

### Primeiro público-alvo

1. Senhora Inês tem 60 anos, é aposentada, possui renda extra com serviços que faz de costura, é formada em Design de Moda e reside em Santos/SP. Durante a pandemia de covid-19, ficou viúva do seu marido após um casamento de 30 anos por complicações da doença. Na tentativa de manter sua saúde mental e emocional, decidiu adotar a cadelinha Nala para ter uma companhia em casa. Sempre gostou muito de viajar com seu marido e, devido à perda, está procurando opções de destinos em Minas Gerais que sejam *pet friendly* para que Nala seja sua companheira de viagem. Inês desconhece as regras de viagem de avião para embarcar com Nala e tem encontrado dificuldades em localizar hospedagens e estabelecimentos que aceitem a cadelinha.

2. Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

3. Mariana tem 25 anos, trabalha como CLT, é programadora, formada em Sistemas de Informação, e mora com a sua cachorrinha Mel em um apartamento em Belo Horizonte/MG. Mariana resgatou Mel da rua quando ela ainda era filhote. Hoje, ela tem hoje 5 anos, e acabou de terminar o seu adestramento profissional, no qual aprendeu a se socializar corretamente. Por isso, Mariana tem visitado vários locais pet-friendly em Belo Horizonte para "testar" o adestramento. Como Mel tem se comportado muito bem, Mariana decidiu que quer viajar DE CARRO com seu pet para o interior de Minas Gerais, porém não sabe quais precauções tomar nem quais normas deve seguir. Além disso, ela tem tido dificuldade em encontrar hospedagens que aceitam seu pet e em saber os tipos de atividades poderia fazer 
durante a viagem.

4. Leandro Silva tem 45 anos e é marceneiro. Ele trabalha em uma fábrica de móveis planejados e mora no interior de São Paulo com seu cachorro Thor, um vira-lata brincalhão que adotou há 7 anos. Solteiro, é uma pessoa tranquila e dedicada, que gosta de passar seu tempo livre tocando violão ou fazendo caminhadas com Thor. Leandro tem muita vontade de viajar para conhecer algumas cachoeiras em Minas Gerais e não abre mão da companhia de seu melhor amigo nessa aventura. No entanto, ele não possui carteira de motorista e tem muito medo de voar de avião, o que o leva a considerar a opção de viajar de ônibus, Leandro está com dificuldades para acessar informações e regras para viajar de ônibus com seu cachorro. Além disso, ele gostaria de ter acesso ao feedback de outros hóspedes para garantir que fez uma boa escolha de acomodação pet friendly.


### Segundo público-alvo

1.


2. José Alfredo tem 45 anos, reside em Mariana — MG, empresário dono de um estabelecimento onde de dia funciona como um restaurante e a noite como Bar, começou a empreender cedo se considera uma pessoa determinada e focada, tem como meta dar mais visibilidade aos seus empreendimentos, também é uma pessoa ativa na causa animal e defende a teoria do bem-estar animal, onde revela como os animais lidam com as condições em que vivem. Um animal está em boa saúde quando é saudável, calmo, bem nutrido, seguro, capaz de expressar um comportamento inato e não sofre de condições desagradáveis, como dor, pavor e angústia. Baseado em suas motivações pessoais, decidiu transformar seu estabelecimento em uma área comum para que tutores e animais possam desfrutar e se divertir de um local onde todos são aceitos.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Tutor de pet | Ter acesso às regras de viagem de avião com pet | Viajar de avião com meu pet |
|Tutor de pet | Localizar hospedagens *pet friendly* em Minas Gerais | Vijar com meu pet para destinos mineiros |
|Tutor de pet | Conhecer estabelecimentos comerciais privados em Minas Gerais que sejam *pet friendly* | Conseguir passear com meu pet durante a viagem |
|Tutor de pet        | Acessar as normas de viagem de carro com pet | Viajar de carro com meu pet         |
|Tutor de pet        | Localizar hospedagens pet friendly no interior de Minas Gerais  | Para viajar com meu pet para o interior de Minas |
|Tutor de pet        | Localizar atividades para fazer com meu pet | Para me divertir com meu pet durante a viagem |
|Tutor de pet        |Acessar regras de viagens de ônibus com pet | Viajar de ônibus com meu pet |
|Viajante        | Acessar feedback de hospedes | Me basear e escolher uma acomodação pet friendly |


Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA |  |
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA | |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
