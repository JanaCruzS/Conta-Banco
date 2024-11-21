aula 05 - Java- Programação Orientada Objetos - Prof Gustavo Guanabara. 


# ContaBanco - Sistema de Conta Bancária

Este projeto implementa uma classe `ContaBanco` que simula operações bancárias básicas, como abrir e fechar contas, depositar e sacar dinheiro, além de pagar mensalidades e exibir o estado atual da conta.

## Funcionalidades

- **Abrir Conta**: Permite abrir uma conta bancária, definindo o tipo (Corrente ou Poupança) e um saldo inicial.
- **Fechar Conta**: Fecha a conta, verificando se há saldo devedor ou positivo.
- **Depositar**: Realiza um depósito em uma conta aberta.
- **Sacar**: Permite realizar um saque, desde que o saldo seja suficiente e a conta esteja aberta.
- **Pagar Mensalidade**: Paga uma mensalidade de acordo com o tipo da conta.
- **Estado Atual**: Exibe o status completo da conta, incluindo número, tipo, dono, saldo e status da conta.

## Estrutura da Classe

- **Atributos**:
  - `numConta`: Número da conta bancária.
  - `tipo`: Tipo da conta (CC - Conta Corrente, CP - Conta Poupança).
  - `dono`: Nome do dono da conta.
  - `saldo`: Saldo disponível na conta.
  - `status`: Status da conta (aberta ou fechada).

- **Métodos**:
  - `abrirConta(String tipo)`: Abre uma nova conta com um tipo e saldo inicial.
  - `fecharConta()`: Fecha a conta, verificando se há saldo ou débito.
  - `depositar(float valor)`: Realiza um depósito na conta aberta.
  - `sacar(float valor)`: Realiza um saque, verificando se há saldo suficiente.
  - `pagarMensal()`: Deduz o valor da mensalidade da conta, de acordo com o tipo.
  - `estadoAtual()`: Exibe as informações da conta.

