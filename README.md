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

<img width="669" height="772" alt="Captura de tela 2025-04-30 132616" src="https://github.com/user-attachments/assets/c8d1ee7c-8ca6-48c3-8411-8b3eb7e29e5a" />

<img width="669" height="772" alt="Captura de tela 2025-04-30 132616" src="https://github.com/user-attachments/assets/65d8816a-e0cb-4221-a038-fd41517e9d1f" />

<img width="669" height="772" alt="Captura de tela 2025-04-30 132616" src="https://github.com/user-attachments/assets/71d5a13d-ab50-4d5a-b229-9018dac220ea" />

<img width="669" height="772" alt="Captura de tela 2025-04-30 132616" src="https://github.com/user-attachments/assets/7eda0819-5565-4be9-be4e-c0872bc64c65" />

