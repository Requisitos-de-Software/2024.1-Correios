# Backward-From

## Introdução

A rastreabilidade tem como objetivo identificar e conectar requisitos durante a fase de desenvolvimento, juntamente rastreá-los ao longo do ciclo de vida do sistema.

Este documento aborda a aplicação da técnica de rastreabilidade backward-from, que tem por objetivo ligar os requisitos às suas fontes (SAYÃO; LEITE, 2005). Essa técnica possibilita simplificar a validação e verificação dos sistemas, contribuindo, assim, para a identificação de possíveis problemas.

## Metodologia

### Classificação das Informações

Toranzo (2002) propõe uma classificação que comporta 4 níveis de informação: ambiental, organizacional, gerencial e de desenvolvimento. Esses níveis e suas descrições estão presentes na tabela 1.

<font size="2"><p style="text-align: center">Tabela 1 - Níveis de informação segundo Toranzo.</p></font>

<Center>

| Nível de Informação | Descrição |
| --- | --- |
| Ambiental | Compreende conceitos relacionados ao contexto político, econômico e padrões que podem afetar uma organização. Essas informações são expressas em termos de objetivos e regras políticas e econômicas que precisam ser atendidas. |
| Organizacional | Refere-se aos conceitos que impulsionam o desenvolvimento e crescimento de uma organização. Inclui a compra e uso de sistemas computacionais para agregar valor aos serviços da organização. |
| Gerencial | Concentra-se no relacionamento entre tarefas e requisitos do sistema, permitindo um melhor acompanhamento e controle dos requisitos. Contribui para o sucesso do projeto e a satisfação dos requisitos. |
| Desenvolvimento | Representa os elementos/artefatos produzidos nas diferentes atividades do desenvolvimento de software, como documentos de requisitos, diagramas e programas. Esse nível é essencial para o rastreamento de requisitos. |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

Essa categorização definida por Toranzo tem o intuito de definir quais informações serão identificadas, assim como classificar elas para entender melhor o processo de rastreabilidade. Para o contexto desse trabalho, destaca-se que todas as informações estão presentes dentro do nível de desenvolvimento, visto que todos os artefatos produzidos são documentos de requisitos de software.

### Meta-Modelo para o Rastreamento de Requisitos

A partir das informações descritas no tópico anterior, Toranzo (2002) define um meta-modelo descrevendo os tipos de relacionamento usados para rastrear informações, sendo eles descritos na tabela 2.

<font size="2"><p style="text-align: center">Tabela 2 - Relacionamentos entre infomações segundo Toranzo.</p></font>

<Center>

| Relacionamento | Descrição |
| --- | --- |
| Satisfação | Representa uma associação de dependência em que a classe origem requer a satisfação da classe destino para cumprir seus objetivos. Por exemplo, um requisito específico pode depender da satisfação de outro requisito para ser atendido. |
| Recurso | Refere-se a uma associação de dependência em que a classe origem tem uma dependência de recurso com a classe destino. Essa relação visa manter a consistência das informações nas instâncias da classe origem, utilizando elementos físicos ou informações como recursos. Por exemplo, um requisito pode depender de um documento de especificação como recurso. |
| Responsabilidade | Captura a participação, responsabilidade e ação das pessoas sobre artefatos ou elementos do processo de software. Por exemplo, a participação de um analista e programador em relação a um subsistema específico. |
| Representação | Essa associação visa capturar a representação dos requisitos em linguagens de modelagem ou programação. É natural no processo de desenvolvimento de software e permite expressar os requisitos de maneira mais detalhada. Por exemplo, um requisito pode ser representado por meio de diagramas UML ou código-fonte. |
| Alocado | Expressa que a classe origem está relacionada com uma instância da classe destino, que representa um subsistema. Indica a alocação de responsabilidades ou recursos entre as partes do sistema. Por exemplo, um requisito pode estar alocado a um subsistema específico. |
| Agregação | Ajuda a expressar que um elemento está composto de outros elementos. É usado para representar a estrutura hierárquica ou composição de partes em um sistema. Por exemplo, um requisito pode ser agregado a outros requisitos para formar um conjunto funcional. |


</Center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

## Rastreabilidade

Legendas:

> - RFx: Requisito Funcional n°X.
> - RNFx: Requisito Não Funcional n°X 
> - AD: Análise Documental
> - BS: Brainstorm 
> - OBS: Observação
> - QS: Questionário

