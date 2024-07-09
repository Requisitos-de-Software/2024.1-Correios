# Histórias de Usuário

## Introdução

Uma História de Usuário descreve uma funcionalidade valiosa para o usuário do software, que é aplicável em qualquer metodologia ágil, não apenas no Scrum (B. Andrea, 2011). As User Stories têm três componentes principais: uma descrição escrita para planejamento, conversas para detalhamento e testes para verificar a conclusão. Elas devem ser pequenas, uma vez que histórias muito grandes são chamadas de Épicos, que são divididas em histórias menores.

## Metodologia

Para desenvolver as histórias de usuário, iniciamos com a elicitação de requisitos, empregando técnicas como [análise documental](../../elicitacao/tecnicas/analise-documental.md), [brainstorming](../../elicitacao/tecnicas/brainstorming.md), [questionários](../../elicitacao/tecnicas/questionario.md) e [observação](../../elicitacao/tecnicas/observacao.md). Após a coleta dos requisitos, procedemos com a priorização, utilizando métodos como [$100](../../priorizacao/tecnicas/$100.md), [First Things First](../../priorizacao/tecnicas/firstThingsFirst.md) e [In or Out](../../priorizacao/tecnicas/inorout.md). Esses documentos foram elaborados em entregas passadas.

<font size="2"><p style="text-align: center">Tabela 1 - Modelo de uma história de usuário.</p></font>

<center class="table_his_usuario">

| ID | Título | História de Usuário | Critério de aceitação | Prioridade | Rastreabilidade | Épico |
| :--: | ---- | ---- | ---- | :----: | :---: | :---: | 
| USxx | Título que contextualiza a história | Como um <usuário\>, quero <algum recurso\>, para que <algum motivo\> | pontos que possibilitam mensurar se o objetivo foi atingido | Prioridade com base na fase de priorização na elicitação e validação nesta etapa | Requisito de referência | [Épico]() associado |

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

## Histórias de Usuário

Na tabela 2, as histórias de usuários são apresentadas juntamente com suas características distintas. Cada história é cuidadosamente elaborada para refletir as necessidades e os desejos dos usuários finais, garantindo que os recursos desenvolvidos estejam alinhados com os objetivos do projeto. As características associadas fornecem um entendimento claro das funcionalidades requeridas, permitindo uma implementação eficaz e focada no usuário.

<font size="2"><p style="text-align: center">Tabela 2 - Histórias de Usuário elaboradas.</p></font>

<center class="table_his_usuario">

