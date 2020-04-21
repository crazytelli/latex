# LaTeX
A ideia é manter os templates mais úteis sempre atualizados e ter maior controle sobre as eventuais modificações e adequações dos templates para os demais modelos de trabalhos acadêmicos.

## Arquivos disponíveis:

O arquivo `template-relatorio.tex` é um template para relatório como usado em `EnD-LaTeX/relatorio_biblatex.tex`.
Ainda há margem para melhorias do arquivo, mas para um relatório básico atende perfeitamente as normas da universidade e ABNT.

O arquivo `tex.snippets` deve ser colocado em algum diretório no path do neovim como `~/AppData/Local/nvim/my_snippets`. Ele necessita do plugin UltiSnips.

## Bibliografias
o arquivo `bib.bib` contém as bibliografias utilizadas de maneira genérica. Aos escrever documentos, priorizar a utilzação do pacote `biblatex` em oposição ao `abntex2cite` por este último utilizar tecnologia mais defasada como BibTex ao invés de BibLaTeX.

## Gerador de tabelas online

O site [table-generator](https://tablesgenerator.com/latex_tables) é um
assistente online de criação de tabelas nos formatos LaTeX, HTML, Markdown, etc.

## A fazer:

- Template para notas de aulas utilizando neovim e UltiSnips