### Requisitos Funcionais

<font size="2"><p style="text-align: center">Tabela 3 - Requisitos Funcionais Versionados.</p></font>

<Center>

| ID  | Descrição | Fonte | Implementado | Versão |
| :-: | --------- | :---: | :----------: | :----: |
| RF01 | O usuário deve poder realizar cadastro pelo app | [BS01][BSRF] | Sim | `1.0` |
| RF02 | O usuário deve poder realizar login pelo app | [BS02][BSRF] | Sim | `1.0` |
| RF03 | O usuário deve poder acessar o histórico de notificações do objeto | [BS03][BSRF] | Não | `1.0` |
| RF04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | [BS04][BSRF] | Não | `1.0` |
| RF05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda | [BS05][BSRF] | Não | `1.0` |
| RF06 | O usuário deve visualizar a estipulação de prazo de entrega | [BS06][BSRF] | Sim | `1.0` |
| RF07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações | [BS07][BSRF] | Não | `1.0` |
| RF08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | [BS08][BSRF] | Não | `1.0` |
| RF09 | O usuário deve receber notificações push pelo aplicativo | [BS09][BSRF] | Sim | `1.0` |
| RF10 | O usuário deve receber notificações SMS | [BS10][BSRF] | Sim | `1.0` |
| RF11 | O usuário deve receber notificações pelo Whatsapp | [BS11][BSRF] | Não | `1.0` |
| RF12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente | [BS12][BSRF] | Não | `1.0` |
| RF13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento | [BS13][BSRF] | Não | `1.0` |
| RF14 | O usuário deve poder receber o status da encomenda pelo WhatsApp | [BS14][BSRF] | Não | `1.1` |
| RF15 | O usuário deve poder aumentar e diminuir a fonte | [BS15][BSRF] | Não | `1.0` |
| RF16 | O usuário deve ter a opção de falar com um atendente para obter ajuda | [BS16][BSRF] | Não | `1.1` |
| RF17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) | [BS17][BSRF] | Não | `1.0` |
| RF18 | O usuário deve poder visualizar sua encomenda no mapa | [BS18][BSRF] | Não | `1.0` |
| RF19 | O usuário deve poder visualizar detalhes da situação do produto | [BS19][BSRF] | Sim | `1.0` |
| RF20 | O usuário deve poder realizar o rastreio por código mais simples | [BS20][BSRF] | Não | `1.0` |
| RF21 | O usuário deve poder realizar o rastreio por QR Code | [BS21][BSRF] | Sim | `1.0` |
| RF22 | O usuário deve receber notificação pelo e-mail | [BS22][BSRF] | Não | `1.0` |
| RF23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | [BS23][BSRF] | Não | `1.0` |
| RF24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | [BS24][BSRF] | Sim | `1.0` |
| RF25 | O aplicativo permite realizar login com sua conta | [OBS01][OBSRF] | Sim | `1.0` |
| RF26 | O aplicativo permite rastreamento de encomendas por código. | [OBS02][OBSRF] | Sim | `1.0` |
| RF27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | [OBS03][OBSRF] | Sim | `1.0` |
| RF28 | O aplicativo possibilite ver seus pagamentos | [OBS04][OBSRF] | Sim | `1.0` |
| RF29 | O aplicativo oferece uma busca por agências próximas ao seu endereço | [OBS05][OBSRF] | Sim | `1.0` |
| RF30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | [OBS06][OBSRF] | Sim | `1.0` |
| RF31 | O aplicativo possibilita a compra de certificados digitais dos correios | [OBS07][OBSRF] | Sim | `1.0` |
| RF32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | [OBS08][OBSRF] | Sim | `1.0` |
| RF33 | O aplicativo permite visualização de mensagens | [OBS09][OBSRF] | Sim | `1.0` |
| RF34 | O aplicativo oferece a visualização de vales postais | [OBS10][OBSRF] | Sim | `1.0` |
| RF35 | O aplicativo oferece uma área de busca por objetos perdidos em envios | [OBS11][OBSRF] | Sim | `1.0` |
| RF36 | O aplicativo fornece uma área de contato sobre violência contra a mulher | [OBS12][OBSRF] | Sim | `1.0` |
| RF37 | As informações das entregas ativas e completas na página de rastreio | [Q01][QRF] | Sim | `1.1` |
| RF38 | Filtrar o tipo de encomenda pelo tipo de entrega | [Q02][QRF] | Não | `1.0` |
| RF39 | Assistente virtual dos correios para ajudar a executar tarefas e achar opções muitas vezes de difícil acesso pelo site. | [Q03][QRF] | Não | `1.1` |
| RF40 | Ter um chat para se comunicar diretamente com o fornecedor, e consiga ter as informações básicas do mesmo. | [Q04][QRF] | Não | `1.1` |
| RF41 | Ter um chat para se comunicar diretamente com o entregador, e consiga ter as informações dos mesmos. | [Q05][QRF] | Não | `1.1` |
| RF42 | Poder fazer os pagamentos pagamento de tributos e taxas de importação em uma página própria para essa finalidade. | [Q06][QRF] | Não | `1.1` |
| RF43 | O usuário deve conseguir mudar a opção de recebimento dentro do aplicativo, antes que sua encomenda seja enviada. | [AD01][QRF] | Não | `1.0` |
| RF44 | O usuário deve ser notificado quando o recebimento for efetuado. | [AD03][QRF] | Não | `1.0` |
| RF45 | O sistema deve permitir que o usuário reserve o locker mais perto de sua casa baseado no CEP informado, de acordo com a disponibilidade | [AD04][QRF] | Não | `1.0` |
| RF46 | O usuário deve poder mudar local de recebimento da encomenda, antes que a mesma tenha sido enviada. | [AD05][QRF] | Não | `1.1` |
| RF47 | O usuário pode optar por retirar em uma agência ou caixa postal | [AD06][QRF] | Não | `1.0` |
| RF48 | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | [AD09][QRF] | Sim | `1.0` |
| RF49 | O usuário deve ser capaz de gerenciar o carrinho de pré-postagens, podendo adicionar ou excluir uma pré-postagem | [AD10][QRF] | Sim | `1.0` |
| RF50 | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | [AD11][QRF] | Não | `1.0` |
| RF51 | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | [AD12][QRF] | Não | `1.0` |
| RF52 | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | [AD14][QRF] | Sim | `1.0` |
| RF53 | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | [AD15][QRF] | Não | `1.0` |
| RF54 | O Usuário deve ser capaz de gerenciar suas importações | [AD16][QRF] | Não | `1.0` |
| RF55 | O Usuário deve ser capaz de resolver situações alfandegárias | [AD17][QRF] | Não | `1.0` |
| RF56 | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | [AD18][QRF] | Não | `1.0` |
| RF57 | O usuário deve ser capaz de inserir novas importações | [AD19][QRF] | Não | `1.0` |
| RF58 | O usuário deve ter acesso a meios de pagamento de taxas | [AD20][QRF] | Não | `1.0` |
| RF59 | O usuário deve ser notificado sobre atualizações de importações | [AD21][QRF] |   | `1.0` |
| RF60 | O usuário deve poder contestar taxas e tributações | [AD22][QRF] | Não | `1.0` |
| RF61 | O Usuário deve ser capaz de emitir comprovante | [AD23][QRF] | Não | `1.0` |
| RF62 | O usuário deve ser capaz de emitir DIS | [AD24][QRF] | Não | `1.0` |
| RF63 | A busca por itens deve ser o mais otimizada possível, com o usuário tendo a opção de filtragem para simplificar e diminuir o tempo de busca por produtos que antes se apresentariam em uma categoria única. | [AD29][QRF] | Não | `1.1` |
| RF64 | O usuário deve poder ter a total liberdade de editar suas informações e transitar pelas etapas que o sistema oferece. | [AD30][QRF] | Não | `1.1` |
| RF65 | O usuário deverá possuir uma opção para ordenar os itens de acordo com seus anseios, como: menor preço, maior preço, maior relevância ou menor. | [AD31][QRF] | Não | `1.1` |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

