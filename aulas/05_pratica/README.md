# Ordenação em Bash

## Deadline

Prazo: **10/11/2021 (Qua)** pelo link do GitHub (https://classroom.github.com/a/xbh37Ie6).

Você deve escolher seu nome na lista de alunos. Em seguida, o GitHub irá criar um repositório deste trabalho em seu usuário.

## Descrição

Ordene usuários de acordo com o formato de entrada abaixo em cada
tarefa:
1. Ordem por login (ordem alfabética)
2. Ordem por nome
3. Agregados por grupo, e ordenados por nome (ordem reversa)
4. Ordenar por idade (ordem numérica)

Formato de entrada:
``` 
login|name|group|age|home
```

Exemplo de entrada: [a6-input-example.txt](./a6-input-example.txt). Para gerar novas
entradas, use o script [gen-random-users.sh](./gen-random-users.sh).

A saída esperada será:
```
Task 1:
        Ana Novaes Alves
        Ana Pinto Rocha
        .......
        Rafael Nascimento Rezende
Task 2:
        Ana Novaes Alves
        .......
        Gabriel Santos Pinto
        Gabriel Mendes Rodrigues
        .......
        Rafael Nascimento Rezende
Task 3:
        inf2000:
                Francisco Gomes Castro
                Ana Pinto Rocha
        inf2001:
                .........
Task 4:
        Maria Silva Campos
        Gabriel Cardoso Castro
        Gabriel Mendes Rodrigues
        ..........
```

**Comandos básicos** - `cat`, `sort`, `uniq`, `cut`.

Dicas:
- Organize cada tarefa em funções Bash
- Procure informações sobre as opções em cada comando

Uma função em `bash` tem o seguinte formato:
```sh
#!/bin/bash

foo(){
    echo "Chamada de funcao aqui"
}

foo
```