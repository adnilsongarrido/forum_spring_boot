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



![image](https://user-images.githubusercontent.com/97981213/149999964-c35f3a4b-f6e2-4e64-8ef6-5cbc3af45257.png)
