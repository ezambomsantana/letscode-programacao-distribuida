# Micros Serviços

## O que são Micros Serviços?

Arquitetura de software na qual a aplicação é divididade em diversos serviços independentes.

### Principais Características

- Propósito Único: Cada microserviço deve ter uma única responsabilidade.
- Baixo Acomplamento: Os serviços tem que ser o mais independentes possível um dos outros. O deploy de cada um obrigatóriamente tem que ser independente. Banco de dados únicos para cada serviço.
- Alta Coesão:

### Exemplo



### Vantagens

- Desenvolvimento mais rápido
- Manutenção mais fácil
- Paralelização de trabalho
- Escalabilidade de serviços específicos

### Desvantagens

- Deploy muito mais complexo
- Desempenho pior por causa de comunicação
- Gerenciamento mais complexo

## Tecnológias Relacionadas

- Conteinerização (Docker)
- Execução e Orquestração de Microsserviços (docker-compose, Kubernetes)
- Comunicação entre serviços (Assíncrona e Síncrona)
- CI/CD
- Cache