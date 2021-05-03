# Histórias de Usuários


## Introdução

<p align = "justify">A verificação do <a href="https://requisitos-de-software.github.io/2020.2-BikeItau/modelagem/nfrFramework/#nfr-suportabilidade">NFR Framework</a> (Non-Functional requiriments) é a parte do projeto onde é feita uma análise para verificar se o artefato atende as qualidades levantadas e sugeridas. Portanto, é uma atividade para revisões de documentação e estudo de viabilidade. </p>
<br/>


## Metodologia

<p align = "justify"> Para cumprir o principal objetivo dessa atividade, a verificação do NFR, foi realizado um método de levantamento de Questão, para atestar a qualidade e objetivar o que pretende que se cumpra, e justificar o motivo dessas questões. Formando um quadro para as Questões e suas Justificativas e depois por método de verificação por Inspeções, uma forma de checagem, e por meio de checklist para verificar se determinada questão, levantada e justificada como critério de verificação e qualidade, cumpre com o esperado, marcando com ( :heavy_check_mark: ) ou se pode ser melhorado de alguma forma, destacando com ( :x: ).</p>
<br/>

## NFR Indentificação

| **ID** | **NFR Identificação** |
| :--- | :--- |
| NFR01 | NFR Geral |
| NFR02 | NFR Usabilidade |
| NFR03 | NFR Confiabilidade |
| NFR04 | NFR Desempenho |
| NFR05 | NFR Suportabilidade |

  

### Questões e Justificativas

| **Questões** | **Justificativas** |
| :--- | :--- |
|  1. Conceito de NFR é apresentado? | Importante para o leitor entender o conceito da metodologia usada.  |
|  2. Legenda dos Símbolos e tipos de contribuições. | Necessário para compreender as ligações entre os símbolos e seus significados.  |
|  3. Softgoal NFR bem definidos? | Os softgoals devem ser claros e autoexplicativos, o que facilita nas tomadas de decisões posteriores, para uma forma hierárquica no diagrama.  |
|  4. Softgoals NFR decompostos em operações | O Softgoal decompõe em operações hierárquicas de tarefas, em forma de gráfico, e concisa, até Softgoal de Operacionalização.  |
|  5. Softgoals de Operacionalização é uma solução? | Os Softgoals de Operações representam soluções de implementação para os Softgoals NFR ou outro Softgoal de Operacionalização.  |
|  6. Softgoal Interdependency Graph (SIG) está coerente? | A forma gráfica registra as considerações do desenvolvedor sobre os softgoals e mostra suas interdependências. | 
|  8. A lógica do SIG está clara? | A hierárquica deve se desenvolver em lógica clara e concisa.  |
|  9. Está redundante? | Não deve existir mais de uma operação utilizando o mesmo nome, para não haver redundância nas ações. |
|  10. Está ambíguo? | O NFR deve está claro em todo seu conjunto e lógica de desenvolvimento. O objetivo deve possuir seu valor qualitativo claro para ter total entendimento do que se trata. |
|  11. Está inconsistente? | A hierárquia proposta por um Softgoal, a mesma lógica de operações não pode chegar a operações com significados diferentes. |
|  12. Está incompleto? | O gráfico deve possuir todas informações para deixar o objetivo claro para todos. |
| Possui versionamento | Deve possuir controle de versionamento para identificar os autores e o progresso das atividades. |


## Inspeção

| **Critério de qualidade (Questões)** | **NFR01** | **NFR02** | **NFR03** | **NFR04** | **NFR05** |
| :--- | :---: | :---: | :---: | :---: | :---: |
| 1. Conceito de NFR é apresentado?  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2. Legenda dos Símbolos e tipos de contribuições.  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 3. Softgoal NFR bem definidos?  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 4. Softgoals NFR decompostos em operações | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 5. Softgoals de Operacionalização é uma solução? | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 6. Softgoal Interdependency Graph (SIG) está coerente? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 7. A lógica do SIG está clara? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 8. Está redundante? | :x: | :x: | :x: | :x: | :x: |
| 9. Está ambíguo? | :x: | :x: | :x: | :x: | :x: |
| 10. Está inconsistente? | :x: | :x: | :x: | :x: | :x: |
| 11. Está incompleto? | :x: | :heavy_check_mark: | :heavy_check_mark: | :x: | :x: |
| 12. Possui versionamento | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Quantidade de sucesso | 100% | 83% | 91% | 100% | 100% |
| Classificação  | Bom | Regular | Regular | Bom | Bom |

!!! Observação
    Algumas questões (8,9,10 e 11) se receberem a negação, significa aceitação da qualidade no teste.

## Melhorias Propostas

| **NFR ID** | **Questão ID** | **Melhorias** |
| :---: | :---: | :--- |
| NFR02  | 5.  | Detalhar o que seria uma interface Simplista. |
| NFR02  | 5.  | Detalhar melhor o que seria uma Interface Intuitiva. |
| NFR02  | 11. |  Softgol de Operações para detalhar melhor o Softgol de Inferface simplista.  |
| NFR02  | 11. |  Softgol de Operações para detalhar melhor o Softgol de Inferface Intuitiva.  |
| NFR02  | 11. |  Explicitar quais opções de idiomas.  |
| NFR02  | 11. |  Adicionar Softgoal explicitando os sistemas e versões que suportam a aplicação.  |
| NFR03  | 11. |  Adicionar Softgoal “Transparência com Usuário” ligando a um novo Softgoal de Operação “Termo de Uso”. |



## Referências

 MATSUMOTOA, Yuuma. SHIRAIA, Sayaka. OHNISHIA, Atsushi. [A Method for Verifying Non-Functional Requirements](https://www.sciencedirect.com/science/article/pii/S1877050917313455), acessado dia 14 de Abril de 2021.


## Bibliografia

> SILVA, Reinaldo. **NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados**. Programa de Pós-Graduação. Universidade Federal de Pernambuco. Recife, 2019.

---

> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 019. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Revisões

| Data | Versão | Descrição | Autor(es) |
| :----: | :----: | :----: | :----: |
| 14/04/2021 | 1.0 | Criação do documento | [Tomás veloso](https://github.com/tomasvelos0) |