# review-apps-nginx
Exemplo de deploy em staging e produção usando nginx

# Motivação 
Ter uma aplicação que eu queira testar e não querer ou não ter recursos para criar mais de uma máquina em alguma cloud.

# Considerações
A configuração do nginx deve ser alterada ao enviar para alguma cloud de acordo com o domínio desejado.

# Como usar
- clone esse projeto
- acesse a pasta clonada
- rode o comando:
```
docker compose up -d
```
- acesse os endereços:
    - http://staging.localhost:8090/
    - http://prod.localhost:8090/