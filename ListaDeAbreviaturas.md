# Usando o nomencl #

O pacote [nomencl](http://www.ctan.org/tex-archive/macros/latex/contrib/nomencl/) gera uma lista das abreviações usadas no texto. Primeiro é necessário copiar os arquivos `nomencl.sty` e `nomencl.ist` para a pasta com o documento `.tex` (eles já vem no **Mestre em LaTeX**). As instruções do **nomencl** são as seguintes:

  * Adicione `\usepackage{nomencl}` e `\makenomenclature` no preâmbulo do documento.
  * Após a primeira aparição de uma abreviação no texto adicione o comando `\nomenclature{SIGLA}{DESCRIÇÃO}%`. O `%` é uma recomendação do autor do pacote.
  * Por fim, adicione o comando `\printnomenclature` no corpo do texto onde a lista será criada.

No entanto, para criar e atualizar a lista é necessário executar um comando extra (além da compilação). No **Linux** e **Mac** o comando é:

```
makeindex ARQUIVO.nlo -s nomencl.ist -o ARQUIVO.nls
```

No **Windows** você pode executar este mesmo comando, mas usando o `makeindex.exe` (vem dentro do diretório do MiKTeX). Para que o comando acima seja executado toda vez que você compilar seu documento, adicione ao _Output profile_ um _Postprocessor_ com o caminho para o `makeindex.exe` no campo _Executable_ e o seguinte no _Arguments_:

```
"%bm".nlo -s nomencl.ist -o "%bm".nls
```

Segue uma figura para ilustrar (apenas lembre de usar o comando acima no campo _Arguments_):

![http://www.latex-community.org/forum/download/file.php?id=353&sid=fcf5ce29a9864daac2b66c787facc716&nonsense=buildprofile.jpg](http://www.latex-community.org/forum/download/file.php?id=353&sid=fcf5ce29a9864daac2b66c787facc716&nonsense=buildprofile.jpg)