# Verificação do Artefato NFR FrameWork

## Introdução

Neste artefato, está descrito os resultados da verificação do artefato de [NFR FrameWork](https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/nfr-framework/) feito pelo [Grupo 03](https://requisitos-de-software.github.io/2024.1-Correios/) da disciplina de Requisitos de Software referente ao aplicativo [Correios](https://www.correios.com.br/). Lembrando que o foco não é apontar quem errou e sim os problemas presentes no artefato produzido, e por fim garantir os critérios de qualidade estabelecidos.

## Metodologia

Este artefato foi produzido por [Danilo][DaniloGH] e verificado por [Pablo S. Costa][PabloGH], seguindo a divisão planejada pelo grupo na [reunião 7](https://requisitos-de-software.github.io/2024.1-Correios/atas/ata7/). Para a verificação do artefato, foi utilizada a versão `1.0` datada do dia 23/05/2024. Adotamos a metodologia de inspeção por [checklist](#checklist-de-verificacao) neste processo. Podemos ver pela Tabela 1 de exemplo, que para cada item do checklist teremos: descrição do item em verificação, resposta à avaliação (pode ser "Sim", "Não", "Incompleto" ou "Não se Aplica"), o número da referência bibliográfica e um link para um print da referência que o fundamenta o item. Ao final, na seção de [Problemas Encontrados](#problemas-encontrados), são comentados os itens negativos.

<font size="2"><p style="text-align: center">Tabela 1 - Modelo da Verificação do NFR.</p></font>

<center>

| ID  | Descrição                                                                                                               | Avaliação | Referência          | Print |
|:--:|-------------------------------------------------------------------------------------------------------------------------|:---------:|:-------------------:|:-----:|
| **1** | O artefato possui uma visão geral clara do NFR Framework?                                                              |           | [1.](#ref1)         | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **2** | O artefato descreve adequadamente o Softgoal Interdependency Graph (SIG)?                                              |           | [1.](#ref1)         | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **3** | O artefato define claramente os tipos de Softgoals usados no NFR Framework?                                            |           | [1.](#ref1)         | [página 31](../../../../assets/prints_verificacao/danilo/NFR_Pagina31.jpeg) |
| **4** | O artefato apresenta exemplos de interdependências entre os Softgoals?                                                 |           | [1.](#ref1)         | [página 31](../../../../assets/prints_verificacao/danilo/NFR_Pagina31.jpeg) |
| **5** | O artefato descreve o procedimento de avaliação dos Softgoals?                                                         |           | [1.](#ref1)         | [página 37](../../../../assets/prints_verificacao/danilo/NFR_Pagina37.jpeg) |
| **6** | O artefato fornece uma visão geral das interdependências e contribuições entre Softgoals?                              |           | [1.](#ref1)         | [página 32](../../../../assets/prints_verificacao/danilo/NFR_Pagina32.jpeg) |
| **7** | O artefato inclui uma discussão sobre a importância dos Requisitos Não-Funcionais (RNFs) desde o início do projeto?    |           | [1.](#ref1)         | [página 38](../../../../assets/prints_verificacao/danilo/NFR_Pagina38.jpeg) |
| **8** | O artefato descreve os elementos que compõem o grafo SIG, como softgoals e interdependências?                          |           | [1.](#ref1)         | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **9** | O artefato menciona a utilização de catálogos de requisitos descritos na notação adotada pelo NFR Framework?           |           | [1.](#ref1)         | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **10** | O artefato apresenta o conceito de refinamentos de Softgoals e suas contribuições para o desenvolvimento do projeto?  |           | [1.](#ref1)       | [página 31](../../../../assets/prints_verificacao/danilo/NFR_Pagina31.jpeg) |

</center>

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes](DaniloGH), 2024.</p></font>

## Apresentação dos Dados

Aqui será apresentado os resultados do checklist e logo após as observações dos itens com resultado negativo.

### Checklist de verificação

<font size="2"><p style="text-align: center">Tabela 2 - Verificação.</p></font>

<center>

| ID | Descrição | Avaliação | Referência | Print |
| --- | --- | --- | --- | --- |
| **1** | O artefato possui uma visão geral clara do NFR Framework? | Sim | [1.](#ref1) | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **2** | O artefato descreve adequadamente o Softgoal Interdependency Graph (SIG)? | Sim | [1.](#ref1) | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **3** | O artefato define claramente os tipos de Softgoals usados no NFR Framework? | Sim | [1.](#ref1) | [página 31](../../../../assets/prints_verificacao/danilo/NFR_Pagina31.jpeg) |
| **4** | O artefato apresenta exemplos de interdependências entre os Softgoals? | Sim | [1.](#ref1) | [página 31](../../../../assets/prints_verificacao/danilo/NFR_Pagina31.jpeg) |
| **5** | O artefato descreve o procedimento de avaliação dos Softgoals? |   | [1.](#ref1) | [página 37](../../../../assets/prints_verificacao/danilo/NFR_Pagina37.jpeg) |
| **6** | O artefato fornece uma visão geral das interdependências e contribuições entre Softgoals? | Sim | [1.](#ref1) | [página 32](../../../../assets/prints_verificacao/danilo/NFR_Pagina32.jpeg) |
| **7** | O artefato inclui uma discussão sobre a importância dos Requisitos Não-Funcionais (RNFs) desde o início do projeto? | Sim | [1.](#ref1) | [página 38](../../../../assets/prints_verificacao/danilo/NFR_Pagina38.jpeg) |
| **8** | O artefato descreve os elementos que compõem o grafo SIG, como softgoals e interdependências? | Sim | [1.](#ref1) | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **9** | O artefato menciona a utilização de catálogos de requisitos descritos na notação adotada pelo NFR Framework? | Sim | [1.](#ref1) | [página 30](../../../../assets/prints_verificacao/danilo/NFR_Pagina30.jpeg) |
| **10** | O artefato apresenta o conceito de refinamentos de Softgoals e suas contribuições para o desenvolvimento do projeto? | Sim | [1.](#ref1) | [página 31](../../../../assets/prints_verificacao/danilo/NFR_Pagina31.jpeg) |

</center>

<font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

### Gravação da verificação

<div style="text-align: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/y6lqOPD0raw" title="Apresentação 7 Interação Humano Computador 2024.1 - Grupo 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<p style="text-align: center">
    <a href="https://youtu.be/y6lqOPD0raw"> Link para o vídeo </a>
</p>

### Problemas Encontrados

- ID 5: O artefato descreve o procedimento de avaliação dos Softgoals?
    - Avaliação:
    - Comentário: Não encontrei referências a este problema nem na bibliografia informada ou no print mostrado ou no arquivo avaliado.

### Sumário dos resultados

<!-- Conte as quantidade de ocorrencias e coloque no Grafico a quantidade em cada tipo de avaliação (se não ouver incidencia de um tipo como "não se aplica", apague a linha do mesmo)-->
A seguir, apresentamos a Figura 1 com o gráfico de pizza do sumário dos resultados.

<font size="2"><p style="text-align: center">Figura 1 - Gráfico de pizza do sumário dos resultados.</p></font>

<center>

``` mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
        'primaryColor': '#FFD400',
        'secondaryColor': '#0083CA',
        'tertiaryColor': '#CD992B',
        'pie4': '#00416B',
        'primaryTextColor': '#8e8e8e',
        'pieStrokeWidth': '0px',
        'pieOuterStrokeWidth': '0px',
        'pieOpacity': '1',
        'pieSectionTextColor': '#fff',
        'pieSectionTextSize': '19px'
    }
  }
}%%
pie
    "Sim" : 9
    "Não respondido" : 1
```

</center>

<font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

## Bibliografia

> 1. <a id="ref1"> </a>Dissertação de mestrado: "NFR4ES: um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados" de Reinaldo Antônio da Silva, de 2019. Acesso em: 29 de junho de 2024.
 

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 29/06/2024 | Criação do documento | [Danilo Carvalho Antunes][DaniloGH] | [Gabriel F.][GabrielFGH] |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

