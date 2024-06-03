Claro! Aqui está uma descrição formatada em Markdown (.md) para seu update no GitHub:

---

# 🚀 Update: Melhoria no Sistema Bancário

## 📋 Principais Alterações:
### 🆕 Cadastro de Usuários:
- Implementação do **cadastro automático de conta corrente** para novos usuários, começando pelo número `000001` e incrementando para cada novo cadastro.
- A agência é fixa com o número `0001`.

### 💰 Depósitos e Saques:
- **Função `depositar`** para adicionar valores ao saldo.
- **Função `sacar`** com limites diários de quantidade (3 saques) e valor de saque (até R$ 500,00 por saque).

### 📄 Extrato Bancário:
- **Função `extrato`** que exibe o saldo atual e todas as movimentações, além da quantidade e valor total dos saques diários.

### 👥 Listagem de Usuários:
- **Função para listar todos os usuários cadastrados**, exibindo nome, CPF, número da conta corrente e agência.
- Mensagem adequada para quando a lista de usuários está vazia.

### 🛠️ Correções e Melhorias Gerais:
- Melhoria no tratamento de verificações de usuários.
- Formatação e organização das saídas de dados para maior clareza.

## 📖 Instruções de Uso:
### Menu Principal:
- **Opção 1**: Depositar
- **Opção 2**: Sacar
- **Opção 3**: Exibir Extrato
- **Opção 4**: Cadastrar Usuário
- **Opção 5**: Listar Usuários
- **Opção 6**: Sair

### Cadastro de Usuário:
- Solicita **CPF**, **nome**, **data de nascimento** e **endereço** (rua, número, bairro, cidade).
- O **número da conta corrente** é gerado automaticamente.

## 📋 Exemplo de Uso:

```python
## SISTEMA BANCÁRIO ##

Escolha o que deseja fazer:
1. Depositar
2. Sacar
3. Extrato
4. Cadastrar Usuário
5. Listar Usuários
6. Sair
```

### Exemplos de Mensagens:
- **Cadastro de Usuário**:
  ```plaintext
  Informe o CPF do usuário para cadastro: 12345678901
  Informe o nome do usuário para o cadastro: João Silva
  Data de nascimento: 01/01/1980
  Digite seu endereço:
  Rua: Rua Exemplo
  Número: 123
  Bairro: Centro
  Cidade: São Paulo

  Usuário cadastrado com sucesso!
  Conta corrente: 000001 Agência: 0001
  ```

- **Listagem de Usuários**:
  ```plaintext
  Nome: João Silva, CPF: 12345678901, Conta Corrente: 000001, Agência: 0001
  ```
