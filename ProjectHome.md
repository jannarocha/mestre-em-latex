**ATENÇÃO:** o desenvolvimento deste projeto migrou para o [GitHub](http://github.com/nelas/mestre-em-latex). Esta página não será mais atualizada. Agora também temos um website novo: http://nelas.github.com/mestre-em-latex/ Visite para acompanhar as modificações mais recentes.

--

O **Mestre em LaTeX** tem como objetivo facilitar a vida de quem está prestes a escrever sua dissertação de mestrado ou tese de doutorado em português. Ele é um modelo de dissertação que contém informações básicas para iniciantes em LaTeX, além de incluir uma série de pacotes úteis para escrever sua dissertação/tese eficientemente na língua portuguesa.

O modelo foi baseado no padrão do Instituto de Biociências da Universidade de São Paulo, que pode ser visto na página de [pós-graduação](http://www.ib.usp.br/pos/formaq.htm).

Uma série de funcionalidades nativas do LaTeX já estão configuradas para usar, entre elas:

  * Hifenação em português
  * Definir espaçamento entre linhas
  * Inclusão de figuras em vários formatos (output em PDF)
  * Criar figuras com subfiguras
  * Criar tabelas com qualidade de publicação
  * Criar links dinâmicos clicáveis e configuráveis para capítulos, seções, figuras e referências
  * Contar número de páginas
  * Customização dos cabeçalhos e rodapés

Funções úteis para uma dissertação/tese, derivadas de pacotes extras, também estão incluídas e configuradas:

  * Caracteres especiais mapeados no PDF (torna-os 100% buscáveis)
  * Formatar as citações de forma flexível no texto
  * Usar a vírgula como separador decimal
  * Colocar figuras de fundo (e.g., para capa e afins)
  * Formatar unidades de forma consistente
  * Criar lista de abreviações
  * Marcar mudanças e fazer comentários

## Download ##

**[Mestre em LaTeX v0.2 - 2010-05-01](http://mestre-em-latex.googlecode.com/files/mestre-em-latex_v0.2-2010-05-01.zip)**

Os arquivos principais e mais atualizados também estão no [Mercurial](http://code.google.com/p/mestre-em-latex/source/browse/).

Sua sugestão é muito importante! Se você usou o **Mestre em LaTeX** e tem sugestões ou comentários entre em [contato](http://organelas.com/contato/).

Caso tenha encontrado algum bug ou queira sugerir alguma melhoria específica adicione um novo item no [tracker do projeto](http://code.google.com/p/mestre-em-latex/issues/list) para que o problema seja resolvido. Este é o melhor jeito para submeter sugestões!

## Informações Relevantes ##

Este pacote foi inteiro testado no **Ubuntu** (Linux) com os pacotes oficiais da distribuição, mas alguns usuários já utilizaram com sucesso no **Windows** e **Mac**.

Para funcionamento básico no Ubuntu instale os pacotes `texlive-full` e `cm-super` (para que os caracteres especiais sejam corretamente escritos no PDF - não é estritamente necessário, mas altamente recomendável).

Para mandar uma versão editável ao seu orientador, caso ele não use LaTeX, transforme seu documento em RTF (editável em MSWord e OOffice) através do pacote `latex2rtf` (_i.e._ execute `latex2rtf mestrado.tex` num terminal).

Como optei por gerar PDFs (e não PS e DVI) o **Mestre em LaTeX** foi configurado para ser compilado com o `pdflatex`. Compilar apenas com o comando `latex` vai gerar arquivos PS e DVI sem figuras e com outras alterações.

## Links Relevantes ##

Não sabe o que é **LaTeX** ou não conseguiu usar o **Mestre em LaTeX**, mas achou interessante? Aqui estão alguns links úteis para começar e continuar aprendendo sobre **LaTeX**:

  * [Wikipedia](http://pt.wikipedia.org/wiki/LaTeX) ([en](http://en.wikipedia.org/wiki/LaTeX)) - Descrição informativa com alguns exemplos
  * [LaTeX Project](http://www.latex-project.org/) - Site do projeto com documentação
  * [TUG](http://www.tug.org/) - Grupo de usuários com muitas informações úteis
  * [CTAN](http://www.ctan.org/) - Arquivo com infinidade de pacotes feitos por usuários
  * [Wikibooks](http://en.wikibooks.org/wiki/LaTeX/) - Excelente página para aprender os básicos
  * [TeX-BR](http://www.tex-br.org/) - Wiki sobre LaTeX em português