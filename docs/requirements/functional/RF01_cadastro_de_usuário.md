# RF01 – Cadastro de Usuário

## Descrição  
O usuário deve poder criar e gerenciar uma conta pessoal (informando e-mail e senha) para utilizar o aplicativo.

## Origem  
Funcionalidade padrão para sistemas com dados personalizados.

## Prioridade  
Alta

## Status  
Elaborado

## Justificativa  
O cadastro de usuário é essencial para garantir uma experiência personalizada e segura dentro do aplicativo.  
Por meio da criação de contas individuais, é possível associar dados, preferências e histórico de uso a cada usuário, viabilizando funcionalidades como login seguro, recuperação de dados, controle de acesso e recomendações personalizadas.

Além disso, o uso de e-mail e senha como credenciais permite a autenticação e a proteção das informações pessoais, assegurando conformidade com práticas de segurança e privacidade de dados.

Trata-se, portanto, de uma funcionalidade fundamental para o funcionamento adequado.

## Critérios de Aceitação

- **CA01:** O sistema deve permitir a criação de uma conta com e-mail válido e senha.  
  - O e-mail deve seguir um formato válido (ex: usuario@dominio.com).  
  - A senha deve atender aos requisitos mínimos definidos (ex: no mínimo 6 caracteres).

- **CA02:** O sistema deve validar se o e-mail informado já está cadastrado.  
  - Caso esteja, deve exibir uma mensagem de erro clara: "E-mail já cadastrado."

- **CA03:** O sistema deve exibir mensagens de erro em caso de:  
  - Dados inválidos;  
  - Campos obrigatórios não preenchidos.

- **CA04:** Ao concluir o cadastro com sucesso:  
  - O usuário deve ser redirecionado para a tela inicial do aplicativo;  
  - Ou receber uma mensagem de confirmação: "Cadastro realizado com sucesso."

- **CA05:** Os dados do usuário devem ser armazenados de forma segura, seguindo boas práticas de proteção de dados.

- **CA06:** Deve haver um mecanismo de recuperação de senha associado ao e-mail cadastrado.

- **CA07:** O sistema deve impedir cadastros duplicados com o mesmo e-mail.