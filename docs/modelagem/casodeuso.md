# Modelagem


## Histórico de Revisões 

| Data | Versão | Descrição | Autor(es) |
| :----: | :----: | :----: | :----: |
| 11/03/2021 | 1.0 | Criação do documento | [Tomás veloso](https://github.com/tomasvelos0) |

## Sumário

[1. Caso de uso](#1-Caso-de-uso)

[2. Itens de Configuração](#2-Diagrama-de-Caso-de-uso)

[3. Referências](#3-Referências)

## 1. Caso de uso

<p align = "justify">Caso de uso é a especificação dos requisitos, realizado na fase de especificação de requisitos em forma de documentos textuais. São redigidos pelos próprios desenvolvedores do sistema em parceria com os usuários. No caso de uso são identificados os autores e são anotadas as interações que realizam no sistema. Como os autores são diferentes pessoas (ou dispositivos) que interagem com o sistema, o autor representa um papel, e precisa ser específico e significativo, por isso é recomendável representar os autores com substantivos significativos para o contexto do sistema.</p>
<br/>

| US ID | Autor | Funcionalidade |
| :----: | :----: | :---------: |
| US01 | Usuário | Realizar login no aplicativo |
| US02 | Usuário | Fazer logout do perfil no aplicativo |
| US03 | Usuário | Recuperar senha |
| US04 | Usuário | Selecionar cidade (praça) |
| US05 | Usuário | Escolher um plano (categoria de uso) |
| US06 | Usuário | Verificar com mais detalhes informações sobre o plano de uso |
| US07 | Usuário | Realizar pagamento |
| US08 | Usuário | Observar em um mapa sua localização e todas as bicicletas disponíveis |
| US09 | Usuário | Selecionar bicicleta desejada |
| US10 | Usuário | Inserir código disponível no celular para liberar o uso da bicicleta |

## 1.1. Fluxo de Caso de uso

#### 1.1.1 Fluxo de uso - Login

|  | **Técnica de caso de uso para o Bike Itaú** |  |
| :--- | :--- | :--- |
| **Atividade:** | Acessar o Bike Itaú   |  |
| **Ator:** | Usuário do Bike Itaú  |  |
| **Pré condição:** |  |  |
|  | 1. O usuário precisa estar com acesso a internet.|  |
| **Fluxo normal:** |  |  |
|  | 1. O usuário acessa o aplicativo e seleciona a opção de realizar login. |  |
|  |2. Insere email e senha de cadastro.  |  |
| **Fluxo Alternativo (extensões):** |  |  |
|  |  1a. O usuário pode acessar também pelo o site do bike Itaú. |  |
|  | 2a. Se o usuário não lembrar da senha, seleciona a opção de recuperação da senha. |  |

#### 1.1.2 Fluxo de uso - Modelo Geral

|  | **Técnica de caso de uso para o Bike Itaú** |  |
| :--- | :--- | :--- |
| **Atividade:** | Utilizar a bicicleta do Bike Itaú  |  |
| **Ator:** | Ciclista do Bike Itaú  |  |
| **Pré condição:** |  |  |
|  |  1. O usuário precisa possuir o aplicativo.|  |
|  | 2. O usuário precisa estar com acesso a internet. |  |
| **Fluxo normal:** |  |  |
|  | 1. O ciclista abre o aplicativo no seu dispositivo móvel. |  |
|  |2. Em um mapa, o ciclista consegue observar sua localização e das bicicletas.  |  |
|  |3. O ciclista seleciona a bicicleta que deseja utilizar.  |  |
|  |4. O ciclista deve escolher o plano que deseja usar.  |  |
|  |5. O ciclista informa os dados do cartão de crédito.  |  |
|  |6. O ciclista finaliza o pagamento e é gerado um código de desbloqueio da bicicleta.  |  |
|  |7. O ciclista digita o código na bicicleta e está liberado para usar.  |  |
| **Fluxo Alternativo (extensões):** |  |  |
|  |1a. Se o usuário não tiver cadastro, será necessário realizar o cadastro com email.  |  |
|  |1b. Caso o usuário tenha que realizar o login e não lembre a senha, pode solicitar a redefinição da senha.  |  |
|  |3a. O usuário pode escolher também a estação de bicicletas, com ou sem posto de autoatendimento.  |  |
|  |4a. Os Planos de uso podem ser adquiridos pelo aplicativo, site ou posto de  |  |


### 1.1.3 Fluxo de uso - Escolha do Plano

|  | **Técnica de caso de uso para o Bike Itaú** |  |
| :--- | :--- | :--- |
| **Atividade:** | Escolher plano de uso para utilizar as bicicletas do Bike Itaú  |  |
| **Ator:** | Usuário do Bike Itaú  |  |
| **Pré condição:** |  |  |
|  | 1. O usuário precisa estar com acesso a internet. |  |
| **Fluxo normal:** |  |  |
|  | 1. O ciclista abre o aplicativo no seu dispositivo móvel. |  |
|  | 2. No menu, selecione a opção Meus planos. |  |
|  | 3. O usuário seleciona a opção de Comprar plano. |  |
|  | 4. O usuário escolhe a cidade. |  |
|  | 5. O usuário seleciona o plano desejado entre as opções. |  |
|  | 6. O usuário opta pela categoria do do plano selecionado. |  |
|  | 7. O usuário finaliza o pagamento com cartão de crédito |  |
| **Fluxo Alternativo (extensões):** |  |  |
|  | 1a. O usuário pode acessar pelo site do bike Itaú. |  |
|  | 2a. Os Planos de uso podem ser adquiridos pelo aplicativo, site ou posto de autoatendimento. |  |
|  | 2b. Existe a alternativa de plano por cartão, onde o desbloqueio das bicicletas são feitos pelo cartão. |  |

### 1.1.4 Fluxo de uso - Solicitar Ajuda

|  | **Técnica de caso de uso para o Bike Itaú** |  |
| :--- | :--- | :--- |
| **Atividade:** | Solicitar ajuda do Bike Itaú  |  |
| **Ator:** | Usuário do Bike Itaú  |  |
| **Pré condição:** |  |  |
|  | 1. O usuário precisa estar com acesso a internet. |  |
| **Fluxo normal:** |  |  |
|  | 1. O usuário entra no aplicativo por meio de um dispositivo móvel. |  |
|  | 2. No menu, selecione a opção de Central de ajuda. |  |
|  | 3. O usuário seleciona a cidade. |  |
|  | 4. O usuário tem acesso às dúvidas mais frequentes, que possuem respostas pré estabelecidas. |  |
|  | 5. O usuário pode selecionar Entrar em contato Conosco, onde entra em uma conversa com um atendente do bike Itaú. |  |
| **Fluxo Alternativo (extensões):** |  |  |
|  |   1a. O usuário pode selecionar a dúvida por categoria, ou pela própria pergunta. |  |



## 2. Diagrama de Caso de uso

<p align = "justify">Diagrama de caso de uso é o conjunto de casos em que os autores atuam no sistema. Portanto é um índice gráfico, elementos gráficos simples, de casos de uso (documentos textuais de especificação de requisitos). Um cenário que representa as funções que o autor irá realizar no sistema.
É apropriado usar diagrama de caso de uso, quando a metodologia de desenvolvimento é voltada para as práticas ágeis e com o foco no cliente, assim adotam a mentalidade de entrega rápida de valor ao cliente. Quando no processo de criação objetiva o usuário no centro dos processos, o autor naquele sistema. Vantajoso para representar requisitos funcionais na perspectiva do usuário do sistema.</p>
<br/>

#### 2.1. Diagrama de Caso de Uso - Modelo Geral

[![Diagrama_de_caso_de_uso_geral](../img/USCasoGeral.png)](../img/USCasoGeral.png)

#### 2.2. Diagrama de Caso de Uso - Usuário Novo

[![Diagrama_de_caso_de_uso_usuario_novol](../img/USUsuario_novo.png)](../img/USUsuario_novo.png)

### # 2.3. Diagrama de Caso de Uso - Usuário Fidelizado

[![Diagrama_de_caso_de_uso_usuario_fidelizado](../img/USUsuario_fidelizado.png)](../img/USUsuario_fidelizado.png)

## 3. Referências
