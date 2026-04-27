# BeatFlow

Sistema de gerenciamento de bandas e músicas desenvolvido em C# com foco em orientação a objetos, modelagem de entidades e manipulação de coleções com LINQ.

---

## Tecnologias

| Tecnologia | Descrição |
|---|---|
| C# | Linguagem principal |
| .NET | Plataforma de desenvolvimento |
| LINQ | Manipulação e consulta de dados |
| OOP | Orientação a objetos |
| Console Application | Interface de execução |

---

## Funcionalidades

- Cadastro de bandas, cantores e músicas
- Sistema de avaliação de bandas com cálculo de média via `Average()`
- Consulta de bandas e músicas por nome com `ContainsKey()`
- Armazenamento em memória com `Dictionary<string, List<T>>`
- Menu interativo no console para navegação entre as opções

---

## Estrutura do projeto

```
BeatFlow/
├── Models/
│   ├── Banda.cs
│   ├── Musica.cs
│   └── Cantor.cs
├── Services/
│   └── BeatFlowService.cs
└── Program.cs
```

---

## Como executar

**Pré-requisito:** .NET SDK instalado — [download aqui](https://dotnet.microsoft.com/download)

```bash
git clone https://github.com/gustavodsilva/BeatFlow
cd BeatFlow
dotnet run
```

---

## Conceitos aplicados

- Modelagem de entidades com classes e propriedades em C#
- Uso de `Dictionary<string, List<T>>` para armazenamento e busca eficiente
- Operações LINQ: `Average()` para média de avaliações, `ContainsKey()` para validação
- Encapsulamento e organização de responsabilidades por classe
- Menu de navegação com controle de fluxo via `switch/case`

---

## Autor

**Gustavo Silva Tiano**
[LinkedIn](https://www.linkedin.com/in/gttiano/) | [GitHub](https://github.com/gustavodsilva)
