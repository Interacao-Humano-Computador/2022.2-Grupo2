# Metodologia

## Introdução

Nossa equipe contou com diferentes metodologias as quais de certa forma integram e agilizam nosso processo de desenvolvimento como um todo. É correto observar, que esse documento tem como objetivo informar sobre nossas metodologias em diferentes situações, e de certa forma,explicar como nosso time se comunicou e trabalhou durante todo o processo.  

## Framework DECIDE

É utilizado para orientar o planejamento, a execução e a análise de tarefase de uma avaliação de IHC. As atividades do framework são interligadas e executadas iterativamente,
à medida que o avaliador articula os objetivos da avaliação, os dados e recursos disponíveis. Então quando o avaliador descobre uma necessidade de modificar os rumos da avaliação por algum motivo, as demais atividades são afetadas. O framework DECIDE é descrito da seguinte forma:

### D - Determinar

Determinar os objetivos da avaliação de IHC. O avaliador deve determinar os objetivos gerais da avaliação e identificar por que e para quem tais objetivos são importantes. O restante do planejamento da avaliação, sua execução e a apresentação dos resultados serão orientados por esses objetivos.

### E - Explorar

Explorar perguntas a serem respondidas com a avaliação. Para cada objetivo definido, o avaliador deve elaborar perguntas específicas a serem respondidas durante avaliação. Essas perguntas são responsáveis por operacionalizar a investigação e o julgamento de valor a serem realizados. Elas devem considerar o perfil dos usuários-alvo e suas atividades.

### C - Escolher (Choose)

Escolher (Choose) os métodos de avaliação a serem utilizados. O avaliador deve escolher os métodos mais adequados para responder as perguntas e atingir os objetivos esperados, considerando também o prazo, o orçamento, os equipamentos disponíveis e o grau de conhecimento e experiência dos avaliadores.

### I - Identificar 

Identificar e administrar as questões práticas da avaliação. Existem muitas questões práticas envolvidas numa avaliação de IHC, como, por exemplo, o recrutamento dos usuários que participarão da avaliação, a preparação e o uso dos equipamentos necessários, os prazos e o orçamento disponíveis, além da mão-de-obra necessária para conduzir a avaliação.

### D - Decidir

Decidir como lidar com as questões éticas. Sempre que usuários são envolvidos numa avaliação, o avaliador deve tomar os cuidados éticos necessários. Os participantes da avaliação devem ser respeitados e não podem ser prejudicados direta ou indiretamente, nem durante os experimentos, nem após a divulgação dos resultados da avaliação.

### E - Avaliar (Evaluate)

Avaliar, interpretar e apresentar os dados. O avaliador precisa estar atento a alguns aspectos da avaliação realizada antes de tirar conclusões e divulgar resultados. Ele deve considerar: o grau de confiabilidade dos dados a validade externa do estudo e a validade ecológica do estudo.

## XP (eXtreme Programming)

O método XP é uma metodologia ágil e pode ser aplicada para otimizar processos e gerar valor ao cliente desejado. Nós usamos também, o método XP pois, de maneira direta, ele tem como objetivo desenvolver sistemas de qualidade, com um interação mais dinâmica e acessível com o cliente e testagem de ciclos de desenvolvimento rápidos e de maneira constante. Nós adaptamos o modelo ao nosso contexto para que dessa forma pudéssemos aproveitar de 100% do processo.

### Refatoração

Nossa equipe, de forma dinâmica e constante, busca melhorar e otimizar o projeto, deixando-o mais claro, com menos possibilidade de erros e de duplicação de processos, a partir de revisões e reuniões.

### Propriedade coletiva

Com o objetivo de tornar o projeto mais dinâmico e de certa forma leve para os membros, as nossas atividades são dividas de maneira que tenha um desenvolvedor e um Revisor(es) para que seja evitado envios e conclusões com erros. No processo, de maneira constante, nós debatemos a maioria das decisões em grupo principalmente quando o tema ou questão é importante e pertinente a todos. Ademais, nas outras atividades consideradas "chave" para o processo de desenvolvimento, nós nos dedicamos na realização a tarefa de maneira coletiva para que possamos assim, ter um pensamento comum e cada membro sinta-se integrado e influente dentro do projeto.

