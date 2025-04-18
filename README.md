# Projeto E-Shop Brasil

## Introdução
A E-Shop Brasil, uma das maiores plataformas de e-commerce do país, enfrenta desafios com a gestão de dados e a logística. Este projeto apresenta uma solução prática utilizando Docker, MongoDB e Streamlit para apoiar essas demandas.

## Objetivos
- Melhorar a gestão de dados utilizando MongoDB.
- Criar uma aplicação prática para inserção, consulta e manipulação de dados.
- Executar tudo em um ambiente Docker padronizado.

## Descrição do Projeto

### Docker
O Docker é usado para garantir que o ambiente da aplicação seja consistente e facilmente reproduzível. Com o `docker-compose.yml`, criamos um container com MongoDB e outro para executar a aplicação Streamlit.

### MongoDB
O banco MongoDB é iniciado em um container Docker, armazenando dados como pedidos, produtos e clientes fictícios.

### Streamlit (app.py)
A aplicação conecta-se ao MongoDB e oferece funcionalidades como:
- Inserção de dados (clientes, pedidos)
- Edição e exclusão
- Consulta e exibição com filtros

## Passos para Implementação

1. Suba a infraestrutura com:
```bash
docker-compose up
```

2. Acesse a aplicação em:
```
http://localhost:8501
```

## Funcionalidades da Aplicação
- Inserir dados no banco MongoDB.
- Manipular dados existentes (edição ou exclusão).
- Concatenar dados de diferentes coleções.
- Realizar consultas e exibir os dados via interface Streamlit.

## Testes e Exemplos
Confira a pasta `/exemplos` com prints do sistema funcionando.

---

