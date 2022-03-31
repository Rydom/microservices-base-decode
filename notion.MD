# Decode #020

## Princípios de microsserviços

- Única responsabilidade dentro do domínio
    - O que é domínio (DDD)?
- Autonomia (sem dependências entre serviços)

### Ganhos

- Independência
    - Times
    - Github
    - CI/CD
- Fácil manutenção
    - Menos código
    - Menos responsabilidades
    - Menos testes
    - Ambiente de dev mais enxuto
- Escalonamento independente

### Desafios

- Observabilidade
- Comunicação
- Resiliência a falhas

### Conceitos importantes

- Isolar por domínios
    - A mesma entidade pode ser representada de formas diferentes em cada domínio
- Banco de dados isolados
- Comunicação assíncrona

## Hands-on

### App

Uma aplicação que simula o recebimento de uma compra e envia os dados do produto comprado para outra plataforma “liberar o acesso” do usuário ao produto.

### Ferramentas

- Kafka
- Node.js
- TypeScript
- PostgreSQL

### Deploy

- Upstash Kafka
- Railway Node.js
