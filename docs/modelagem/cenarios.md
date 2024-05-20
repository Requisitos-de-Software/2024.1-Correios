## Introdução
Os cenários são parte da composição de um caso de uso. Em um cenário temos diferentes passos que os desdobram a partir de um evento que o inicia e das condições que afetam seu comportamento. Sua descrição explora alguns pontos, são eles: como e quando um caso de uso começa, quando um caso de uso interage com os autores e quais dados eles trocam entre si, quando os casos de uso referencia ou mantém dados, como e quando os casos de uso terminam. Na descrição do cenário não abordamos aspectos de interface gráfica com o usuário, ou qualquer requisito funcional. Com isso identificaremos os cenários para identificar os os casos de uso em nosso trabalho sobre os sites dos correios.

## Metodologia
Como metodologia, usamos o método em que um cenário deve ter os seguintes elementos característicos: contexto, atores, objetivos, planejamento, ações, eventos e avaliações (CARROLL, 2002; COOPER, 1999), sendo feito da maneira apresentada na Tabela 01, com o título de cada atributo e uma descrição do mesmo.

<font size="2"><p style="text-align: center">Tabela 01 - estrutura de um cenário.</p></font>

| **Elemento** | **Descrição** |
| | |
| **Título** | Um nome que identifica o cenário. |  
| **Objetivo** | A finalidade do cenário.  |
| **Contexto** | Descreve o estado inicial do cenário, suas pré-condições e locais físicos e tempo. |
| **Atores** | Pessoa ou estruturaorganizacional que tem o papel no cenário. |
| **Recursos** | Identifica os objetos passivos com os quais lidam os atores. |
| **Episódios** | Cada episódio apresenta uma ação realizada por um ator onde participam outros atores utilizando os recursos disponíveis, um episódio pode pertencer a outro cenário, e  neles podemos ter restrições e exceções. As restrições são qualquer coisa que restrinja um episódio de um cenário. Uma exceção é o tratamento para uma ação excepsional ou de erro. |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024</p></font>

## Cenários 

### 1. Calcular preços e prazos de entrega

| **Elemento** | **Descrição** |
| | |
| **Título** | |
| **Objetivo** | |
| **Contexto**| **Local**:  <br><br> **Tempo**:  <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> oi </ul>|
| **Atores** | |
| **Recursos** | |
| **Episódios** | |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [](), 2024.</p></font>

### 2. Realizar compras na loja online

| **Elemento** | **Descrição** |
| | |
| **Título** | Realizar uma compra na loja online. |  
| **Objetivo** |  Comprar selos na loja online dos correios. |
| **Contexto**| **Local**: Escritório do trabalho. <br><br> **Tempo** Meio da tarde.:  <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> Possuir um celular com conexão à internet. <li>Possuir um cadastro e estar logado no app dos correios. <li> Acessar a loja online dos correios. <li> Possuir um endereço para o recebimento de uma encomenda. <li> Possuir meios para realizar o pagamento do valor referente ao produto escolhido. </ul>|
| **Atores** | Usuário do aplicativo e site dos correios. |
| **Recursos** | Celular. <br>Acesso à internet. <br> CEP e informações do endereço para a entrega.  |
| **Episódios** | O usuário acessa a o ambiente da loja online dos correios; <br><br> Busca pelos selos desejados inserindo a temática deles no campo de busca; <br><br> Encontra os selos desejados e clica no item; <br><br> Adiciona ao carrinho clicando em comprar; <br><br> Altera a quantidade de itens e insere o CEP do destinatári; <br><br> Confere os dados de envio e dos itens escolhidos; <br><br> Escolhe a opção de pagamento por cartão de crédito; <br><br> Insere as informações do cartão e finaliza a compra.|
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira](https://www.github.com/EliasOliver21), 2024.</p></font>

### 3. Emitir certificados digitais

| **Elemento** | **Descrição** |
| | |
| **Título** | |
| **Objetivo** | |
| **Contexto**| **Local**:  <br><br> **Tempo**:  <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> oi </ul>|
| **Atores** | |
| **Recursos** | |
| **Episódios** | |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [](), 2024.</p></font>

### 4. Realizar pré-postagem

| **Elemento** | **Descrição** |
| | |
| **Título** |Realizar pré-postagem |  
| **Objetivo** | Abrir o aplicativo dos correios e realizar a tarefa de fazer uma pré-postagem |
| **Contexto** | **Local**: casa do usuário <br><br> **Tempo**: início da noite <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li>Aplicativo instalado <li>Acesso à internet <li>Possuir conta no aplicativo <li>Conhecimento das informações de preenchimento obrigatório <li>Dinheiro para pagar a pré-postagem </ul>|
| **Atores** | Usuário do aplicativo dos Correios e sistema do aplicativo dos Correios |
| **Recursos** | Aparelho celular <br><br> Internet <br><br> Conta no aplicativo dos Correios <br><br> Informações sobre o endereço do remetente e do destinatário <br><br> Informações sobre a encomenda <br><br> Meio de pagamento |
| **Episódios** | Usuário acessa a tela de pré-postagem <br><br> Usuário realiza login <br><br> Aplicativo carrega endereço do remetente a partir do endereço principal na conta do usuário <br><br> Usuário insere CEP do destinatário <br><br> Apliativo carrega informações do destinatário a partir do CEP fornecido <br><br> Usuário insere nome, email e número do endereço do destinatário <br><br> Usuário informa tipo da embalagem <br><br> Usuário fornece dimensões da embalagem <br><br> Usuário escolhe serviço SEDEX <br><br> Usuário fornece dados da nota fiscal eletrônica do produto da encomenda <br><br> Usuário confere informações e adiciona postagem ao carrinho <br><br> Usuário escolhe pagar com cartão <br><br> Aplicativo gera pop-up de confirmação do meio de pagamento <br><br> Usuário confirma meio de pagamento, preenche dados do cartão e finaliza a compra |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](GabrielfGH), 2024.</p></font>

