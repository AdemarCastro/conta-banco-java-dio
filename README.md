# ContaBanco - Desafio

## Descrição do Projeto
Este é um projeto para criar um programa Java chamado ContaBanco que recebe dados via terminal para registrar as características de uma conta bancária. O programa utiliza a classe ContaTerminal.java para a codificação.

**Importante**
Este projeto será atualizado com uma versão MVC, a ideia é criar um sistema bancário com Agência > Conta > Cliente. O projeto contará com uma classe de validação dos valores de entrada e também com a seção de testes desenvolvida para validar o sistema.

## Características da Conta
O programa irá solicitar ao usuário as seguintes informações sobre a conta bancária:

- **Número**: Número da conta (inteiro).
- **Agência**: Número da agência (texto no formato XXXX-X).
- **Nome do Cliente**: Nome do titular da conta (texto).
- **Saldo**: Saldo da conta (valor decimal).

## Requisitos
Antes de prosseguir com o desafio, é importante revisar os seguintes conceitos:

1. Regras de declaração de variáveis em Java.
2. Utilização de terminal, argumentos da função main e a classe Scanner para leitura de entrada.
3. Concatenação de strings usando a classe String e o método `concat`.

## Instruções
1. Abra o projeto ContaBanco em um ambiente de desenvolvimento Java.
2. Crie a classe ContaTerminal.java para realizar a codificação do programa.
3. Utilize a classe Scanner para receber os dados do usuário via terminal.
4. Solicite que o usuário digite as informações da conta, seguindo a sequência informada no exemplo:
   ```
   Programa: "Por favor, digite o número da Agência !"
   Usuário: 1021 (pressione ENTER para o próximo campo)
   ```
5. Depois que todas as informações forem inseridas, o sistema deverá exibir a seguinte mensagem:
   ```
   "Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque".
   ```
   Os campos entre colchetes `[ ]` devem ser substituídos pelas informações fornecidas pelo usuário.

## Exemplo de Uso
```
Por favor, digite o número da Agência: 1021
Por favor, digite o número da Conta: 12345
Por favor, digite o nome do Cliente: Mario Andrade
Por favor, digite o saldo da Conta: 237.48

Olá Mario Andrade, obrigado por criar uma conta em nosso banco, sua agência é 1021, conta 12345 e seu saldo 237.48 já está disponível para saque.
```

## Dicas
- Certifique-se de utilizar as estruturas corretas de controle de fluxo para receber e exibir os dados do usuário de forma adequada.
- Faça a validação dos dados inseridos pelo usuário, garantindo que estejam no formato correto.
- Utilize a classe String para a concatenação da mensagem final.

## Boa sorte!
Divirta-se codificando e resolvendo o desafio! Se precisar de alguma ajuda, não hesite em procurar suporte adicional. Happy coding!