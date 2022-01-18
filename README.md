# forum_spring_boot

Segue alguns exemplos de teste (com Postman, por exemplo):

1 - http://localhost:8080/topicos (POST)
    {
    "titulo":"",
    "mensagem":"Texto da mensagem 2",
    "nomeCurso":"Spring Boot"
    }
    
2 - http://localhost:8080/topicos/3 (GET)

3 - http://localhost:8080/topicos/3 (PUT)
    {
    "titulo":"Atualizado",
    "mensagem":"Mensagem nova"
    }
    
4 - http://localhost:8080/topicos/2 (DELETE)
