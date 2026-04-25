<h1 align="center">
  <a name="eu"></a>Quem sou eu?
</h1>

<div align="center">
  <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/19749bf0-99d6-4455-97a5-0fdf29606e98" />
</div>

###

Sou Yan, estudante de Banco de Dados na FATEC São José dos Campos.Comecei essa jornada no segundo semestre de 2023. Desde então, participei das API’s (Aprendizagem por Projetos Integrados) onde tive meus primeiros contatos com projetos reais envolvendo linguagens de programação, banco de dados, metodologias scrum e clientes. Desenvolvi aplicações com Python e Java, além de frameworks como Vue.js, Spring Boot e Django. Também tive experiência com diversos bancos de dados, como PostgreSQL, MySQL e MongoDB. Neste portfólio, apresento os projetos que desenvolvi ao longo da minha trajetória na FATEC e minha evolução prática na área de tecnologia.

<h1 align="center">
  <a name="contatos"></a>Contatos
</h1>

<div align="center">
  <a href="https://www.linkedin.com/in/yan-yamim-185220278/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://github.com/Yan-Yamim" target="_blank">  
    <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge" height="40" alt="github logo"  />
  </a>
</div>

---

# Sumário
- [Quem sou eu?](#eu)
- [Contatos](#contatos)
- [Projetos](#projetos)
  - [1° semestre | 2/2023 - VCCorp](#vccorp)
  - [2° semestre | 1/2024 - Leitor de climas](#leitor)
  - [3° semestre | 2/2024 - Cerberus](#cerberus)
  - [4° semestre | 1/2025 - TerraVision](#terravision)
  - [5° semestre | 2/2025 - Jiboia](#jiboia)
  - [6° semestre | 1/2026 - Thunder Stone](#pokemon)

---

# <a name="projetos"></a>Projetos

## <a name="vccorp"></a>1° semestre | 2/2023

**Projeto**: VCCorp  
**Empresa parceira**: Professor Lucas Nadalete - utilizando o nome fictício PBLTeX

### Problema
A PBLTeX utiliza uma metodologia de ensino diferenciada chamada PBL (Problem Based Learning), que depende da gestão de múltiplos "ciclos de entregas" e do registro de "scores parciais" de cada aluno para, ao final, computar o "Fator de Ensino Evolutivo" (FEE).

Atualmente, a instituição não possui um sistema de informação que suporte essa técnica específica. Isso força que o acompanhamento dos ciclos, a coleta dos scores e o cálculo do FEE sejam realizados através de processos manuais ou ferramentas genéricas (como planilhas). Esse método é lento, propenso a erros de cálculo e difícil de escalar à medida que o número de alunos aumenta, tornando a aplicação eficiente da sua principal técnica de ensino um desafio operacional.

### Solução
O sistema foi desenvolvido especificamente para a instituição de ensino PBLTeX, especializada em cursos baseados no método PBL. A aplicação permite o gerenciamento dos "ciclos de entregas" e o cálculo do "Fator de Ensino Evolutivo (FEE)", viabilizando a operacionalização da técnica de ensino da instituição. A proposta consiste em uma aplicação backend com interface de linha de comando (CLI), permitindo que administradores e responsáveis acadêmicos realizem operações de forma rápida, direta e automatizada.

Link do repositório: [VCCorp](https://github.com/Yan-Yamim/1-API)

### Tecnologias usadas
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
</div>

---

### Contribuições Pessoais

No primeiro projeto, atuei como desenvolvedor, sendo responsável pela implementação das regras de negócio do produto. Além do entendimento da aplicação, fui responsável pela tela de menu incial de usuário, o cálculo das médias das notas dos alunos, cadastro dos ciclos e de turmas. 
- **Desenvolvimento da tela de Menu**
    <details>
      <summary>Ver detalhes</summary>
      Criei um menu interativo no terminal utilizando Python puro. O menu exibia opções numeradas para acesso às funcionalidades do sistema, como cadastro de ciclos, turmas e cálculo de médias.
        Implementei validação de entrada do usuário para evitar erros e garantir uma navegação fluida. A estrutura utilizava <code>while</code> e <code>if-elif</code> para manter o programa em execução até que o usuário optasse por sair.
    </details>
    
- **Cálculo das médias das notas dos alunos**
    <details>
      <summary>Ver detalhes</summary>
        Desenvolvi uma função em Python responsável por calcular a média das notas dos alunos com base em uma lista de valores numéricos.
        A lógica considerava pesos iguais para todas as provas e incluía validações para evitar divisão por zero ou dados inválidos.
        O resultado era exibido diretamente no terminal com formatação adequada.
    </details>

- **Cadastro de ciclos**
    <details>
      <summary>Ver detalhes</summary>
        Implementei uma funcionalidade para cadastrar ciclos de ensino, armazenando as informações em estruturas de dados como listas ou dicionários.
        O sistema coletava dados como o nome do ciclo e o identificador, garantindo que entradas duplicadas fossem evitadas.
        Os dados eram mantidos na memória durante a execução do programa, simulando um armazenamento temporário.
    </details>

- **Cadastro de Turmas**
    <details>
      <summary>Ver detalhes</summary>
        Criei um sistema de cadastro de turmas no terminal, onde era possível informar o nome da turma, o ciclo ao qual pertencia e outras informações relevantes.
        Os dados das turmas eram organizados em listas de dicionários para facilitar o gerenciamento.
        Também implementei verificações para garantir que a turma fosse associada a um ciclo previamente cadastrado.
    </details>

### Hard Skills

- **Git** – Utilizado diariamente para versionar o código-fonte da aplicação. Trabalhamos com ramificações específicas para funcionalidades (feature branches), criamos pull requests para revisão de código e resolvemos conflitos em equipe, garantindo organização e segurança no controle de versões do projeto colaborativo.
- **Python** -  Linguagem utilizada para construir toda a lógica de negócio da aplicação, como o cálculo por trás das notas, cadadstro de ciclos, turmas, alunos e grupo e, não menos importante, a exportação para arquivo CSV

### Soft Skills

- Durante a execução do projeto, assumi um papel de liderança devido a problemas de engajamento da equipe e para orientá-los na definição de metas e prioridades. Identifiquei a necessidade de realinhar as entregas e por meio de reuniões objetivas e divisão de tarefas. Promovi um ambiente colaborativo, mediando conflitos e incentivando a contribuição de cada membro.
- Enfrentei prazos curtos, problemas de comunicação, dificuldades de compreensão de requisitos e engajamento da equipe. Mesmo diante desses obstáculos, mantive o foco e a motivação. Organizei prioridades, reestruturei tarefas e, com esforço contínuo, garanti que as entregas fossem feitas com qualidade, respeitando os prazos estabelecidos.
- Em um projeto com requisitos complexos, tomei a iniciativa de estruturar a base do código antes mesmo da definição final das regras de negócio. Defini como será estruturado o desenvolvimento e documentei as decisões técnicas para alinhar a equipe. Essa abordagem não apenas acelerou o processo de implementação, mas também serviu como referência para evitar retrabalhos. Isso garantiu que o projeto avançasse de forma organizada, mesmo em um cenário de incertezas.

---

## <a name="leitor"></a>2° semestre | 1/2024

**Projeto**: Leitor de climas  
**Empresa parceira**: Professor Emanuel Mineda

### Problema
Ter um bom entendimento do clima de uma região é essencial para o planejamento de atividades em diversas áreas. Por exemplo, conhecer a temperatura e umidade média em determinados períodos do ano pode influenciar na escolha do que plantar em uma fazenda.
Atualmente, existem diversas bases de dados públicas em arquivos CSV. Cada cidade pode ter múltiplas estações de monitoramento, cada uma com formatos diferentes. Isso torna o processamento manual lento, propenso a erros e difícil de escalar.

---

### Solução
O sistema foi desenvolvido para processar arquivos CSV de estações meteorológicas, armazenar os dados em um banco relacional, validar registros suspeitos e gerar relatórios detalhados por cidade e período. Também possibilita o gerenciamento de estações, cidades e unidades de medida, garantindo dados consistentes e acessíveis.

Link do repositório: [Leitor de climas](https://github.com/Yan-Yamim/Leitor-de-clima)

### Tecnologias Usadas

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" height="40" alt="java logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
</div>

---

### Contribuições Pessoais

Nesse projeto, pela primeira vez atuei como Scrum Master, ou seja, minhas responsabilidades foram mais direcionadas a parte administrativa do grupo. Dentre elas fui responsável pela divisão das tarefas para cada pessoa do grupo em cada sprint para todos terem suas tarefas dentro dos seus limites possíveis, além disso elaborei as reuniões de equipe para acompanhar o andamento do grupo para verificar se há tarefas pendentes, em andamento ou em conclusão e para isso precisei cobrar o time para que evitassem ter atrasos ou problemas com as entregas.

- **Divisão das tarefas para cada membro da equipe durante as sprints**
    <details>
      <summary>Ver detalhes</summary>
      Durante as sprints, analisei as habilidades individuais da equipe e alinhei as tarefas conforme a expertise de cada um (ex.: back-end, front-end, QA). Utilizei ferramentas como <strong>Jira</strong> e <strong>Trello</strong> para atribuir atividades, definir prazos e monitorar o progresso. Para evitar gargalos, redistribuí tarefas quando necessário, garantindo equilíbrio na carga de trabalho. Isso resultou em um fluxo contínuo de entregas e maior engajamento do time.
    </details>

- **Responsável pelas reuniões de equipe**
    <details>
      <summary>Ver detalhes</summary>
      Organizei e conduzi reuniões diárias (<strong>stand-ups</strong>) e semanais (<strong>sprint planning</strong> e <strong>retrospectivas</strong>). Criava agendas claras com tópicos como: progresso das tarefas, bloqueadores e ajustes de prioridades. Documentava os acordos em notas compartilhadas (Google Docs) e incentivava a participação de todos. Como resultado, mantivemos a comunicação alinhada e reduzimos retrabalhos causados por mal-entendidos.
    </details>

- **Cobrança da equipe pelas entregas**
    <details>
      <summary>Ver detalhes</summary>
      Monitorei o cumprimento de prazos através de checkpoints periódicos (ex.: atualizações no Github) e abordagens individuais para identificar dificuldades. Em casos de atrasos, propunha soluções como pair programming ou redistribuição de tarefas. Sempre priorizei um tom colaborativo, focando em remover obstáculos em vez de apenas pressionar. Essa prática aumentou a taxa de entregas em 30% e fortaleceu a confiança dentro da equipe.
    </details>

### Hard Skills

- **Github** – Usamos o github para guardar nosso repositório em alterações e também usar o Kanbam do próprio Github para as divisões de tarefas
- **Java** – Linguagem utilizada para construir toda a lógica de negócio da aplicação, como a integração com o JavaFX, com o banco de dados e a geração dos gráficos com base no que foi parametrado pelo usuário. Desenvolvemos classes para entidades como Registro, Parametros, Cidade e Estação, além de serviços para realizar a associação e busca por essas entidades.
- **MySQL** – Serviu como o banco de dados da aplicação. Modelamos tabelas como `estacao`, `registro`, `parametros` e `cidade`. Utilizamos SQL para armazenar os dados registrados pelo usuário e para assim poder criar os gráficos necessários com base nos parâmetros obtidos

---

### Soft Skills

- Como Scrum Master, enfrentei o desafio de equilibrar autonomia e suporte, garantindo que a equipe se sentisse capacitada para entregar resultados com qualidade. Para isso, promovi um ambiente de confiança mútua, onde cada membro tinha clareza sobre suas responsabilidades, mas sabia que poderia contar com meu apoio em impedimentos técnicos ou burocráticos. Realizei check-ins individuais para entender dificuldades e facilitar soluções, além de incentivar a colaboração entre pares. O resultado foi um time mais coeso, com entregas consistentes e um aumento significativo na auto-organização.
- Em um projeto com requisitos em evolução, a comunicação clara foi essencial para evitar retrabalhos e ambiguidades. Como Scrum Master, atuei como facilitador, garantindo que as informações fluíssem de forma transparente entre desenvolvedores, Product Owner e clientes. Implementei técnicas como Daily Objetivas (focadas em bloqueios) e revisões de backlog com linguagem não técnica para alinhar expectativas. Além disso, documentei decisões-chave em canais acessíveis. Essa abordagem reduziu as dúvidas críticas durante as sprints e aumentou a eficiência nas entregas.
- Diante de uma equipe sobrecarregada e prazos realistas, priorizei o bem-estar do time sem comprometer o valor do produto. Adaptei o ritmo das sprints, negociando prazos com o Product Owner quando necessário, e introduzi práticas como buffer times para imprevistos. Promovi retrospectivas honestas para ajustar processos e, em casos específicos, aceitei entregas parciais para evitar burnout. Essa flexibilidade equilibrou sustentabilidade e resultados: a produtividade aumentou a longo prazo, e a equipe manteve um engajamento alto, mesmo em fases críticas.

---

## <a name="cerberus"></a>3° semestre | 2/2024

**Projeto**: Cerberus  
**Empresa parceira**: GWS - Especializada em desenvolvimento e implantação de soluções inteligentes em Tecnologia da Informação para gestão empresarial, gestão tributária, operações em comércio exterior e CRM

Link do repositório: [Cerberus](https://github.com/c137santos/FATEC-API-3-SEMESTRE)

### Problema
Atualmente, a coleta de notícias estratégicas e dados relevantes é feita de forma manual, exigindo que analistas acessem diversos portais e APIs para buscar informações. Esse processo é demorado, sujeito a falhas e dificulta o acompanhamento contínuo de temas importantes para o negócio. Muitas vezes, por falta de tempo ou excesso de tarefas, as atualizações deixam de ser feitas, comprometendo a análise de tendências e a tomada de decisões baseada em dados.

---

### Solução
O sistema foi desenvolvido com o objetivo de automatizar a captura, armazenamento e exibição de notícias estratégicas e dados provenientes de APIs externas. A aplicação permite o cadastro de portais, jornalistas, tags e APIs, além de realizar web scraping periódico para coleta de novas informações.
Exibindo os dados de forma clara, permitindo consultas rápidas e identificação de tendências. O projeto também foi estruturado para, em estágios futuros, integrar algoritmos de inteligência artificial e machine learning para análise preditiva.

### Tecnologias usadas:
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" alt="spring logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="40" alt="vuejs logo"  />
</div>


### Contribuições Pessoais

Nesse projeto, atuei diretamente no desenvolvimento fullstack, sendo responsável pela implementação das principais funcionalidades de cadastro dos portais de notícias e das tags além de suas páginas web responsáveis por isso. Também desenvolvi uma feature de poder relacionar várias tags a um portal de notícia tanto no cadastro quanto na edição precisando até corrigir bugs em relação a essa listagem. Incluive também desenvolvi o modal capaz de visualizar a notícia já cadastrada pelo scrapping em formato de pop-up. As interfaces foram desenvolvidas com Vue.js 3, integrando-se ao backend via Axios para garantir a persistência e sincronia dos dados entre o sistema e o banco de dados.

- **Método responsável pelo cadastro de Tags e de Portais**
    <details>
      <summary>Ver detalhes</summary>
      No back-end, desenvolvi os métodos <code>POST</code> em controladores Spring Boot (<code>TagController</code> e <code>PortalController</code>) para receber dados JSON e persistir as entidades no banco usando JPA. Utilizei as anotações <code>@RequestBody</code> e <code>@PostMapping</code>, garantindo validação e integridade dos dados. No repositório, empreguei <code>save()</code> do <code>JpaRepository</code>. Isso garantiu a criação de novos registros tanto de tags quanto de portais de forma segura.
    </details>

- **Página web que cadastra Tags e de Portais**
    <details>
      <summary>Ver detalhes</summary>
      No front-end, criei componentes Vue separados para o cadastro de tags e portais. Utilizei <code>v-model</code> para fazer o binding dos inputs com os dados e <code>axios</code> para enviar os dados via requisições <code>POST</code> para os respectivos endpoints da API. Os formulários foram montados com HTML semântico, CSS para estilo, e validadores simples para impedir envios incompletos.
    </details>

- **Possibilidade de relacionar várias tags a um portal de notícia tanto no cadastro quanto na edição**
    <details>
      <summary>Ver detalhes</summary>
      No front-end, implementei um método responsável por buscar todas as tags salvas no banco de dados e exibi-las em um campo de seleção múltipla. Utilizeio `axios` para consumir a API de listagem de tags com os nomes e IDs. Também criei uma estrutura reativa para armazenar as tags selecionadas pelo usuário. Essas informações eram enviadas no corpo da requisição `POST` ou `PUT` ao cadastrar ou editar um portal. Além disso, adaptei os DTOs para aceitar e retornar listas de IDs de tags associadas a cada portal.    
    </details>

- **Correção de bug envolvendo registro de portais**
    <details>
      <summary>Ver detalhes</summary>
      Corrigi um bug no cadastro de portais que a checkbox sempre dava como ativa, mas precisava ter a opção de ativar ou desativar o portal de notícia
    </details>

- **Exibição do conteúdo da notícia através de um pop-up**
    <details>
      <summary>Ver detalhes</summary>
      No front-end Vue.js, implementei uma modal reutilizável com <code>&lt;dialog&gt;</code> e transições para exibir o conteúdo completo da notícia. Cada card de notícia tinha um botão "Exibir notícia" que acionava a exibição do pop-up com o corpo da notícia. Os dados eram passados como props para o componente da modal e renderizados dinamicamente com Vue.
    </details>

### Hard Skills

- **Git** – Utilizado diariamente para versionar o código-fonte da aplicação. Trabalhamos com ramificações específicas para funcionalidades (feature branches), criamos pull requests para revisão de código e resolvemos conflitos em equipe, garantindo organização e segurança no controle de versões do projeto colaborativo.
- **Java** – Linguagem utilizada para construir toda a lógica de negócio da aplicação, como o tratamento das requisições do front-end, a integração com o banco de dados e o processamento das notícias obtidas pelo crawler. Desenvolvemos classes para entidades como Tag, Portal e Notícia, além de serviços para realizar a associação e busca por essas entidades.
- **Spring Boot** – Framework usado para estruturar a API REST que permitia ao front-end consultar e cadastrar dados como notícias, tags e portais. Com ele, criamos os controladores, endpoints, camadas de serviço e repositórios JPA para gerenciar o fluxo completo de dados entre o crawler, o banco e o front-end.
- **PostgreSQL** – Serviu como o banco de dados da aplicação. Modelamos tabelas como `noticia`, `portal`, `tag` e tabelas de associação para representar os relacionamentos entre elas. Utilizamos SQL e JPA para armazenar as notícias capturadas pelo crawler e consultá-las conforme as tags e portais selecionados pelo usuário.
- **Docker** – Empregado para padronizar o ambiente da aplicação. Criamos contêineres para o back-end, banco de dados e crawler, utilizando `Dockerfile` e `docker-compose` para garantir que toda a equipe pudesse rodar o sistema localmente de forma uniforme, além de facilitar o deploy.
- **Vue.js** – Utilizado na construção da interface web da aplicação. Desenvolvemos componentes que permitiam ao usuário cadastrar e visualizar tags, portais e resultados de busca. A interface consumia os dados da API de forma reativa e dinâmica, possibilitando a busca de notícias em tempo real a partir de critérios definidos.

---

### Soft Skills
- Durante o desenvolvimento do projeto, enfrentei situações técnicas complexas que exigiram clareza na comunicação. Para superar essas dificuldades, procurei colegas mais experientes, explicando de forma objetiva os problemas enfrentados e ouvindo atentamente sugestões e feedbacks. Essa troca constante foi essencial para encontrar soluções eficientes e manter a fluidez no andamento da equipe.
- A colaboração entre os membros foi fundamental para o sucesso da API. Participei ativamente de reuniões de alinhamento, dividi responsabilidades com clareza e mantive um canal aberto para revisões de código e suporte mútuo. A soma de conhecimentos e o respeito pelas ideias dos colegas resultaram em um desenvolvimento mais ágil e com maior qualidade técnica.
- Enfrentei prazos curtos, bugs inesperados e dificuldades de compreensão de requisitos. Mesmo diante desses obstáculos, mantive o foco e a motivação. Organizei prioridades, reestruturei tarefas e, com esforço contínuo, garanti que as entregas fossem feitas com qualidade, respeitando os prazos estabelecidos.
- Tive que lidar com ferramentas e frameworks até então desconhecidos, como o Spring Boot e o Docker. Para acompanhar o ritmo da equipe e contribuir efetivamente, dediquei-me a aprender rapidamente por meio de cursos, documentação oficial e tutoriais. Essa capacidade de aprender e aplicar novos conhecimentos foi decisiva para minha evolução no projeto.</li> </ul>

---

### <a name="terravision"></a>4° semestre | 1/2025

**Projeto**: Terravision  
**Empresa parceira**: Visiona - Integração de soluções baseadas em sistemas espaciais

### Problema
As empresas agrícolas que utilizam sistemas de mapeamento geoespacial enfrentam dificuldades em validar e corrigir os polígonos gerados por modelos de inteligência artificial. Atualmente, analistas precisam revisar manualmente diversos talhões utilizando ferramentas dispersas, muitas vezes sem suporte adequado para edição, comparação ou controle de versões. Além disso, a colaboração entre diferentes perfis — administradores, analistas e consultores — ocorre de maneira pouco estruturada, dificultando o registro do histórico de alterações, a rastreabilidade das revisões e o acompanhamento da produtividade individual. Em muitos casos, a ausência de um ambiente centralizado para edição e análise geoespacial atrasa o processo de revisão, reduz a qualidade das correções e prejudica o refinamento dos modelos de IA responsáveis pelo mapeamento agrícola. Também não há uma forma padronizada de medir a performance das correções, o que impede administradores de avaliar a eficiência dos analistas e dificulta o uso dos polígonos revisados como benchmark de qualidade.

### Solução
A solução oferece um editor interativo de GeoJSON, permitindo que analistas revisem e ajustem os polígonos diretamente no mapa, com ferramentas adequadas para manipulação geométrica e atualização das propriedades associadas. Todas as modificações realizadas passam a ser registradas em um histórico de alterações, garantindo rastreabilidade e permitindo auditorias precisas. Além disso, o sistema organiza o fluxo de trabalho entre administradores, analistas e consultores por meio de controle de permissões, garantindo que cada tipo de usuário tenha acesso apenas às funcionalidades necessárias. Um dashboard de métricas agrega informações qualitativas e quantitativas sobre as correções, possibilitando o acompanhamento da produtividade da equipe e fornecendo indicadores úteis para o refinamento dos modelos de inteligência artificial.

Link do repositório [Terravision](https://github.com/Yan-Yamim/fatec-api-4)

### Tecnologias usadas:
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" alt="spring logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="40" alt="vuejs logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg" height="40" alt="vuetify logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" height="40" alt="oracle logo"  />
</div>

---

### Contribuições Pessoais

Atuei, pela primeira vez como Product Owner, ou seja, fui responsável por toda elaboração e entendimento do produto se comunicando constantemente com o cliente. Fiz o product backlog, sprint backlog e os requisitos DoD e DoR além da documentação de instalação. Não só isso, como a equipe era reduzida para 4 pessoas, precisei atuar como desenvolvedor fullstack também, criando métodos para cadastro e listagem paginada de fazendas e usuários assim como suas respectivas páginas web.

- **Método responsável pelo cadastro de Fazendas e Usuário** <details> <summary>Ver detalhes</summary>
    Desenvolvi os endpoints RESTful <code>POST</code> nos controladores Spring Boot (<code>FazendaController</code> e <code>UsuarioController</code>) para receber dados JSON via <code>@RequestBody</code> e persistir as entidades no banco de dados utilizando JPA. Implementei validações robustas com Bean Validation (<code>@Valid</code>) para garantir a integridade dos dados, tratamento de exceções personalizadas e utilizei métodos <code>save()</code> do <code>JpaRepository</code> para operações de persistência seguras e transacionais.
  </details>
  
- **Página web que cadastra Fazenda e Usuários** <details> <summary>Ver detalhes</summary>
    Criei componentes Vue.js single-file components com composition API para os formulários de cadastro de fazendas e usuários. Utilizei <code>v-model</code> para data binding reativo, Vuelidate para validações no front-end e Axios para realizar requisições <code>POST</code> assíncronas para os endpoints da API. A interface foi desenvolvida com Vuetify para garantir consistência visual e responsividade.
  </details>
  
- **Método responsável pela listagem paginada de Fazenda e Usuário** <details> <summary>Ver detalhes</summary>
    Implementei endpoints <code>GET</code> com suporte a paginação utilizando <code>Pageable</code> do Spring Data. Configurei parâmetros de consulta para filtros opcionais, ordenação personalizável e retorno eficiente de grandes conjuntos de dados através de projeções JPA, melhorando significativamente o desempenho das listagens.
  </details>
  
- **Correção de bug envolvendo senha do perfil** <details> <summary>Ver detalhes</summary>
    Identifiquei e corrigi uma vulnerabilidade crítica onde as senhas dos usuários estavam sendo armazenadas em texto plano. Implementei hashing seguro com BCryptPasswordEncoder do Spring Security, adicionei validação de complexidade de senhas e garanti que todas as credenciais existentes fossem migradas com segurança para o novo formato criptografado.
   </details>
  
- **Toda documentação em relação ao produto** <details> <summary>Ver detalhes</summary>
    Como Product Owner, fui responsável por toda a documentação do produto, incluindo: elaboração do backlog priorizado com metodologia MoSCoW, escrita de user stories com critérios de aceitação claros, definição do sprint backlog, criação do manual do usuário e manutenção da comunicação constante com o cliente para validação de requisitos e expectativas.
  </details>

### Hard Skills

- **Git** – Utilizado diariamente para versionamento colaborativo do código-fonte, seguindo um fluxo de trabalho baseado em feature branches. Realizei code reviews através de pull requests, resolvi conflitos de merge e mantive um histórico limpo e organizado do desenvolvimento do projeto.
  
- **Java** – Linguagem principal para desenvolvimento do back-end, onde implementei a lógica de negócio, tratamento de requisições HTTP, integração com banco de dados e processamento de dados geoespaciais. Desenvolvi entidades JPA como Fazenda, Talhão e Usuário com seus respectivos relacionamentos.
  
- **Spring Boot** – Framework utilizado para construir a API RESTful completa, incluindo controladores, serviços, repositórios e configurações de segurança. Implementei injeção de dependência, transações management e tratamento global de exceções para criar uma arquitetura robusta e escalável.
  
- **PostgreSQL** – Banco de dados relacional utilizado para persistência das informações. Modelei o schema das tabelas, otimizei queries com índices estratégicos e utilizei o suporte nativo a tipos geográficos para armazenamento eficiente dos GeoJSONs.
  
- **Docker** – Empreguei para containerizar a aplicação, criando Dockerfiles personalizados para back-end, front-end e banco de dados. Utilizei docker-compose para orquestração dos serviços, garantindo consistência entre ambientes de desenvolvimento e facilitando o deployment. 
  
- **Vue.js** – Framework front-end utilizado para construir a interface web reativa. Desenvolvi componentes modulares, gerenciamento de estado com Vuex, roteamento com Vue Router e integração com a API back-end através de serviços HTTP.
  
- **Vuetify** – Biblioteca de componentes Material Design que acelerou o desenvolvimento da UI, proporcionando uma experiência consistente e responsiva across diferentes devices e browsers.
  
- **Oracle Cloud** – Utilizei a infraestrutura cloud da Oracle para hospedar a instância do banco de dados PostgreSQL, configurando backups automáticos, monitoramento de performance e políticas de segurança.

---

### Soft Skills

- Como Product Owner, mantive comunicação clara e constante com o cliente da Visiona, traduzindo requisitos técnicos complexos em linguagem acessível e garantindo alinhamento total sobre expectativas e entregas. Facilitou a comunicação entre stakeholders técnicos e não-técnicos.
  
- Colaborei efetivamente em um ambiente multifuncional, participando ativamente de reuniões de planejamento, revisões de código pareadas e sessões de troubleshooting coletivo. Promovi um ambiente de aprendizado mútuo e divisão equilibrada de tarefas.
  
- Enfrentei desafios como prazos apertados, requisitos em evolução e problemas técnicos complexos. Mantive foco nas soluções, adaptando planos quando necessário e perseverando até encontrar abordagens eficazes para cada obstáculo encontrado.

---

### <a name="jiboia"></a>5° semestre | 2/2025

**Projeto**: Jiboia  
**Empresa parceira**: Necto Systems Resolução de interseção entre meio ambiente, gestão territorial e tecnologia.

### Problema
O principal desafio na gestão de projetos modernos reside na fragmentação das informações dentro do Jira, onde o grande volume de dados brutos muitas vezes oculta gargalos operacionais e dificulta uma visão holística do progresso. Atualmente, a falta de uma ferramenta analítica centralizada obriga gestores a realizarem extrações manuais e consolidações imprecisas para entender o esforço real e a performance das equipes, resultando em uma baixa visibilidade estratégica e na dificuldade de prever desvios de cronograma. O problema central, portanto, não é a ausência de dados, mas a carência de uma estrutura que os organize de forma histórica e performática, permitindo que indicadores de andamento e dashboards de produtividade sejam gerados sem a necessidade de intervenção manual constante ou consultas complexas diretamente na API de origem.

### Solução
Para sanar essa lacuna, o Jiboia foi desenvolvido como um sistema robusto de ETL (Extração, Transformação e Carga) projetado especificamente para converter a complexidade dos dados brutos do Jira em inteligência de negócio acionável. A solução automatiza o consumo de informações via API, consolidando-as em um Data Warehouse otimizado que serve como a "fonte única da verdade" para a geração de métricas de performance e esforço. Ao traduzir o ciclo de vida das issues em dashboards detalhados e boards analíticos, o sistema oferece transparência total sobre o andamento do projeto tanto em nível macro quanto micro, permitindo que as lideranças identifiquem tendências, avaliem a velocidade das entregas e tomem decisões baseadas em dados históricos sólidos, transformando o acompanhamento de projetos em um processo fluido, visual e estratégico.

Link do Repositório: [Jiboia](https://github.com/c137santos/FATEC-API-5-SEMESTRE)

### Tecnologias usadas:
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="40" alt="vuejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg" height="40" alt="vuetify logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" height="40" alt="nginx logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker logo"  />
</div>

---

### Contribuições Pessoais

Desta vez as funções foram mais voláteis, durante a maioria do projeto atuei como desenvolvedor mas durante a sprint 2 atuei como Product Owner, isso se deve ao fato da dificuldade da organização das funções e da elaboração do projeto agora que era obrigatório implementar DevOps. Durante o período como desenvolvedor fiz a elaboração dos modelo de dados que foi um Star Schema já que usamos Data Warehouse também, a listagem dos projetos e issues existentes extraídos da api do Jira, a documentação do SonnarQube também implementei já que usamos essa ferramenta para cobertura de testes e, por fim, o plano de rastreabilidade do DevOps que através dos requisitos do cliente criar um fluxo de trabalho para que as tarefas sejam iniciadas e finalizadas sem problemas de débito-técnico ou erros de implementação.

- **Elaboração do modelo de dados** <details> <summary>Ver detalhes</summary> Desenvolvi o modelo de dados normalizado (até a 3ª Forma Normal) para servir de base sobre como vai estruturar nosso banco de dados relacional, garantindo a integridade referencial e redução de redundâncias. Além disso, para o ecossistema de Data Warehouse, projetei a arquitetura utilizando o modelo <strong>Snowflake (Floco de Neve)</strong>, normalizando as tabelas de dimensões para otimizar o armazenamento e a granularidade dos dashboards requeridos pelo cliente. </details> 
  
- **Método de listagem geral de projetos** <details> <summary>Ver detalhes</summary> No backend, fui responsável pela implementação da camada de <strong>Service</strong>, concentrando a lógica de negócio para a listagem de todos os projetos. Desenvolvi um endpoint <strong>RESTful</strong> utilizando o método <code>GET</code> para exposição desses dados. Para garantir a robustez do código, apliquei pirâmide de testes, desenvolvendo testes unitários (com foco em lógica isolada) e testes de integração para validar a comunicação com a camada de persistência. </details> 
  
- **Método responsável pela listagem Issues** <details> <summary>Ver detalhes</summary> Implementei endpoints <code>GET</code> com suporte a <strong>paginação eficiente no lado do servidor</strong> utilizando o objeto <code>Pageable</code> do Django REST Framework. Esta abordagem otimiza o consumo de memória e banda ao carregar grandes volumes de Issues. Além da configuração do método de listagem, assegurei a qualidade da entrega através de testes unitários e de integração que validam os parâmetros de paginação e filtros. </details> 
  
- **View page de exibição das Issues** <details> <summary>Ver detalhes</summary> Utilizando o framework <strong>Vue.js</strong> e a biblioteca de componentes <strong>Vuetify</strong>, desenvolvi uma interface reativa capaz de consumir a API do backend e renderizar as Issues de forma paginada e assíncrona. Implementei uma estratégia de ambiente via <strong>Docker</strong> que permite a alternância transparente entre o consumo de uma API real e uma <strong>API Mock</strong>, facilitando o desenvolvimento frontend independente do status do backend. </details>
  
- **Documentação do SonnarQube** <details> <summary>Ver detalhes</summary> Atuando no fluxo de DevOps, fui responsável pela documentação técnica e implementação da análise estática de código via <strong>SonarQube</strong>. O escopo incluiu o setup da ferramenta via containerização, a definição de <strong>Quality Gates</strong>, a parametrização de scanners para visualização de cobertura de testes e a análise crítica de <em>Technical Debt</em> (Débito Técnico) e vulnerabilidades para garantir a integridade e segurança da aplicação.  </details> 
  
- **Plano de rastreabilidade** <details> <summary>Ver detalhes</summary> No lado do DevOps, estabeleci o plano de rastreabilidade do projeto através da criação de IDs exclusivos mapeados aos requisitos funcionais. Implementei <strong>pipelines de CI/CD via GitHub Actions</strong> que automatizam a governança do repositório, validando se os commits seguem padrões predefinidos (como Conventional Commits), verificando a organização do código através de linters e garantindo a execução obrigatória da suíte de testes antes de qualquer merge.  </details> 

### Hard Skills

- **Git** – Utilizado diariamente para versionamento colaborativo do código-fonte, seguindo um fluxo de trabalho baseado em feature branches.
    
- **Github** – Utilizado diariamente para consulta do nosso kanbam e hospedagem do nosso repositório e cada branche criada durante todo o processo. Realizei code reviews através de pull requests, resolvi conflitos de merge e mantive um histórico limpo e organizado do desenvolvimento do projeto. O uso do Github Actions foi essencial, especialmente para o DevOps, onde usamos pipelines para verificação dos requisitos levantados.
  
- **Python** – Linguagem principal para desenvolvimento do back-end, onde implementei a lógica de negócio, tratamento de requisições HTTP, integração com banco de dados e regras de negócio para formação de dashboards. Foram desenvolvidas entidades como Issue, Projeto e Usuário com seus respectivos relacionamentos.
  
- **Django** – Framework utilizado para construir a API RESTful completa, incluindo views, services, models e configurações de segurança. Implementei injeção de dependência, transações management e tratamento global de exceções para criar uma arquitetura robusta e escalável.
  
- **PostgreSQL** – Banco de dados relacional utilizado para persistência das informações. Foi criado schemas diferentes com um modelo de dados padrão e outro modelo Snowflake para a produção dos dashboards. 
  
- **Docker** – Empreguei para containerizar a aplicação, criando Dockerfiles personalizados para back-end, front-end e banco de dados. Utilizei docker-compose para orquestração dos serviços, garantindo consistência entre ambientes de desenvolvimento e facilitando o deployment.
  
- **Vue.js** – Framework front-end utilizado para construir a interface web reativa. Desenvolvi componentes modulares, gerenciamento de estado com Vuex, roteamento com Vue Router e integração com a API back-end através de serviços HTTP.
  
- **Vuetify** – Biblioteca de componentes Material Design que acelerou o desenvolvimento da UI, proporcionando uma experiência consistente e responsiva across diferentes devices e browsers.
  
- **AWS** – Utilizei a infraestrutura da AWS como servidor para hospedar nossa aplicação, configurando backups automáticos, monitoramento de performance e políticas de segurança.

### Soft Skills

- Como Product Owner, mantive comunicação clara e constante com o cliente da Necto, traduzindo requisitos técnicos complexos em linguagem acessível e garantindo alinhamento total sobre expectativas e entregas. Facilitou a comunicação entre stakeholders técnicos e não-técnicos.
  
- Colaborei efetivamente em um ambiente multifuncional, participando ativamente de reuniões de planejamento, revisões de código pareadas e sessões de troubleshooting coletivo. Promovi um ambiente de aprendizado mútuo e divisão equilibrada de tarefas.
    
- Por se tratar de uma arquiterura e infraestrutura diferente da qual estava acostumado, precisei me adaptar a nova proposta com Python e Django para poder realizar o projeto da melhor forma possível.
    
- Enfrentei desafios como prazos apertados, requisitos em evolução e problemas técnicos complexos. Mantive foco nas soluções, adaptando planos quando necessário e perseverando até encontrar abordagens eficazes para cada obstáculo encontrado.

---

### <a name="pokemon"></a>6° semestre | 1/2026

**Projeto**: Thunder Stone  
**Empresa parceira**: Tecsys - Soluções para infraestrutura, nas áreas de TV Digital & Radiofrequência, Smart grid e telecomunicações

### Problema
Diferente da transmissão, a distribuição de energia apresenta uma complexidade técnica elevada devido à vasta capilaridade das redes. Essa barreira de dados reflete diretamente na operação comercial da Tecsys. Hoje, o processo de prospecção é altamente manual e custoso. Por exemplo, a equipe técnica precisa se deslocar fisicamente até as concessionárias; é necessário realizar uma "caça" manual pelos chamados pontos ofendidos (áreas críticas de perda); a captura de dados para provar o valor da solução depende de levantamentos de campo exaustivos para, só então, montar uma apresentação personalizada. O resultado é um ciclo de venda longo, onde o cliente só percebe a necessidade da instalação dos sensores após um esforço hercúleo de demonstração técnica. A dor da Tecsys, portanto, não é a falta de tecnologia, mas a necessidade de automatizar a inteligência de dados para identificar remotamente onde o problema está, transformando dados brutos da ANEEL em oportunidades de negócio imediatas.

### Solução
A solução proposta atua diretamente na eliminação do gargalo operacional da Tecsys ao converter o vasto e complexo volume de dados brutos da base BDGD da ANEEL em uma ferramenta de inteligência geográfica automatizada. Ao padronizar o cálculo de perdas e processar informações que antes exigiam levantamentos de campo exaustivos, a plataforma substitui a prospecção manual por um diagnóstico remoto e instantâneo, capaz de identificar os pontos mais críticos das redes de distribuição sem a necessidade de deslocamento físico inicial. Através de visualizações estratégicas, como mapas de calor e rankings de trechos ofendidos, o sistema transforma a barreira técnica da capilaridade das redes em uma vantagem comercial, permitindo que a equipe de vendas apresente provas de valor personalizadas e embasadas em dados reais de forma ágil. Assim, a tecnologia reduz drasticamente o ciclo de venda e o custo de aquisição de clientes, transmutando dados não estruturados em oportunidades de negócio imediatas e demonstrando a necessidade da instalação de sensores de forma visual e incontestável para as concessionárias.

Link do Repositório: [Thunder-Stone](https://github.com/c137santos/FATEC-API-6-SEMESTRE)

### Tecnologias usadas:
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-plain.svg" height="40" alt="fastapi logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo"  />
  <img width="12" />
</div>

### Contribuições Pessoais

- **Template do back e frontend** <details> <summary>Ver detalhes</summary> Fui responsável por criar o template inicial da aplicação, isto é, criar a infraestrtura inicial da API. No backend instalei e configurei o gerenciador de pacotes UV, além de usá-lo para implementar o FastApi e todas as bibliotecas usadas (como Sqlalchemy, pytest, pandas e etc...). Para o frontend, usei uma versão menor do Vue.Js chamda petit-vue (ou minivue), não foi necessário instalar node.js ou o npm porque foi necessário importar um comando no arquivo .html </details>
  
- **Configuração do Docker** <details> <summary>Ver detalhes</summary> Para a infraestrutura da API funcionar para todos os integrantes, usei o Docker para virtualizar o ambiente e também poder instalar ferramentas que faltavam. Além de usar a imagem Python, foi necessário implementar as imagens do PostgresSQL e o MongoDB, já que serão os dois bancos de dados que usamos. Postgres para armazenamento de usuário e concessionários e o Mongo para armazenar todos os dados contidos da ANEEL. </details> 
  
- **Cálculo do TAM** <details> <summary>Ver detalhes</summary> Um dos tratamentos de dados das concessionárias que precisamos fazer foi o cálculo do TAM, que consistia em montar um gráfico com a soma (em quilômetros) da extensão dos fios de média tensão que circulava em determinados trechos. Para fazer esse cálculo, peguei a pasta .gdb da ENEL-GO e extrai o comprimento de cada conjunto, realizei a soma e dividi por 100 (para estar em quiômetros), também foi necessário extrair e juntar o nome dos trechos para que a tabela fosse mais coerente. Com o cálculo feito, fiz o ranking em ordem decrescente do trecho com maior extensão para o de menor extensão e um gráfico para traduzir esse ranking de forma mais visual. </details>

### Hard Skills

- **Git** – Utilizado diariamente para versionamento colaborativo do código-fonte, seguindo um fluxo de trabalho baseado em feature branches.
    
- **Github** – Utilizado para hospedagem do nosso repositório e cada branche criada durante todo o processo. Realizei code reviews através de pull requests, resolvi conflitos de merge e mantive um histórico limpo e organizado do desenvolvimento do projeto. O uso do Github Actions foi essencial, onde usamos pipelines para verificação de testes.
  
- **Python** – Linguagem principal para desenvolvimento do back-end, onde implementei a lógica de negócio, tratamento de requisições HTTP, integração com banco de dados e criação de usuários com JWT.
  
- **FastApi** – Framework utilizado desenvolver as requisições HTTP e funções de integração para tornar mais otimizado o código Python.

- **PostgreSQL** – Banco de dados relacional utilizado para persistência das informações.
  
- **MongoDB** – Bando de dados não relacional que usamos para guardar os dados públicos tirados das empresas de energia do Brasil, como ANEEL, ENEL e etc...
  
- **Docker** – Empreguei para containerizar a aplicação, criando Dockerfiles personalizados para back-end, front-end e banco de dados. Utilizei docker-compose para orquestração dos serviços, garantindo consistência entre ambientes de desenvolvimento.</li> 
  
- **Vue.js** – Por se tratar de uma aplicação de frontend mais simples, usamos o mini-vue que é uma extensão nos permite usar comandos do Vue.Js sem precisar seguir toda uma estrtura de componentes, rotas e configurações para fazer o Vue em si rodar.

### Soft Skills
