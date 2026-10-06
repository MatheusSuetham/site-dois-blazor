# Site Dois Blazor

Projeto desenvolvido em Blazor para praticar interatividade, formulários simples, navegação e uso de eventos com C#.

## Exercícios implementados

### 1. Conversor de Temperatura

Rota:

```text
/conversor
```

Permite informar uma temperatura em Celsius e convertê-la para Fahrenheit usando:

```text
F = (C × 9/5) + 32
```

### 2. Calculadora de Média

Rota:

```text
/media
```

Permite informar duas notas, calcula a média aritmética e exibe:

- `Aprovado!` para média maior ou igual a 7
- `Reprovado!` para média menor que 7

### 3. Sorteador de Números

Rota:

```text
/sorteio
```

Gera um número aleatório entre 1 e 100 utilizando `Random`.

### 4. Menu lateral

As páginas Conversor, Calculadora de Média e Sorteador foram adicionadas ao `NavMenu.razor`.

## Tecnologias utilizadas

- C#
- .NET 10
- Blazor
- Razor Components
- Interactive Server

## Como executar

Entre na pasta do projeto:

```bash
cd SiteDoisBlazor
```

Execute:

```bash
dotnet watch
```

Depois utilize o menu lateral para acessar as páginas.

## Repositório

Nome solicitado para o repositório:

```text
site-dois-blazor
```
