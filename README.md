# Desafio de Controle de Fluxo - Java

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

## 📝 Descrição

Este repositório contém a resolução do **Desafio de Controle de Fluxo**, proposto durante a trilha de **Java Básico**.

O objetivo do projeto é exercitar o pensamento computacional e os conceitos fundamentais da linguagem Java, implementando um sistema que recebe dois parâmetros via terminal e realiza uma contagem baseada na interação entre esses números.

O projeto foca nos seguintes conceitos:
- Manipulação de entrada de dados (`Scanner`).
- Estruturas condicionais e loops (`if`, `for`).
- Tratamento de exceções customizadas (`try-catch`).

## 📂 Estrutura do Projeto

O projeto é composto por duas classes principais:

1.  **`Contador.java`**:
    - Classe principal responsável por interagir com o usuário via terminal.
    - Recebe dois números inteiros.
    - Chama o método `contar` para processar a lógica.
    - Trata a exceção caso a lógica de entrada seja inválida.

2.  **`ParametrosInvalidosException.java`**:
    - Uma classe de exceção personalizada (estende `Exception`).
    - Garante que o programa sinalize erros de lógica de negócio de forma clara.

## 🚀 Como Executar

Siga os passos abaixo para rodar o projeto na sua máquina local.

### Pré-requisitos
- **Java JDK** instalado (versão 8 ou superior).
- Um terminal (CMD, PowerShell, Bash, etc) ou uma IDE (IntelliJ, Eclipse, VS Code).

### Passo a Passo

1. **Clone o repositório**:
   ```bash
   git clone [https://github.com/LarissaBSouza/desafio-controle-fluxo.git](https://github.com/LarissaBSouza/desafio-controle-fluxo.git)

2. **Navegue até a pasta do projeto:**:
   ```bash
   cd desafio-controle-fluxo

3. **Compile os arquivos Java: No terminal, execute o comando abaixo para gerar os arquivos `.class`:**
   ```bash
   javac Contador.java ParametrosInvalidosException.java

4. **Execute o programa: Após compilar, execute a classe principal:**
   ```bash
   java Contador

5. **Interaja com o programa: O terminal solicitará dois parâmetros. Digite os números conforme solicitado.**

### Exemplo de Uso
**Ao executar o programa, o fluxo esperado segue o padrão:**

```bash
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
Imprimindo o número 1
Imprimindo o número 2
...
``` 

**Caso a regra de negócio seja violada (exceção disparada), a saída será uma mensagem de erro explicativa definida na exceção customizada.**

### Autor
Desenvolvido por LarissaBSouza durante a trilha de Java Básico.
