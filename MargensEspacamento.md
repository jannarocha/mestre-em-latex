# Margens #

Para alterar o tamanho das margens laterais experimente mudar os valores no arquivo `pre.tex` linhas 5 e 6, 24 e 25 (ele aparece 2 vezes por causa da página em branco depois da capa). O **Mestre em LaTeX** está configurado para que a margem interna seja maior que a externa (para que o conteúdo não seja obstruído quando o volume for encadernado). Os valores não são muito intuitivos... o valor 1.2cm não quer dizer q a margem tem 1.2cm, mas sim que tem 1.2cm a mais do que a margem padrão.

Se preferirem que as margens internas e externas tenham o mesmo tamanho em páginas ímpares e pares vá para o `meta.tex` na linha 13 e descomente (retire o `%` da frente do comando):

```
%\geometry{hcentering}
```

ps: vou melhorar estas instruções. em caso de dúvida entre em contato!

# Espaçamento #

O pacote que comanda o espaçamento entre linhas é o `setspace` (linha 11 do `meta.tex`) e já está pronto pra usar. Para mudar o espaçamento é só inserir um dos comandos ao longo do texto e tudo que vier abaixo estará com o novo espaçamento.

O padrão é **espaçamento simples**. Coloquei o comando `\doublespacing` para **espaçamento duplo** na linha 150 do arquivo `pre.tex`. Se você apagar este comando tudo ficará com espaçamento simples. Se substituí-lo por outro, todo o texto abaixo do comando vai mudar o espaçamento. Caso o comando seja colocado mais para o início do documento as primeiras páginas (capa, etc) podem perder a formatação original.

Enfim, experimente com os comandos e ajuste à gosto:

```
\singlespacing (simples)
\onehalfspacing (1,5)
\doublespacing (duplo)
```

Lembrando que o comando deve estar entre `\begin{document}` e `\end{document}`.