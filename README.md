🏦 Sistema Bancário em Python (POO)

Este projeto implementa um sistema bancário simples utilizando Programação Orientada a Objetos (POO) em Python.
O sistema permite criar contas, cadastrar no banco, consultar saldo, realizar depósitos, saques e transferências.

📌 Classes do Sistema
🔹 Classe conta

Representa uma conta bancária individual.

Atributos:

numero — número da conta

saldo — saldo atual da conta

Métodos:

get_numero() — retorna o número da conta

get_saldo() — retorna o saldo da conta

debitar(valor) — tenta retirar um valor da conta

creditar(valor) — adiciona um valor à conta

🔹 Classe Banco

Responsável por gerenciar várias contas.

Atributos:

contas — lista fixa com até 100 contas

indice — indica quantas contas já foram cadastradas

Métodos:

cadastrar(conta) — adiciona uma nova conta ao banco

procurar_conta(numero) — retorna a conta com o número informado

debitar(numero, valor) — debita o valor de uma conta

creditar(numero, valor) — credita o valor em uma conta

saldo(numero) — retorna o saldo da conta

transferir(origem, destino, valor) — transfere valor entre contas

📂 Exemplo de Uso (já incluído no código)

O programa cria e cadastra três contas:

conta1 = conta(1001, 1000.00)
conta2 = conta(1002, 500.00)
conta3 = conta(1003, 200.00)


Em seguida:

Consulta saldos

Realiza depósito

Realiza saque

Realiza transferência

Exibe saldos finais

Tudo isso é mostrado automaticamente no terminal ao executar o arquivo.

▶️ Como Executar

Instale o Python (se ainda não tiver).

Execute o arquivo:

python atv1.py


A saída mostrará:

Contas cadastradas

Saldos iniciais

Operações realizadas

Saldos finais
