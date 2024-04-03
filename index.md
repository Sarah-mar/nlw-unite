#HTML
o html sempre considera o conjunto tag+conteudo como uma linha só
*hypertext*
- hyperlink: <a href="https://linkdosite.com">nomedositenohtml</a>
*markup*
- Tags
- Atributes
*language*

<div> (tag sem significado, serve para agrupar outras tags)

*criando tabelas*
<table>
<thead> (cria o cabeçalho da tabela)
<tr> (cria a linha da tabela)
<th> (adiciona um elemento da linha do cabeçalho)</th>
</tr>
</thead>
<tbody> (cria o corpo da tabela)
<td> (adiciona um elemento da linha do corpo)
<strong> (coloca negrito)
<br> (quebra a linha)

</table>

*criando formulários*
<form>
<fieldset> (cria um conjunto de campos (do formulário))
<legend> (cria a legenda do formulário)
<input type="text"> (cria um input e n tem fechamento
podem ser atribuidos outras caracteristicas como o placeholder - o que aparece antes de começar a digitar)


#JS
````js
//variaveis:
//guardam informaçoes no codigo
//const blablabla = cria uma variavel, que pode ser chamada so por blablabla
//tipos de dados:
  //number
  //"string"
  //

//funcoes:
//nome da funcao()
//objetos: elementos com funcoes e propriedades
const participante = { //cria objetos dentro de variaveis
  nome: "Sarah Marinho",
  email: "sarah@gmail.com",
  datainscricao: new Date(2024, 2, 22, 19, 20), //o mês é uma range
  datacheckin: new Date(2024, 2, 25, 22, 00)
} 
array: []
```
adicionamos a biblioteca dayjs para ajustar o tempo das datas, e também a linguagem em que essa data aparece
booleana: variavel de true ou false

#css
cores: hexadecimal - 3 pares de 2 digitos, o primeiro par vai de 0 até F, um quarto par define a opacidade
fonte: 300 16px/140% 'roboto', sans-serif:
       (grossura da fonte, tamanho, largura da linha, estilo da fonte padrão, estilo reserva)
no css, a tela é dividida em caixas, formadas pela margin, border, padding e o content
o css atua por cascata e especificidade: quanto mais especifico for a declaração, a alteração dela é aplicada. Caso não, é sempre a ultima declaração da cascata
variável:
:root {
  --nomedavariavel: caracteristicas
}
classes:
.nomedaclasse {}
seletor universal:
* {}