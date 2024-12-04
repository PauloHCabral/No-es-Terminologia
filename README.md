Hiperligações
Hiperlinks (ou apenas links) permitem que um usuário navegue para outras coisas. 
Pode ser outra página no seu site, um site completamente separado ou até mesmo um endereço de e-mail. Um dos principais objetivos do HTML era permitir que esses "ponteiros" fossem adicionados a uma página para facilitar o acesso. 
Isso é feito através de links.

A tag usada para criar um link é a, que é a abreviação de anchor. O conteúdo entre a tag open e close a torna-se hipertexto que permite que um usuário acesse o recurso.

O recurso que está sendo referenciado é indicado usando um atributo chamado href (ou referência de hipertexto). Os atributos são adicionados dentro da tag de abertura e normalmente são um nome emparelhado com um valor (chamados pares chave-valor) com o valor contido nas aspas.


<a href="some url">clickable text</a>


Imagens
A img tag é usada para exibir imagens em uma página. 
Ao contrário da maioria dos outros elementos, img não tem tag de fechamento. 
O src atributo é usado para apontar para o local da imagem a ser exibida na página, e o alt descreve o conteúdo da imagem para coisas como mecanismos de pesquisa e leitores de tela.

Importante

Embora os height atributos e width possam ser usados para especificar a altura e a largura de exibição da imagem, eles não redimensionam o arquivo de imagem em si. 
A melhor prática é tornar o arquivo de imagem as dimensões que você usará na página.

<img src="headshot.png" alt="Picture of an employee."


Para criar uma lista, você primeiro decidirá o tipo de lista que deseja criar.
Uma lista ordenada é ordenada com números (o padrão) ou letras e usos para lista ordenada.ol Uma lista não ordenada usa marcadores e é identificada com ul para lista não ordenada.
Os itens são indicados com li para item de lista.

O seguinte cria uma lista não ordenada:

<ul>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ul>

A lista gerada:

1.Primeiro item
2.Segundo ponto
3.Terceiro item







O seguinte cria uma lista ordenada:

<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>

A lista gerada:

1.Primeiro item
2.Segundo ponto
3.Terceiro item



