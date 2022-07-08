# Praticando a Linguagem Markdown

___

## Formatação de textos
 
Para usar o **negrito** utilizo dois asterisco no começo e dois no final. Ou utilizo  dois caracteres underline e também irá ficar em __negrito__.



Para usar o *itálico* utilizo um asterisco no começo e um no final. Ou utilizo uma caracteres underline e também irá ficar em _itálico_.



**OBS:** Podendo também se misturar configurações, para ter por exemplo uma _*negrito e itálico*_ juntos



Usando o til (~) você deixa a palavra ~~tachada~~.



Para destacar um comando basta somente colocar esse comando entre crases.
**Exemplo**

`document.getElementById();`



Para criar um bloco de código cercado coloque três crases antes do conteúdo e três crases depois do conteúdo.
**Exemplo:**

```
{
  "nome": "Hiury",
  "sobrenome": "Lima",
  "idade": 22
}
```

Para colocar emojis basta utilizar os dois pontos e após o código do emoji.
**Exemplo:**

:V
:+1
:vulcan_salute
:hand

OBS: Acessando no link ![emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet) você encontra todos os emoji com seus devidos códigos

**Como formatar os títulos?**

Usando uma hashtag você faz um título de nível 1. E aumtando a quantidade de hashtags (até 6) vai abaixando o nível dos titulos.
**Exemplo:**

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

Usando três traços ou três asterico cria-se uma linha horizontal conforme a que está abaixo:
***




## Listas

Para fazer uma lista numerada utiliza-se um número (qualquer, podendo até mesmo ser repetido) e um ponto.
**Exemplo:**

1. Item
1. Item
1. Item
7. Item



Para fazer um subitem basta colocar com três espacos do começo do item principal.
**Exemplo:**

1. Item
   4. subitem



Para fazer uma lista demarcada utiliza-se um asterico e na frente a palavra desejada. E da mesma maneira anteriormente ensinado faz um subitem.
**Exemplo:**

* Item
* Item
   * subitem
* Item



Para fazer uma lista de tarefas utiliza-se os colchetes e na frente a tarefa desejada. E para marcar a tarefa coloco o 'x' dentro dos colchetes. Como estamos trabalhando com lista é necessário iniciar a linha do item com um traço -.
**Exemplo:**

- [] Tarefa
- [] Tarefa
- [x] Tarefa
- [] Tarefa
- [] Tarefa



### Imagens e Links

Para colocar imagens, inicio com o ponto de exclamação (!), seguindo dos colchetes para colocar a descrição da imagem e por ultimo os parênteses para a url da imagem.
**Exemplo:**

![Descrição da imagem](./midia/GitHub-Mark.png)



Para colocar links, é basicamente a mesma estrutura mas sem o ponto de exclamação (!) no inicio.
**Exemplo:**

[Praticando a linguagem Markdown](https://github.com/DevHiuryLima/Praticando-a-Linguagem-Markdown)



### Tabelas

Para criar uma tabela em Markdown nós usamos traços (–) e barras verticais (|) para separar linhas e colunas.
A primeira linha da tabela é onde construímos o cabeçalho, separando essa linha por três ou mais traços --- para que o processador Markdown entenda a formatação. A separação das colunas é feita usando a barra vertical |, também chamada de pipe por programadores.
**Exemplo:**

| Título  | Título   |
| ------- | -------- |
| Texto   | Texto    |
| Texto   | Texto    |



Pode criar uma tabela sem as barras laterais.
**Exemplo:**

 Título  | Título   
 ------- | -------- 
 Texto   | Texto    
 Texto   | Texto    



 Alargur das células, dentro da tabela pode variar.
 **Exemplo:**

 | Título | Título |
| --- | ----------- |
| Texto | Texto |
| Texto     | Texto |



Para alinhar um conteúdo à esquerda em uma tabela do Markdown, coloque dois pontos (:) antes dos traços (---) que separam a linha do cabeçalho.
**Exemplo:**

| Frutas  | Verduras | Legumes |
| :---    | :----    | :---    |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |



Para alinhar o texto à direita dentro da tabela do Markdown, insira os dois pontos (:) depois dos traços (---) que separam a linha do cabeçalho.
**Exemplo:**

| Frutas  | Verduras | Legumes |
|    ---: |    ----: |    ---: |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |



Para alinhar o conteúdo da coluna ao centro em uma tabela do Markdown, adicione dois pontos : antes e depois dos traços que separam a linha do cabeçalho.
**Exemplo:**

| Frutas  | Verduras | Legumes |
|  :---:  |  :----:  |  :---:  |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |



É possível mesclar a formatação de alinhamento, já que, essa, somente influencia o conteúdo de dentro da coluna.
**Exemplo:**

| Frutas  | Verduras | Legumes |
| :---    |  :----:  |    ---: |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |