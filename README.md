# 🃏 Super Trunfo - Nível Novato (Estácio - Exercício 01)

Este projeto é o **primeiro desafio prático** do jogo **Super Trunfo de Países/Cidades**, desenvolvido em linguagem C.  
O objetivo é praticar a **leitura de dados do usuário**, o **armazenamento em variáveis** e a **exibição formatada das informações**.

---

## 🎯 Objetivo do Exercício

Criar um programa em C que permita ao usuário cadastrar **duas cartas** do Super Trunfo com informações sobre cidades.  
Após o cadastro, os dados devem ser exibidos de forma clara e organizada na tela.

---

## 📋 Dados de cada carta

Cada carta deve armazenar as seguintes informações:

- **Estado:** Uma letra de `A` a `H` (char).  
- **Código da Carta:** A letra do estado seguida de um número de `01` a `04` (string).  
- **Nome da Cidade:** Nome da cidade (string).  
- **População:** Número de habitantes (int).  
- **Área:** Área da cidade em km² (float).  
- **PIB:** Produto Interno Bruto em bilhões de reais (float).  
- **Número de Pontos Turísticos:** Quantidade de pontos turísticos (int).  

---

## 📌 Regras e Simplificações

- O programa deve **cadastrar apenas duas cartas**.  
- Não utilizar **estruturas de repetição** (`for`, `while`) nem **estruturas de decisão** (`if`, `else`).  
- O código deve ser uma **sequência linear de instruções**.  
- O foco é apenas **ler, armazenar e exibir** os dados (sem comparações entre cartas).  

---

## 🖥️ Exemplo de Execução

### Entrada do Usuário:
```
Cadastro da Carta 1
Digite o estado (A-H): A
Digite o código da carta (Ex: A01): A01
Digite o nome da cidade: São Paulo
Digite a população: 12325000
Digite a área em km²: 1521.11
Digite o PIB (em bilhões de reais): 699.28
Digite o número de pontos turísticos: 50

Cadastro da Carta 2
Digite o estado (A-H): B
Digite o código da carta (Ex: B02): B02
Digite o nome da cidade: Rio de Janeiro
Digite a população: 6748000
Digite a área em km²: 1200.25
Digite o PIB (em bilhões de reais): 300.50
Digite o número de pontos turísticos: 30
```

### Saída esperada:
```
=== Carta 1 ===
Estado: A
Código: A01
Nome da Cidade: São Paulo
População: 12325000
Área: 1521.11 km²
PIB: 699.28 bilhões de reais
Número de Pontos Turísticos: 50

=== Carta 2 ===
Estado: B
Código: B02
Nome da Cidade: Rio de Janeiro
População: 6748000
Área: 1200.25 km²
PIB: 300.50 bilhões de reais
Número de Pontos Turísticos: 30
```

---

## 🛠️ Tecnologias Utilizadas

- Linguagem **C**
- Entrada/Saída padrão (`scanf` e `printf`)

---

## 🚀 Como Executar

1. Compile o programa:
   ```bash
   gcc supertrunfo.c -o supertrunfo
   ```

2. Execute o programa:
   ```bash
   ./supertrunfo
   ```

3. Digite os dados solicitados para cadastrar as duas cartas.  

---

## ✅ Critérios de Avaliação

- O programa **compila sem erros**.  
- As informações das cartas são **lidas corretamente** e **exibidas de forma organizada**.  
- O código é **simples, indentado e comentado** para melhor legibilidade.  

---

📚 Exercício da disciplina de **Programação Estruturada (Estácio)**.  
👨‍💻 Nível: **Novato**
