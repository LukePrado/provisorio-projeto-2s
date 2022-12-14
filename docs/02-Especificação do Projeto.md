# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO...| QUERO/PRECISO ...|PARA ... |
|--------------------|------------------------------------|----------------------------------------|
|Zoe  | Encontrar os melhores cursos de programação para iniciantes| Poder conhecer a área e encontrar materiais mais bem avaliados|
|Sol | Achar cursos de Scrum com certificações| Para evoluir profissionalmente |
|Gabriel | Achar cursos back-end de carga horária curta | Se tornar um profissional mais completo |
|Caio | Achar cursos de desenvolvimento front-end com profissionais gabaritados e cursos bem avaliados. | Capacitar-se no mundo do desenvolvimento front-end através de cursos de React gratuitos|
|Ravi | Conhecer mais sobre o setor financeiro através de um material confiável. | Aprender sobre uma nova área e verificar qual melhor se encaixa na sua metodologia de estudo |
|Letícia | Encontrar cursos de inglês básicos para o ENEM | Buscar os conteúdos mais enxutos sobre Inglês modelo ENEM |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A solução deve oferecer um campo de para cadastramento do usuario como dados básicos como: Nome, sexo, formação academica, e-mail. | ALTA | 
|RF-002| A solução deve apresentar, obrigatoriamente, no mínimo um texto com 500 caracteres.  | MÉDIA  |
|RF-003| A solução deve possibilitar um usuário, cadastrado ou não, possa realizar pesquisa de material para estudo.  | ALTA | 
|RF-004| A solução deve possibilitar que um usuário cadastrado possa avaliar o material pesquisado   | ALTA |
|RF-005|A site deve oferecer uma funcionalidade de filtro/pesquisa do material de forma especifica.  | ALTA | 
|RF-006| A solução deve possibilitar que um usuário cadastrado possa incluir uma referência de material para consulta com os seguintes campos: Título do, área do conhecimento, resumo, link de acesso. | ALTA |
|RF-007| A solução deve possibilitar que uma referência de material seja avaliado como confiável ou não confiável pelos administradores | ALTA|


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
|01| A primeira etapa do projeto, referente a Concepção e proposta de solução, deverá ser entregue dia 11/09/2022 |
|02| A segunda etapa do projeto, referente ao Projeto da solução, deverá ser entregue dia 02/10/2022  |
|03| A terceira etapa do projeto, referente a primeira fase do Desenvolvimento da solução, deverá ser entregue dia 30/10/2022  |
|04| A quarta etapa do projeto, referente a segunda fase do Desenvolvimento da solução, deverá ser entregue dia 27/11/2022  |
|05| Os relatórios das avaliações e entrega da solução deverá ser até o dia 11/12/2022  |

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
