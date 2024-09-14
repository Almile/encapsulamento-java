# 🚗💰 Exercícios em Java: Carro, Conta Bancária e Gestão de Produtos


Bem-vindo ao repositório de exercícios em Java! Aqui você encontrará soluções para exercícios focados no aprimoramento de habilidades em programação orientada a objetos utilizando **Java**. Os exercícios cobrem conceitos-chave como encapsulamento, manipulação de dados e lógica simples de negócios.

## 📚 Visão Geral dos Exercícios


### Exercício 1: Evoluindo o Conceito de Carro 🚗

Neste exercício, você irá expandir o conceito básico de uma classe `Carro`. Vamos adicionar a funcionalidade de calcular o custo total para encher o tanque de combustível.

**Instruções:**

- Adicione um novo atributo `capacidadeTanque` à classe.
- Crie um método para calcular o custo total para encher o tanque com base no preço do combustível fornecido pelo usuário.
- Inclua métodos getters e setters para os atributos.

**Requisitos:**

- O usuário deve fornecer informações do carro, como modelo, fabricante e capacidade do tanque.
- O método para calcular o custo do combustível deve receber o preço do combustível como parâmetro.


### Exercício 2: Gestão de Conta Bancária 💰

Este exercício introduz um sistema bancário simples usando a classe `ContaBancaria`.

**Instruções:**

- Crie uma classe `ContaBancaria` com os atributos privados `saldo` e `titular`.
- Os métodos para modificar o saldo devem ser públicos:
  - `depositar` - Permite depósitos, somente para valores positivos.
  - `sacar` - Permite saques apenas se o saldo for suficiente.
- Crie instâncias da classe e teste diferentes operações no método `main`.


### Exercício 3: Gestão de Produtos 🛒

Neste exercício, você implementará uma classe `Produto` que lida com a gestão básica de estoque.

**Instruções:**

- Adicione os atributos privados `nome`, `preco` e `quantidadeEstoque`.
- Utilize getters e setters para esses atributos.
- Implemente validações nos setters:
  - `preco` não pode ser negativo.
  - `quantidadeEstoque` só pode ser atualizada se for maior ou igual a zero.
- No método `main`, crie um objeto `Produto` e teste as regras de validação.

## 🚀 Como Executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/Almile/encapsulamento-java.git
   ```

2. Abra o projeto no seu IDE Java (ex: IntelliJ, Eclipse).

3. Execute cada exercício a partir do seu respectivo método `main`.

## 💻 Tecnologias Utilizadas

![GIT](https://img.shields.io/badge/Git-ededed?style=for-the-badge&logo=git&logoColor=gray) - **Git**: Controle de versão para acompanhar o progresso.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=gray) - **Java**: A linguagem de programação utilizada para programação orientada a objetos.



