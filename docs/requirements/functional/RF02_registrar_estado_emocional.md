# RF02 – Registrar Estado Emocional

## Descrição  
O sistema DEVE permitir que o usuário registre o seu humor, oferecendo os seguintes métodos, que poderão ser combinados entre si livremente: inserir uma anotação textual (texto livre), gravar uma anotação de voz usando o microfone, selecionar sentimentos específicos de uma lista predefinida (ótimo, bem, mais ou menos, mal, bem mal) e utilizar emojis.

## Origem  
Coletada inicialmente com Analogia (aplicativos semelhantes, como o Daylio); validada por Questionário com ambos usuários e profissionais.

## Prioridade  
Alta

## Status  
Elaborado

## Justificativa  
Registrar o estado emocional é uma funcionalidade central para o propósito do aplicativo, pois permite ao usuário acompanhar sua saúde mental e emocional ao longo do tempo.  
A diversidade de métodos de registro (texto, voz, lista de sentimentos e emojis) respeita diferentes estilos de expressão, tornando a experiência mais inclusiva e personalizada.

Além disso, o registro contínuo do humor fornece dados valiosos tanto para o próprio usuário quanto para profissionais de saúde que possam acompanhar sua evolução.  
Essa funcionalidade contribui diretamente para o engajamento do usuário com o aplicativo e para a construção de um histórico emocional útil e significativo.

## Critérios de Aceitação

- **CA01:** O sistema deve permitir que o usuário registre seu humor a qualquer momento do dia.

- **CA02:** O registro pode ser feito por qualquer uma das seguintes formas, combinadas ou individualmente:  
  - Anotação textual (campo de texto livre);  
  - Gravação de voz, utilizando o microfone do dispositivo;  
  - Seleção de sentimentos a partir de uma lista predefinida (ótimo, bem, mais ou menos, mal, bem mal);  
  - Escolha de emojis representando o estado emocional.

- **CA03:** O sistema deve salvar corretamente os dados registrados e associá-los à data e hora do registro.

- **CA04:** O sistema deve exibir uma confirmação visual ou textual após o registro bem-sucedido (ex: "Humor registrado com sucesso").

- **CA05:** Os dados registrados devem estar disponíveis para visualização posterior no histórico emocional do usuário.

- **CA06:** O componente de gravação deve solicitar permissão de uso do microfone, conforme exigido pelo sistema operacional.

