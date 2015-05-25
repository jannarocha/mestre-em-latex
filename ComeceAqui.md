# Introdução #

O LaTeX é uma ferramenta para criar e formatar documentos de maneira eficiente e prática. A curva de aprendizado é um pouco íngreme e requer no mínimo uma semana de estudos para entender como funciona. Se seu trabalho envolve escrever documentos estruturados e complexos como artigos, relatórios, textos científicos, etc... este investimento valerá a pena, pois irá poupar-lhe muito tempo na confecção e formatação destes.

[Processadores de texto](http://pt.wikipedia.org/wiki/Processador_de_texto) como o Microsoft Word e Open Office formatam o texto enquanto as letras são digitadas e o resultado final do documento aparece na hora na tela, sistema denominado de [WYSIWYG](http://pt.wikipedia.org/wiki/WYSIWYG) (o que você vê é o que você obtém).

Com o LaTeX você pode usar qualquer [editor de texto](http://en.wikipedia.org/wiki/List_of_text_editors) para escrever. No texto você deve incluir comandos que irão definir a formatação do texto e de seus elementos. Veja abaixo a estrutura básica de um `documento.tex`:

```
\documentclass{article}

% Este espaço é o preâmbulo e isto é um comentário
% Aqui serão incluídos comandos que ativam pacotes, e.g.:

\usepackage{nomedopacote}
 
\begin{document}

O texto do seu documento vai aqui.

\end{document}
```

Este é o código-fonte, ou texto cru, do seu documento. Para formatá-lo você precisa passar o arquivo `documento.tex` por um programa que interprete os comandos e gere um documento. Este programa é o LaTeX. Para tal é necessário rodar o LaTeX sobre o arquivo a partir de um terminal:

```
pdflatex documento.tex
```

Com isso seu computador criará um `documento.pdf` bem formatado de acordo com os comandos especificados no arquivo `documento.tex`. Isto significa que a formatação não é feita na hora, como os processadores citados acima, mas apenas quando você executar o LaTeX sobre o arquivo fonte.

Esta diferença fundamental permite que a formatação do documento seja feita de maneira mais precisa e eficiente, para dizer o mínimo. Os processadores de texto não atingem este patamar de qualidade, pois seria necessário um grande consumo de memória para formatar o texto com tamanha precisão enquanto você digita.

Além da superioridade visual o LaTeX cria índices, numera figuras e gera a lista de referências bibliográficas automaticamente e com uma formatação consistente. Ou seja, você não vai perder tempo arrumando checando em que página começa o capítulo, trocando os números das figuras ou formatando referências.

Como o LaTeX existe desde meados de 1980, uma vasta documentação está disponível para consulta na rede. Com o **Mestre em LaTeX** é possível aprender os conceitos básicos na prática, mas é muito recomendável (pra não dizer essencial) ler alguns textos ou tutoriais para dominar melhor o assunto. Sugiro começar pela [Wikipedia](http://en.wikipedia.org/wiki/LaTeX) que contém as informações básicas e diversos links úteis. Repito abaixo alguns links relevantes:

  * [Wikipedia](http://pt.wikipedia.org/wiki/LaTeX) ([en](http://en.wikipedia.org/wiki/LaTeX)) - Descrição informativa com alguns exemplos
  * [LaTeX Project](http://www.latex-project.org/) - Site do projeto com documentação
  * [TUG](http://www.tug.org/) - Grupo de usuários com muitas informações úteis
  * [CTAN](http://www.ctan.org/) - Arquivo com infinidade de pacotes feitos por usuários
  * [Wikibooks](http://en.wikibooks.org/wiki/LaTeX/) - Excelente página para aprender os básicos

Leia as instruções de instalação.