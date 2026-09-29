# Aula7_Atividade
## API Empresa de Notebooks

Projeto exemplo para aula de desenvolvimento de sistemas backend utilizando dados em mockup JSON

- times.json

```JSON
[
    {
        "id": 1,
        "item": "Notebook Dell",
        "local": "Labarotório 01",
        "dataRegistro": "2026-09-10",
        "valor": 3500.00,
        "patrimonio": "PAT-00125"
    },
    {
        "id": 2,
        "item": "Projetor Epson",
        "local": "Sala 03",
        "dataRegistro": "2026-09-03",
        "valor": 2800.00,
        "patrimonio": "PAT-00126"
    }
]
```

## Tecnologias
- VsCode
- Node.js
- JavaScript
- JSON

## Passos para executar

- 1 Clone o repositório
- 2 Abra com VsCode e em um teminal CMD ou BASH didige:

npm install
npm run dev

- 3 Teste as rotas com a extensão Thunder Client do VsCode

### Para testar o Front-End
- Abra o arquivo client/index.html com a extensão Live Server do VsCode

## Rotas

app.get: http://localhost:3000/inventario

app.post: http://localhost:3000/inventario

app.delete: http://localhost:3000/inventario/:id

app.put: http://localhost:3000/inventario/:id

## Exemplos de requisições
- Create POST: http://localhost:3000/inventario
- Corpo

```JSON
{
        "item": "Notebook Samsung",
        "local": "Sala 05",
        "dataRegistro": "2026-10-09",
        "valor": 3000.00,
        "patrimonio": "PAT-00127"
}
```

- Resposta

```JSON
{
        "id": 3,
        "item": "Notebook Samsung",
        "local": "Sala 05",
        "dataRegistro": "2026-10-09",
        "valor": 3000.00,
        "patrimonio": "PAT-00127"
}
```

- Update PUT: http://localhost:3000/inventario/:id

```JSON
{
        "item": "Notebook AOC",
        "local": "Sala 04",
        "dataRegistro": "2026-10-10",
        "valor": 2900.00,
        "patrimonio": "PAT-00128
}
```

- Resposta

```JSON
{
        "id": 4,
        "item": "Notebook AOC",
        "local": "Sala 07",
        "dataRegistro": "2026-10-11",
        "valor": 2990.00,
        "patrimonio": "PAT-00129
}
```

## Testes com extensão Thunder Client do VsCode

<img width="904" height="800" alt="image" src="https://github.com/user-attachments/assets/950888fe-8917-46cc-b68b-3b2a7ffe2ae0" />

<img width="915" height="965" alt="image" src="https://github.com/user-attachments/assets/def77966-c98a-4e0d-a77c-98e109ca8a2f" />

<img width="858" height="900" alt="image" src="https://github.com/user-attachments/assets/b6b648a7-e8de-4fa0-9a3b-7680064ae9c7" />

<img width="858" height="900" alt="image" src="https://github.com/user-attachments/assets/693e3718-083b-4ef3-b092-984aa86c338b" />

