## Introdução

Neste artefato, está descrito os resultados da verificação do artefato de [Backlog][Backlog] feito pelo [Grupo 03][Grupo 03 Correios] da disciplina de Requisitos de Software, e referente ao aplicativo [Correios](https://correios.com.br). Lembrando que o foco não é apontar quem errou e sim os problemas presentes no artefato produzido, e por fim garantir os critérios de qualidade estabelecidos.

## Metodologia

Este artefato foi verificado por [Pablo][PabloGH], seguindo a divisão planejada pelo grupo na [reunião 7](https://requisitos-de-software.github.io/2024.1-Correios/atas/ata7/). Adotamos a metodologia de inspeção por [checklist](#checklist-de-verificacao) neste processo. Para cada item do checklist, será atribuído uma avaliação entre "Sim", "Não" ou "Incompleto". A lista de verificação também conta tanto com uma coluna de descrição do item em verificação quanto outra para a fonte que o fundamenta. Ao final, será comentado os itens negativos na seção de [Problemas Encontrados](#problemas-encontrados).

## Apresentação dos Dados

Abaixo, nas Tabela 1 e 2, temos respectivamente o checklist elaborado para a verificação e outro já preenchido com base no artefato em questão. Logo após, temos também a gravação da verificação realizada.

### Checklist de verificação

<font size="2"><p style="text-align: center">Tabela 1 - Perguntas elaboradas de acordo com os objetivos.</p></font>

<center>

| ID | Descrição | Avaliação | Referência | Print |
|:--:| --------- | :-------: | :--------: | :---: |
| **1** | O backlog contém uma lista dos requisitos a serem implementados? | Sim | <a href="#ref1">1</a> | [pg 38][REF1-pg38] |
| **2** | Os requisitos estão descritos como histórias de usuário? | Sim | <a href="#ref1">1</a> | [pg 38][REF1-pg38] |
| **3** | Os requisitos estão priorizados? | Não | <a href="#ref1">1</a> | [pg 38][REF1-pg38] |
| **4** | Os requisitos foram priorizados com a participação do PO? | Não se aplica | <a href="#ref2">2</a> | [pg 41][REF2-pg41] |
| **5** | Caso o PO tenha sido envolvido na priorização, foi apresentado à ele um termo de consentimento para participar no projeto? | Não se aplica | <a href="#ref3">3</a> | [pg 141][REF3-pg141] |

</center>

<font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

### Gravação da verificação

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/V-3KWMkG-hI" title="Entrega 5.1 (Verificação grupo + 1) - Verificação do Backlog" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[https://youtu.be/V-3KWMkG-hI](link)

</center>


### Problemas Encontrados

*   ID 3: Os requisitos estão priorizados?
    *   Avaliação: Não
    *   Comentário: Não há a priorização dos requisitos.

*   ID 4: Os requisitos foram priorizados com a participação do PO?
    *   Avaliação: Não se aplica
    *   Comentário: Não há participação do PO nem a priorização.

*   ID 5: Caso o PO tenha sido envolvido na priorização, foi apresentado à ele um termo de consentimento para participar no projeto?
    *   Avaliação: Não se aplica
    *   Comentário: Não há a participação do IPO nem a priorização por isso não se aplica

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
    "Sim" : 2
    "Não" : 1
    "Não se Aplica" : 2
```

</center>

<font size="2"><p style="text-align: center">Fonte: [Pablo][PabloGH], 2024.</p></font>

## Bibliografia
>1. Lino, Ester. **Backlog do Projeto**. Repositório do grupo GOV.br da disciplina de Requisitos de Software da Universidade de Brasília, 2024. Disponível em: https://requisitos-de-software.github.io/2024.1-Gov.br/#/modelagem/agil/backlog. Acesso em: 09 maio 2023.


## Referências Bibliográficas

> 1<a id="ref1">.</a> **ISO/IEC/IEEE International Standard - Systems and software**. engineering--Vocabulary. ISO/IEC/IEEE 24765:2017(E) , vol., no., pp.1-541, 28 August of 2017. Disponível em: <https://ieeexplore.ieee.org/document/8016712>. Acesso em: 28 de Junho de 2024
>
> 2<a id="ref2">.</a> Wiegers, K.E. **(2013) Software Requirements, 3rd Edition**. Microsoft Press, Redmond. Acesso em: 09 de Junho de 2024
>
> 3<a id="ref3">.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021). **Interação Humano-Computador e Experiência do usuário**. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em: 09 de Junho de 2024

[REF1-pg38]: ../../../../assets/prints_verificacao/gabrielF/Backlog%20ref1%20-%20pg38.jpeg
[REF2-pg41]: ../../../../assets/prints_verificacao/gabrielF/Backlog%20ref2%20-%20pg41.jpeg
[REF3-pg141]: ../../../../assets/prints_verificacao/gabrielF/Backlog%20ref3%20-%20pg141.jpeg 

[Grupo 03 Correios]: https://requisitos-de-software.github.io/2024.1-Correios/
[Backlog]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/backlog/

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 29/06/2024 | Criação do documento | [Elias F. Oliveira][EliasGH] | [Claudio H.][ClaudioGH] |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo