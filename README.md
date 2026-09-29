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

{
        "item": "Notebook Samsung",
        "local": "Sala 05",
        "dataRegistro": "2026-10-09",
        "valor": 3000.00,
        "patrimonio": "PAT-00127"
}

- Resposta

{
        "id": 3,
        "item": "Notebook Samsung",
        "local": "Sala 05",
        "dataRegistro": "2026-10-09",
        "valor": 3000.00,
        "patrimonio": "PAT-00127"
}

- Update PUT: http://localhost:3000/inventario/:id

{
        "item": "Notebook AOC",
        "local": "Sala 04",
        "dataRegistro": "2026-10-10",
        "valor": 2900.00,
        "patrimonio": "PAT-00128
}

- Resposta

{
        "id": 4,
        "item": "Notebook AOC",
        "local": "Sala 07",
        "dataRegistro": "2026-10-11",
        "valor": 2990.00,
        "patrimonio": "PAT-00129
}

## Testes com extensão Thunder Client do VsCode

<img width="1881" height="771" alt="image" src="https://github.com/user-attachments/assets/7384554a-3467-4e45-b09c-cf445d9af8db" />

<img width="1841" height="715" alt="image" src="https://github.com/user-attachments/assets/69a5b8d4-6cfb-441c-80b1-37716d5441c0" />

<img width="1852" height="849" alt="image" src="https://github.com/user-attachments/assets/712d7144-f73e-4971-82f2-aa4de94fc681" />

<img width="1766" height="798" alt="image" src="https://github.com/user-attachments/assets/56ad4dfc-9db2-4329-9afc-e3697702981a" />