### Requisitos Não-Funcionais

<font size="2"><p style="text-align: center">Tabela 4 - Requisitos Não-Funcionais Versionados.</p></font>

<Center>

| ID  | Descrição | Fonte | Implementado | Versão |
| :-: | --------- | :---: | :----------: | :----: |
| RNF01 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | [BS25][BSRNF] | Não | `2.0` |
| RNF02 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | [BS26][BSRNF] | Não | `2.0` |
| RNF03 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | [BS27][BSRNF] | Sim | `2.0` |
| RNF04 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | [BS28][BSRNF] | Não | `2.0` |
| RNF05 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | [BS29][BSRNF] | Não | `2.0` |
| RNF06 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | [BS30][BSRNF] | Não | `2.0` |
| RNF07 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | [BS31][BSRNF] | Não | `2.0` |
| RNF08 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | [BS32][BSRNF] | Não | `2.0` |
| RNF09 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | [BS33][BSRNF] | Não | `2.0` |
| RNF10 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | [BS34][BSRNF] | Não | `2.0` |
| RNF11 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status. | [BS35][BSRNF] | Não | `2.0` |
| RNF12 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | [BS36][BSRNF] | Não | `2.0` |
| RNF13 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | [BS37][BSRNF] | Sim | `2.0` |
| RNF14 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão. | [OBS13][OBSRNF] | Sim | `2.0` |
| RNF15 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas. | [OBS14][OBSRNF] | Sim | `2.0` |
| RNF16 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm. | [OBS15][OBSRNF] | Sim | `2.0` |
| RNF17 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores. | [OBS16][OBSRNF] | Não | `2.0` |
| RNF18 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros. | [OBS17][OBSRNF] | Sim | `2.0` |
| RNF19 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas. | [OBS18][OBSRNF] | Sim | `2.0` |
| RNF20 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações. | [OBS19][OBSRNF] | Sim | `2.0` |
| RNF21 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email. | [OBS20][OBSRNF] | Sim | `2.0` |
| RNF22 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações. | [OBS21][OBSRNF] | Sim | `2.0` |
| RNF23 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação. | [OBS22][OBSRNF] | Sim | `2.0` |
| RNF24 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas. | [OBS23][OBSRNF] | Sim | `2.0` |
| RNF25 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento. | [OBS24][OBSRNF] | Sim | `2.0` |
| RNF26 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial. | [OBS25][OBSRNF] | Sim | `2.0` |
| RNF27 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior. | [OBS26][OBSRNF] | Sim | `2.0` |
| RNF28 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status. | [OBS27][OBSRNF] | Sim | `2.0` |
| RNF29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | [Q07][QRNF] | Sim | `1.0` |
| RFN30 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | [Q08][QRNF] | Não | `1.1` |
| RNF31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | [Q09][QRNF] | Sim | `1.0` |
| RNF32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | [Q10][QRNF] | Não | `1.0` |
| RNF33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | [Q11][QRNF] | Não | `1.0` |
| RNF34 | O chat com o entregador deve ser protegido de acessos indevidos (de acordo com as especificações de segurança do [Art. 46](#referencias-bibliograficas) da LGPD) por meio de criptografia AES-256 | [Q12][QRNF] | Não | `1.1` |
| RNF35 | O usuário deve poder mudar o método de recebimento em até 3 cliques desde iniciar a ação. | [AD02][QRNF] | Não | `1.1` |
| RNF36 | Os ícones de opção dentro dessa funcionalidade devem ser 44x44 pixels, para melhor visualização de cada um dos ícones para pessoas com leves problemas visuais. | [AD07][QRNF] | Não | `1.1` |
| RNF37 | A funcionalidade deve ser aparente na página principal. | [AD08][QRNF] | Não | `1.1` |
| RNF38 | O usuário deve ser perguntado sobre a confirmação de operações importantes como exclusão de itens do carrinho | [AD13][QRNF] | Sim | `1.0` |
| RNF39 | As informações devem ser atualizadas em tempo de execução | [AD25][QRNF] | Não | `1.0` |
| RNF40 | A liberação das encomendas deve ser automática | [AD26][QRNF] | Não | `1.0` |
| RNF41 | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | [AD27][QRNF] | Não | `1.0` |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

## Elos

### Requisitos Funcionais

<font size="2"><p style="text-align: center">Tabela 5 - Elos dos Requisitos Funcionais.</p></font>

<center>

|Elo| ID Requisito | Descrição | Tipo de Relacionamento | Descrição do Relacionamento |
|:---:| ------------ | --------- | :--------------------: | --------------------------- | 
|ERF01| RF01 | O usuário deve poder realizar cadastro pelo app |  Satisfação | Este requisito depende de uma base de dados para armazenar as informações do usuário. |
|ERF02| RF02 | O usuário deve poder realizar login pelo app |  Satisfação | Depende do cadastro de usuários (RF01) para funcionar. |
|ERF03| RF03 | O usuário deve poder acessar o histórico de notificações do objeto |  Representação | Esse requisito tem uma relação de representação, pois envolve a visualização de informações específicas. |
|ERF04| RF04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | Recurso | Necessita integração com funcionalidades de segurança do sistema operacional do dispositivo. |
|ERF05| RF05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda |  Recurso | Depende da disponibilidade de hardware (chip de localização) para ser implementado. |
|ERF06| RF06 | O usuário deve visualizar a estipulação de prazo de entrega |  Representação | Este requisito pode ser representado por meio de uma interface de usuário detalhando prazos. |
|ERF07| RF07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações |  Satisfação | Esse requisito possui relacionamento de satisfação, pois a atualização do prazo é relevante para o usuário. |
|ERF08| RF08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | Agregação | Faz parte de um conjunto de funcionalidades de suporte ao cliente. |
|ERF09| RF09 | O usuário deve receber notificações push pelo aplicativo |  Satisfação | Relacionado à satisfação, pois as notificações push são importantes para manter o usuário informado. |
|ERF10| RF10 | O usuário deve receber notificações SMS |  Satisfação | Relacionado à satisfação, pois as notificações SMS são importantes para manter o usuário informado. |
|ERF11| RF11 | O usuário deve receber notificações pelo WhatsApp |  Satisfação | Relacionado à satisfação, pois as notificações via WhatsApp são importantes para manter o usuário informado. |
|ERF12| RF12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente |  Alocado | Este requisito está alocado ao subsistema de suporte ao cliente. |
|ERF13| RF13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento |  Representação | Pode ser representado por meio de vídeos ou textos explicativos na interface do usuário. |
|ERF14| RF14 | O usuário deve poder receber o status da encomenda pelo WhatsApp |  Satisfação | Seu relacionamento é do tipo satisfação, pois está relacionado com a satisfação do usuário de receber informações. |
|ERF15| RF15 | O usuário deve poder aumentar e diminuir a fonte |  Representação | Requer ajustes na interface de usuário para permitir controle de tamanho de fonte. |
|ERF16| RF16 | O usuário deve ter a opção de falar com um atendente para obter ajuda |  Alocado | Está alocado ao subsistema de suporte ao cliente. |
|ERF17| RF17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) |  Agregação | Parte do subsistema de suporte ao cliente, agregando várias perguntas e respostas. |
|ERF18| RF18 | O usuário deve poder visualizar sua encomenda no mapa |  Representação | Requer integração com APIs de mapas para exibir a localização da encomenda. |
|ERF19| RF19 | O usuário deve poder visualizar detalhes da situação do produto |  Recurso | Requer acesso a dados detalhados sobre a encomenda. |
|ERF20| RF20 | O usuário deve poder realizar o rastreio por código mais simples |  Representação | Requer uma interface de entrada simplificada para códigos de rastreamento. |
|ERF21| RF21 | O usuário deve poder realizar o rastreio por QR Code | Representação | Necessita uma interface que permita a leitura de QR Codes. |
|ERF22| RF22 | O usuário deve receber notificação pelo e-mail |  Satisfação | As notificações por e-mail são relevantes para manter o usuário informado. |
|ERF23| RF23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | Recurso | Requer integração com sistemas de pagamento e bancos. |
|ERF24| RF24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | Representação | Simulação de envio depende de um subsistema que calcula tarifas e prazos. |
|ERF25| RF25 | O aplicativo permite realizar login com sua conta |  Satisfação | Depende da funcionalidade de cadastro de usuário (RF01). |
|ERF26| RF26 | O aplicativo permite rastreamento de encomendas por código |  Representação | Requer interface de rastreamento integrada com base de dados de encomendas. |
|ERF27| RF27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) |  Agregação | Parte das funcionalidades principais do aplicativo, agregando várias formas de envio. |
|ERF28| RF28 | O aplicativo possibilita ver seus pagamentos |  Representação | Requer uma interface para visualizar histórico e detalhes de pagamentos. |
|ERF29| RF29 | O aplicativo oferece uma busca por agências próximas ao seu endereço |  Recurso | Integração com serviços de localização e base de dados de agências. |
|ERF30| RF30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais |  Recurso | Integração com sistemas de cálculo de tarifas e prazos de entrega. |
|ERF31| RF31 | O aplicativo possibilita a compra de certificados digitais dos correios | Recurso | Integração com sistemas de venda e emissão de certificados digitais. |
|ERF32| RF32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo |  Recurso | Integração com sistemas de gerenciamento de contas e serviços de recarga. |
|ERF33| RF33 | O aplicativo permite visualização de mensagens | Representação | Requer uma interface que exibe mensagens recebidas pelo usuário. |
|ERF34| RF34 | O aplicativo oferece a visualização de vales postais | Representação | Necessita de uma interface que permita ao usuário visualizar informações sobre vales postais. |
|ERF35| RF35 | O aplicativo oferece uma área de busca por objetos perdidos em envios |  Agregação | Parte de um conjunto de funcionalidades de suporte ao cliente, agregando a busca por objetos perdidos. |
|ERF36| RF36 | O aplicativo fornece uma área de contato sobre violência contra a mulher |  Representação | Está relacionado à representação pois envolve a criação de uma área específica de contato. |
|ERF37| RF37 | As informações das entregas ativas e completas na página de rastreio | Representação  |  Este requisito está relacionado à representação, pois envolve a exibição de informações específicas na página de rastreio. |
|ERF38| RF38 | Filtrar o tipo de encomenda pelo tipo de entrega | Recurso |  Necessita acesso a dados categorizados das encomendas para aplicar filtros. |
|ERF39| RF39 | Assistente virtual dos correios para ajudar a executar tarefas e achar opções muitas vezes de difícil acesso pelo site. | Recurso  | Depende da implementação de um sistema de assistente virtual integrado com funcionalidades do site e aplicativo.  |
|ERF40| RF40 | Ter um chat para se comunicar diretamente com o fornecedor, e consiga ter as informações básicas do mesmo. | Alocado | Este requisito está alocado ao subsistema de comunicação com fornecedores.  |
|ERF41| RF41 | Ter um chat para se comunicar diretamente com o entregador, e consiga ter as informações dos mesmos. | Alocado  | Este requisito está alocado ao subsistema de comunicação com entregadores.  |
|ERF42| RF42 | Poder fazer os pagamentos pagamento de tributos e taxas de importação em uma página própria para essa finalidade. | Recurso | Requer integração com sistemas de pagamento e bancos, além de uma página dedicada para transações financeiras.  |
|ERF43| RF43 | O usuário deve conseguir mudar a opção de recebimento dentro do aplicativo, antes que sua encomenda seja enviada. |  Satisfação | Depende da atualização das preferências de recebimento antes do envio da encomenda.  |
|ERF44| RF44 | O usuário deve ser notificado quando o recebimento for efetuado. |  Recurso | Depende de sistemas de notificação que informem o usuário sobre o status do recebimento.  |
|ERF45| RF45 | O sistema deve permitir que o usuário reserve o locker mais perto de sua casa baseado no CEP informado, de acordo com a disponibilidade | Recurso  | Requer integração com o sistema de lockers e um mecanismo para verificar a disponibilidade baseado no CEP informado.  |
|ERF46| RF46 | O usuário deve poder mudar local de recebimento da encomenda, antes que a mesma tenha sido enviada. | Satisfação | Depende da funcionalidade de gerenciamento de endereço de entrega. |
|ERF47| RF47 | O usuário pode optar por retirar em uma agência ou caixa postal | Representação | Envolve a representação das opções de retirada no sistema. |
|ERF48| RF48 | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | Recurso | Necessita de integração com o serviço de pré-postagem. |
|ERF49| RF49 | O usuário deve ser capaz de gerenciar o carrinho de pré-postagens, podendo adicionar ou excluir uma pré-postagem | Satisfação | Depende da funcionalidade de pré-postagem (RF48). |
|ERF50| RF50 | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | Recurso | Necessita de integração com serviços de pagamento. |
|ERF51| RF51 | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | Recurso | Requer integração com a base de dados de endereços do usuário. |
|ERF52| RF52 | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | Recurso | Necessita de integração com serviços de pagamento e armazenamento seguro de dados. |
|ERF53| RF53 | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | Representação | Envolve a representação de dados na seção de achados e perdidos. |
|ERF54| RF54 | O Usuário deve ser capaz de gerenciar suas importações | Satisfação | Depende das funcionalidades de importação e gerenciamento de dados alfandegários. |
|ERF55| RF55 | O Usuário deve ser capaz de resolver situações alfandegárias | Representação | Representa as interações necessárias para resolver pendências alfandegárias. |
|ERF56| RF56 | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | Representação | Envolve a representação de dados históricos sobre situações alfandegárias. |
|ERF57| RF57 | O usuário deve ser capaz de inserir novas importações | Satisfação | Relacionado ao gerenciamento de importações (RF54). |
|ERF58| RF58 | O usuário deve ter acesso a meios de pagamento de taxas | Recurso | Necessita de integração com serviços de pagamento de taxas. |
|ERF59| RF59 | O usuário deve ser notificado sobre atualizações de importações | Satisfação | Depende do gerenciamento e monitoramento de importações. |
|ERF60| RF60 | O usuário deve poder contestar taxas e tributações | Representação | Representa a interface de contestação de taxas e tributações. |
|ERF61| RF61 | O Usuário deve ser capaz de emitir comprovante | Representação | Envolve a emissão e representação de comprovantes de transações. |
|ERF62| RF62 | O usuário deve ser capaz de emitir DIS | Representação | Relacionado à emissão e representação de documentos de importação. |
|ERF63| RF63 | A busca por itens deve ser o mais otimizada possível, com o usuário tendo a opção de filtragem para simplificar e diminuir o tempo de busca por produtos que antes se apresentariam em uma categoria única. | Satisfação | Depende da implementação de funcionalidades de busca e filtragem. |
|ERF64| RF64 | O usuário deve poder ter a total liberdade de editar suas informações e transitar pelas etapas que o sistema oferece. | Representação | Representa a interface de edição de informações do usuário. |
|ERF65| RF65 | O usuário deverá possuir uma opção para ordenar os itens de acordo com seus anseios, como: menor preço, maior preço, maior relevância ou menor. | Satisfação | Depende das funcionalidades de ordenação e filtragem de itens. |

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva][GabrielFGH] e [Ricardo Augusto][RicardoGH], 2024.</p></font>