### 5. Gerenciar minhas importações

| **Elemento** | **Descrição** |
| | |
| **Título** | |
| **Objetivo** | |
| **Contexto**| **Local**:  <br><br> **Tempo**:  <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> oi </ul>|
| **Atores** | |
| **Recursos** | |
| **Episódios** | |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa](PabloGH), 2024.</p></font>

### 6. Rastrear encomendas

| **Elemento** | **Descrição** |
| | |
| **Título** | |
| **Objetivo** | |
| **Contexto**| **Local**:  <br><br> **Tempo**:  <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> oi </ul>|
| **Atores** | |
| **Recursos** | |
| **Episódios** | |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto](RicardoGH), 2024.</p></font>

### 7. Buscar por documentos perdidos :

| **Elemento** | **Descrição** |
| | |
| **Título** | Buscar por Documentos Perdidos |
| **Objetivo** | Permitir ao usuário do aplicativo dos Correios verificar se seus documentos perdidos foram encontrados e estão disponíveis para retirada. |
| **Contexto** | **Local**: Qualquer local com acesso ao aplicativo dos Correios <br><br> **Tempo**: Qualquer horário <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li>Aplicativo instalado <li>Acesso à internet <li>Possuir conta no aplicativo <li>Informações sobre o tipo de documento e nome completo </ul>|
| **Atores** | Usuário do aplicativo dos Correios <br><br>Sistema do aplicativo dos Correios |
| **Recursos** | Aparelho celular <br><br> Internet <br><br> Conta no aplicativo dos Correios <br><br> Informações sobre os documentos perdidos |
| **Episódios** | Usuário acessa a tela de busca por documentos perdidos <br><br> Usuário seleciona o tipo de documento <br><br> Usuário insere o nome completo <br><br> Usuário clica no botão "Buscar" <br><br> Aplicativo verifica nos registros de achados e perdidos <br><br> Aplicativo exibe resultados indicando se o documento foi encontrado ou não <br><br> Caso encontrado, aplicativo fornece informações sobre a agência onde o documento pode ser retirado <br><br> Usuário pode optar por mais informações ou instruções de retirada |
| **Exceções** | |
| **Restrições** | |

<font size="2"><p style="text-align: center"> Fonte: [Danilo Carvalho Antunes](DaniloGH), 2024.</p></font>

## Bibliografia
> 1. Engenharia de Requisitos - Sheila Reinehr. Acesso 15 de maio de 2024.
> 2. BERGMANN, Ulf; LEITE, Julio Cesar S. do Prado; BREITMAN, Karin Koogan. Um Mecanismo de Rastreamento da Evolução de Cenários Baseado em Transformações. Anais do Simpósio Brasileiro de Engenharia de Software (SBES), [S.l.], p. 63-78, out. 2003. ISSN 0000-0000. Disponível em: <https://sol.sbc.org.br/index.php/sbes/article/view/23853>. Acesso em: 18 maio 2024.
> 3. Slides professora Milene presente no site do aprender da matéria de requisitos, disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1218860>. Acesso em: 18 de maio de 2024.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 15/04/2024 | Criação do documento | [Gabriel B. Bertolazi](https://github.com/Bertolazi) | |