| ID | Título | Histórias de Usuário | Critério de aceitação | Prioridade | Rastreabilidade | Épico |
| :---: | --- | --- | --- | :---: | :---: | :---: |
| **US01** | Visualizar Encomenda no Mapa | Como um usuário, quero visualizar minha encomenda no mapa, para que eu possa acompanhar seu status. | É exibido um mapa com a última localização atualizada da encomenda | Alta | [RF18][RFlink] | [EP01][epicos] |
| **US02** | Atualização de Localização em Tempo Real | Como um usuário, quero ver a atualização de localização em tempo real, para que eu possa saber onde minha encomenda está a qualquer momento. | As atualizações automáticas são exibidas com um atraso máximo de 5 minutos | Alta | [RF18][RFlink] | [EP01][epicos] |
| **US03** | Atualização de Prazo de Entrega | Como um usuário, quero receber a atualização do prazo de entrega, para que eu possa me preparar para receber a encomenda. | As notificações de atualização do prazo de entrega são enviadas por e-mail, SMS ou WhatsApp e exibido na interface do app | Alta | [RF07][RFlink] | [EP02][epicos] |
| **US04** | Estipulação de Prazo de Entrega | Como um usuário, quero estipular um prazo de entrega ao enviar uma encomenda, para que eu possa informar o destinatário quando esperar a entrega. | O prazo estipulado é exibido na interface do app | Alta | [RF06][RFlink] | [EP02][epicos] |
| **US05** | Simular Preços e prazos de Encomendas Nacionais e Internacionais | Como um usuário, quero simular preços e prazos de encomendas nacionais e internacionais, para que eu possa escolher a melhor opção de envio. | <ul> <li>É permitida a entrada de diferentes destinos e tipos de encomenda</li> <li>Os resultados exibem preços e prazos detalhados para cada opção</li> </ul> | Alta | [RF30][RFlink] | [EP03][epicos] |
| **US06** | Realizar nova Postagem | Como um usuário, quero realizar uma nova postagem, para que eu possa enviar encomendas facilmente. | <ul> <li>A interface de postagem coleta todas as informações necessárias para o envio</li> <li>A confirmação de postagem é fornecida após a conclusão do pagamento</li> </ul> | Alta | [RF49][RFlink] | [EP04][epicos] |
| **US07** | Realizar pagamento da Postagem | Como um usuário, quero realizar o pagamento da postagem, para que eu possa concluir o processo de envio da encomenda. | <ul> <li>O sistema aceita vários métodos de pagamento (cartão de crédito, débito, pix e boleto)</li> <li>A confirmação do pagamento é fornecida por meio de um código para postagem</li> </ul> | Alta | [RF50][RFlink] | [EP04][epicos] |
| **US08** | Alterar Endereço de Entrega | Como um usuário, quero alterar o endereço de entrega, para que minha encomenda possa ser redirecionada caso necessário. | <ul> <li>A interface permite a alteração do endereço de entrega antes da entrega final, porém, com um limite de 12h antes da entrega</li> <li>O novo endereço é atualizado no status da encomenda</li> </ul> | Alta | [RF47][RFlink] | [EP05][epicos] |
| **US09** | Reservar um locker | Como um usuário, quero reservar um locker, para que eu possa armazenar meus pertences temporariamente. | <ul> <li>O usuário consegue selecionar e reservar um locker disponível</li> <li>O sistema confirma a reserva do locker</li> </ul> | Alta | [RF45][RFlink] | [EP05][epicos] |
| **US10** | Acessar Histórico de Notificações | Como um usuário, quero acessar o histórico de notificações, para que eu possa revisar as comunicações anteriores. | <ul> <li>O usuário consegue visualizar uma lista de notificações passadas</li> <li>O usuário pode filtrar notificações por data e tipo</li> </ul> | Média | [RF03][RFlink] | [EP06][epicos] |
| **US11** | Receber Notificações por WhatsApp | Como um usuário, quero receber notificações por WhatsApp, para que eu possa ser informado rapidamente sobre atualizações. | <ul> <li>O sistema envia notificações para o WhatsApp do usuário</li> <li>O usuário confirma o recebimento das notificações</li> </ul> | Alta | [RF11][RFlink] | [EP07][epicos] |
| **US12** | Receber Notificações por E-mail | Como um usuário, quero receber notificações por e-mail, para que eu possa estar atualizado sobre eventos importantes. | <ul> <li>O sistema envia notificações para o e-mail do usuário de 12h em 12h</li> <li>O usuário confirma o recebimento das notificações</li> </ul> | Alta | [RF22][RFlink] | [EP07][epicos] |
| **US13** | Acessar Chatbot para Suporte | Como um usuário, quero acessar o chatbot para suporte, para que eu possa obter ajuda imediata com minhas dúvidas. | <ul> <li>O usuário consegue iniciar uma conversa com o chatbot</li> <li>O chatbot fornece respostas úteis ou direciona para suporte humano se necessário</li> </ul> | Alta | [RF12][RFlink] | [EP08][epicos] |
| **US14** | Acessar Página de FAQ | Como um usuário, quero acessar a página de FAQ, para que eu possa encontrar respostas para perguntas frequentes. | <ul> <li>O usuário consegue acessar a página de FAQ</li> <li>O conteúdo da FAQ é claro e relevante para as perguntas frequentes</li> </ul> | Alta | [RF17][RFlink] | [EP09][epicos] |
| **US15** | Visualizar Tutorial de Rastreamento | Como um usuário, quero visualizar o tutorial de rastreamento, para que eu possa entender como rastrear minhas encomendas. | <ul> <li>O usuário consegue acessar e visualizar o tutorial de rastreamento</li> <li>O tutorial cobre todos os passos necessários para o rastreamento</li> </ul> | Média | [RF13][RFlink] | [EP09][epicos] |
| **US16** | Realizar Pagamento de Impostos | Como um contribuinte, quero realizar o pagamento de impostos online, para evitar filas e agilizar o processo. | <ul> <li>Confirmação de pagamento recebida</li> <li>Recibo disponível para download</li> </ul> | Alta | [RF23][RFlink] | [EP10][epicos] |
| **US17** | Realizar Cadastro no Aplicativo | Como um novo usuário, quero me cadastrar no aplicativo, para acessar seus serviços exclusivos. | <ul> <li>Cadastro concluído com sucesso</li> <li>Acesso liberado ao usuário</li> </ul> | Alta | [RF01][RFlink] | [EP11][epicos] |
| **US18** | Realizar Login no Aplicativo | Como um usuário registrado, quero realizar login no aplicativo, para acessar minha conta pessoal. | <ul> <li>Login efetuado com sucesso</li> <li>Acesso à conta confirmado</li> </ul> | Alta | [RF25][RFlink] | [EP11][epicos] |
| **US19** | Buscar Agências Próximas | Como um cliente, quero buscar agências próximas, para encontrar a mais conveniente para mim. | Lista de agências próximas exibida com base na localização atual | Alta | [RF29][RFlink] | [EP12][epicos] |
| **US20** | Acessar Contatos das Empresas | Como um usuário, quero acessar contatos das empresas, para resolver questões específicas. | Informações de contato das empresas disponíveis e atualizadas | Média | [RF08][RFlink] | [EP12][epicos] |
| **US21** | Buscar Objetos Perdidos | Como um usuário, quero buscar objetos perdidos, para tentar recuperá-los. | Sistema de busca de objetos perdidos implementado e funcional | Alta | [RF53][RFlink] | [EP12][epicos] |
| **US22** | Acessar Área de Contato sobre Violência contra a Mulher | Como uma mulher, quero acessar a área de contato sobre violência contra a mulher, para buscar ajuda e suporte. | Canal de suporte dedicado e informações sobre recursos de ajuda disponíveis | Média | [RF36][RFlink] | [EP12][epicos] |


