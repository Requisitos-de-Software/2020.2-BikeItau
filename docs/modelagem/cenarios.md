# Cenários
## Introdução
<div style="text-align: justify">Young (2004) define cenários como histórias que buscam engajar o leitor no entendimento de como um novo produto ou serviço irá integrar e afetar a vida de diferentes stakeholders.</div>

## Cenários
### Cenário 01

|  |  |
| --- | --- |
| **Titulo** | Logar |
| **Objetivo** | Efetuar login no aplicativo |
| **Contexto** | Local: tela inicial do app.</br>Pré-condição: usuário deve possuir cadastro |
| **Atores** | usuário não logado |
| **Recursos** | Internet, aplicativo instalado, e-mail válido, senha válida |
| **Episódios** | Usuário clica no menu principal.</br>Usuário clica em "Faça seu Login".</br>Usuário preenche e-mail e senha válidos e clica em "Continuar". |
| **Exceção**| Usuário não cadastrado.</br>Internet indisponível. |


## Cenário 02

|  |  |
| --- | --- |
| **Titulo** | Cadastrar |
| **Objetivo** | Efetuar novo cadastro no aplicativo |
| **Contexto** | Local: tela inicial do app.</br>Pré-condição: usuário deve possuir app instalado e conectado |
| **Atores** | Usuário não cadastrado |
| **Recursos** | Internet, aplicativo instalado, e-mail válido, senha válida, dados cadastrais |
| **Episódios** | Usuário clica no menu principal.</br>Usuário clica em "Crie sua Conta".</br>Usuário preenche e-mail e senha válidos e clica em "Continuar".</br>Usuário preenche os dados cadastrais de nacionalidade, CPF, nome, data de nascimento e número de celular. |
| **Exceção**| Internet indisponível.</br>Endereço de e-mail inválido ou senha inválidos.</br>Dados cadastrais incompletos.</br>Cadastro já existente |


## Cenário 03

|  |  |
| --- | --- |
| **Titulo** | Retirar bicicleta |
| **Objetivo** | Retirar bicicleta de uma estação para uso |
| **Contexto** | Local: tela inicial do app.</br>Pré-condição: usuário deve possuir app conectado a internet e login efetuado |
| **Atores** | Usuário logado |
| **Recursos** | Internet, aplicativo instalado, GPS ativo |
| **Episódios** | Usuário clica na aba "Bikes".</br>Usuário seleciona estação no mapa com número de bicicletas superior a zero.</br>Usuário gera o código para retirada.</br>Usuário dirige-se fisicamente até a estação e retira a bicicleta usando o código gerado. |
| **Exceção**| Internet indisponível.</br>Usuário não logado.</br>GPS desabilitado. |


## Cenário 04

|  |  |
| --- | --- |
| **Titulo** | Devolver bicicleta |
| **Objetivo** | Colocar bicicleta em uma estação após o uso |
| **Contexto** | Local: tela inicial do app.</br>Pré-condição: usuário deve possuir app conectado a internet, login efetuado e bicicleta do app em uso |
| **Atores** | Usuário logado |
| **Recursos** | Internet, aplicativo instalado, GPS ativo, bicicleta do app |
| **Episódios** | Usuário clica na aba "Vagas".</br>Usuário seleciona estação no mapa com número de vagas superior a zero.</br>Usuário gera o código para devolução.</br>Usuário dirige-se fisicamente até a estação com a bicicleta e a deposita usando o código gerado. |
| **Exceção**| Internet indisponível.</br>Usuário não logado.</br>GPS desabilitado. |


## Referências
YOUNG, Ralph. The Requirements Engineering Handbook. Noorwood, MA: Artech House, 2004.

## Histório de Revisões

| Data | Versão | Descrição | Autor(es) |
| --- | --- | --- | --- |
| 21/03/2021 | 1.0 | Criação do documento e cenários de 01 a 04 | [Matheus Clemente](https://www.github.com/matheusclemente/) |

Criação do documento e cenários.
