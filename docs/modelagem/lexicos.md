# Léxicos



## Introdução 

<p align = "justify"> A técnica do Léxico tem como principal objetivo explicar símbolos ou termos usados por determinada comunidade para a compreensão de todos envolvidos no mesmo projeto. Portanto, torna-se uma fonte de consulta dos participantes do projeto para compreender os termos usados, e assim compartilharem do mesmo conhecimento e linguagem.</p>

## Metodologia

<p align = "justify"> Durante o desenvolvimento desta técnica de modelagem de requisitos, usamos vocábulos e símbolos em ordem alfabética para descrever os léxicos mais importantes encontrados no aplicativo Bike Itaú. Os léxicos foram definidos usando suas noções e impactos na aplicação, que significam os significados e efeitos causados por cada léxico.</p>

### L01 - Bike

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Bike | Veículo de duas rodas, sendo a traseira acionada por um sistema de pedais que movimentam uma corrente transmissora | Forma como o aplicativo apresenta "bicicleta" para o [Usuário](#l08-usuario). | Bicicleta | Objeto |

### L02 - Cartão de Desbloqueio

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Cartão de Desbloqueio | Cartão que é usado para retirada de [Bike](#l01-bike) nas [Vagas](#l07-vagas) | Cartão que pode ser solicitado pelo [Usuário](#l08-usuario) para a retirada da [Bike](#l01-bike) nas estações ([Vagas](#l07-vagas)) sem usar o aplicativo | Cartão de Desbloqueio, cartão de Giro | Objeto |

### L03 - Localização Atual

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Localização atual | Lugar em que se encontra uma pessoa, um objeto, um processo ou fenômeno, bem como a origem desse | No aplicativo, a função foca no [Mapa](#l04-mapa) a localização em tempo real do celular usando o GPS interno | Posicionamento, lugar, local | Ação |

### L04 - Mapa

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Mapa | Representação gráfica, em escala reduzida, da superfície total ou parcial da Terra | Ambiente principal do aplicativo, onde serão visualizadas as [Bikes](#l01-bike), [Vagas](#l07-vagas) e pontos de interesse pela cidade | Miniatura, tela principla | Objeto |

### L05 - Perfil

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Perfil | Dados dos [Usuários](#l08-usuario) criados durante o cadastro | Contém informações sobre o [Usuários](#l08-usuario), endereço, dados de pagamento, etc. | Dados | Objeto |

### L06 - Planos

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Planos |  Modalidades de serviço que o [Usuários](#l08-usuario) pode contratar diferenciando entre Eventual, Rotineiro e Profissional | Cada plano libera uma categoria de benefício diferente para o [Usuários](#l08-usuario) | Categorias, serviços | Objeto |

### L07 - Vagas

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Vagas | Lugar vazio onde se pode estacionar um veículo: vaga de estacionamento | Forma de vialização no [Mapa](#l04-mapa) onde o aplicativo deixa visível as possíveis [Vagas](#l07-vagas) para estacionar as [Bikes](#l01-bike) retiradas anteriormente. Locais de retirada e devolução | Toten, estação, pontos | Objeto |

### L08 - Usuário

| Léxico | Noção | Impacto | Sinônimos | Tipo |
| :---: | :---: | :---: | :---: | :---: |
| Usuário | Sujeito que utiliza o aplicativo | Usuário é cadastrado no sistema e pode utilizar a [Bikes](#l01-bike), escolher [Planos](#l06-planos) e consultar [Vagas](#l07-vagas) atráves do [Mapa](#l04-mapa). | Cliente, utilizador e desfrutador | Sujeito |

## Histórico de Revisões

| Data | Versão | Descrição | Autor(es) |
| --- | --- | --- | --- |
| 21/03/2021 | 1.0 | Criação do documento e adição inicial de léxicos | [Marcos Raimundo](https://www.github.com/MarcosFloresta/) |
| 22/04/2021 | 1.0 | Modificações por consulta à [Validação dos Léxicos](https://requisitos-de-software.github.io/2020.2-BikeItau/modelagem/verificacao_lexico/) | [Tomás veloso](https://github.com/tomasvelos0) |