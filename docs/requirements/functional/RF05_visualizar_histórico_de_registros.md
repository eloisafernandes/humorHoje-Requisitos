# RF05 – Visualizar Histórico Emocional

## Descrição  
O usuário deve poder visualizar o histórico completo de seus registros emocionais, através de uma lista ou calendário. O histórico será apresentado dentro do sistema em uma seção exclusiva, e poderá ser consultado a qualquer momento. Por padrão, o histórico exibe somente os registros do mês atual, mas o mês a ser visualizado pode ser alterado e selecionado através de um calendário. Os registros serão exibidos em uma listagem vertical, contendo a data, o humor, o registro feito pelo usuário (texto livre ou anotação de voz) e quaisquer informações complementares.

## Origem  
Questionário com usuários.

## Prioridade  
Alta

## Status  
Em progresso

## Justificativa  
A funcionalidade de visualização do histórico emocional permite ao usuário refletir sobre sua jornada emocional ao longo do tempo. Ter acesso fácil e organizado aos registros passados contribui para a autoconsciência, o reconhecimento de padrões e o acompanhamento da evolução do bem-estar.

Ao oferecer diferentes formas de visualização (lista e calendário), o sistema atende às preferências individuais e facilita a navegação. A filtragem por mês torna a interface mais leve e o acesso às informações mais objetivo, sem sobrecarregar o usuário. Essa funcionalidade também pode auxiliar em futuras consultas com profissionais da saúde mental, tornando-se um recurso valioso e recorrente no uso do aplicativo.

## Critérios de Aceitação

- **CA01:** O sistema deve disponibilizar uma seção exclusiva para o histórico emocional do usuário, acessível a qualquer momento.

- **CA02:** O histórico deve ser apresentado em formato de:  
  - Lista vertical (com registros organizados por data);  
  - E/ou visualização em calendário, com a opção de alternar entre os formatos.

- **CA03:** Por padrão, o sistema deve exibir apenas os registros do mês atual.

- **CA04:** O usuário deve poder alterar o mês visualizado por meio de um seletor de data (calendário interativo ou dropdown).

- **CA05:** Cada item da lista de registros deve conter, no mínimo:  
  - A data do registro;  
  - O humor selecionado;  
  - O conteúdo registrado (texto e/ou áudio);  
  - As informações complementares inseridas (se houver).

- **CA06:** Ao clicar em um item da lista ou calendário, o usuário deve conseguir visualizar os detalhes completos do registro.

- **CA07:** A interface deve permitir a navegação entre meses anteriores sem limites de retrocesso (até o primeiro registro feito pelo usuário).

- **CA08:** Os dados exibidos devem estar organizados cronologicamente, do mais recente para o mais antigo.

- **CA09:** Os áudios registrados devem estar acessíveis com botão de reprodução diretamente na interface do histórico.


 **Acesse o Caso de Uso 01 - Jornada Emocional:**  
[📄 Visualizar imagem](https://drive.google.com/file/d/1uHwN2ZoX-hZo0s-Nux4ztnLxPx7Dcon6/view?usp=sharing)