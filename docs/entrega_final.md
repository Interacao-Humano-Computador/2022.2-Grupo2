# Entrega Final

## Introdução

Durante o segundo semestre de 2022, o grupo 2 da disciplina Interação Humano Computador, da Universidade de Brasília/FGA, estudou, e documentou, as interações humano computador na plataforma de xadrez [Lichess](https://lichess.org). O presente artefato tem como principal objetivo sintetizar o processo desenvolvido ao longo do processo, desde as etapas de planejamento aos resultados alcançados.

## Planejamento

Antes do início do projeto, a equipe de trabalho reuniu-se presencialmente, durante a aula de Interação Humano Computador, para definir as ferramentas de comunicação e horários das reuniões semanais. Então, durante as primeiras reuniões, foram definidas a [metodologia de trabalho](planejamento/metodologias.md), o [cronograma](planejamento/cronograma.md) e as [ferramentas](planejamento/tools.md) utilizadas durante o projeto. Além disso, cada integrante fez a [avaliação heurística de um sítio](planejamento/sites_avaliados.md), que serviu de base para a definição do [sítio escolhido](planejamento/app_selected.md).

A Tabela 1 sintetiza os artefatos referentes ao planejamento da equipe, que elaborados ao longo do semestre.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Sítio Selecionado](planejamento/app_selected.md) | Lucas Gabriel  | Nicolas Souza |
[Cronograma](planejamento/cronograma.md)|  Maurício Machado | Nicolas Souza |
[Cronograma realizado](planejamento/cronograma_realizado.md) | Mauricio Machado | Nicolas Souza |
[Metodologias](planejamento/metodologias.md) | Davi Silva e Nicolas Souza  | Maurício Machado |
[Processo de Design](planejamento/processo_de_design.md)  | Nicolas Souza | Davi Silva |
[Sítios Avaliados](planejamento/sites_avaliados.md)                                           | Nicolas Souza | Davi Silva    |
[Avaliação do sítio: Age Telecom](planejamento/sítios_avaliados/resultados_age_telecom.md)| Mauricio Machado | Nicolas Souza  |
[Avaliação do sítio: Lichess](planejamento/sítios_avaliados/resultados_lichess.pdf) | Lucas Gabriel | Nicolas Souza  |
[Avaliação do sítio: Eleições - TSE](planejamento/sítios_avaliados/resultados_tse.md)| Nicolas Souza | Mauricio Machado    |
[Ferramentas](planejamento/tools.md) | Lucas Macedo  | Nicolas Souza |
[Ata da reunião (01/11/2022)](atas/ata_01_11.md)        | Nicolas Souza |  Lucas Gabriel  |
[Ata da reunião (10/11/2022)](atas/ata_10_11.md)              | Lucas Macedo  |   Nicolas Souza  |
[Ata da reunião (15/11/2022)](atas/ata_15_11.md)             | Nicolas Souza |    Maurício     |
[Ata da reunião (22/11/2022)](atas/ata_22_11.md)             |  Davi Silva   | Lucas Macedo |
[Ata da reunião (29/11/2022)](atas/ata_29_11.md) | Lucas Macedo | Lucas Gabriel |
[Ata da reunião (06/12/2022)](atas/ata_06_12.md) | Mauricio Machado | Lucas Macedo |
[Ata da reunião (13/12/2022)](atas/ata_13_12.md)              |  Davi Silva   |  Nicolas Souza   |
[Ata da reunião (20/12/2022)](atas/ata_20_12.md) | Lucas Gabriel |    Davi     |
[Ata da reunião (03/01/2023)](atas/ata_03_01.md)              |  Davi Silva   |  Lucas Gabriel   |
[Ata da reunião (18/01/2023)](atas/ata_18_01.md)    | Nicolas| Lucas Gabriel |
[Ata da reunião (25/01/2023)](atas/ata_25_01.md) |   Davi    | Lucas Gabriel |

<div style="text-align: center">
<p> Tabela 1: Síntese dos artefatos de Planejamento (Fonte: autor, 2023).</p>
</div>

</center>

<!-- @TODO: cronograma planejado e executado, em uma mesma tabela -->

## Ferramentas

<!-- @TODO: incluir quais ferramentas foram utilizadas em quais artefatos, aproveitar pra refatorar o arquivo de ferramentas pra remover as que não foram usadas e incluir as que foram e não estão lá -->

## Ciclo de Vida

