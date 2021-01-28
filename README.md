
# :new_moon: Desafio GoStack 
## Primeiro Desafio - Módulo 1 

##### :pencil2: SOBRE O DESAFIO:

Desafio da Rocketseat. Uma API para adição, edição, visualização e remoção de projetos e suas tarefas, do zero

###### :pushpin: MÉTODOS UTILIZADOS -HTTP, DESCRIÇÃO E ROTAS:
- [x] Listar todos os projetos
```
server.get('/projects');
```
- [x] Criar um projeto
```
server.post('/projects');
```

- [x] Listar apenas um projeto
```
server.get('/projects/:id');
```

- [x] Editar o title de um projeto
```
server.put('/projects/:id');
```

- [x] Excluir um projeto
```
server.delete('/projects/:id');
```

- [x] Adicionar uma tarefa no projeto
```
server.post('/projects/:id/tasks');
```

###### :mag: Tecnologias utilizadas: 

- Yarn
- Nodemon
- Express
- Node.js

Feito by Alexandre Martins 
