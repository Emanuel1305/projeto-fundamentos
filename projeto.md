<img src='/img/1.png' alt='logo da empresa' width='150px' heidth='150px'/>

# *IF Sabores*

# PROJETO DE SOFTWARE

## *Stakeholders*

|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Emanuel Victor Marcelo Fagundes|Implementador / Programador|[emanuelfafa1313@gmail.com](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox?compose=DmwnWrRlQzLpWvjCkNvwSwXktzMNtvqRdQJmsXVggGnsHRvzHQxZsDBgntvFvLFtkBSCxPhjJqHG)|
|Henrique Araujo de Oliveira |Especificador de Requisitos / Analista de Requisitos|[henriquearaujodeoliveira1@gmail.com](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox?compose=DmwnWsCQfzdrmRHJBSWgsBqTnQLsMJnnDJlJMKdNdTMgNdThHWgzgfgGbwpNCxnDKxfCPqmlpNkL)|
|Leonardo Neiva Lopes|Analista de teste|[leokjlps@gmail.com](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox?compose=DmwnWrRrlHzvjrbChnPFHPSjTpWqPjMtqJGLxjVhlQKpqJGLCDHCggjBpXPmTNmJmCdHBzghBKqV)|
|Gabriel Teles de Andrade|Testador de Software|[gabrieltelesdeandradett@gmail.com](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox?compose=DmwnWtDtZMNKMfktWTFfsblVVxdXHZPHDQzTqVRhPvLvQKCpvBPktrZPMDBhnDtlgqhzMdRpWpKQ)|
|Luiz Guilhermy Moretti de Oliveira|Coordenador de projeto / Gerente de Projeto|[luizguilhermy83302@gmail.com](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox?compose=GTvVlcSGMGMrDLFjKlXvvwvQmGjCDpNpqBwhjldQwznfnmQjPqdMNvNBzqFhkJldqBqCbHNLprCZC)|
|Adrielle Morini Freitas|Designer de interface com o usuário|[adriellemorini@gmail.com](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox?compose=CllgCJfrtMfkxqkTMqNpxTSVlpKlbkgVRChBvrjTgKcMwfZbdrgJBWbjQGbkStlsQjXFJJXmnwg)|
# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Fibonacci Management System |
| GERENTE DO PROJETO | Wagner Ferreira |
| PRINCIPAL OBJETIVO | Auxiliar o sistema de ensino através de ferramentas síncronas e assíncronas que serão usadas por funcionários e alunos da instituição de ensino. |
| BENEFÍCIOS ESPERADOS |* Melhor acompanhamento pedagógico;<br/>* Redução da evasão escolar;<br/>* Aumento do número de matrículas;<br/>* Redução da inadimplência escolar;<br/>* Automatização dos processos financeiross|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#if-sabores) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_If Sabores_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

## CONCEPÇÃO DO SISTEMA

Foram usados dois métodos para que pudessem ser obtidos os requisitos do sistema:
* Pesquisas:
  * Uso de pesquisas em sites similares para verificar os requsitos que precisamos implementar em nosso programa.
* Consultas com professores:
  * Wagner da Silva Ferreira Filho, professor do Instituto Federal de Rondônia - Campus Vilhena orientou na concepção do sistema devido sua experiência em auxiliar alunos na área técnica em informática;



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* If: Instituto Ferderal
* IFRO: Intituto Federal de Rondônia

