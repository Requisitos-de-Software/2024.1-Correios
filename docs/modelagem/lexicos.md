## Introdução

O léxico é uma notação utilizada para apresentar os símbolos de uma linguagem através da descrição de termos, o principal uso dos léxicos na engenharia de requisitos é encontrar palavras ou frases que são peculiares no meio social do estudo em questão. Nos léxicos cada símbolo é caracterizado com noção e impacto, onde noção denota o significado do símbolo, já o impacto representa: o efeito, uso ou ocorrência do símbolo no sistema ou ainda o efeito de algo na aplicação sobre o símbolo.

## Metodologia

Tendo como base os [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) na etapa anterior identificamos e apresentamos os devidos léxicos separando em três tipos de classificação que são: Objeto, Verbo e Estado que são descritos logo abaixo. Na tabela 01 é mostrado o formato ao qual os léxicos estão estruturados, para a criação dos léxicos utilizamos o LAL (Léxico Ampliado da Imagem) que é uma maneira mais refinada de registro de termos próprios da aplicação.

<font size="3"><p style="text-align: center">**Tabela 01: Formato do Léxico** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
|LXX - Nome. |Objeto, Verbo, Estado.|Significado do símbolo.|Efeito, uso ou ocorrência na aplicação.|Termo similar.|Integrante responsável pelo léxico.|

<center>**Fonte**:  [Elias Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc), 2024. </center>



## Objeto

Nos léxicos do tipo Objeto é definido: o objeto, outros objetos com os quais se relaciona e as ações que poderão ser empregadas ao objeto. Na tabela 02 logo abaixo estão descritos os léxicos do tipo objeto.

