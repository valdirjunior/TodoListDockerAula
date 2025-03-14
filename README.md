# TodoListDockerAula

Aula de monolito com docker, docker-compose e nginx.

## Instruções do professor

1. Faça um fork deste repositório.
2. Clone o repositório para a sua máquina.
3. Siga as instruções do arquivo [Tutorial.md](Tutorial.md) para realizar a atividade.
4. Após finalizar a atividade, faça um commit e um push para o seu repositório.
5. Envie o link do seu repositório para o professor.

# Instruções para rodar o programa

1. Clone o repositório para a pasta de sua preferência na sua máquina;
2. No terminal, execute para construir o docker:

```sh
    docker compose up -d --build
    # não precisa se preocupar com as dependências,o docker instalará todas as necessárias através do Dockerfile
```

3. Caso queira conferir se os conteiners executaram corretamente, execute:

```sh
    docker compose ps
```
4. Acesse no seu navegador o endereço localhost;

5. Para encerrar e excluir os conteiners, execute:

```sh
    docker compose down
```
