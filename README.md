## Subindo o ambiente com Docker e criando o modelo

1. Subir os containers em segundo plano:
   
```
docker compose up -d
```
2. Criar o modelo dentro do container já rodando:

```
docker compose exec ollama ollama create js-tester -f /models/js-tester.Modelfile
```