A Engenharia de Usabilidade de Mayhew (Figura 1) reúne e organiza diferentes atividades na área de Interação Humano Computador, orientando o designer por uma direção interativa [1]. Por meio desse ciclo de vida, é possível, por meio de atividades bem detalhadas, conhecer o perfil do usuário do site, e só então partir para uma etapa de design, sempre apoiada na avaliação, iterando por prototipações em diversos níveis. Dessa forma, durante todas as etapas do ciclo a interação entre as fases do projeto mostra-se presente.

A definição deste ciclo de vida para o projeto levou em consideração os fatores supracitados, o nível de detalhamento das atividades de cada fase e o processo de aprendizagem dos estudantes do grupo. Dessa forma, o [cronograma](planejamento/cronograma.md) foi elaborado de acordo com as atividades de **análise de requisitos** e **design, avaliação e desenvolvimento**. Dada a natureza do projeto, as atividades de **instalação** foram executadas juntamente com a análise de requisitos, pois o produto já está finalizado.

<center>
![Ciclo de vida Mayhew](img/planejamento/processo_de_design/ciclo-de-vida-mayhew.png)

<div style="text-align: center">
<p> Figura 1: Ciclo de vida da Mayhew (Fonte: [1]).</p>
</div>
</center>

### Análise de Requisitos

Na fase de análise de requisitos são definidas as [metas de usabilidade](analise_requisitos/metas_usabilidade.md) com base no [perfil dos usuários](analise_requisitos/perfil_usuario.md), [análise de tarefas](analise_requisitos/analise_tarefas.md), possibilidades e limitações da plataforma em que o sistema será executado e princípios gerais de design de IHC. Nesse processo, as [metas de usabilidade](analise_requisitos/metas_usabilidade.md) costumam ser representadas em [guias de estilos](analise_requisitos/guia_de_estilo.md) para auxiliar sua verificação durante as demais atividades do processo [1].

A análise de requisitos do projeto foi documentada nos artefatos representados na Tabela 2.
<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
| [Análise de Tarefas](analise_requisitos/analise_tarefas.md) |Nicolas Souza | Lucas Macedo
| [Aspectos Éticos](analise_requisitos/aspectos_eticos.md) | Lucas Gabriel | Davi Silva
| [Cenários](analise_requisitos/cenarios.md) | Lucas Gabriel | Nicolas Souza
| [Guia de Estilo](analise_requisitos/guia_de_estilo.md) | Lucas Macedo e Lucas Gabriel | Nicolas Souza
| [Mapa de Empatia](analise_requisitos/mapa_empatia.md) | Lucas Macedo | Nicolas Souza
| [Metas de Usabilidade](analise_requisitos/metas_usabilidade.md) | Maurício Machado | Nicolas Souza
| [Perfil dos Usuários](analise_requisitos/perfil_usuario.md) | Maurício Machado | Lucas Macedo
| [Personas](analise_requisitos/personas.md) | Maurício Machado | Lucas Macedo
| [Princípios Gerais do Projeto](analise_requisitos/principios_gerais.md) | Davi Silva | Lucas Macedo

<div style="text-align: center">
<p>
Tabela 2: Síntese dos artefatos de Análise de Requisitos (Fonte: autor, 2023).
</p>
</div>

</center>

### Design, Avaliação e Desenvolvimento

