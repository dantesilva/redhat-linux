# Entendedo o Shell

## Shel

Interpretador de comandos em um Sistema Operacional Unix e Gnu/Linux. Um programa que executa outros programas. Fornece uma interface que possibilita o usuário uma interface para executar diferentes comandos e utilitários , com alguns dados de entrada.

## Variáveis do ambiene Shell

Quando fazemos login em um shell, uma ambiente com váriaveis é criado para aquela sessão.
Usando o comando 'env' é possível ver as varíaveis do sistema.

## Login mode e no login mode

Login mode -> Recomendado para investigar problemas com o  usuário;

#su - usuario (Entrar em login mode).

#su usuario (sem o hifen, para entrar no modo no login mode)

## Verificar váriavés do ambiente

#env -> Mostra todas as variáveis de ambiente de usuário

## Adicionar váriavel de usuario

Editar arquivo '.bashrc' que está dentro da pasta de usuário, e adicionar váriável ao final do arquivo.

Exemplo:

            $variavel=variavel1

Dando o comando 'echo $VARIAVEL' , o resultado será 'variavel1'.


