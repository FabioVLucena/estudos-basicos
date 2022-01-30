- = arquivo comum
d = diretorio
l = link simbolico
b = dispositivo de bloco
c = dispositivo de caractere
s = socket

rw- dono "d"
r-- grupo "g"
r--outros "o"

r = read {4}
w = write {2}
x = execute {1}

111 = dono, grupo e outros com execute
222 = dono, grupo e outros com escrita
444 = dono, frupo e outros com leitura
	
121 = dono execute, grupo escrita e outros execute

6 = 4 + 2 = leitura e escrita
5 = 4 + 1 = leiura e execute
3 = 2 + 1 = escrita e execute
7 = 4 + 2 + 1 = etc..

-rw-r--r-- 1jeferson staff 0B Oct 8 23:03 giropops

CHMOD = altera permissões de arquivos 
CHOWN = muda o dono ou o grupo dono = dono:grupodono

-rw-r--r-- 1jeferson staff 0B Oct 8 23:03 giropops

permissões especiais:

suid {4} = concede permissao temporaria a um usuario
sgid {2} = concede permissao temporaria a um grupo

setfacl -m user:fabio:rwx arquivo = permite ao fabio todos os acessos ao arquivo
setfacl -m group:grupo:rwx arquivo = permite ao grupo todos os acessos ao arquivo
setfacl -mr pode ser usado de forma recursiva para alterar todos os acessos da pasta e etc
getfacl arquivo = mostra as permissoes do arquivo

