# Metas de Usabilidade

## Introdução

Durante a fase de Análise de Requisitos do [processo de design](../planejamento/processo_de_design.md) são definidas as metas de usabilidade. A definição é feita com base no [perfil do usuário](./perfil_usuario.md), [análise de tarefas](analise_tarefas.md), possibilidades e limitações da [plataforma](#plataforma-do-sistema) em que o sistema será executado e [princípios gerais de design](principios_gerais.md) em IHC ([1]).

O [guia de estilo](guia_de_estilo.md) auxilia a verificação das metas de usabilidade e servirá de apoio durante as etapas da fase de design, avaliação e desenvolvimento. A definição das metas de usabilidade propostas no trabalho, baseiam-se também na engenharia de usabilidade de Nielsen.

## Plataforma do sistema

O sistema lichess é disponibilizado para dispositivos móveis e na forma de aplicação web executável em navegadores de internet. As metas definidas no presente documento visam a utilização da aplicação web nos principais navegadores de internet (Google Chrome, Firefox, Safari e Microsoft Edge) em suas versões mais atuais no período de execução do projeto (Outubro de 2022 a Fevereiro de 2023).

## Definição das metas

De acordo com as normas [2] e [3], a usabilidade pode ser definida das seguintes formas, respectivamente:

> Um conjunto de atributos relacionados com o esforço necessário para o uso de um sistema
> interativo, e relacionados com a avaliação individual de tal uso, por um conjunto específico de
> usuários.

> O grau em que um produto é usado por usuários específicos para atingir objetivos específicos
> com eficácia, eficiência e satisfação em um contexto de uso específico.

Para além da visão técnica, também vale ressaltar que a usabilidade está intimamente ligada a capacidade cognitiva, perceptiva e motora dos usuários empregada durante as interações ([1]).

A definição das metas de usabilidade teve como base a análise de requisitos, como um todo, as normas supracitadas e os fatores de usabilidade de Nielsen.

### Eficácia

Um produto é **eficaz** quando realiza as atividades propostas com sucesso, conforme o esperado.

### Eficiência

A eficiência está relacionada a quantidade de tempo e recursos desprendidos na execução de uma tarefa com sucesso, quanto menor esse quantidade, maior a eficiência.

### Segurança no uso

A segurança no uso está relacionada ao grau de proteção de um sistema contra condições desfavoráveis ou perigosas para o usuário ([1]). Um sistema deve fornecer segurança ao usuário durante as interações, minimizando as possibilidades de erros e fornecendo saídas para que ele consiga se recuperar de erros, caso ocorram.

### Facilidade de aprendizado

A facilidade de aprendizado se refere ao tempo e esforço necessários para que o usuário aprenda a utilizar o sistema com determinado nível de competência e desempenho [1].

### Facilidade de recordação

A facilidade de recordação diz respeito ao esforço cognitivo do usuário necessário para lembrar como interagir com a interface do sistema interativo, conforme aprendido anteriormente ([1]).

### Satisfação do usuário

A satisfação do usuário está relacionado às emoções e sentimentos do usuário durante as interações com o sistema, sua avaliação ocorre de maneira subjetiva.

## Requisitos a partir das metas de usabilidade

Abaixo temos uma tabela que apresenta os requisitos identificados a partir das metas de usabilidade do projeto

| ID  |                                                      Descrição                                                       |
| :-: | :------------------------------------------------------------------------------------------------------------------: |
| MU1 |                       Sistema deve permitir acesso a uma funcionalidade em 4 cliques ou menos                        |
| MU2 |      Porcentagem de cliques na seção de ajuda em relação ao tamanho da base de usuários deve ser menor que 30%       |
| MU3 |                             Tempo de sessão média de usuário deve ser maior que uma hora                             |
| MU4 |                         Coleta de NPS do sistema deve ter média promotora maior ou igual a 9                         |
| MU5 | Tempo médio para iniciar uma partida deve ser menor que um minuto (Contando a partir da inicialização do aplicativo) |
| MU6 |                        Sistema deve fornecer notificações push sobre novos acessos ao sistema                        |

<div style="text-align: center">
<p> Tabela 1: Requisitos de usabilidade (Fonte: Mauricio Machado, 2023).</p>
</div>

## Bibliografia

[1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

[2] Norma ISO/IEC 9126 (2001)

[3] Norma ISO 9241-11 (2019)

## Histórico de Versão

| Versão | Data       | Descrição                                                                | Autor(es)        | Revisor(es)      |
| ------ | ---------- | ------------------------------------------------------------------------ | ---------------- | ---------------- |
| `1.0`  | 09/12/2022 | Criação do documento.                                                    | Nicolas Souza    | Maurício Machado |
| `1.1`  | 24/01/2023 | Resolver consertos identificados pelo verificação do Ponto de Controle 3 | Mauricio Machado | Lucas Macedo     |
| `1.2`  | 26/01/2023 | Alteração requisitos de Usabilidade                                      | Mauricio Machado | -                |
