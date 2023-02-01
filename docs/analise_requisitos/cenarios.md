# Cenários

## Introdução

Cenários são descrições evolutivas de situações em um ambiente composto por um conjunto ordenado de interações entre seus participantes, realizadas por usuários ou sistemas externos [2]. Diante disso, os cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos [2]. Portanto, é uma estratégia para elicitar a parte comportamental do software[1].

## Modelo de Cenário

Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste documento será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente [2], tal modelo pode ser observado a seguir na Tabela 1.

| Elemento   | Descrição      |
| ---------- | ----------- |
| Objetivo   | Finalidade do cenário       |
| Contexto   | Descrição de pré-condições, local (físico) e tempo    |
| Recursos   | Objetos passivos com os quais os atores interagem     |
| Ator       | Pessoa ou estrutura organizacional       |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário     |
| Exceção    | Tratamento para uma situação excepcional ou de erro   |

<div style="text-align: center">
<p> Tabela 1: Modelo texto estruturado para descrição de cenários (Fonte: [2], 2022).</p>
</div>

## Cenários identificados

Os cenários identificados foram determinados levando em consideração as Personas criadas e seus objetivos. A seguir, esses podem ser observados nas tabelas abaixo:

### C01: Jogar uma partida de xadrez contra o computador

| Elemento   | Descrição     |
| ---------- | --- |
| Objetivo   | jogar uma partida de xadrez contra o computador usando o sítio eletrônico Lichess           |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições:  ter acesso a internet, ter acesso ao sítio eletrônico Lichess         |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess      |
| Ator       | Jogador de xadrez          |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa o menu lateral direito <br> - O usuário seleciona "Jogar Contra o Computador"  <br> - O usuário inicia a partida |
| Restrições | - Fluxo de navegação intuitivo          |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet          |

### C02: Jogar uma partida de xadrez contra outro jogador

| Elemento   | Descrição           |
| ---------- | --------- |
| Objetivo   | jogar uma partida de xadrez contra outro jogador usando o sítio eletrônico Lichess   |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess   |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess            |
| Ator       | Jogadores de xadrez |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa o menu central e escolhe um ritmo de jogo <br> - O usuário aguarda por um adversário <br> - O usuário inicia a partida |
| Restrições | - Fluxo de navegação intuitivo   |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de adversário <br> - Falta de acesso à internet  |

### C03: Aprender xadrez com o sítio eletrônico

| Elemento   | Descrição    |
| ---------- | ------------ |
| Objetivo   | Aprender mais sobre o jogo xadrez      |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess         |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess     |
| Ator       | Jogador de xadrez         |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa a opção "Aprender" no menu superior <br> - O usuário seleciona "Estudar" <br> - O usuário seleciona um opção de tópico para estudo <br> - O usuário estuda o tópico |
| Restrições | - Fluxo de navegação intuitivo         |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet  <br> - Falta de tópicos cadastrados           |

### C04: Recuperar a senha esquecida

| Elemento   | Descrição          |
| ---------- | ---------- |
| Objetivo   | Recuperar a senha esquecida     |
| Contexto   | - Local: em casa <br> - Tempo: durante a noite <br>  - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess     |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess           |
| Ator       | Usuário do Lichess |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa o menu superior <br> - O usuário seleciona a opção "Entrar" <br> - O usuário seleciona a opção "Redefinir a palavra-passe" <br>- O usuário solicita um e-mail de recuperação de senha <br> - O usuário acessa e-mail recebido <br> - O usuário acessa o link e redefine sua senha |
| Restrições | - Fluxo de navegação intuitivo  |
| Exceção    | - Falta de energia no dispositivo <br> - Dispositivo danificado <br> - Falta de acesso a internet|

### C05: Selecionar a dificuldade da partida ao jogar com o computador

| Elemento   | Descrição        |
| ---------- | ----- |
| Objetivo   | Selecionar a dificuldade da partida contra o computador |
| Contexto   | - Local: em casa <br> - Tempo: durante a noite <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess    |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess         |
| Ator       | Jogador de xadrez|
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa a opção "Jogar Contra o Computador" no menu lateral direito <br> - O usuário seleciona a dificuldade desejada e inicia a partida |
| Restrições | - Fluxo de navegação intuitivo|
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet|

### C06: Reportar um usuário por suspeita de trapaça

| Elemento   | Descrição          |
| ---------- | ------ |
| Objetivo   | Denunciar um outro jogador por suspeita de trapaça        |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess  |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess           |
| Ator       | Jogadores de xadrez|
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa sua conta <br>- O usuário seleciona joga uma partida e suspeita de trapaça durante o jogo <br> - Ao final do jogo o usuário denúncia o suspeito |
| Restrições | - Fluxo de navegação intuitivo  |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet <br> - Falta de adversário |

### C07: Visualizar uma tela de instruções durante o primeiro uso do sítio eletrônico em uma conta cadastrada

| Elemento   | Descrição           |
| ---------- | ----------- |
| Objetivo   | Obter informações sobre o sítio eletrônico ao acessar ele pela primeira vez em uma conta          |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess   |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess            |
| Ator       | Usuário do Lichess  |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa sua conta pela primeira vez <br> - É exibido ao usuário um opção de tutorial e ele a utiliza |
| Restrições | - Fluxo de navegação intuitivo   |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet   |

### C08: Personalizar a partida de acordo com o modo e tempo de jogo desejado

| Elemento   | Descrição    |
| ---------- | ------------ |
| Objetivo   | Criar uma partida personalizada        |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess         |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess     |
| Ator       | Jogadores de xadrez       |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa o menu lateral direito <br> - O usuário seleciona "Criar uma partida" <br> -O usuário seleciona as configurações de jogo <br> - O usuário aguarda por um adversário |
| Restrições | - Fluxo de navegação intuitivo         |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet         |

### C09: Visualizar o ranqueamento de usuários da plataforma Lichess

| Elemento   | Descrição|
| ---------- | ---------- |
| Objetivo   | Criar uma partida personalizada    |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter acesso ao sítio eletrônico Lichess     |
| Recursos   | - Internet <br> - Computador <br> - Sítio eletrônico Lichess |
| Ator       | Jogadores de xadrez   |
| Episódios  | - O usuário acessa o sítio eletrônico Lichess <br> - O usuário acessa o menu superior <br> - O usuário seleciona "Comunidade" <br> -O usuário seleciona "Jogadores" <br> - O usuário observa o ranqueamento |
| Restrições | - Fluxo de navegação intuitivo     |
| Exceção    | - Falta de energia <br> - Dispositivo danificado <br> - Falta de acesso à internet <br> - Falta de jogadores suficientes para o ranqueamento            |

## Bibliografia

[1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 11 dez. 2022.

## Histórico de Versão

| Versão | Data  | Descrição   | Autor(es)     | Revisor(es)   |
| ------ | ----- | ------------- | ------------- | ------------- |
| `1.0`  | 26/01 | Criação do documento     | Lucas Gabriel | Nicolas Souza |
| `2.0`  | 31/01 | Adição de novos cenários | Lucas Gabriel | Nicolas Souza |
