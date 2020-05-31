# curl.md

http://onlinecurl.com

### Help
```properties
curl --help
```

| Opção | Descrição |
|-------|-----------|
-H    | Modificar abeçalho | "Content-type: application/json" |
-d    | Payload | '{"name": "Geilson Ribeiro"}' |
-i    | Incluir cabeçalho no resultado |
-I    | Retorna apenas o cabeçalho |
-X    | Especifica o verbo HTTP |

### Retornar requisição e cabeçalho
```properties
curl -i http://jsonplaceholder.typicode.com/posts/1
```

### Retornar apenas o cabeçalho
```properties
curl -I http://jsonplaceholder.typicode.com/posts/1
```
