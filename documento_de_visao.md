# Documento de Visão do Projeto -  UnB Monitorias

## Histórico de Revisão
| Data   | Versão | Modificação  | Autor  |
| :-- | :-- | :-- | :-- |
| 04/08/2021 | 0.0 | Estrutura do documento documento de visão|  Flavio Vieira |

## Sumário
    1. INTRODUÇÃO    
        1.1.	Problema 
        1.2.	Declaração do Problema  
        1.3.	Objetivos do Projeto
    2. STAKEHOLDERS  
    3. VISÃO GERAL DO PRODUTO  
        3.1.	Declaração de Posição do Produto  
        3.2.	Mínimo Produto Viável (MVP)
    4. VISÃO GERAL DO PROJETO  
        4.1.	Organização do Projeto  
    5. FERRAMENTAS, AMBIENTE E INFRA-ESTRUTURA  
        5.1.	Hardware  
        5.2.	Software
    6. PROCESSO DE GERÊNCIA DE PROJETO  
        6.1.	Planejamento das Fases e Iterações do Projeto  
        6.2.	Processo de Desenvolvimento e Mensuração  
        6.3.	Matriz de Comunicação  
        6.4.	Escalabilidade do Projeto  
        6.5.	Gerenciamento de Riscos  
    7. LIÇÕES APRENDIDAS
    8. REFERÊNCIAS
    9. CANVAS MVP

## Visão do Projeto
- Para os alunos, monitores, professores e coordenadores de graduação da UnB que desejam gerenciar as suas monitorias do semestre. O UnB monitorias é uma plataforma web. Isso facilita o acesso às informações de todas as monitorias e do processo de candidatura à monitoria, pois podem ser acessadas a todo momento e em qualquer lugar por meio de um celular. Atualmente, as informações das monitorias estão dispersas entre diversas plataformas (sigaa, aprender) e redes sociais(facebook, whatsapp, telegram). Essa dispersão de informações dificulta o acesso à monitoria. Nosso produto tem como intuito unificar todo o processo de candidatura à monitoria, gerência e também acesso por parte dos alunos, professores e coordenadores. 
### 1. Introdução  
#### 1.1. Declaração do Problema
| Questionamento | Resposta |
| :-- | :-- |
| O problema  | Falta de um sistema para gestão de monitoria |
| Afeta | Os alunos, monitores, professores e coordenadores de graduação |
| Cujo impacto é | Informações dispersas e burocratização no processo de candidatura à monitoria  |
| Uma solução de sucesso seria | Centralizar as informações em uma só plataforma |  

&nbsp;
#### 1.2. Objetivos do Projeto
* Unificar todo o processo de candidatura à monitoria, gerência e também acesso por parte dos alunos, professores e coordenadores.   
* Facilitar o acesso às informações do perfil e da disponibilidade dos monitores.  
* Acesso rápido às informações sobre as monitorias selecionadas pelo aluno


&nbsp;
## 2. Stakeholders
| Nome | Descrição | Responsabilidade |
| :-- | :-- | :-- |
|Aluno | Graduando da UnB| Selecionar as monitoria de sua preferência para receber as informações. Se candidatar a monitor se desejar |
| Monitor | Aluno aceito no processo de candidatura a monitoria| Cadastra as informações referentes as monitorias que ministra |
|Professor  | Ministra uma disciplina | Solicitar monitores para sua disciplina e avaliá-los|   
| Coordenador | Responsável pelo processo de candidatura a monitoria| Laçar editais do processo de monitoria, avaliar e selecionar os alunos que serão monitores|
| Equipe de desenvolvimento | Planejamento, desenvolvimento e manutenção da plataforma |Executar o projeto dentro do prazo estipulado com base no escopo de engenharia de requisitos |

&nbsp;
## 3. Visão Geral do Produto  
### 3.1. Declaração de Posição do Produto
| Posição do produto | Descrição |
|:--|:--|
| Para|alunos, monitores, professores e coordenadores de graduação da UnB|
| Quem | deseja gerenciar as suas monitorias do semestre |
| O *UnB Monitorias* | é uma plataforma web de gestão de monitorias |
| Que | facilita o acesso às informações de todas as monitorias e do processo de candidatura à monitoria, pois podem ser acessadas a todo momento e em qualquer lugar por meio de um celular |
| Ao contrário | dos formulários em papel, das informações dispersas sobre a monitoria e do seu processo de candidatura |
| Nosso produto | unifica todo o processo de candidatura à monitoria, gerência e também acesso por parte dos alunos, professores e coordenadores.  |

