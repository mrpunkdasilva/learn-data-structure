# List

As listas são um ADT que:
- Permite armazenar um elemento de qualquer tipo de dado
- Permite escrever um elemento em uma posição
- Permite ler um elemento em uma posição
- Permite remover um elemento em uma posição
- Permite atualizar um elemento em uma determinada posição

Uma implementação concreta deste ADT é uma Array, onde:
- Os elementos da array podem ser de qualquer tipo de dado
- Temos todas as opções a cima de operações

```c
int A[10];

A[0] = 10;

print A[0];
```

Então podemos montar algumas funcionalidades:

```
List
|__ lista vazia tem tamanho 0
|__ insert
|__ remove
|__ count (quantidade de elementos)
|__ ler/modificar elemento em determinada posição
|__ especificar o tipo de dado
```

 ## Pensando nas operações

