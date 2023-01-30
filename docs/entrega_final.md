# Entrega Final

## Introdução

Durante o segundo semestre de 2022, o grupo 2 da disciplina Interação Humano Computador, da Universidade de Brasília/FGA, estudou, e documentou, as interações humano computador na plataforma de xadrez [Lichess](https://lichess.org). O presente artefato tem como principal objetivo sintetizar o processo desenvolvido ao longo do processo, desde as etapas de planejamento aos resultados alcançados.

## Sítio escolhido

<!-- @TODO:  -->

## Planejamento

<!-- @TODO: cronograma planejado e executado, em uma mesma tabela -->
<!-- @TODO: inserir artefatos criados na etapa de planejamento -->
<!-- @TODO: inserir síntese das atas -->

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

A análise de requisitos do projeto foi documentada nos artefatos representados na Tabela 1.
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
Tabela 1: Síntese dos artefatos de Análise de Requisitos (Fonte: autor, 2023).
</p>
</div>

</center>

### Design, Avaliação e Desenvolvimento

As atividades de Design, Avaliação e Desenvolvimento dividem-se em três níveis de detalhes, e essa etapa do processo tem por objetivo fornecer uma solução de IHC que atenda às [metas de usabilidade](analise_requisitos/metas_usabilidade.md) que foram estabelecidas durante a [Análise de Requisitos](./#analise-de-requisitos) [1].

#### Nível 1

O primeiro nível dessa etapa consiste em uma análise conceitual, e durante a execução do trabalhou essa análise esteve focada nas tarefas que o usuário irá desenvolver no sistema e suas motivações para utilizá-lo, representadas, respectivamente, pela [Análise de Tarefas](analise_requisitos/analise_tarefas.md#analise-da-tarefa-aprender-a-jogar-xadrez) e pelos [Storyboards](design_avaliacao_desenvolvimento/nivel_1/storyboard/planejamento_avaliacao.md#storyboards-desenvolvidos). Afim de certificar que as expectativas dos usuários foram alcançadas, realizou-se a avaliação dos artefatos elaborados, por meio de entrevistas com usuários do sítio [Lichess](https://lichess.org) dentro do [perfil de usuário](analise_requisitos/perfil_usuario.md) previamente determinado.

O primeiro nível do processo de design, avaliação e desenvolvimento foi documentado por meio dos artefatos presentes na Tabela 2.

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
Tabela 2: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 1)
(Fonte: autor, 2023).
</p>
</div>

</center>

#### Nível 2

Após o nível conceitual, o designer parte para a elaboração de padrões de design de IHC para a solução que está sendo concebida, que são validados por meio da avaliação de protótipos de média fidelidade. Para validar os padrões desenvolvidos durante o projeto. Optou-se pelo uso de [protótipos de papel](design_avaliacao_desenvolvimento/nivel_2/relato_resultados_prototipo_papel.md#prototipo-de-papel) para validar com o usuário os padrões de design desenvolvidos.

A Tabela 3 sintetiza os artefatos elaborados durante essa etapa do projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Planejamento da Avaliação do Protótipo de Papel](design_avaliacao_desenvolvimento/nivel_2/planejamento_avaliacao_prototipo_baixa_fidelidade.md)| Mauricio Machado | Nicolas Souza |
[Relato dos Resultados da Avaliação do Protótipo de Papel](design_avaliacao_desenvolvimento/nivel_2/relato_resultados_prototipo_papel.md)| Lucas Macedo e Lucas Gabriel | Davi Silva|

<div style="text-align: center">
<p>
Tabela 3: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 2)
(Fonte: autor, 2023).
</p>
</div>

</center>

#### Nível 3

No último nível da etapa de Design, Avaliação e Desenvolvimento, o designer elabora o projeto detalhado da interface, tendo como base os requisitos identificados na [Análise de Requisitos](./#analise-de-requisitos), esse projeto foi representado por meio de um [Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/resultados_alta_fidelidade.md#prototipo-de-alta-fidelidade) e em seguida a interface foi avaliada com a participação de usuários, por meio de um teste de usabilidade.

A Tabela 4 sintetiza os artefatos desenvolvidos durante essa etapa do projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Planejamento da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/planejamento_alta_fidelidade.md) |  Nicolas Souza | Davi Silva |
[Planejamento do Relato de Resultados da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/planejamento_relato_resultados_alta_fidelidade.md)  | Lucas Gabriel | Nicolas Souza  |
[Relato dos Resultados da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/resultados_alta_fidelidade.md) |  Nicolas Souza | Lucas Macedo |

<div style="text-align: center">
<p>
Tabela 4: Síntese dos artefatos de Design, Avaliação e Desenvolvimento (nível 3)
(Fonte: autor, 2023).
</p>
</div>

</center>

## Síntese das Avaliações

Durante a execução do projeto, foram elaboradas algumas avaliações de protótipos e modelos conceituais (storyboard e análise de tarefas) e a tabela 5 sintetiza a aplicação dessas atividades.

| Avaliação | Metodologia | Avaliador(es) | Número de Participantes | Resultados |
| - | - | - | - | - |
| Avaliação do Storyboard | Entrevista | Nicolas Souza  | 1 | [Relato dos Resultados da Avaliação do Storyboard](design_avaliacao_desenvolvimento/nivel_1/storyboard/relato_resultados.md)|
| Avaliação da Análise de Tarefas | Entrevista |  Davi Silva  | 1 | [Relato dos Resultados da Avaliação da Análise de Tarefas](design_avaliacao_desenvolvimento/nivel_1/analise_tarefas/relato_resultados_analise.md)
| Avaliação do Protótipo de Papel | Entrevista | Lucas Macedo e Lucas Gabriel  | 1 | [Relato dos Resultados da Avaliação do Protótipo de Papel](design_avaliacao_desenvolvimento/nivel_2/relato_resultados_prototipo_papel.md)|
| Avaliação do Protótipo de Alta Fidelidade | Teste de Usabilidade |   Nicolas Souza  | 3 | [Relato dos Resultados da Avaliação do Protótipo de Alta Fidelidade](design_avaliacao_desenvolvimento/nivel_3/resultados_alta_fidelidade.md)

<!-- @TODO: uma tabela com todas as avaliações dos protótipos contendo o nome dos avaliadores, número de participantes, e metodologia utilizada (entrevista, teste de usabilidade) -->

## Técnicas Utilizadas

<!-- @TODO: incluir uma tabela com as técnicas utilizadas ao longo do projeto, em quais artefatos foram usadas e quais são os autores/revisores desses artefatos  -->

## Verificação dos Artefatos

<!-- @TODO: incluir a metodologia usada na verificação, e uma tabela contendo quem fez cada checklist e cada verificação -->

## Resultados Alcançados

<!-- @TODO: incluir os resultados alcançados com a execução do projeto, as facilidades e dificuldades  -->

## Bibliografia

[1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

## Histórico de Versão

| Versão | Data  | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ----- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 29/01/2023      | Criação da versão inicial do documento contendo introdução, ciclo de vida e estrutura para inserção das demais seções.  | Nicolas Souza   |               |
