# Projeto de pesquisa - Criando ambientes virtuais de conversação com uso system call select()

## Compilando o servidor

```
gcc -o servidor servidor.c
```

## Rodando o servidor

```
./servidor [ip do servidor] [porta do servidor]

# Exemplo
./servidor 127.0.0.1 4000
```

## Conectando clientes

```
telnet 127.0.0.1 4000

# Insira o nome de usuário
Vitor

# Insira a sala que deseja entrar (-1 para criar um novo bate-papo)
-1

# Limite de participantes
5

# Inicie o bate papo
Eae guys, tudo certo?
```

# Comandos

```
# Listar
/l ou /listar

# Trocar de sala
/trocar_sala ou /t
$[número da sala desejada]

## Exemplo
/t
1

# Sair 
/s ou /sair

```
