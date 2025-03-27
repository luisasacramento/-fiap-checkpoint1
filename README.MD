# API de Pedidos - Checkpoint 1

Esta API permite gerenciar pedidos através de operações CRUD.

# Spring Initializr
![alt text](image.png)
- Java 17
- Spring Boot 
- H2 Database

# H2 conectado 
![alt text](image-1.png)



# Endpoints

## `GET /pedidos` → Lista todos os pedidos.
![alt text](image-3.png)

## `GET /pedidos/{id}` → Busca um pedido pelo ID.
![alt text](image-4.png)
![alt text](image-5.png)

## `POST /pedidos` → Cria um novo pedido.
![alt text](image-2.png)

## `PUT /pedidos/{id}` → Atualiza um pedido existente. (Pedido 1 alterado.)
![alt text](image-6.png)

## `DELETE /pedidos/{id}` → Remove um pedido. (pedido 1 não exixte mais)
![alt text](image-7.png)

## `DELETE /pedidos/{id}` listagem sem o pedido 1 que foi deletado
![alt text](image-8.png)


# Resultado final do H2
![alt text](image-9.png)
