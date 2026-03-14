# 🏦 Sistema Bancário Simples — Java

Aplicação de console desenvolvida em Java que simula operações bancárias básicas por meio de um menu interativo.

---

## 📋 Descrição

O programa exibe os dados iniciais de um cliente e oferece um menu com opções para consultar saldo, receber valores, realizar transferências e sair do sistema. Ideal para praticar conceitos fundamentais de Java como `Scanner`, `do-while`, `switch-case` e estruturas condicionais.

---

## ⚙️ Funcionalidades

- ✅ Exibição dos dados iniciais do cliente
- ✅ Consulta de saldo
- ✅ Recebimento de valores
- ✅ Transferência com validação de saldo suficiente
- ✅ Menu em loop até o usuário escolher sair

---

## 🖥️ Como executar

### Pré-requisitos

- [Java JDK](https://www.oracle.com/java/technologies/downloads/) 8 ou superior instalado
- Terminal ou IDE de sua preferência (IntelliJ, Eclipse, VS Code)

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# 2. Acesse a pasta do projeto
cd seu-repositorio

# 3. Compile o arquivo
javac Main.java

# 4. Execute o programa
java Main
```

---

## 📸 Exemplo de uso

```
************************
Dados iniciais do cliente:

Nome: Ana
Tipo de conta: Corrente
Saldo inicial: R$2500.0
************************

***** MENU *****
1. Consultar saldo
2. Receber valor
3. Transferir valor
4. Sair
Digite a opção desejada:
> 1
Saldo: R$2500.0

***** MENU *****
...
> 3
Informe o valor a ser transferido:
> 500
Saldo atualizado: R$2000.0

***** MENU *****
...
> 4
Saindo... Até logo!
```

---

## 🧱 Estrutura do projeto

```
📦 projeto
 ┗ 📄 Main.java
```

---

## 🧠 Conceitos praticados

| Conceito | Uso no projeto |
|---|---|
| `Scanner` | Leitura de dados do teclado |
| `do-while` | Loop do menu até o usuário sair |
| `switch-case` | Tratamento de cada opção do menu |
| `if-else` | Validação de saldo na transferência |
| `double` | Armazenamento de valores monetários |

---

## 👩‍💻 Autora
Feito por **Clara Kethurin** 🚀
