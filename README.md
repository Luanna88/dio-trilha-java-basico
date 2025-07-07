# 💻 Desafio: Sintaxe - ContaBanco

Neste desafio, vamos praticar os conceitos fundamentais de **sintaxe Java** aprendidos até aqui, implementando um pequeno sistema bancário interativo no terminal.

## 🧾 Descrição do Desafio

Você deve criar um projeto Java chamado **ContaBanco**, que será executado via terminal e receberá os dados de uma conta bancária utilizando a classe `Scanner`. Em seguida, o programa exibirá uma mensagem formatada com os dados informados.

---

## 📁 Estrutura do Projeto

Dentro do projeto, crie a classe principal chamada:


Todo o código será implementado nesta classe.

---

## 🧠 Conceitos a Revisar

Antes de iniciar o desenvolvimento, é importante revisar os seguintes conteúdos:

- Regras de declaração de variáveis
- Utilização do método `main(String[] args)`
- Leitura de dados com a classe `Scanner`
- Concatenação de strings usando `+` ou o método `concat()`

---

## 📌 Atributos da Conta

A tabela a seguir apresenta os atributos que o sistema irá solicitar, seus tipos e exemplos de valores:

| Atributo        | Tipo     | Exemplo         |
|------------------|----------|-----------------|
| Número           | Inteiro  | 1021            |
| Agência          | Texto    | 067-8           |
| Nome do Cliente  | Texto    | MARIO ANDRADE   |
| Saldo            | Decimal  | 237.48          |

---

## 🧑‍💻 Interação com o Usuário

Durante a execução, o programa deverá solicitar ao usuário os seguintes dados:

```text
Por favor, digite o número da Conta:
Por favor, digite o número da Agência:
Por favor, digite o nome do Cliente:
Por favor, digite o saldo inicial:

Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, 
sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque.

Por favor, digite o número da Conta:
1021
Por favor, digite o número da Agência:
067-8
Por favor, digite o nome do Cliente:
MARIO ANDRADE
Por favor, digite o saldo inicial:
237.48

Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco, 
sua agência é 067-8, conta 1021 e seu saldo 237.48 já está disponível para saque.
