# Teste_Python
Teste para processo seletivo, realizado em Python, utilizando o Jupyter. Solicitado a criação de um cadastro de clientes, permitindo a exclusão e exportando os dados em PDF.

#Requisitos:

1. Cadastro de Clientes:
  - Campos necessários: nome, CPF, e-mail, endereço e telefone.
  - Validações:
    - CPF: Deve ser validado para garantir que é um CPF válido
    - E-mail: Deve ser validado com uma expressão regular.

2. Emissão de um documento pdf:
  - Após o cadastro, um documento pdf deve ser gerado em formato PDF com os dados do cliente (nome, CPF, data de emissão).
  - O arquivo PDF será salvo localmente.

3. Exclusão de cliente:
  - Deve ser possível excluir um cliente da lista.
  - Ao excluir, gerar um novo documento em pdf, contendo o nome do cliente, CPF, data do cancelamento, e o motivo da exclusão.