<font size="3"><p style="text-align: center">**Tabela 02: Léxicos do tipo Objeto** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
| <a id="correios">L01 - Correios</a> | Objeto | Empresa pública federal responsável pela execução do sistema de envio e entrega de <a href="#encomenda">encomendas</a> no Brasil, assim como presta outros serviços de apoio ao Governo.  | Responsável pelo desenvolvimento e manutenção do aplicativo "Correios". | Empresa Brasileira de Correios e Telégrafos |[Claudio Henrique](https://github.com/claudiohsc) |
| L02 - | Objeto |  |  | |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
| <a id="encomenda">L03 - Encomenda </a> | Objeto | Objeto que é embalado e enviado de um local para outro, quando o <a href="#usuario">usuário</a> realiza um <a href="#enviar">envio</a> ou recebe alguma  <a href="#encomenda">encomenda</a>. | É possível realizar o <a href="#enviar">envio</a>, <a href="#adiamento">adiamento</a> ou <a href="#cancelamento">cancelamento</a> da entrega da encomenda. | Pacote |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
| L04 - | Objeto |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
| L05 - | Objeto |  |  | |[Gabriel Fernando](https://github.com/MMcLovin) |
| L06 - | Objeto |  |  | |[Pablo Santos](https://github.com/pabloheika) |
| L07 - Código de rastreio | Objeto | Sequência de caracteres alfanuméricos que representa a <a href="#encomenda">encomenda</a> e permite rastrear e verificar seu status. | Acompanhar o status e localização da <a href="#encomenda">encomenda</a>. | Número de rastreio |[Ricardo Augusto](https://github.com/avmricardo) |
| <a id="cep">L08 - CEP</a> | Objeto | É a sigla de Código de Endereçamento Postal que serve para organizar e facilitar a postagem, <a href="#rastrear">rastreio</a> e distribuição das <a href="#encomenda">encomendas</a> de forma lógica. | O CEP é utilizado para identificar rapidamente o endereço que será utilizado para fins de <a href="#simular">simulação</a> e postagens das <a href="#encomenda">encomendas</a> e correspondências.  | Código de Endereçamento Postal |[Claudio Henrique](https://github.com/claudiohsc) |


<center>**Fonte**: Autores das descrições dos léxicos do tipo Objetos, 2024. </center>

## Verbo

Nos léxicos do tipo verbo deve-se descrever: quem realiza, quando realiza, quais os processos realizados e quais os reflexos da ação no ambiente. Abaixo na tabela 03 estão descritos os léxicos do tipo verbo.

<font size="3"><p style="text-align: center">**Tabela 03: Léxicos do tipo Verbo** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
|<a id="simular">L09 - Simular</a> | Verbo | O usuário pode <a href="#simular">simular</a>, antes do envio, os preços e prazos de entrega de uma <a href="#encomenda">encomenda</a> a partir do CEP de origem e destino. |  | |[Claudio Henrique](https://github.com/claudiohsc) |
|L10 - | Verbo |  |  | |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
|<a id="enviar">L11 - Enviar </a> | Verbo | O envio pode ser realizado pelo <a href="#usuario">usuário</a> ao expedir uma <a href="#encomenda">encomenda</a> para um destinatário. | A <a href="#encomenda">encomenda</a> é enviada entregando ela em uma agência dos correios, e seu envio pode ser feito por diferentes meios de transporte chegando até ao <a href="#destinatário">destinatário</a>.  | expedir |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
|L12 - | Verbo |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
|L13 - | Verbo |  |  | |[Gabriel Fernando](https://github.com/MMcLovin) |
|L14 - | Verbo |  |  | |[Pablo Santos](https://github.com/pabloheika) |
|<a id="rastrear">L15 - Rastrear</a> | Verbo | O usuário pode consultar o status da entrega da <a href="#encomenda">encomenda</a> em tempo real, verificando sua localização, histórico de movimentações e eventuais problemas na entrega. | Permite ao usuário acompanhar o andamento da entrega, ter previsões de entrega e se preparar para recebê-la. | Acompanhar. |[Ricardo Augusto](https://github.com/avmricardo) |

<center>**Fonte**: Autores das descrições dos léxicos do tipo Verbo, 2024. </center>


## Estado

Nos léxicos do tipo estado são definidos: qual o significado das ações e quais levaram a esse estado, e mostrar quais outros estados e ações que pode-se chegar e realizar a partir do estado atual. Abaixo na tabela 04 são elencados os léxicos do tipo estado.

<font size="3"><p style="text-align: center">**Tabela 04: Léxicos do tipo Estado** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
| <a id="logado">L16 - Usuário logado</a> | Estado | Ocorre quando o usuário faz o seu Login no aplicativo do <a href="#correios">Correios</a>.  | É possível realizar pré-postagem, ver mensagens, vales postais e sobre a conta. Quando o usuário desconecta da sua conta, ele sai do estado atual.  | Usuário conectado |[Claudio Henrique](https://github.com/claudiohsc) |
| L17 - | Estado |  |  | |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
| <a id="embaraço_aduaneiro">L18 - Embaraço Aduaneiro </a> | Estado | A  <a href="#encomenda">encomenda</a> fica retida em uma sede de inspeção da receita federal para a averiguação do objeto e possível tributação.O objeto é levado para a aduana por ser identificado algum item que não foi tributado ou foi tributado de maneira incorreta. | Pode-se realizar o <a href="#pagamentodetaxas">pagamento de taxas</a> alfandegárias ou <a href="#cancelar_o_recebimento">cancelar o recebimento</a> da encomenda. | Restrição alfandegária |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
| L19 - | Estado |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
| L20 - | Estado |  |  | |[Gabriel Fernando](https://github.com/MMcLovin) |
| L21 - | Estado |  |  | |[Pablo Santos](https://github.com/pabloheika) |
| L22 - Em Trânsito | Estado | A <a href="#encomenda">encomenda</a> está se movimentando entre os Correios e ainda não chegou ao destinatário. | Indica que a entrega da <a href="#encomenda">encomenda</a> está em andamento e que o usuário pode acompanhar seu status através do código de rastreio. | Em transporte |[Ricardo Augusto](https://github.com/avmricardo) |
| L23 - Entregue | Estado | A <a href="#encomenda">encomenda</a> foi entregue ao destinatário e a entrega está finalizada. | Indica que o destinatário já recebeu a <a href="#encomenda">encomenda</a> e que o processo de entrega foi concluído com sucesso. | Objeto entregue ao destinatário |[Ricardo Augusto](https://github.com/avmricardo) |

<center>**Fonte**: Autores das descrições dos léxicos do tipo Estado, 2024. </center>



## Bibliografia

> 1. SERRANO, Milene. Requisitos – Aula 10. Apresentação de slides. Disponível em: [Requisitos Aula - 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf). Acesso em: 16/05/2024.
> 2. SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 16/05/2024.

## Histórico de versões
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
` 1.0 `| 15/05/2024 | Criação do Documento | [Elias Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc) | []() |