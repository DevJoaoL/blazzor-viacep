# 📮 BlazzorWasmViaCep

Aplicação web desenvolvida com **Blazor WebAssembly (.NET 8)** para consulta de endereços a partir do CEP, utilizando a API pública [ViaCEP](https://viacep.com.br/).

## 🔗 Demo

[https://DevJoaoL.github.io/blazzor-viacep/](https://DevJoaoL.github.io/blazzor-viacep/)

## ✨ Funcionalidades

- Consulta de endereço por CEP em tempo real
- Exibição de rua, bairro, cidade, região, UF e DDD
- Validação de CEP (somente números, 8 dígitos)
- Tratamento de erros de conexão e CEP inválido

## 🛠️ Tecnologias

- [Blazor WebAssembly](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor) — .NET 8
- [ViaCEP API](https://viacep.com.br/) — API pública de consulta de CEPs
- Bootstrap 5 — estilização

## 🚀 Como rodar localmente

**Pré-requisito:** [.NET 8 SDK](https://dotnet.microsoft.com/download)

```bash
git clone https://github.com/DevJoaoL/blazzor-viacep.git
cd blazzor-viacep/BlazzorWasmViaCep
dotnet run
```

Acesse `http://localhost:5000` no navegador.

## 📁 Estrutura do projeto

```
BlazzorWasmViaCep/
├── Pages/
│   └── Home.razor        # Página principal com a consulta de CEP
├── Models/
│   └── Endereco.cs       # Model com os campos retornados pela API
├── Layout/
│   └── MainLayout.razor  # Layout base da aplicação
└── wwwroot/
    └── index.html        # Entry point da aplicação
```

## 📄 Licença

Este projeto está sob a licença MIT.
