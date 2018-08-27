---
layout: post
title:  "Documento de Visão"
date:   2018-08-24 13:50:39
categories: docs
---

## Histórico de Revisão

| Data       | Responsável          | Versão   | Mudança realizada                                 |  
| ---------- | -------------------- |:--------:| ------------------------------------------------- |
|**15/03/17**|  Iasmin Mendes     | 0.1  | Criação do Documento de Visão                         |   

-----

[1. Introdução](#1-introdução)   
[2. Posicionamento](#2-posicionamento)   
[3. Descrições dos Envolvidos e dos Usuários](#3-descrições-dos-envolvidos-e-dos-usuários)   
[4. Visão Geral do Produto](#4-visão-geral-do-produto)   
[5. Requisitos Funcionais](#5-requisitos-funcionais)   
[6. Restrições](#6-restrições)   
[7. Requisitos Não Funcionais](#7-requisitos-não-funcionais)

-----
## 1. Introdução

Este documento visa o entendimento geral do projeto ao definir as necessidades para o desenvolvimento do Aplicativo RecomendaFGA, o qual refere-se a um sistema para indicação de locais que facilitem a vida acadêmica próximo a Faculdade do Gama - FGA, campus da Universidade de Brasília - UnB. As informações contidas neste documento são apresentadas com alto nível de abstração, de forma que o entendimento sobre o sistema seja claro para todos os envolvidos na produção. Além dos atributos necessários para a compreensão do software, também será descrito o sistema de forma contextual, destacando o seu posicionamento frente ao problema, os envolvidos e seu determinado escopo. Para tal, segue-se uma organização em tópicos informativos relacionados às necessidade do projeto.

### 1.1 Finalidade

O presente documento tem como finalidade manter uma visão comum para os envolvidos no projeto do aplicativo RecomendaFGA ao expor as ideias necessárias para seu desenvolvimento.

### 1.2 Escopo

São tratados nesse documento os pontos necessários para a elaboração da aplicação, desde a concepção do projeto até a implantação, de forma que possam ser entendidos sem o total conhecimento dos termos técnicos utilizados por desenvolvedores.

### 1.3 Definições, Acrônimos e Abreviações

Abaixo serão apresentados alguns conceitos de documentação de software desejáveis para o melhor entendimento deste documento e termos aplicados ao contexto da universidade:

1. UnB: Universidade De Brasília.
2. FGA: Faculdade do Gama - Campus da Universidade de Brasília localizado no Gama.
3. RecomendaFGA: Aplicativo mobile com intuito de compartilhar recomendações de locais próximos a FGA que facilite a vida acadêmica.
4. UML (*Unified Modeling Language*): Linguagem de modelagem que define representações de um sistema de forma padronizada com o objetivo de facilitar a compreensão.
5. RUP (*Rational Unified Process*): É um modelo de processo unificado de Engenharia de Software derivado da UML criado pela Rational Software Corporation e adquirido pela IBM em 2003. Possui elementos de modelos genéricos para apoiar o desenvolvimento de softwares incentivando a interação e exemplificando boas práticas de projeto e especificação.
6. SIGS: Sistema Inteligente de Gestão de Salas.
7. EPS: Disciplina de Engenharia de Produto de Software.
8. MDS: Disciplina de Métodos de Desenvolvimento de Software.


### 1.4 Referências

SOMMERVILLE, Ian. **Engenharia de Software.** São Paulo: Pearson Prentice Hall. 9ª edição. 2011.

GUEDES, Gilleanes T. A. **UML: uma abordagem prática.** Novatec Editora, 2008.

### 1.5 Visão Geral

Elaborado de acordo com a metodologia RUP, o *Rational Unified Process*, este documento define o problema a ser resolvido. Descrevendo os requisitos do software, os envolvidos e usuários, a demografia dos mercados, a visão geral do produto e seus recursos.

## 2. Posicionamento

### 2.1 Oportunidade de Negócios
A Faculdade do Gama - FGA é um dos campus mais novos da Universidade de Brasília e recebe alunos de vários lugares do Brasil. A faculdade ainda está em desenvolvimento, portanto faltam serviços e estruturas básicas necessárias às atividades acadêmicas, fazendo com que alunos, professores e servidores precisem sair do campus. Muitos se perdem ao procurar lugares próximos seja para lanchar ou comprar algum material de trabalho. Sendo assim, o RecomendaFGA visa o compartilhamento de locais e experiências em relação aos bens e serviços oferecidos, próximos ao campus, com o objetivo de facilitar as buscas e melhorar a vida acadêmica.

### 2.2 Descrição do Problema

<table>
  <tr><th> O problema         </th><td> A falta de informação do que existe nas proximidades da faculdade por parte da comunidade acadêmica. </td></tr>
  <tr><th> Afeta                 </th><td> A comunidade acadêmia em geral.</td></tr>
  <tr><th> cujo impacto é        </th><td> Eventuais má experiências com serviços disponíveis ou desorientação em realação a localização.</td></tr>
  <tr><th>Uma boa solução seria </th><td> Um aplicativo voltado a realidade da faculdade o qual pessoas da comunidade pudessem compartilhar locais, experiencias e que indicasse de forma precisa a localização de estabelicimentos. </td></tr>
</table>


### 2.3 Sentença de Posição do Produto

<table>
  <tr><th>Para</th><td>Membros da comunidade acadêmica da Faculdade do Gama - FGA</td></tr>
  <tr><th>Que</th><td>Necessitam se deslocar do campus em busca de bens e serviços </td></tr>
  <tr><th>O</th><td>RecomendaFGA</td></tr>
  <tr><th>Que</th><td>Compartilha locais e experiências </td></tr>
  <tr><th>Diferente do</th><td>Todos os lugares ao redor e TripAdvisitor</td></tr>
  <tr><th>Nosso produto</th><td>Indica locais de acordo com a experiências de outros integrantes da comunidade acadêmica da FGA</td></tr>

</table>

## 3. Descrições dos Envolvidos e dos Usuários

### 3.1 Resumo dos Envolvidos

| Nome                           | Descrição                                                                 | Responsabilidades                                                                |
|--------------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| Clientes               | Prof. Carla Silva Rocha Aguiar, doutora docente na Universidade de Brasília | Acompanhar o andamento do projeto e disponibilizar informações sobre o mesmo.    |
| Coaches                        | -                | - |
| Equipe de  Desenvolvimento     | Equipe de alunos da UnB  de Métodos de  Desenvolvimento  de Software.    | Planejar, desenvolver e  implementar o sistema.                                     |
| Equipe de Gestores  de Projeto | Equipe de alunos da UnB  de Disciplina de Engenharia de Produto de Software. | Planejar, desenvolver e gerenciar o projeto.                 |

### 3.2 Resumo dos Usuários

|    Nome    |      Descrição      |                                   Responsabilidades                                  |       Envolvido      |
|:----------:|:-------------------:|:------------------------------------------------------------------------------------:|:--------------------:|
| Administrador | Moderador responsável por controlar os usuários | O administrador exerce o papel de avaliar a legitimidade dos locais indicados |Corpo acadêmico da universidade |
| Usuário Comum | Alunos, professores e servidores contemplados pelo aplicativo | Solicitar o cadastro ao sistema e indicar locais nas proximidades do campus | Corpo acadêmico da universidade |


### 3.3 Perfis dos Envolvidos

##### 3.3.1 Clientes
<table>
  <tr>
    <td><b>Representantes</b></td>
    <td>Carla Silva Rocha Aguiar</td>
  </tr>
  <tr>
    <td><b>Descrição</b></td>
    <td>Atua na graduação em disciplinas orientadas desenvolvimento de  software livre (MDS/EPS) e coordena o Laboratório Avançado de Produção, Pesquisa e Inovação em Software (LAPPIS).</td>
  </tr>
  <tr>
    <td><b>Tipo</b></td>
    <td>Cliente que requisitou o projeto.</td>
  </tr>
  <tr>
    <td><b>Responsabilidades</b></td>
    <td>Observar e validar o andamento do software.</td>
  </tr>
  <tr>
    <td><b>Critérios de Sucesso</b></td>
    <td>Receber um software que realize de forma sucinta a indicação de locais que facilitem a vida acadêmica próximo a Faculdade do Gama - FGA</td>
  </tr>
  <tr>
    <td><b>Envolvimento</b></td>
    <td>Alto.</td>
  </tr>
  <tr>
    <td><b>Comentários</b></td>
    <td></td>
  </tr>
</table>

##### 3.3.2 Coaches
<table>
  <tr>
    <td><b>Representantes</b></td>
    <td>-</td>
  </tr>
  <tr>
    <td><b>Descrição</b></td>
    <td>Coaches responsáveis pela equipe de MDS e EPS.</td>
  </tr>
  <tr>
    <td><b>Tipo</b></td>
    <td>Graduandos da Universidade de Brasília no curso de Engenharia de Software, aos quais exercem o cargo de monitora das disciplinas de Gestão de Portfólios e Projetos de Software e Métodos de Desenvolvimento de Software, respectivamente.</td>
  </tr>
  <tr>
    <td><b>Responsabilidades</b></td>
    <td>Observar e auxiliar ambas as equipes do projeto na questão de dúvidas e dificuldades no andamento do mesmo.</td>
  </tr>
  <tr>
    <td><b>Critérios de Sucesso</b></td>
    <td>Ajudar as equipes na conquista de conclusão do projeto.</td>
  </tr>
  <tr>
    <td><b>Envolvimento</b></td>
    <td>Médio.</td>
  </tr>
  <tr>
    <td><b>Comentários</b></td>
    <td></td>
  </tr>
</table>

#### 3.3.3 Equipe de Desenvolvedores
<table>
  <tr>
    <td><b>Representantes</b></td>
    <td>Gabriel Davi Silva Pereira<br>
  Heron Rodrigues Souza<br>
    João Lucas Fragoso Zarbiélli<br>
		Lucas Maciel Aguiar<br>
		Matheus Gomes Ferreira<br>
		Weiller Fernandes Pereira<br>
		<br>
    </td>
  </tr>
  <tr>
    <td><b>Descrição</b></td>
    <td>Desenvolvedores do Projeto</td>
  </tr>
  <tr>
    <td><b>Tipo</b></td>
    <td>Graduandos de Engenharia de Software na Universidade de Brasília, matriculados na disciplina de Métodos de Desenvolvimento de Software.</td>
  </tr>
  <tr>
    <td><b>Responsabilidades</b></td>
    <td>Projetar a aplicação, documentar a estrutura do software, programar os recursos definidos e realizar testes de implementação.</td>
  </tr>
  <tr>
    <td><b>Critérios de Sucesso</b></td>
    <td>Entregar aplicação no prazo para a Universidade de Brasília e aumentar experiência na área de desenvolvimento de software.</td>
  </tr>
  <tr>
    <td><b>Envolvimento</b></td>
    <td>Alto.</td>
  </tr>
  <tr>
    <td><b>Comentários</b></td>
    <td></td>
  </tr>
</table>

#### 3.3.4 Equipe de Gestores
<table>
  <tr>
    <td><b>Representantes</b></td>
    <td>Iasmin Santos Mendes
	  <br>Renato Valério Gomes</br>
    </td>
  </tr>
  <tr>
    <td><b>Descrição</b></td>
    <td>Gestores do Projeto.</td>
  </tr>
  <tr>
    <td><b>Tipo</b></td>
    <td>Graduandos de Engenharia de Software na Universidade de Brasília, matriculados na disciplina de Engenharia de Produto de Software.</td>
  </tr>
  <tr>
    <td><b>Responsabilidades</b></td>
    <td>Efetuar todo o planejamento do projeto, projetar a aplicação, programar os recursos definidos do projeto e gerenciar a equipe de desenvolvedores, escopo, custos, riscos e requisitos.</td>
  </tr>
  <tr>
    <td><b>Critérios de Sucesso</b></td>
    <td>Entregar aplicação no prazo para a Universidade de Brasília e aumentar experiência na área de desenvolvimento de software e gestão de projeto.</td>
  </tr>
  <tr>
    <td><b>Envolvimento</b></td>
    <td>Alto.</td>
  </tr>
  <tr>
    <td><b>Comentários</b></td>
    <td></td>
  </tr>
</table>

### 3.4 Perfil dos Usuários

#### 3.4.1 Administrador

| **Representante** | Corpo acadêmico da universidade |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição** | Um usuário com a capacidade de excluir locais mal indicados e moderar comportamentos inadequados detro do aplicativo |
| **Tipo** | Desenvolvedores do aplicativo |
| **Responsabilidades** | Analisar informações inseridas por usuários  |
| **Critérios de Sucesso**  | Obter um software resultante capaz de automatizar o processo de alocação de salas, prevenindo choques de horários e longas distâncias entre salas do mesmo curso. |
| **Envolvimento** | Usuário final do sistema. |
| **Produtos Liberados** | - Relação de disponibilidade das salas; <br> - Informações técnicas de cada sala; <br> - Relatório de Disciplinas Alocadas com suas respectivas salas.|
| **Comentários** | |

#### 3.4.2 Coordenador

| **Representante** | Symone Rodrigues Jardim |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição** | Responsável pela listagem das disciplinas de seu respectivo curso, contendo a relação de demanda, horários e necessidades de cada disciplina. |
| **Tipo** | Mestres e Doutores que lecionam na universidade e atuam no cargo de Coordenador de Curso, além de seus respectivos assistentes. |
| **Responsabilidades** | Fornecer as informações necessárias para a alocação de cada turma, caso necessário, solicitar a reserva de salas no espaço comum da faculdade.|
| **Critérios de Sucesso**  | Obter um software resultante capaz de automatizar o processo de alocação de salas, prevenindo choques de horários e longas distâncias entre salas do mesmo curso. |
| **Envolvimento** | Usuário final do sistema. |
| **Produtos Liberados** | Solicitação contendo as informações necessárias para alocar as disciplinas do seu respectivo curso. |
| **Comentários** |  |

### 3.5 Principais Necessidades dos Usuários ou dos Envolvidos

| Necessidade | Prioridade | Preocupação | Solução Atual | Solução Proposta |
| ----------- | ---------- | ----------- | ------------- | ---------------- |
| Reservar Sala | Alta |  Choque de horário entre disciplinas; Curso prioritário sob determinadas salas; Período de expiração da reserva para evitar a inutilização dos espaços físicos; Disciplinas comuns podem ter mais de um curso associado a mesma turma. | Verificação manual do mapa de sala elaborado para o semestre. | - Categorizar as salas entre disponíveis e ocupadas, de forma que as salas já ocupadas em determinado horário não sejam dispostas para o usuário escolher; <br> - Controle temporal sobre o período letivo; <br> - Permitir ao Coordenador associar cursos diferentes a uma determinada turma, além do seu próprio.|
| Minimizar a distância percorrida pelo aluno entre as trocas de sala | Alta | Manter as aulas de um mesmo curso, preferencialmente, a no máximo 1km de distância das outras aulas do mesmo curso. | Não possui | Agrupar as salas com base em seus respectivos prédios e departamentos, além de segregar o espaço comum da faculdade em Norte e Sul, de forma que um dado curso ofereça todas as suas disciplinas somente em uma dessas regiões. |
| Realizar trocas de salas | Média | Caso haja a necessidade, deve ser possível realizar mudanças no quadro de alocações. | A troca é feita pelos próprios professores, sem o conhecimento dos responsáveis, de forma que impossibilita o uso da sala previamente alocada, por esta constar como ocupada nos registros. | O sistema deverá fornecer a possibilidade de realocar uma turma em outra sala a escolha do usuário. |
| Descrição dos recursos contidos em cada Sala | Baixa | Informar as condições e recursos dispostos na sala para garantir, já na alocação, que uma sala contemple as necessidades de uma dada Disciplina. | Não Possui | Disponibilizar ao usuário a possibilidade de descrever cada sala. |


### 3.6 Alternativas e Concorrência

#### 3.6.1 Catraca Livre

 aplicativo ordena todos os passeios encontrados de acordo com a proximidade do usuário, indo do mais próximo para o mais distante. Também é possível aplicar filtros para datas de eventos que ainda vão ocorrer ou categoria dos eventos(Balada, dança, barato...).
![Catraca_livre](https://raw.githubusercontent.com/fga-eps-mds/RecomendaFGA/DocVisao/docs/static/DocVis_images/8cgrxx4mrv4nji662b7c2dn5f.jpg)

#### 3.6.2  What3Words(W3W)
Serviço de localização, já com o suporte para o idioma português, que utiliza somente 3 palavras para encontrar qualquer endereço do mundo.Basta que o usuário resuma sua busca em no mínimo 3 palavras que o programa dará uma possível localização do lugar. Além da ferramenta de busca, o app também possui a opção de traçar uma rota até o ponto encontrado na busca.

![W3W](https://raw.githubusercontent.com/fga-eps-mds/RecomendaFGA/DocVisao/docs/static/DocVis_images/size_960_16_9_20151020-25144-zw89r7.jpg)

#### 3.6.3 Kekanto

O Kekanto indica bares, restaurantes, baladas e diversos estabelecimentos de acordo com o local do usuário. O app mostra as avaliações dos estabelecimentos,realizadas pela comunidade que utiliza o serviço. Além do mais, Cada usuário pode publicar sua resenha e enviar fotos de estabelecimentos de todas as cidades do Brasil e mais 14 países, entre Argentina, Chile, Estados Unidos e Portugual, por exemplo.

![Kekanto](https://raw.githubusercontent.com/fga-eps-mds/RecomendaFGA/DocVisao/docs/static/DocVis_images/kekanto.jpeg)

#### 3.6.4 Yelp

Yelp é um app que pesquisa locais próximos do usuário, utilizando a localização por GPS. Primeiro o usuario informa o tipo de local (bares, restaurantes, shoppings...) e então possível filtrar os resultados obtidos por varias características: valor, mais avalidados, aceita cartões, bom para crianças, entre outros. A distância máxima dos locais também pode ser definida. Para uma escolha melhor do local, o usuário pode ver avaliações escritas por outros usuários.

![Yelp](https://raw.githubusercontent.com/fga-eps-mds/RecomendaFGA/DocVisao/docs/static/DocVis_images/ZRKtVyQ.jpg)

## 4. Visão Geral do Produto

### 4.1 Perspectiva do Produto

O SIGS - Sistema Inteligente de Gestão de Salas irá sistematizar o processo de alocação de salas referente às disciplinas oferecidas pela Universidade de Brasília. De tal forma que, Coordenadores e membros do departamento tenham o controle sobre o mapeamento das salas ocupadas no respectivo departamento, enquanto que as áreas comuns ficam sob jurisdição da Prefeitura da Universidade. O produto fornecerá aos usuários as informações necessárias para melhor gerirem os espaços físicos. Tais informações contemplam disponibilidade da sala, capacidade, topologia, recursos e proximidade de uma dada sala do espaço comum com as salas respectivas de um curso. Assim, têm-se como expectativa facilitar e agilizar o processo de alocação de salas da UnB, além de evitar qualquer inconsistência em relação às salas e horários, como choques de horários entre turmas.

### 4.2 Resumo dos Recursos

| Código |Recurso | Benefício|
|:------:|--------|----------|
| R01 | Sistematização do processo de alocação de salas.| Agiliza o processo de alocação de salas para disciplinas, um processo que atualmente é feito de maneira mecânica, com a utilização de ferramentas como planilhas. Além disso, evita choque de horários entre disciplinas, adequação da capacidade das salas e também de grandes distâncias entre disciplinas de um mesmo curso. |
| R02 | Fornecer um panorama da atual situação das salas referentes às suas respectivas alocações. | Permite uma maior organização uma vez que que o sistema garantirá que não haja nenhum tipo de inconsistência em relação às salas e horários. |

## 5. Requisitos Funcionais

##### Legenda de Prioridades dos Requisitos:

| Prioridade | Característica |
| ---------- | -------------- |
| Alta | Requisito fundamental para o sistema. |
| Intermediária | Requisito importante, mas não é fundamental para o funcionamento do sistema. |
| Baixa | Requisito não fundamental e pouco usado no sistema. |

| Identificador | Nome | Descrição | Prioridade |
|---|---|---|---|
| RF1 | Autenticar Usuário | O Sistema deve solicitar o usuário e autenticar a sessão do mesmo, após a aprovação. | Alta |
| RF2 | Controlar Cadastro  | O Sistema deve autorizar o Assistente Administrativo de editar as informações dos usuários e aprovar seu cadastro. | Intermediária |
| RF3 | Controlar Sala | O Sistema deve permitir o Assistente Administrativo a manter as informações das salas. | Intermedária |
| RF4 | Controlar Turmas | O sistema deve permitir que os usuários possam manter as informações das turmas. | Alta |
| RF5 | Controlar Alocações | O sistema deve permitir que os usuários possam gerenciar as alocações feitas, e que o Assistente Administrativo controle as de espaço comum. |Alta|
| RF6 | Orientar Alocações | O sistema deve permitir que os usuários possam visualizar as alocações e geram seus respectivos relatórios. | Baixa|

## 6. Restrições

* O cadastro de usuários deve ser aprovado apenas com a utilização de uma matrícula válida pela Unb;
* Somente os Admnistradores do Sistema poderam realizar a remoção de uma conta de usuário comum.
* O sistema só funcionará mediante uma conexão de rede pelo menos satisfatória e será mantido em um servidor Rails.
* A documentação do sistema será escrita em sua maioria na língua portuguesa, assim restringindo o entendimento da documentação apenas para pessoas com conhecimento na língua, salvo partes mais técnicas relacionadas diretamente ao código da aplicação.

## 7. Requisitos Não Funcionais

### 7.1 Requisito do Sistema

* O sistema deve estar hospedado em um servidor da mesma linguagem de programação e versão do software, e também ter acesso a uma rede estável para a conexão com os usuários.

* Para ter acesso ao aplicativo o usuário deve ter um telefone celular com sistema operacional Android ou iOS, e conta na suas respectivas centrais de aplicativos.

### 7.2 Requisito de Desempenho

* O sistema deve ter o tempo de execução e resposta de acordo com a qualidade da conexão de internet, sendo assim, a velocidade de rede irá impactar diretamente o sistema em todas as suas funcionalidades.

### 7.3 Requisito de Design

* O sistema deve ter uma interface organizada e utilizar de ícones intuitivos que facilitam o entendimento de seus significados além de fluxos fáceis de aprender e memorizar.

### 7.4 Requisito de Confiabilidade

* Informações não serão alugadas nem vendidas a terceiros fora do RecomendaFGA.

* Quando inseridos dados pessoais do usuário, o sistema deve mantê-los protegidos de quaisquer influências externas.

* Deve existir um sistema de autenticação de contas, por meio da matrícula e senha ou e-mail e senha.

* O sistema deve aprensentar a menor quantidade possível de falhas, mas não garante que a plataforma seja livre de imprecisões, falhas, erros ou interrupções.


### 7.5 Requisito de Arquitetura

* O backend deve seguir a arquitetura MVC (*Model View Controller*) do Ruby on Rails.

* O frontend deve seguir a arquitetura Modular do React Native.

### 7.6 Requisito de Usabilidade

* Os sistema deve ser nativo para o sistema operacional utilizado pelo usuário e não uma aplicação web.

* O sistema deve facilitar a utilização e compreensão de sua interface por parte dos usuário, além de buscar facilitar que o utilizador tem em alcançar os seus objetivos por meio da simplicidade no uso.



### 7.7 Requisito de Suportabilidade

* A linguagem de programção deve ser multiplataforma, a qual pode ser utilizada em qualquer sistema operacional mobile.

### 7.8 Requisito de Segurança

* O sistema deve conter validações para cada campo no formulário a ser preenchido pelo usuário.
* O sistema deve criar uma sessão para o usuário após o mesmo efetuar o login.
* O sistema deve criar níveis de permissão para cada tipo de conta em relação ao acesso a cada funcionalidade.
