# RF04 – Registrar Informações Complementares

## Descrição  
O sistema DEVE permitir o registro de informações complementares ao humor, a cada interação de inserção de humor, incluindo:

- Qualidade do sono (escala de 1 a 5);  
- Nível de estresse e ansiedade (escala de 1 a 5);  
- Sintomas físicos (entrada digitada ou seleção de sintomas predefinidos: dor de cabeça, dor no pescoço, dor nas costas, tontura e náusea);  
- Atividade física (tipo e duração em minutos);  
- Alimentação (registro digitado ou categorias predefinidas);  
- Interações sociais (entrada digitada ou seleção entre “nenhuma”, “poucas”, “moderadas” e “muitas”).

Essas informações devem ser acompanhadas de descrições curtas ou exemplos que orientem o usuário a identificar e preencher os dados. Por exemplo, o sistema pode exibir um pequeno texto como: “O que impactou o seu dia hoje?”, seguido de um menu com as opções acima, que podem ser registradas ou não, de forma opcional.

## Origem  
Coletada inicialmente com Analogia (aplicativos semelhantes); validada por Questionário com ambos usuários e profissionais.

## Prioridade  
Alta

## Status  
Em progresso

## Justificativa  
O registro de informações complementares ao humor permite uma compreensão mais ampla e contextualizada do estado emocional do usuário. Fatores como sono, estresse, sintomas físicos e interações sociais influenciam diretamente o bem-estar e, ao serem registrados, possibilitam análises mais precisas e reflexões mais profundas sobre os padrões emocionais ao longo do tempo.

Além disso, essas informações podem auxiliar tanto o próprio usuário quanto profissionais de saúde mental na identificação de gatilhos, rotinas e comportamentos associados às variações de humor. O uso de exemplos e orientações breves durante o preenchimento torna a experiência mais acessível e acolhedora, incentivando o engajamento sem sobrecarregar o usuário.

## Critérios de Aceitação

- **CA01:** O sistema deve permitir que, a cada registro de humor, o usuário possa inserir informações complementares de forma opcional.

- **CA02:** O sistema deve oferecer os seguintes campos complementares:  
  - Qualidade do sono (escala de 1 a 5);  
  - Nível de estresse e ansiedade (escala de 1 a 5);  
  - Sintomas físicos (entrada digitada **ou** seleção múltipla entre: dor de cabeça, dor no pescoço, dor nas costas, tontura e náusea);  
  - Atividade física (tipo e duração em minutos);  
  - Alimentação (registro livre **ou** categorias predefinidas);  
  - Interações sociais (entrada digitada **ou** escolha entre “nenhuma”, “poucas”, “moderadas” e “muitas”).

- **CA03:** O sistema deve permitir que o usuário preencha todos, alguns ou nenhum dos campos complementares, sem impedir o envio do registro principal de humor.

- **CA04:** Os dados complementares devem ser armazenados corretamente e associados ao mesmo registro de humor com data e hora.

- **CA05:** O sistema deve exibir uma confirmação visual ou textual após o registro bem-sucedido, incluindo as informações complementares inseridas.

- **CA06:** O usuário deve poder visualizar posteriormente essas informações no histórico de humor.

- **CA07:** O sistema deve garantir que os dados inseridos fiquem visíveis apenas para o próprio usuário ou profissionais autorizados (em conformidade com as regras de privacidade).
