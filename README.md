# Projeto conversão de temperatura

### Sobre o projeto
Git clonado do curso devopspro  -> git@github.com:KubeDev/conversao-temperatura.git, aula realizada por fabricioveronez
Aula -> Transforme seu Desenvolvimento com Docker

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Criando e Executando -> imagem e Container
```
docker build -t conversao-temperatura .
docker container run --name conversao_temperatura -d -p 8080:8080 conversao-temperatura
```
