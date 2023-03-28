 l# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1. Senhora Inês tem 60 anos, é aposentada, possui renda extra com serviços que faz de costura, é formada em Design de Moda e reside em Santos/SP. Durante a pandemia de covid-19, ficou viúva do seu marido após um casamento de 30 anos por complicações da doença. Na tentativa de manter sua saúde mental e emocional, decidiu adotar a cadelinha Nala para ter uma companhia em casa. Sempre gostou muito de viajar com seu marido e, devido à perda, está procurando opções de destinos em Minas Gerais que sejam pet friendly para que Nala seja sua companheira de viagem. Inês desconhece as regras de viagem de avião para embarcar com Nala e tem encontrado dificuldades em localizar hospedagens e estabelecimentos que aceitem a cadelinha.
2. Mariana tem 25 anos, trabalha como CLT, é programadora, formada em Sistemas de Informação, e mora com a sua cachorrinha Mel em um apartamento em Belo Horizonte/MG. Mariana resgatou Mel da rua quando ela ainda era filhote. Hoje, ela tem hoje 5 anos, e acabou de terminar o seu adestramento profissional, no qual aprendeu a se socializar corretamente. Por isso, Mariana tem visitado vários locais pet-friendly em Belo Horizonte para "testar" o adestramento. Como Mel tem se comportado muito bem, Mariana decidiu que quer viajar DE CARRO com seu pet para o interior de Minas Gerais, porém não sabe quais precauções tomar nem quais normas deve seguir. Além disso, ela tem tido dificuldade em encontrar hospedagens que aceitam seu pet e em saber os tipos de atividades poderia fazer durante a viagem. 

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Tutor de pet        | Acessar as normas de viagem de carro com pet | Viajar de carro com meu pet         |
|Tutor de pet        | Localizar hospedagens pet friendly no interior de Minas Gerais  | Para viajar com meu pet para o interior de Minas |
|Tutor de pet        | Localizar atividades para fazer com meu pet | Para me divertir com meu pet durante a viagem |

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
