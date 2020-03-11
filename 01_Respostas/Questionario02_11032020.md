# Sistemas Operacionais Embarcados

** Question�rio 02 - 11/03 **

**1 - O que � o Linux?**

Sistema operacional baseado em Unix, criado para desktop. Composto por um kernel , software utilizado para fazer a comunica��o de outros programas e traduzi-los em comandos para a CPU e outros componentes eletr�nicos.

**2 - O que s�o daemons?**
Programa de computador que roda em plano de fundo.Recomenda-se finalizar o nome dos processos que s�o daemons com a letra 'd' para diferenciar um processo do tipo daemon de um processo comum de outros usu�rios interativos.

**3 - O que � o shell?**
Liga��o entre usu�rio e sistema, respons�vel por interpretar os comandos entrados para outros aplicativos ou diretamente em chamadas de sistema. Possui recursos indispens�veis para lidar com tarefas repetidas ou programar determinada a��o.

**4 - Por que � importante evitar executar o terminal como super usu�rio?**
O super-usu�rio ou root, tem controle total sobre o sistema e pode deletar arquivos, programas e at� mesmo remover usu�rios. Sendo assim, � recomendado evitar usar o terminal como super usu�rio para que n�o ocorra erros ou remo��es indesejadas.

**5 - Qual bot�o do terclado completa o que o usu�rio escreve no terminal, de acordo com o contexto?**
O bot�o TAB.

**6 - Quais os bot�es do teclado apresentam instru��es escritas anteriormente?**
 As setas direcionais para cima e para baixo

**7 - Apresente os respectivos comandos no terminal para:**

* (a) Obter mais informa��es sobre um comando.
-help ou -h

* (b) Apresentar uma lista com os arquivos dentro de uma pasta.
ls

* (c) Apresentar o caminho completo da pasta.
pwd % 

* (d) Trocar de pasta.
cd

* (e) Criar uma pasta.
mkdir % make directory

* (f) Apagar arquivos definitivamente.
rm %

* (g) Apagar pastas definitivamente.
rm ou rmddir % remove/remove directory

* (h) Copiar arquivos.
cp

* (i) Copiar pastas.
cp -a

* (j) Mover arquivos.
mv

* (k) Mover pastas.
mv -a

* (l) Renomear pastas.
mv ./nomeVelho ./nomeNovo

* (m) Apresentar o conte�do de um arquivo.
cat nomeDoArquivo %

* (n) Apresentar o tipo de um arquivo.
file -b nomeDoArquivo %

* (o) Limpar a tela do terminal.
clear

* (p) Encontrar ocorr�ncias de palavras-chave em um arquivo-texto.
grep PalavraChave NomeDoArquivo

* (q) Ordenar informa��es em um arquivo-texto.
sort NomeDoArquivo

* (r) Substituir ocorr�ncias de palavras-chave em um arquivo-texto.
sed -n PalavraChave

* (s) Conferir se dois arquivos s�o iguais.
diff NomeDoArquivo1 NomeDoArquivo2 ou cmp -- silent NomeDoArquivo1 NomeDoArquivo2

* (t) Escrever algo na tela.
echo "texto a ser impresso"