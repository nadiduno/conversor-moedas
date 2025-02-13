## Tecnologias

*   **Java:** Linguagem de programação principal.
*   **Spring Boot:** Framework para desenvolvimento rápido de aplicações Java.
*   **Maven:** Ferramenta de gerenciamento de dependências e build.
*   **PostgreSQL:** Banco de dados relacional utilizado.

## Configuração do Banco de Dados

Para configurar o banco de dados, você precisará ajustar as seguintes propriedades no arquivo `application.properties` ou `application.yml` (preferencialmente `application.yml` para melhor organização):

```xml
  datasource:
    url: jdbc:postgresql://localhost:8080/ moeda_db
    username: # Seu usuário do PostgreSQL
    password: # Sua senha do PostgreSQL
    
```


## 🙌 Contribuindo

Estamos sempre abertos a novas ideias e contribuições! Siga estas etapas:

1. **Faça um fork do repositório**
2. **Crie uma nova branch**: `git checkout -b minha-contribuicao`
3. **Faça suas alterações e commit**: `git commit -m "Adicione uma mensagem descritiva"`
4. **Envie suas alterações**: `git push origin minha-contribuicao`
5. **Abra uma solicitação pull**