[ [INÍCIO](#if-sabores) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O IF Sabores é um site onde temos varias de receitas, com o objetivo de facilitar sua vida na hora de preparar suas receitas.

 Uma gama de diversidade, tanto salgadas quanto doces, tudo que você procurar de diversas localidades do Brasil e no mundo, bolos, tortas, pães, cookie, sorvete e afins.

 Está afim de fazer um bolo de chocolate de liquidificador? Nós temos o jeito de preparo, todos os ingredientes. Tudo o que precisa é encontrado aqui.

Tudo preparado e testado pela nossa equipe altamente qualificada, para melhores resultados.

Além disso, nosso site também oferece dicas e truques para ajudá-lo a melhorar suas habilidades culinárias e aprimorar suas receitas favoritas. Não hesite em entrar em contato conosco pelo nosso SAC se tiver alguma dúvida ou sugestão. Esperamos que você goste de cozinhar conosco!
O escopo do **produto** pode ser consultado nos [requisitos do software](#requisitos-do-software)

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Venda de produtos;
* Treinamento de instalação, configuração, administração e  utilização do sistema;


## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e visualizar receitas. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das funcionalidades do programa e pela alocação de outros administradores|

## Abrangência e sistemas similares

### Abrangência:

O programa IF Sabores oferece uma variedade de ferramentas para a criação e compartilhamento de receitas deliciosas. Os usuários podem explorar e contribuir com um catálogo de receitas, adaptando-as de acordo com seus gostos e preferências. O programa permite aos usuários criar seus próprios perfis, interagir com outros entusiastas da culinária e participar de desafios culinários emocionantes.

Das ferramentas do programa podemos citar:

* **Catálogo de Receitas:** Explore uma variedade de receitas de diferentes culinárias;

* **Criação de Receitas Personalizadas:** Crie suas próprias receitas e compartilhe com a comunidade;

* **Avaliação de Receitas e Estatísticas:** Avalie as receitas, veja estatísticas de desempenho e descubra as mais populares;

### Sistemas similares:

No cenário nacional encontram-se três sistemas que se assemelham ao nosso, sendo eles:

**TudoGostoso:** é um site brasileiro dedicado à culinária e receitas. Ele oferece uma ampla variedade de receitas, desde pratos principais até sobremesas e bebidas. Os usuários podem pesquisar e compartilhar suas receitas favoritas, além de ler comentários e avaliações de outros usuários sobre as receitas, possui um designer bom porém muito simples e algumas de suas funções são de dificil entendimento para o usuario.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 5Gb de armazenamento em disco
* Para uso do sistema é preciso ter instalado o Java SE versão 8 e o MySql versão 8.0.28.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Os colaboradores da empresa contratante possuem bastante experiência com aplicações desta natureza, os analistas também estão familiarizados com esta área de aplicação comercial, porém o sistema utiliza uma tecnologia nova, com a qual os analistas e programadores não estão familiarizados. No que se refere ao tamanho do sistema, trata-se de um projeto de médio porte, com baixo nível de complexidade, que não será integrado a outros sistemas, limitando-se a atender a demanda da escola no que se refere à EaD, que, atualmente possui 1.000 alunos matriculados. Conclui-se que o projeto possui viabilidade técnica, em virtude dos baixos riscos identificados.

## Viabilidade Econômica

Foi realizada uma análise de custo-benefício, e, mesmo com estimativas conservadoras do retorno sobre o investimento e dos benefícios totais, este projeto é viável economicamente. Após a implantação, espera-se uma melhoria na qualidade dos serviços prestados e aumento da capacidade de vagas da unidade escolar.

## Viabilidade Organizacional

Do ponto de vista organizacional, este projeto apresenta baixo risco. Os diretores e coordenadores da instituição demonstram forte interesse no projeto. Espera-se que os professores e alunos aprovem a implantação do sistema, visto que atualmente a escola não possui uma ferramenta específica para o controle das informações, o que está provocando enormes transtornos para a instituição.


[ [INÍCIO](#if-sabores) ]

# Metodologia Adotada no Desenvolvimento


[ [INÍCIO](#if-sabores) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001|Armazenar Receitas|Banco de dados extenso, para maior atendimento|
|RF-002|Realizar Pesquisas|Um local para o usuário encontrar o item desejado|
|RF-003|Cadastrar Usuários|Etapa de identificação de usuário|
|RF-004|Transmitir Notificações|Mensagem informativa ao ser cadastrado no site sobre um novo item|
|RF-005|Recomendar Itens|Mensagem recomendando um item relacionado às pesquisas recentes|
|RF-006|Receitas via E-mail|Permite ao usuário receber receitas através do e-mail cadastrado|
|RF-007|Filtrar Receitas|Deve ser possível filtrar as receitas por tempo de preparo, dificuldade, número de porções, etc|
|RF-008|Manter uma Organização|As receitas devem ser apresentadas de forma clara e organizada, com lista de ingredientes, modo de preparo e foto|
|RF-009|Salvar Receitas|O usuário deve ter a opção de salvar suas receitas favoritas em uma lista de favoritos|
|RF-010|Compartilhar Receitas|Deve ser possível compartilhar receitas por e-mail ou em redes sociais|
|RF-011|Avaliar Receitas|Os usuários devem ser capazes de avaliar as receitas e deixar comentários avaliativos|
|RF-012|Classificar Receitas|Deve haver um sistema de classificação de receitas, com base nas avaliações dos usuários|
|RF-013|Enviar Suas Receitas|O site deve permitir que os usuários enviem suas próprias receitas|
|RF-014|Imprimir Receitas|Os usuários devem poder imprimir as receitas em um formato fácil de ler|
|RF-015|Oferecer Dicas|O site deve oferecer dicas e truques de culinária para ajudar os usuários a melhorar suas habilidades na cozinha|
|RF-016|Sugerir Receitas|O site deve oferecer sugestões de receitas com base nos ingredientes que o usuário tem em casa|
|RF-017|Criar Albuns|O site deve permitir que os usuários criem coleções de receitas com base em diferentes temas, como receitas de verão, receitas para crianças, receitas para churrasco, entre outros|
|RF-019|Visualizar Receitas|Deve ser possível visualizar receitas em modo de apresentação, com instruções passo a passo e imagens ilustrativas para facilitar o entendimento|
|RF-020|Baixar Receitas|Permite ao usuário a realizar upload de receitas para a visualização off-line|


## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Desempenho|Site leve, minimalista, podendo ser executado em qualquer maquina,tanto IOS quanto Android e Windows |
|RNF-002 |Confiabilidade|Site com produtos e receitas de alta qualidade e confiabilidade, sem chance de erros|


[ [INÍCIO](#if-sabores) ]


# Prototipagem

[Protótipo criado no FIGMA em 2023 por estudantes](https://www.figma.com/file/vmd7jOKgHvRq5uSc5SRJBm/SIte?type=design&node-id=73%3A143&t=rO47lqBjq79RA3KC-1)

![Imagem do Protótipo](/img/home.PNG)
![Imagem do Protótipo](/img/cadastro.PNG)

[ [INÍCIO](#if-sabores) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |

[ [INÍCIO](#if-sabores) ]

# Diagrama de Classes

[ [INÍCIO](#if-sabores) ]

# Diagrama de Sequências

[ [INÍCIO](#if-sabores) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
