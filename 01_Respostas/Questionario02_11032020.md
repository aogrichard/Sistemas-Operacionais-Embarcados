# Sistemas Operacionais Embarcados

** Questionário 02 - 11/03 **

**1 - O que é o Linux?**

Sistema operacional baseado em Unix, criado para desktop. Composto por um kernel , software utilizado para fazer a comunicação de outros programas e traduzi-los em comandos para a CPU e outros componentes eletrônicos.

**2 - O que são daemons?**
Programa de computador que roda em plano de fundo.Recomenda-se finalizar o nome dos processos que são daemons com a letra 'd' para diferenciar um processo do tipo daemon de um processo comum de outros usuários interativos.

**3 - O que é o shell?**
Ligação entre usuário e sistema, responsável por interpretar os comandos entrados para outros aplicativos ou diretamente em chamadas de sistema. Possui recursos indispensáveis para lidar com tarefas repetidas ou programar determinada ação.

**4 - Por que é importante evitar executar o terminal como super usuário?**
O super-usuário ou root, tem controle total sobre o sistema e pode deletar arquivos, programas e até mesmo remover usuários. Sendo assim, é recomendado evitar usar o terminal como super usuário para que não ocorra erros ou remoções indesejadas.

**5 - Qual botão do terclado completa o que o usuário escreve no terminal, de acordo com o contexto?**
O botão TAB.

**6 - Quais os botões do teclado apresentam instruções escritas anteriormente?**
 As setas direcionais para cima e para baixo

**7 - Apresente os respectivos comandos no terminal para:**

* (a) Obter mais informações sobre um comando.
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

* (m) Apresentar o conteúdo de um arquivo.
cat nomeDoArquivo %

* (n) Apresentar o tipo de um arquivo.
file -b nomeDoArquivo %

* (o) Limpar a tela do terminal.
clear

* (p) Encontrar ocorrências de palavras-chave em um arquivo-texto.
grep PalavraChave NomeDoArquivo

* (q) Ordenar informações em um arquivo-texto.
sort NomeDoArquivo

* (r) Substituir ocorrências de palavras-chave em um arquivo-texto.
sed -n PalavraChave

* (s) Conferir se dois arquivos são iguais.
diff NomeDoArquivo1 NomeDoArquivo2 ou cmp -- silent NomeDoArquivo1 NomeDoArquivo2

* (t) Escrever algo na tela.
echo "texto a ser impresso"