&nbsp;
### 3.2. Escopo do Produto

#### 3.2.1 Requisitos Funcionais
* Cadastrar disciplina  
* Registrar alunos  
* Registrar monitores  
* Registrar coordenadores  
* Registrar professores  
* Lançar edital/cadastrar monitoria  
* Selecionar monitores  
* Cadastrar plano de monitoria  
* Avaliar monitor  
* Autenticar usuários  
* Registrar a candidatura do aluno à monitoria  

&nbsp;
#### 3.2.2 Requisitos não Funcionais
* Versionamento via Github
* React para front-end
* Python para back-end
* Telegram para comunicação interna
* Microsoft teams para comunicação
* VSCode como editor de texto
* Pycharm como editor de texto

&nbsp;
### 3.3 Mínimo Produto Viável (MVP)


&nbsp;
## 4. Visão Geral do Projeto  
### 4.1. Organização do Projeto
| Papel | Atribuições | Responsável | Participantes |
|:----:|:----:|:----:|:----:|
| - | - | - | - | 

&nbsp;
## 5. Ferramentas, Ambiente e Infra-Estrutura
### 5.1. Hardware  
| Perfil | Tipo de Hardware | Configurações | Qtd. PLanejada | Prazo Estimado | Observação |
|:----:|:----:|:----:|:----:|:----:|:----:|
| Desenvolvedor | Computador | Intel I3; 4gb RAM | 6 | 02/08/2021 |

&nbsp;
### 5.2. Software  
| Perfil | Tipo de Software | Nome da Ferramenta | Versão | Qtd. Licensas | Prazo Estimado | Observação |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| Desenvolvedor | Editor de Código  | VSCode/Pycharm | - | Free | - | 06/08/2021 |
| Desenvolvedor | Gerenciador de Versionamento  | Git | - | Free | - | 06/08/2021 |
| Desenvolvedor | Comunicação  | Microsoft Teams / Telegram | - | Free | - | 06/08/2021 |
| Desenvolvedor | Deploy  | Vercel | - | Free | - | 06/08/2021 |

&nbsp;

## 6. Processo de Gerência de Projeto  
&nbsp;
### 6.1. Processo de Desenvolvimento e Mensuração  
Especifique como será acompanhado o progresso, por exemplo, por meio de reuniões de revisão diárias, avaliações de iteração, relatórios de Burndown de Projeto e Burndown de Iteração.

&nbsp;
### 6.2. Planejamento das Fases e Iterações do Projeto
[Registrar o projeto, as fases de seu ciclo de vida e suas iterações, especificando suas datas de início e de fim, bem como os produtos a serem gerados.]  


&nbsp;
### 6.3. Matriz de Comunicação 
[Esta seção descreve a estratégia de comunicação adotada para monitoramento do progresso do projeto. Identificar a periodicidade de reuniões e o envio dos relatórios exigidos pelo processo e opcionalmente outros relatórios exigidos pelo cliente.] 
| Descrição | Área/Envolvidos | Periodicidade | Produtos Gerados |
| :----: | :----: | :----: | :----: |
| - | - | - | - |

### 6.4. Escalabilidade do Projeto
[Os conflitos que possam ocorrer no projeto devem ser identificados, descrevendo os papéis responsáveis pela resolução. Quando não solucionado na primeira instância, o conflito é escalado para a 2a e se ainda assim não solucionado, este pode ser escalado para a última instância. Exemplos: aumentos de custo e prazo do projeto são escaláveis ao professor.] 

&nbsp;
### 6.5. Gerenciamento de Riscos
[Para o Gerenciamento de Riscos devem ser realizadas tarefas, como:  
Identificar todos os riscos possíveis e detectáveis em cada fase do projeto; 
Executar as ações para mitigar os riscos que tenham um alto grau de exposição ao risco caso este ocorra na Lista de Riscos do Projeto;
Fazer uma revisão da lista dos riscos periodicamente, com o propósito de averiguar uma possível incidência de um risco e ver se há outros riscos ainda não relatados;
Em caso de confirmação de um risco previsto, agir no sentido de contingenciá-lo conforme programado;
Registrar os riscos no Painel de Controle do Projeto e no Plano do Projeto (Riscos iniciais);]


&nbsp;
### 6.6. Critérios de Replanejamento  
[Descrever os critérios de replanejamento que serão utilizados, caso seja necessário realizá-lo no projeto.]

&nbsp;
## 7. Lições Aprendidas
.....................
## 8. Referências 
.....................
## 9. Canvas MVP 
.....................