</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin) (US01 - US08); [Gabriel B. Bertolazi][GabrielBGH] (US09 - US15); [Pablo S. Costa][PabloGH] (US16 - US22), 2024.</p></font>

## Reunião de Validação

Para validar as histórias de usuário, realizamos uma entrevista com o Product Owner (PO) [**Diego Medeiros**](https://www.instagram.com/diegoomedeiros23/). A entrevista está disponível através de um video não listado no Youtube. A sessão ocorreu via **Teams** no dia **27/05/2024 às 21h**. 

<p style="text-align: center">
    <iframe width="560" height="315" src="https://youtube.com/embed/_QHMTiSvG_U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<p style="text-align: center">
    <a href="https://youtube.com/_QHMTiSvG_U">Link para o vídeo</a>
</p>

## Referências Bibliográficas

> 1. BALLE, R. ANDREA. **Análise de Metodologias Ágeis: Conceitos, Aplicações e Relatos sobre XP e Scrum**. UNIVERSIDADE FEDERAL DO RIO GRANDE DO SUL, 2011. Disponível em: <https://lume.ufrgs.br/bitstream/handle/10183/31028/000782065.pdf?sequence=>. Acesso em: 27 de maio de 2024.

## Bibliografia

> 1. Roger Pressman, Bruce Maxim. **Software Engineering: A Practitioner's Approach**. McGraw-Hill Education, 2019. Disponível em: <https://www.amazon.com/ISE-SOFTWARE-ENGINEERING-PRACTITIONERS-APPROACH/dp/1260548007>. Acesso em: 27 de maio de 2024.
>
> 2. BALLE, R. ANDREA. **Análise de Metodologias Ágeis: Conceitos, Aplicações e Relatos sobre XP e Scrum**. UNIVERSIDADE FEDERAL DO RIO GRANDE DO SUL, 2011. Disponível em: <https://lume.ufrgs.br/bitstream/handle/10183/31028/000782065.pdf?sequence=>. Acesso em: 27 de maio de 2024.
>

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 27/05/2024 | Criação do documento | [Gabriel F. J. Silva](https://github.com/MMcLovin), [Pablo S. Costa][PabloGH] e [Gabriel B. Bertolazi][GabrielBGH] |  [Ricardo Augusto][RicardoGH] |
| `1.1`  | 27/05/2024 | Corrigindo prioridade | [Gabriel F. J. Silva](https://github.com/MMcLovin) |  [Gabriel B. Bertolazi][GabrielBGH] |
| `1.2`  | 08/07/2024 | Corrigindo hiperlinks | [Gabriel F. J. Silva](https://github.com/MMcLovin) |  [Gabriel B. Bertolazi][GabrielBGH] |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
[temas]: https://interacao-humano-computador.github.io/2024.1-Correios/modelagem/agil/backlog/#temas
[epicos]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/backlog/#epicos
[RFlink]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/requisitos_elicitados/#requisitos-funcionais
