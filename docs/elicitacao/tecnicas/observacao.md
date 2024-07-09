# Observação

## Introdução

A técnica de elicitação de requisitos _Observação_, também chamada de _etnografia_, é utilizada em áreas onde se sabe da importância de obter o entendimento das interações entre pessoas com outras pessoas, instituições, seu ambiente ou máquinas e softwares. Para esse entendimento, é preciso assimilar o que as pessoas conhecem sobre alguma área e como esse conhecimento é criado, transmitido, distribuído e aplicado <a id="a" href="#aa">[1]</a>.

Uma das variações dessa técnica é a abordagem por aprendiz, em que o analista de requisitos atua como um novato no sistema que será observado pela equipe, com o intuito de aprender como executar o sistema. Essa será a técnica utilizada pelo grupo, em que um integrante irá representar um aprendiz do sistema, e outro irá ter a tarefa de observar o aprendiz utilizando o aplicativo.

## Metodologia

A aplicação da técnica de observação foi realizada por dois integrantes do grupo, e foi implementada a abordagem por aprendiz descrita no tópico anterior. Um integrante do grupo foi o representante de um aprendiz do sistema e outro foi o observador.

A reunião dos [integrantes](#tabelaIntegrantes) ocorreu no dia 16 de abril de 2024, às 17h, para implementarem a técnica de elicitação por observação. Previamente, foi definido que o aprendiz vai começar fazendo seu login no aplicativo, posteriormente ele irá passar pelas funcionalidades presentes na tela inicial do aplicativo, e para finalizar ele deverá acessar as funcionalidades presentes no menu da esquerda presente no aplicativo. Para essa técnica, o observador participou de maneira passiva da observação, não influenciando e não dando dicas/sugestões para o aprendiz.

Para a documentação da técnica, o aprendiz do sistema gravou a tela do celular mostrando as ações realizadas por ele dentro do aplicativo, o link para a gravação se encontra [aqui](#video). Durante a análise, foram levantados os requisitos observados, presentes nas tabelas [2](#tabelaRequisitosFuncionais) e [3](#tabelaRequisitosNaoFuncionais).

### Participantes

<center>
<a name="tabelaIntegrantes"></a>
<font size="2"><p>
    <b>Tabela 1</b> - Integrantes participantes da técnica
</p></font>

| Integrante | Tarefa |
|:-:|:-:|
| [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) | Representante do aprendiz |
| [Ricardo Augusto](https://github.com/avmricardo) | Observador |

<font size="2"><p>Fonte: [Ricardo Augusto](https://github.com/avmricardo), 2024.</p></font>
</center>

### Gravação

A execução da técnica foi documentada por meio de vídeo que se encontra abaixo.

<center>
<a name="video"></a>
<iframe width="560" height="315" src="https://www.youtube.com/embed/PVUJ4Stf4pU?si=6RG3A9vCvF-DiJwX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

Após a execução, os integrantes se reuniram para poder fazer a análise do vídeo e realizar a elicitação dos requisitos.

## Requisitos elicitados

Neste tópico estão descritos os requisitos elicitados a partir da técnica de observação. Abaixo se encontra a legenda para as tabelas de requisitos:

Legenda:

- RFxx: Requisito funcional número xx;
- RNFxx: Requisito não funcional número xx;
- OBSxx: Requisito elicitado pela técnica de observação número xx.

### Requisitos Funcionais (RF)

<center>
<font size="2"><p>
    <b>Tabela 2</b> - Requisitos Funcionais 
</p></font>

| Tipo | Descrição | ID | Implementado | Versão |
|-|-|-|-|-|
| RF01 | O aplicativo permite realizar login com sua conta | OBS01 | Sim | `1.0` |
| RF02 | O aplicativo permite rastreamento de encomendas por código. | OBS02 | Sim | `1.0` |
| RF03 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | OBS03 | Sim | `1.0` |
| RF04 | O aplicativo possibilite ver seus pagamentos | OBS04 | Sim | `1.0` |
| RF05 | O aplicativo oferece uma busca por agências próximas ao seu endereço | OBS05 | Sim | `1.0` |
| RF06 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | OBS06 | Sim | `1.0` |
| RF07 | O aplicativo possibilita a compra de certificados digitais dos correios | OBS07 | Sim | `1.0` |
| RF08 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | OBS08 | Sim | `1.0` |
| RF09 | O aplicativo permite visualização de mensagens | OBS09 | Sim | `1.0` |
| RF10 | O aplicativo oferece a visualização de vales postais | OBS10 | Sim | `1.0` |
| RF11 | O aplicativo oferece uma área de busca por objetos perdidos em envios | OBS11 | Sim | `1.0` |
| RF12 | O aplicativo fornece uma área de contato sobre violência contra a mulher | OBS12 | Sim | `1.0` |


<font size="2"><p>Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), [Ricardo Augusto](https://www.github.com/avmricardo), 2024.</p></font>
</center>

### Requisitos Não Funcionais (RNF)

=== "1.0"
    Legenda Requisitos das tabelas:

    - RNFx: Requisito Não-Funcional nºx
    - OBSx: Requisito nºx elicitado pela Observação.

    <font size="3"><p style="text-align: center">Tabela 3: Requisitos Não Funcionais versão 1.0.</p></font>

    <center>

    | Tipo | Descrição | ID | Implementado | Versão |
    |-|-|-|-|-|
    | RNF01 | O aplicativo deve manter a privacidade dos dados do usuário. | OBS13 | Sim | `1.0` |
    | RNF02 | O sistema de rastreamento de encomendas deve ser rápido e eficiente | OBS14 | Sim | `1.0` |
    | RNF03 | O sistema de envio de encomendas deve ser robusto o suficiente para lidar com diferentes tipos de objetos | OBS15 | Sim | `1.0` |
    | RNF04 | O acesso aos pagamentos deve ser protegido por autenticação do usuário | OBS16 | Não | `1.0` |
    | RNF05 | A busca por agências deve ser precisa e baseada na localização do usuário | OBS17 | Sim | `1.0` |
    | RNF06 | O cálculo de preços e prazos de encomendas deve ser preciso e rápido | OBS18 | Sim | `1.0` |
    | RNF07 | A compra de certificados digitais deve ser segura e protegida | OBS19 | Sim | `1.0` |
    | RNF08 | O acompanhamento da conta e recargas devem ser realizados de forma segura e confiável | OBS20 | Sim | `1.0` |
    | RNF09 | A visualização de mensagens deve ser rápida e fácil de usar | OBS21 | Sim | `1.0` |
    | RNF10 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado | OBS22 | Sim | `1.0` |
    | RNF11 | A busca por objetos perdidos deve ser eficiente e precisa | OBS23 | Sim | `1.0` |
    | RNF12 | A área de contato sobre violência contra a mulher deve ser sensível e oferecer suporte adequado | OBS24 | Sim | `1.0` |
    | RNF13 | O aplicativo requer uma interface amigável e fácil de usar. | OBS25 | Sim | `1.0` |
    | RNF14 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones. | OBS26 | Sim | `1.0` |
    | RNF15 | O aplicativo deve fornecer notificações sobre o status da entrega. | OBS27 | Sim | `1.0` |

    </center>

    <font size="2"><p style="text-align: center">FFonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), [Ricardo Augusto](https://www.github.com/avmricardo), 2024.</p></font>

=== "2.0"
    
    Legenda Requisitos das tabelas:

    - RNFx: Requisito Não-Funcional nºx
    - OBSx: Requisito nºx elicitado pela Observação.

    <font size="3"><p style="text-align: center">Tabela 4: Requisitos Não Funcionais versão 2.0.</p></font>

    <center>

    | Tipo | Descrição | ID | Implementado | Versão |
    |--------|-----------|------------|-----------|--------|
    | RNF01 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão. | OBS13 | Sim | `2.0` |
    | RNF02 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas. | OBS14 | Sim | `2.0` |
    | RNF03 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm. | OBS15 | Sim | `2.0` |
    | RNF04 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores. | OBS16 | Não | `2.0` |
    | RNF05 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros. | OBS17 | Sim | `2.0` |
    | RNF06 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas. | OBS18 | Sim | `2.0` |
    | RNF07 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações. | OBS19 | Sim | `2.0` |
    | RNF08 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email. | OBS20 | Sim | `2.0` |
    | RNF09 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações. | OBS21 | Sim | `2.0` |
    | RNF10 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação. | OBS22 | Sim | `2.0` |
    | RNF11 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas. | OBS23 | Sim | `2.0` |
    | RNF12 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento. | OBS24 | Sim | `2.0` |
    | RNF13 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial. | OBS25 | Sim | `2.0` |
    | RNF14 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior. | OBS26 | Sim | `2.0` |
    | RNF15 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status. | OBS27 | Sim | `2.0` |

    </center>

    <font size="2"><p style="text-align: center">FFonte: [Ricardo Augusto](https://www.github.com/avmricardo), 2024.</p></font>

## Bibliografia 

> <a id="a" href="#aa">1.</a> CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016.

> <a id="b" href="#bb">2.</a> Correios. Disponível em: <https://apps.apple.com/br/app/correios/id1399617917>. Acesso em: 17 abr. 2024.

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor |
| --- | --- | --- | --- | --- |
| `1.0` | 17/04/2024 | Criação do documento | [Ricardo Augusto](https://www.github.com/avmricardo), [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) | [Pablo S. Costa](https://www.github.com/pabloheika) |
| `1.1` | 23/06/2024 | Refatoração dos requisitos não funcionais | [Ricardo Augusto](https://www.github.com/avmricardo) | [Gabriel F. J. Silva](https://www.github.com/MMcLovin) |
