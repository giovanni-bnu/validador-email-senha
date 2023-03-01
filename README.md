### Validador de Email e Senha

Construa uma página HTML contendo um formulário de registro com os campos nome, email e senha onde, ao submeter o formulário, deverá ser feita uma validação para verificar se o email é um email válido e se a senha atende as regras mínimas de seguraça.

Para que um email seja válido ele deve possuir:

- Um caractere @
- Texto antes do @ com pelo menos 2 caracteres, números ou \_ (underscore).
- Texto após o @ com pelo menos 2 caracteres
- Um . seguido de mais texto com pelo menos 2 caracteres após o texto após o @
- Estrutura de um email válido: **xx@xx.xx**

Para que uma senha seja válida ela deve possuir:

- Pelo menos uma letra minúscula.
- Pelo menos uma letra maiúscula.
- Pelo menos um número
- Pelo menos um caractere especial.
- Pelo menos 8 caracteres.

As validação devem ser escritas em funções separadas que lançam um novo erro em caso de falha com uma mensagem apropriada. Esse erro deverá ser tratado através de um bloco trycatch, evitando que um erro seja emitido no console do navegador e mostrando para o usuário o erro ocorrido.
