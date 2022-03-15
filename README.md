# Primeiro-Repositório
conhecimentos sobre git

#  GIT 

### Comandos basicos para o terminal

#### windows                                         linux 

cd- navegar pela pasta                                    cd-         "" 

dir- lista                                                              ls-           ""

mkdir- cria pasta                                              mkdir-    ""

del/rrmdir deletar pasta                                 rm -rf -   ""

cls - limpar                                                         clear-     ""

echo imprimi na tela 

cd .. - sair                                                             cd ..-    ""

ls -a mostra arquivos ocultos

#### Por baixo dos panos do git

sha1- significa secure hash algorithm(algoritmo seguro), é um conjunto de funções 

hash criptográficas projetadas pela nsa(agência de segurança nacional dos EUA).

A encriptação gera conjunto de charactes identificador de 40 dígitos. Git usa ele

 porque é muito seguro.



 

openssl sha1 “arquivo”.txt



**Objetos fundamentais**



Blobs- Os arquivos ficam guardados nesse objetos e tem vários metadados nele

ex:Blob

​      \0

​     Ola Mundo



Trees- Armazena e aponta blobs, tem metadados , tem o arquivo. A tree é responsavel de

montar todas as estruturas aonde estão localizados os arquivos. Tree aponta pra outra tree





Commits- ele é objeto que vai juntar tudo. O commit ele aponta pra o tree, parente

ou seja(pra o último commit feito),autor(da sentido), mensagem(da sentido 

nas informações), timestamp.OBS- o commit só pode um autor.



**Sistema distribuido**



**Segurança**





**CHAVE SSH**



É uma forma de fazer uma conexão segura e incriptada entre duas máquinas ou seja

conectar com servidor do github e nossa máquina local como uma maquina confiável
