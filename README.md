--------------------  Comandos Bash --------------------

\> <nome_do_arquivo>

mkdir - Cria Diretorio

!$ - Repete o último argumento do camando anterior

cat <nome_do_arquivo> - exibe o conteudo do arquivo

rm <nome_do_arquivo> - apaga um arquivo
rm -r <nome_do_diretorio> - apaga um diretorio com conteudo
rm -rf <nome_do_diretorio> - apaga um diretorio com conteudo sem perguntar

file - Identifica o tipo de arquivo

./ - diretorio atual.

echo $? - retorno do programa 

man 3 printf - Manual de C no linux

cat <nome_do_arquivo> - Exibe conteudo do arquivo.

hd -

bc - 

cp /home/teste.txt /home/exemplo - copia arquivos
cp diretorio-01 diretorio-02 - copia diretorio
cp aula01_teste.c aula01.c - renomeia arquivos.
mv /home/teste.txt /home/exemplo - recorta (move) arquivos.

mv diretorio diretorio-01 - renomeia diretorio

echo $? - significa status do seu comando anterior

------------------------- SSH -------------------------

service ssh status

------------------------- GCC -------------------------

gcc -o <nome_do_programa_copilado> <nome_do_programa_em_c>

!gcc - 

--------------------- Comandos VIM ---------------------

:set nocp - Modo compatibilidade VIM

i - Entra no Modo de edição
ESC- Entra no Modo de comandos

:q - Sair
:w - Salvar
:w <Nome do arquivo> - Salvar um novo arquivo
:wq - Salvar e sair
:x  - Salvar e Sair
vi <nome_do_arquivo> - Cria um arquivo.


o - Cria uma nova linha abaixo do cursor
u - Undu (Desfazer)
Ctrl + a - Adiciona uma unidade um u número.
Ctrl + x - Remove um aunidade de um número.
dd - Deleta uma linha.
x - Deleta de catacter em caracter.

-- Recortar e Colar --
v - para selecionar
y - copiar
d - recortar
p - colar


u - desfaz a última mudança (pode ser repetido para diversos comandos)
U - desfaz todas as mudanças na última linha editada
CTRL-R - refaz as mudanças desfeitas (isto é, um "undo do undo").

-- Configurações:
:set nu - Numera as linhas
:syntax on - Cor no código
