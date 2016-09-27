# Template LaTeX para Trabalho de Conclusão de Curso da UTFPR (UTFPR-GP/Curso de TSI) 

Site: http://tcc.tsi.gp.utfpr.edu.br/paginas/modelos-latex-da-utfpr

Customização da classe abnTeX2: https://github.com/abntex/abntex2

Para instalar a versão mais recente do abnTeX2, siga as instruções em: https://github.com/abntex/abntex2/wiki/InstalacaoLinux

# Editar
No arquivo principal "utfpr-tcc.tex" estão todas as inclusões das partes do trabalho, caso não queira inserir algum dos elementos basta excluir a linha que contém o comando \include do arquivo que se deseja excluir.

Caso queira incluir mais capítulos dentro da pasta "estrutura/textuais/desenvolvimento" basta criar o arquivo .tex dentro da pasta e incluí-lo via comando \include no arquivo principal "utfpr-tcc.tex".

Utilize um editor de textos de sua preferência (recomendável ATOM ou GEDIT) para editar os arquivos .tex
Todas as seções do trabalho são auto-explicativas bastando seguir as orientações de cada arquivo.

Os elementos referentes a dados do trabalho, tais como figuras, quadros, tabelas, algoritmos, devem ser armazenados no diretório "\dados" do projeto e inseridos conforme instruções da seção de orientações gerais.

As referências devem ser inseridas no arquivo "base-referencias.bib" e serão incluídas na seção de referências do trabalho caso sejam citadas no corpo do trabalho. Podem ser inseridas todas as referências desejadas no arquivo "base-referências.bib" com intuito de formar uma base de dados, estas referências não aparecerão no trabalho a menos que sejam citadas.
Caso deseje pode ser utilizado algum software de gestão de referências para gerar automaticamente o arquivo "base-referencias.bib" (recomendável JabRef).

# Compilar
Para compilar o projeto e gerar o documento no formato PDF, execute o seguinte comando dentro do diretório do projeto:

$ make

# Limpar
Para limpar os arquivos temporários, execute o seguinte comando dentro do diretório do projeto:

$ make clean