### Requisitos Não-funcionais

<font size="2"><p style="text-align: center">Tabela 6 - Elos dos requisitos não funcionais.</p></font>

<center>

|Elo| ID Requisito | Descrição | Tipo de Relacionamento | Descrição do Relacionamento |
|:---:| ------------ | --------- | :--------------------: | --------------------------- | 
|ERNF01| RNF01 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | Satisfação | Relacionado ao RF04 para garantir segurança em caso de furto |
|ERNF02| RNF02 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | Recurso | Relacionado ao RF18 para fornecer atualizações precisas no mapa |
|ERNF03| RNF03 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | Recurso | Relacionado ao RF21 para garantir identificação rápida por QR Code |
|ERNF04| RNF04 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | Satisfação | Suporta RF22 e RF01 para resposta rápida por e-mail cadastrado |
|ERNF05| RNF05 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | Representação | Relacionado a todos os requisitos de UI para clareza e usabilidade |
|ERNF06| RNF06 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | Satisfação | Suporta RF22 para notificações por e-mail |
|ERNF07| RNF07 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | Representação | Relacionado ao RF20 para simplificação de códigos de rastreio |
|ERNF08| RNF08 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | Recurso | Relacionado ao RF12 para suporte eficiente ao cliente |
|ERNF09| RNF09 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | Representação | Relacionado ao RF16 e RF17 para acessibilidade e ajuda rápida |
|ERNF10| RNF10 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | Satisfação | Suporta RF13 para fornecer tutoriais claros e rápidos |
|ERNF11| RNF11 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status | Satisfação | Suporta RF09, RF10, RF11 e RF22 para notificações rápidas |
|ERNF12| RNF12 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | Recurso | Relacionado a todos os requisitos de UI para garantir acessibilidade |
|ERNF13| RNF13 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | Recurso | Relacionado a todos os requisitos para garantir performance eficiente |
|ERNF14| RNF14 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão | Recurso | Relacionado a todos os requisitos para garantir segurança de dados |
|ERNF15| RNF15 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas | Recurso | Relacionado ao RF03, RF18, RF19, RF20 e RF21 para respostas rápidas com relação ao status do objeto |
|ERNF16| RNF16 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm | Recurso | Relacionado ao RF27 para suporte a diversos tipos de encomendas |
|ERNF17| RNF17 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores | Recurso | Relacionado ao RF23 e RF28 para segurança em transações financeiras |
|ERNF18| RNF18 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros | Recurso | Relacionado ao RF29 para fornecer resultados precisos |
|ERNF19| RNF19 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas | Recurso | Relacionado ao RF30, que permite cálculo de preços e prazos |
|ERNF20| RNF20 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações | Responsabilidade | Relacionado ao RF31, que permite compra de certificados digitais |
|ERNF21| RNF21 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email | Recurso | Relacionado ao RF32, que oferece acompanhamento da conta e recargas |
|ERNF22| RNF22 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações | Recurso | Relacionado ao RF33, que permite visualização de mensagens |
|ERNF23| RNF23 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação | Recurso | Relacionado ao RF34, que oferece visualização de vales postais |
|ERNF24| RNF24 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas | Recurso | Relacionado ao RF35, que oferece busca por objetos perdidos |
|ERNF25| RNF25 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento | Satisfação | Relacionado ao RF36, que fornece área de contato sobre violência contra a mulher |
|ERNF26| RNF26 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial | Representação | Facilitar a navegação do usuário no aplicativo |
|ERNF27| RNF27 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior | Recurso | Compatibilidade com versões específicas de sistemas operacionais |
|ERNF28| RNF28 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status | Satisfação | Relacionado ao RF09, que permite notificações push pelo aplicativo |
|ERNF29| RNF29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | Representação | Facilitar acesso à opção de filtro de encomendas |
|ERNF30| RNF30 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | Satisfação | Relacionado ao RF09, RF10, RF11, RF14, RF22 para notificações múltiplas |
|ERNF31| RNF31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | Recurso | Garantir precisão nas informações de rastreamento |
|ERNF32| RNF32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | Satisfação | Medir satisfação do usuário com o aplicativo em lojas de aplicativos de celulares com sistema Android e IOS |
|ERNF33| RNF33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | Representação | Facilitar acesso à opção de rastreamento de encomendas |
|ERNF34| RNF34 | O chat com o entregador deve ser protegido de acessos indevidos (de acordo com as especificações de segurança do [Art. 46](#referencias-bibliograficas) da LGPD) por meio de criptografia AES-256 | Responsabilidade | Garantir segurança no chat com o entregador seguindo as especificações da LGPD |
|ERNF35| RNF35 | O usuário deve poder mudar o método de recebimento em até 3 cliques desde iniciar a ação | Satisfação | Relacionado ao RF23, que permite realizar o pagamento de impostos/taxas de importação pelo aplicativo, possibilitando a mudança de método de recebimento |
|ERNF36| RNF36 | Os ícones de opção dentro dessa funcionalidade devem ser 44x44 pixels, para melhor visualização de cada um dos ícones para pessoas com leves problemas visuais | Satisfação | Relacionado ao RF15, que permite aumentar e diminuir a fonte, melhorando a acessibilidade visual |
|ERNF37| RNF37 | A funcionalidade deve ser aparente na página principal | Representação | Relacionado ao RNF33, que exige que a opção de rastrear encomendas esteja na página principal e seja de fácil acesso |
|ERNF39| RNF39 | As informações devem ser atualizadas em tempo de execução | Satisfação | Relacionado ao RNF02, que exige atualização em tempo real da localização da entrega |
|ERNF40| RNF40 | A liberação das encomendas deve ser automática | Satisfação | Relacionado ao RF23, que permite realizar o pagamento de impostos/taxas de importação pelo aplicativo, facilitando a liberação automática das encomendas |
|ERNF41| RNF41 | Sempre que presente o documento do destinatário na encomenda, as importações devem ser inseridas automaticamente | Satisfação | Relacionado ao RF18, que permite visualizar a encomenda no mapa, garantindo a precisão das informações de importação |

</center>

<font size="2"><p style="text-align: center">Fonte: [Cláudio Henrique][ClaudioGH], 2024.</p></font>

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 20 de junho de 2024.

> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

## Referências Bibliograficas

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 21 de junho de 2024.

> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 23/06/2024 | Criação do documento | [Cláudio Henrique](https://github.com/pabloheika), [Gabriel F. J. Silva][GabrielFGH], [Ricardo Augusto][RicardoGH]  | [DaniloGH][DaniloGH]  |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

<Links das seções da análise documental>
[ADRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental
[ADRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental

<Links das seções do brainstorm>
[BSRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/#requisitos-elicitados
[BSRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/#requisitos-elicitados

<Links das seções da observação>
[OBSRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/#requisitos-nao-funcionais-rnf
[OBSRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/#requisitos-funcionais-rf

<Links das seções do questionário>
[QRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#funcionais
[QRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#nao-funcionais
