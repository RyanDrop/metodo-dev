## :hammer_and_wrench: **O que é HTML?**

<div>

HTML (Linguagem de Marcação de Hipertexto) é o código que você usa para estruturar uma página web e seu conteúdo. HTML não é uma linguagem de programação; é uma linguagem de marcação, usada para definir a estrutura do seu conteúdo. HTML consiste de uma série de elementos, que você usa para delimitar ou agrupar diferentes partes do conteúdo para que ele apareça ou atue de determinada maneira na sua página.

---

## Anatomia de um documento HTML

DOCTYPE html — o doctype. É a parte inicial obrigatória do documento. Nas névoas do tempo, quando o HTML era novo (por volta de 1991/2), doctypes eram criados para agir como links para um conjunto de regras que a página HTML tinha que seguir para ser considerada um bom HTML, o que poderia significar checagem automática de erros e outras coisas úteis. No entanto, atualmente, eles não fazem muito sentido e são basicamente necessários apenas para garantir que o documento se comporte corretamente. Isso é tudo que você precisa saber agora.

html — o elemento html. Esse elemento envolve todo o conteúdo da página e às vezes é conhecido como o elemento raiz.

head — o elemento head. Esse elemento age como um recipiente de tudo o que você deseja incluir em uma página HTML que não é o conteúdo que você quer mostrar para quem vê sua página. Isso inclui coisas como palavras-chave e uma descrição que você quer que apareça nos resultados de busca, CSS para dar estilo ao conteúdo, declarações de conjuntos de caracteres e etc.

meta charset="utf-8" — esse elemento define o conjunto de caracteres que seu documento deve usar para o UTF-8, que inclui praticamente todos os caracteres da grande maioria dos idiomas escritos. Essencialmente, agora ele pode manipular qualquer conteúdo textual que você possa colocar. Não há razão para não definir isso e assim pode ajudar a evitar alguns problemas no futuro.

title — o elemento title. Ele define o título da sua página, que é o título que aparece na guia do navegador onde sua página é carregada. Ele também é usado para descrever a página quando você a adiciona aos favoritos.

body — o elemento body. Contém todo o conteúdo que você quer mostrar ao público que visita sua página, seja texto, imagens, vídeos, jogos, faixas de áudio reproduzíveis ou qualquer outra coisa.

---

## As principais partes de um elemento são:

1 => A tag de abertura: Consiste no nome do elemento (no caso, p), envolvido em parênteses angulares de abertura e fechamento. Isso demonstra onde o elemento começa, ou onde seu efeito se inicia — nesse caso, onde é o começo do parágrafo.

2 => A tag de fechamento: Isso é a mesma coisa que a tag de abertura, exceto que inclui uma barra antes do nome do elemento. Isso demonstra onde o elemento acaba — nesse caso, onde é o fim do parágrafo. Esquecer de incluir uma tag de fechamento é um dos erros mais comuns de iniciantes e pode levar a resultados estranhos.

3 => O conteúdo: Esse é o conteúdo do elemento, que nesse caso é apenas texto.

4 => O elemento: A tag de abertura, a de fechamento, e o conteúdo formam o elemento.

</div>

---

## :sparkles: **O que é CSS?**

<div>
Assim como o HTML, o CSS não é realmente uma linguagem de programação. Também não é uma linguagem de marcação — é uma linguagem de folhas de estilos. Isso significa que o CSS permite aplicar estilos seletivamente a elementos em documentos HTML. Por exemplo, para selecionar todos os elementos parágrafo de uma página HTML e tornar o texto dentro deles vermelho, você escreveria este CSS:

p {
color: red;
}

---

## Anatomia de um conjunto de regras CSS

Toda essa estrutura é chamada de conjunto de regras (mas geralmente usamos o termo "regra", por ser mais curto). Note os nomes das partes individuais:

Seletor (Selector)
O nome do elemento HTML no começo do conjunto de regras. Ele seleciona o(s) elemento(s) a serem estilizados (nesse caso, elementos p). Para dar estilo a um outro elemento, é só mudar o seletor.
Declaração (Declaration)
Uma regra simples como color: red; especificando quais das propriedades do elemento você quer estilizar.
Propriedades (Property)
Forma pela qual você estiliza um elemento HTML. (Nesse caso, color é uma propriedade dos elementos p.) Em CSS, você escolhe quais propriedades você deseja afetar com sua regra.
Valor da propriedade (Property value)
À direita da propriedade, depois dos dois pontos, nós temos o valor de propriedade, que escolhe uma dentre muitas aparências possíveis para uma determinada propriedade (há muitos valores color(cor) além do red(vermelho)).
Note outras partes importantes da sintaxe:

Cada linha de comando deve ser envolvida em chaves ({}).
Dentro de cada declaração, você deve usar dois pontos (:) para separar a propriedade de seus valores.
Dentro de cada conjunto de regras, você deve usar um ponto e vírgula (;) para separar cada declaração da próxima.

p{
color: red;
width: 200px;
font-size: 18px;
}

Selecionando múltiplos elementos

p, h1, li {
color: red;
}

---

## Diferentes tipos de seletores

Há muitos tipos diferentes de seletores. Abaixo, nós mostramos apenas os seletores de elementos, que selecionam todos os elementos de um determinado tipo nos documentos HTML. Mas nós podemos fazer seleções mais específicas que essas. Aqui estão alguns dos tipos mais comuns de seletores:

    * (asterisco) — Seleciona todos os elementos.
    # (hifen) — Seleciona todos os elementos com um ID específico.
    . (ponto) — Seleciona todos os elementos com um classe específica.
    [] (colchetes) — Seleciona todos os elementos com um atributo específico.
    : (dois pontos) — Seletor de pseudo-classes.

---

## Box-model

Uma coisa que você notará sobre escrever CSS é que muito disso é sobre caixas — indicar seu tamanho, cor, posição, etc. Muitos dos elementos HTML da sua página podem ser pensados como caixas umas em cima das outras.

Como esperado, o layout CSS é baseado principalmente no modelo de caixas. Cada um dos blocks que ocupam espaço na sua página tem propriedades como essas:

padding, o espaço ao redor do conteúdo (ex.: ao redor do texto de um parágrafo).
border, a linha sólida do lado de fora do padding.
margin, o espaço externo a um elemento.

</div>

---

## :boy: _Autor_

<div align="center">

<a href="https://github.com/RyanDrop">
 <img src="https://avatars.githubusercontent.com/u/82955110?s=96&v=4"  width="100px;" alt="Profile Photo Ryan Drop"/>
 <br/>
 <sub><b>RyanDrop</b></sub>
</a>

Desenvolvido com ❤️ por RyanDrop 👋🏽 Meus Contatos!

[![Linkedin Badge](https://img.shields.io/badge/-RyanDrop-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ryan-on/)
[![Github Badge](https://img.shields.io/badge/-RyanDrop-000?style=flat-square&logo=Github&logoColor=white)](https://github.com/RyanDrop)

</div>

---

## :balance_scale: **Licença**

<div align="center">

Copyright © 2022 .<br />
This project is licensed by [MIT](./LICENSE).

</div>
