# RentalCar.Coupon
Microserviço para gestão dos cupons oferecidos pela loja de aluguer de carros.

# Arquitectura do Projecto
![Diagrama](https://github.com/user-attachments/assets/3f4e648a-f0dd-4e5f-b633-d5fdbe90098a)


# Enum
### Type
| Key          | Value   |
|--------------|---------|
| Percentage   |   P     |
| FixedAmount  |   F     |


# Entities
### Coupon
| Type         | Variavel          | Description |
|--------------|-------------------|-------------|
| string       |   Id              |             |
| string       |   IdService       |             |
| decimal      |   Valor           |             |
| string       |   Codigo          |             |
| Type         |   Type            |             |
| DateTime     |   CreatedAt       |             |
| DateTime     |   ExpirationDate  |             |
| DateTime     |   UpdatedAt       |             |
| DateTime     |   DeletedAt       |             |
| bool         |   IsDeleted       |             |
<br/>

# Auxiliary Projects
| Project      | Link       | 
|--------------|----------------------------------------------------|
| Security     | https://github.com/Muecalia/RentalCar.Security     |

<br/>

# Linguagens, Ferramentas e Tecnologias
<div align="left">
  <p align="left">
    <a href="https://go-skill-icons.vercel.app/">
      <img src="https://go-skill-icons.vercel.app/api/icons?i=cs,dotnet,mysql,rabbitmq,git,kubernetes,docker,sonarqube,swagger,postman,githubactions,aws" />
    </a>
  </p>
</div> <br/>

# Monitoramento
<div align="left">
  <p align="left">
    <a href="https://go-skill-icons.vercel.app/">
      <img src="https://go-skill-icons.vercel.app/api/icons?i=prometheus,grafana" />
    </a>
  </p>
</div> <br/>

# Observabilidade e Tracing
![Jaeger_OpenTelemetry](https://github.com/user-attachments/assets/bac7e17b-c42c-48a8-83ab-c0c3c1b0f3dc)

<br/>

