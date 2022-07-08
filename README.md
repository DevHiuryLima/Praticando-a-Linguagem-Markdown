# Praticando a Linguagem Markdown

___

## Formatação de textos
 
Para usar o **negrito** utilizo dois asterisco no começo e dois no final. Ou utilizo  dois caracteres underline e também irá ficar em __negrito__.

**Exemplo:**
```**negrito** ou  __negrito__ e ficará em negrito.```



Para usar o *itálico* utilizo um asterisco no começo e um no final. Ou utilizo uma caracteres underline e também irá ficar em _itálico_.

**Exemplo:**
```*itálico* ou  _itálico_ e ficará em itálico.```

**OBS:** Podendo também se misturar configurações, para ter por exemplo uma _*negrito e itálico*_ juntos.
``` Utilize: assim _*negrito e itálico*_```



Usando o til (~) você deixa a palavra ~~tachada~~.

**Exemplo:**
```~~tachada~~ e ficará tachada.```



Para destacar um comando basta somente colocar esse comando entre crases (`).

**Exemplo:**
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
```
:v:
:+1:
:vulcan_salute:
:hand:
```

OBS: Acessando no link [emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet) você encontra todos os emoji com seus devidos códigos
OBS: Acessando a [Emojipedia](https://emojipedia.org) encontre seu emoji favorito, e o procedimento é de copiar e colar.



Para marcar uma pessoa utilize o (@) antes do nome.
**Exemplo:**
```@DevHiuryLima```



Para usar a barra vertical o código ```&#124;``` se transformará em uma barra vertical |.



**Como formatar os títulos?**

Usando uma hashtag você faz um título de nível 1. E aumtando a quantidade de hashtags (até 6) vai abaixando o nível dos titulos.

**Exemplo:**
```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

Usando três traços ou três asterico ```***``` ou três traços ```---``` cria-se uma linha horizontal conforme a que está abaixo:
***



## Listas

Para fazer uma lista numerada utiliza-se um número (qualquer, podendo até mesmo ser repetido) e um ponto.

**Exemplo:**
```
1. Item
1. Item
1. Item
7. Item
```



Para fazer um subitem basta colocar com três espacos do começo do item principal.

**Exemplo:**
```
1. Item
   4. subitem
```



Para fazer uma lista demarcada utiliza-se um asterico e na frente a palavra desejada. E da mesma maneira anteriormente ensinado faz um subitem.

**Exemplo:**
```
* Item
* Item
   * subitem
* Item
```



Para fazer uma lista de tarefas utiliza-se os colchetes e na frente a tarefa desejada. E para marcar a tarefa coloco o 'x' dentro dos colchetes. Como estamos trabalhando com lista é necessário iniciar a linha do item com um traço -.

**Exemplo:**
```
- [] Tarefa
- [] Tarefa
- [x] Tarefa
- [] Tarefa
- [] Tarefa
```
---



### Imagens e Links

Para colocar imagens, inicio com o ponto de exclamação (!), seguindo dos colchetes para colocar a descrição da imagem e por ultimo os parênteses para a url da imagem.

**Exemplo:**
```
![Descrição da imagem](./midia/GitHub-Mark.png)
```



Para colocar links, é basicamente a mesma estrutura mas sem o ponto de exclamação (!) no inicio.

**Exemplo:**
```
[Praticando a linguagem Markdown](https://github.com/DevHiuryLima/Praticando-a-Linguagem-Markdown)
```
---



### Tabelas

Para criar uma tabela em Markdown nós usamos traços (–) e barras verticais (|) para separar linhas e colunas.
A primeira linha da tabela é onde construímos o cabeçalho, separando essa linha por três ou mais traços --- para que o processador Markdown entenda a formatação. A separação das colunas é feita usando a barra vertical |, também chamada de pipe por programadores.

**Exemplo:**
```
| Título  | Título   |
| ------- | -------- |
| Texto   | Texto    |
| Texto   | Texto    |
```



Pode criar uma tabela sem as barras laterais.

**Exemplo:**
```
 Título  | Título   
 ------- | -------- 
 Texto   | Texto    
 Texto   | Texto    
 ```



 Alargur das células, dentro da tabela pode variar.
 
 **Exemplo:**
```
| Título | Título |
| --- | ----------- |
| Texto | Texto |
| Texto     | Texto |
```



Para alinhar um conteúdo à esquerda em uma tabela do Markdown, coloque dois pontos (:) antes dos traços (---) que separam a linha do cabeçalho.

**Exemplo:**
```
| Frutas  | Verduras | Legumes |
| :---    | :----    | :---    |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |
```


Para alinhar o texto à direita dentro da tabela do Markdown, insira os dois pontos (:) depois dos traços (---) que separam a linha do cabeçalho.

**Exemplo:**
```
| Frutas  | Verduras | Legumes |
|    ---: |    ----: |    ---: |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |
```



Para alinhar o conteúdo da coluna ao centro em uma tabela do Markdown, adicione dois pontos : antes e depois dos traços que separam a linha do cabeçalho.

**Exemplo:**
```
| Frutas  | Verduras | Legumes |
|  :---:  |  :----:  |  :---:  |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |
```



É possível mesclar a formatação de alinhamento, já que, essa, somente influencia o conteúdo de dentro da coluna.

**Exemplo:**
```
| Frutas  | Verduras | Legumes |
| :---    |  :----:  |    ---: |
| Caju    | Agrião   | Cenoura |
| Maçã    | Brócolis | Ervilha |
```
---


## Notas de rodapé

Nota de rodapé no Markdown permite que o usuário crie uma referência para algum conceito citado no documento. A primeira parte representa o número contendo o link e é criado usando colchetes, um acento circunflexo e um identificador.

**Exemplo:** ```[^1]```

Depois é o conteúdo da referência em si, para criá-la use colchetes, um acento circunflexo seguido pelo mesmo identificador (que você criou anteriormente), dois pontos, um espaço em branco e o texto.

**Exemplo:**
```[^1]: Minha nota de rodapé```

OBS: O rodapé não pode ser colocado dentro de outros elementos Markdown como, tabelas, listas e blocos de código. As notas de rodapé serão, sempre, sequenciais (1, 2 e 3), independente dos identificadores que você criou.

---



## IDs e Classes

Para adicionar um id ou uma classe a um elemento do Markdown abra chaves, logo após o conteúdo do elemento, coloque uma hashtag para indicar um id ou um ponto para indicar uma classe, em seguida, o próprio identificador e, por fim, feche as chaves.

**Exemplo:**
```
### Título {#idTitulo}

Meu parágrafo{.classe-paragrafo}
```
---



## Referências

1. > Markdown: [Sintaxe Estendida - Recursos avançados que se baseiam nos fundamentos do Markdown.](https://markdown.net.br/sintaxe-estendida/)
1. > Curso em vídeo: [Manual do Markdown para GitHub](https://github.com/gustavoguanabara/git-github/blob/master/manuais-PDF/guia-markdown.pdf)

&#xa0;

[Voltar para o topo](https://github.com/DevHiuryLima/Praticando-a-Linguagem-Markdown/blob/main/README.md#top)