As atividades de Design, Avaliação e Desenvolvimento dividem-se em três níveis de detalhes, e essa etapa do processo tem por objetivo fornecer uma solução de IHC que atenda às [metas de usabilidade](analise_requisitos/metas_usabilidade.md) que foram estabelecidas durante a [Análise de Requisitos](./#analise-de-requisitos) [1].

#### Nível 1

O primeiro nível dessa etapa consiste em uma análise conceitual, e durante a execução do trabalhou essa análise esteve focada nas tarefas que o usuário irá desenvolver no sistema e suas motivações para utilizá-lo, representadas, respectivamente, pela [Análise de Tarefas](analise_requisitos/analise_tarefas.md#analise-da-tarefa-aprender-a-jogar-xadrez) e pelos [Storyboards](design_avaliacao_desenvolvimento/nivel_1/storyboard/planejamento_avaliacao.md#storyboards-desenvolvidos). Afim de certificar que as expectativas dos usuários foram alcançadas, realizou-se a avaliação dos artefatos elaborados, por meio de entrevistas com usuários do sítio [Lichess](https://lichess.org) dentro do [perfil de usuário](analise_requisitos/perfil_usuario.md) previamente determinado.

O primeiro nível do processo de design, avaliação e desenvolvimento foi documentado por meio dos artefatos presentes na Tabela 3.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Planejamento da Avaliação do Storyboard](design_avaliacao_desenvolvimento/nivel_1/storyboard/planejamento_avaliacao.md) | Nicolas | Lucas Gabriel |
[Planejamento do Relato dos Resultados da Avaliação do Storyboard](design_avaliacao_desenvolvimento/nivel_1/storyboard/planejamento_relato.md) | Nicolas Souza | Lucas Gabriel   |
[Relato dos Resultados da Avaliação do Storyboard](design_avaliacao_desenvolvimento/nivel_1/storyboard/relato_resultados.md)| Nicolas Souza |  Mauricio Machado  
[Planejamento da Avaliação da Análise de Tarefas](design_avaliacao_desenvolvimento/nivel_1/analise_tarefas/planejamento_avaliacao.md)  | Lucas Gabriel | Nicolas Souza   |
[Planejamento do relato de Resultados da Avaliação da Análise de Tarefas](design_avaliacao_desenvolvimento/nivel_1/analise_tarefas/planejamento_resultado_analise_tarefas.md)  | Maurício Machado | Nicolas Souza |
[Relato dos Resultados da Avaliação da Análise de Tarefas](design_avaliacao_desenvolvimento/nivel_1/analise_tarefas/relato_resultados_analise.md) | Davi Silva | Lucas Gabriel |

<div style="text-align: center">
<p>
Tabela 3: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 1)
(Fonte: autor, 2023).
</p>
</div>

</center>

#### Nível 2

Após o nível conceitual, o designer parte para a elaboração de padrões de design de IHC para a solução que está sendo concebida, que são validados por meio da avaliação de protótipos de média fidelidade. Para validar os padrões desenvolvidos durante o projeto. Optou-se pelo uso de [protótipos de papel](design_avaliacao_desenvolvimento/nivel_2/relato_resultados_prototipo_papel.md#prototipo-de-papel) para validar com o usuário os padrões de design desenvolvidos.

A Tabela 4 sintetiza os artefatos elaborados durante essa etapa do projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Planejamento da Avaliação do Protótipo de Papel](design_avaliacao_desenvolvimento/nivel_2/planejamento_avaliacao_prototipo_baixa_fidelidade.md)| Mauricio Machado | Nicolas Souza |
[Relato dos Resultados da Avaliação do Protótipo de Papel](design_avaliacao_desenvolvimento/nivel_2/relato_resultados_prototipo_papel.md)| Lucas Macedo e Lucas Gabriel | Davi Silva|

<div style="text-align: center">
<p>
Tabela 4: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 2)
(Fonte: autor, 2023).
</p>
</div>

</center>

#### Nível 3

No último nível da etapa de Design, Avaliação e Desenvolvimento, o designer elabora o projeto detalhado da interface, tendo como base os requisitos identificados na [Análise de Requisitos](./#analise-de-requisitos), esse projeto foi representado por meio de um [Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/resultados_alta_fidelidade.md#prototipo-de-alta-fidelidade) e em seguida a interface foi avaliada com a participação de usuários, por meio de um teste de usabilidade.

A Tabela 5 sintetiza os artefatos desenvolvidos durante essa etapa do projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Planejamento da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/planejamento_alta_fidelidade.md) |  Nicolas Souza | Davi Silva |
[Planejamento do Relato de Resultados da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/planejamento_relato_resultados_alta_fidelidade.md)  | Lucas Gabriel | Nicolas Souza  |
[Relato dos Resultados da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/resultados_alta_fidelidade.md) |  Nicolas Souza | Lucas Macedo |

<div style="text-align: center">
<p>
Tabela 5: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 3)
(Fonte: autor, 2023).
</p>
</div>

</center>

## Síntese das Avaliações

Durante a execução do projeto, foram elaboradas algumas avaliações de protótipos e modelos conceituais (storyboard e análise de tarefas) e a tabela 5 sintetiza a aplicação dessas atividades.

<center>

| Avaliação | Metodologia | Avaliador(es) | Número de Participantes | Resultados |
| - | - | - | - | - |
| Avaliação do Storyboard | Entrevista | Nicolas Souza  | 1 | [Relato dos Resultados da Avaliação do Storyboard](design_avaliacao_desenvolvimento/nivel_1/storyboard/relato_resultados.md)|
| Avaliação da Análise de Tarefas | Entrevista |  Davi Silva  | 1 | [Relato dos Resultados da Avaliação da Análise de Tarefas](design_avaliacao_desenvolvimento/nivel_1/analise_tarefas/relato_resultados_analise.md)
| Avaliação do Protótipo de Papel | Entrevista | Lucas Macedo e Lucas Gabriel  | 1 | [Relato dos Resultados da Avaliação do Protótipo de Papel](design_avaliacao_desenvolvimento/nivel_2/relato_resultados_prototipo_papel.md)|
| Avaliação do Protótipo de Alta Fidelidade | Teste de Usabilidade |   Nicolas Souza  | 3 | [Relato dos Resultados da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/resultados_alta_fidelidade.md)

<div style="text-align: center">
<p>
Tabela 6: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 3)
(Fonte: autor, 2023).
</p>
</div>

</center>

## Técnicas Utilizadas

<!-- @TODO: incluir uma tabela com as técnicas utilizadas ao longo do projeto, em quais artefatos foram usadas e quais são os autores/revisores desses artefatos  -->

## Verificação dos Artefatos

A verificação será feita por meio da inspeção, com base na proposta de Fagan [3], utilizando um checklist de erros mais comuns que podem ser identificados em projetos, tomando como base os projetos anteriores da disciplina de [Interação Humano Computador](https://github.com/Interacao-Humano-Computador), os critérios do Plano de Ensino [2], a bibliografia da disciplina [1] e os feedbacks dos monitores. A Tabela 7 sintetiza os responsáveis pela elaboração dos checklists para cada artefato, nos artefatos de planejamento, e execução das verificações, nos artefatos de resultados.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
| [Verificação PC1 - Planejamento](verificacao_validacao/pc1-planejamento.md) |  Davi | Maurício |
| [Verificação PC1 - Resultados](verificacao_validacao/pc1-resultados.md)  | Davi      | Mauricio |
| [Verificação PC2 - Planejamento](verificacao_validacao/pc2-planejamento.md) | Nicolas Souza | Lucas Gabriel |
| [Verificação PC2 - Resultados](verificacao_validacao/pc2-resultados.md)| Nicolas Souza | Lucas Gabriel |
| [Verificação PC3 - Planejamento](verificacao_validacao/pc3-planejamento.md) |  Mauricio Machado |    Davi     |
| [Verificação PC3 - Resultados](verificacao_validacao/pc3-resultados.md) | Mauricio Machado |     Davi     |
| [Verificação PC4 - Planejamento](verificacao_validacao/pc4-planejamento.md) | Lucas Gabriel | Nicolas Souza   |
| [Verificação PC4 - Resultados](verificacao_validacao/pc4-resultados.md) | Lucas Gabriel | Nicolas Souza   |
| [Verificação PC5 - Planejamento](verificacao_validacao/pc5-planejamento.md)  | Lucas Macedo | Lucas Gabriel |
| [Verificação PC5 - Resultados](verificacao_validacao/pc5-resultados.md) |  Lucas Macedo | Lucas Gabriel |
| [Verificação PC7 - Planejamento](verificacao_validacao/pc7-planejamento.md)  | Lucas Gabriel | Lucas Macedo |
| [Verificação PC7 - Resultados](verificacao_validacao/pc7-resultados.md) | Lucas Gabriel | Nicolas Souza   |

<div style="text-align: center">
<p>
Tabela 7: Síntese dos artefatos de Verificação (Fonte: autor, 2023).
</p>
</div>

</center>

## Resultados Alcançados

<!-- @TODO: incluir os resultados alcançados com a execução do projeto, as facilidades e dificuldades  -->

## Bibliografia

[1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
[2] Plano de Ensino da disciplina Interação Humano Computador.
[3] Gerência e Qualidade de Software - Aula 06 - Técnica de revisão – UNIVESP<br/>

## Histórico de Versão

| Versão | Data  | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ----- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 29/01/2023 | Criação da versão inicial do documento contendo introdução, ciclo de vida e estrutura para inserção das demais seções.  | Nicolas Souza   |               |
| `1.1`  | 30/01/2023 | Inclusão das seções de planejamento, síntese das avaliações e verificação dos artefatos |   Nicolas Souza |
