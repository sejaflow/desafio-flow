# Desafio Seja Flow
## Introdução
O desafio da Flow é composto de 3 níveis de classificação: 
1. **Nível 1**: destinado a saber se você sabe o básico de HTML + CSS + JS.  
2. **Nível 2**: destinado a saber se você sabe o básico de banco de dados, back-end e front-end.
3. **Nível 3**: destinado a saber se você sabe o básico de desenvolvimento web (Back-end e Front-End).
  
Cada um dos níveis é classificatorio e não eliminatório. Segue a pontuação:

1. **Nível 1**: 10 Midi-chlorians!.  
2. **Nível 2**: 100 Midi-Clorians!.
3. **Nível 3**: 1000 Midi-clorians!.

Para cada nível há critérios para conseguir a pontuação. Caso você não saiba o que é um Midi-chorian, acesse o [link](http://sociedadejedi.com.br/2015/12/06/afinal-o-que-sao-as-midi-chlorians/). 

## Escopo do problema

O desafio é desenvolver um programa que permita realizar as seguintes buscas: 
1. Listar os **órgãos, códigos e editais dos concursos públicos** que encaixam no perfil do candidato tomando como base o **CPF** do candidato ; 
2. Listar o **nome, data de nascimento e o CPF** dos candidatos que se encaixam no perfil do concurso tomando com base o **Código do Concurso** do concurso público;

O arquivo **candidatos.txt** contém as informações dos candidatos:

| Nome  | Data de Nascimento  | CPF |  Profissões|
|---|---|---|---|
| Lindsey Craft  |  19/05/1976  |  182.845.084-34  |  [carpinteiro]  | 
| Jackie Dawson  |  14/08/1970  |  311.667.973-47  |  [marceneiro, assistente administrativo]  |
| Cory Mendoza |   11/02/1957 |  565.512.353-92  |  [carpinteiro, marceneiro] |

O arquivo **concursos.txt** contém as informações dos concursos públicos:

| Órgão  | Edital  | Código do Concurso |  Lista de vagas|
|---|---|---|---|
| SEDU  | 9/2016  |  61828450843  |  [analista de sistemas, marceneiro]  | 
| SEJUS | 15/2017  |  61828450843  |  [carpinteiro,professor de matemática,assistente administrativo] |
| SEJUS | 17/2017 |  95655123539  |  [professor de matemática] |

**Escolha as tecnologias que você vai usar e tente montar uma solução completa para rodar a aplicação**.

Para enviar o resultado, basta realiazar um **Fork** deste repositório e **abra um Pull Request**, **com seu nome e o número de inscrição**.  

**É importante comentar que deve ser enviado apenas o código fonte. Não aceitaremos códigos compilados**.

Por fim, o candidato deve atualizar o Readme.md com as seguintes informações: 
1. Documentação da solução: use a criatividade para documentar;
2. Lista dos diferenciais implementados  

## Avaliação

## Nível 1
O jedi deve construir uma página web utilizando HTML, CSS e JS que implemente os itens do desafio. A págia web deve consumir as informações do serviço web disponibilizado em [link](http://sejaflow.pythonanywhere.com/).  

Caso queira rodar localmente, você baixar o código fonte do nosso [git](https://github.com/sejaflow/desafio-webservice).

### Conteúdos que podem lhe ajudar:
1. [W3School HTML](https://www.w3schools.com/html/)
2. [W3School CSS](https://www.w3schools.com/css/default.asp)
3. [W3School JS](https://www.w3schools.com/js/default.asp)

## Nível 2
O jedi deve construir uma aplicação web em qualquer tecnologia (e.g., PHP, Python, Java) que resolve o desafio com o banco de dados. Para isso, o usuário pode utilzar o banco de dados disponibilizado.   

### Conteúdos que podem lhe ajudar:
1. [W3School HTML](https://www.w3schools.com/html/)
2. [W3School CSS](https://www.w3schools.com/css/default.asp)
3. [W3School JS](https://www.w3schools.com/js/default.asp)
4. [W3School PHP](https://www.w3schools.com/php/default.asp)
5. [W3School SQL](https://www.w3schools.com/sql/default.asp)
6. [Django Girls](https://tutorial.djangogirls.org/pt/)
7. [Django Mozila](https://developer.mozilla.org/pt-BR/docs/Learn/Server-side/Django/skeleton_website)

## Nível 3

O jedi deve construir uma aplicação web com Fron-End e Back-End separados em qualquer tecnologia (e.g., PHP, Python, Java) que resolve. Não pode utilizar o banco de dados disponibilizado.


### Conteúdos que podem lhe ajudar:
**Todos os anteriores.** =)

# Avaliação do código
O programa será avaliado levando em conta os seguintes critérios:

| Nível  | Legibilidade do Código | Documentação do código| Documentação da solução|Tratamento de Erros|
|---|---|---|---|---|
| Nível 1 |  2.5  |2.5  |2.5  |2.5  |
| Nível 2|  25  |25  |25  |25  |
| Nível 3|250  |250  |250  |250  |

A pontuação do candidato será a soma dos valores obtidos nos critérios acima.

## Diferenciais 

O candidato pode aumentar a sua pontuação na seleção implementando um ou mais dos itens abaixo:

| Item  | Pontos Ganhos | 
|---|---|
| Criar um [serviço](https://martinfowler.com/articles/microservices.html) com o problema |  30  |
| Utilizar banco de dados| 30|
| Implementar Clean Code |  20  |
| Implementar o padrão de programação da tecnologia escolhida |  20  |
| Qualidade de [Código com SonarQube](https://about.sonarcloud.io/) |  15  |
| Implementar testes unitários |  15  |
| Implementar testes comportamentais |  15  |
| Implementar integração com [Travis](https://travis-ci.org/)  |  10  |
| Implementar integração com Travis + SonarQube |  10  |
| Implementar usando Docker| 5|
| Total| 170|

A nota final do candidato será acrescido dos pontos referente ao item implementado corretamente.

## Penalizações

O candidato será desclassifiado nas seguintes situações:

1. Submeter um solução que não funcione; 
2. Não cumprir os critérios presentes no seção **Avaliação**
3. Plágio