## Proposta de Comunicação

Com o intuito de nos organizarmos e evitar problemas e divergências com as entregas das tarefas, nós nos planejamos em como seria nosso plano de comunicação.

Os membros tem acesso a praticamente todas as plataformas disponíveis e essenciais de comunicação que nós planejamos ter durante o processo de desenvolvimento, são elas: Teams, telegram, github, google workspace e discord.

As tarefas foram geridas a partir de issues e pull requests e de maneira técnica e rápida nos comunicamos a partir de comentários em cada canal.

Os membros da equipe usaram também o telegram, o qual é, de certa forma, um meio de comunicação eficiente para troca de informações rápidas e avisos de novas atualizações e mudanças acerca do projeto, bem como também, tira dúvidas e esclarecimentos.

## Encontros semanais

Além de todos os meios de comunicação por mensagem rápidas e tarefas do git, nós nos reunimos toda semana nas terças-feira às 20 horas da noite na plataforma "Teams", para alinharmos nossas questões acerca do projeto e também colocarmos nossas ideias em sincronia com os demais membros da equipe. Ademais, organizamos nosso cronograma e planejamos as tarefas da próxima semana, e se de alguma forma haver alguma tarefa atrasada, colocamos como preferência e como equipe, ajudamos a terminá-la da maneira mais breve possível.

## SCRUM

Afim de assegurar uma quantidade consistente e rápida de entregas, a metodologia ágil SCRUM foi adotada para organização do tempo do time. Foi definido o timebox de uma semana para cada sprint, iniciado e finalizado pelas reuniões semanais nas terças-feiras às 20:00.

As reuniões semanais têm como principais objetivos a realização de um  momento de review (_sprint review_) da sprint finalizada e organização das tarefas da sprint que se inicia (_sprint planning_). A atribuição das tarefas foi feita no início do projeto e encontra-se disponível no [cronograma](/docs/planejamento/cronograma.md), sendo assim, em cada _sprint planning_ será verificado com cada integrante a possibilidade de realizar a entrega à qual ele foi designado.

A organização das tarefas será feita por meio da criação de _issues_ e a revisão dos artefatos será feita durante o _pull request_ referente à cada funcionalidade adicionada. Dessa forma é possível manter uma rastreabilidade das alterações e revisões efetuadas.

## Políticas

### Política de _branches_

As branches devem ser nomeadas de acordo com a _issue_ correspondente, seguindo o seguinte padrão:
`git checkout -b "[tipo]/#issue-descrição`

Onde `tipo` diz respeito ao tipo de _issue_: _feat_ (funcionalidade), _refac_ (refatoração) ou _fix_ (conserto).

> Exemplo:
>
> A branch referente à issue `#3 feature: metodologias` pode ter o nome: `feat/3-metodologias`

### Política de _commits_

As mensagens dos _commits_ devem seguir o padrão:

`git commit -m "#issue descrição`

> Exemplo:
>
> O _commit_ referente a criação do arquivo `metodologias.md` pode ter a mensagem `#3 cria documento de metodologias`

## Bibliografia

[1] Bourque and R.E. Fairley, eds., Guide to the Software Engineering Body of Knowledge, Version 3.0, IEEE Computer Society, 2014; www.swebok.org.
[2] Barbosa e Silva, Planejamento de avaliação de IHC;

## Histórico de Versão

| Versão |    Data    |         Descrição         |         Autor(es)          | Revisor(es) |
| :----: | :--------: | :-----------------------: | :------------------------: | :---------: |
| `1.0`  | 18/11/2022 |   Criação do documento    | Davi Silva e Nicolas Souza |  Maurício   |
| `1.1`  | 26/01/2023 | Padronização do documento | Davi Silva e Nicolas Souza |  Maurício   |
