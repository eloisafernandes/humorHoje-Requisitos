# RF06 – Visualizar Registro Individual

## Descrição  
O usuário deve poder visualizar um registro feito, com todos os detalhes inseridos (texto, áudio, emojis, etc.). O registro será acessado pela seção descrita no RF03.

## Origem  
Analogia e ambos os questionários com usuários e psicólogos.

## Prioridade  
Alta

## Status  
Em progresso

## Justificativa  
Permitir a visualização detalhada de um registro individual é fundamental para que o usuário possa revisar suas informações emocionais e complementares com clareza e precisão.  
Esse acesso detalhado facilita a reflexão sobre cada momento registrado, possibilitando maior compreensão dos estados emocionais e padrões comportamentais.

Além disso, essa funcionalidade apoia a consulta com profissionais de saúde mental, que poderão analisar os dados completos em contextos terapêuticos, melhorando a qualidade do acompanhamento e tratamento.

## Critérios de Aceitação – RF06: Visualizar Registro Individual

- **CA01:** O sistema deve permitir que o usuário acesse qualquer registro individual por meio da seção de histórico (conforme RF05).

- **CA02:** Ao selecionar um registro, o sistema deve exibir uma tela ou modal com todos os detalhes associados, incluindo:  
  - Data e hora do registro;  
  - Humor selecionado (nome e/ou emoji);  
  - Texto livre (se houver);  
  - Áudio gravado (se houver), com opção de reprodução;  
  - Sentimentos selecionados ou adicionados;  
  - Informações complementares (sono, estresse, sintomas físicos, etc.).

- **CA03:** O sistema deve apresentar as informações de forma organizada, agrupando-as por categoria (ex: “Humor”, “Sintomas físicos”, “Atividade física”, etc.).

- **CA04:** O usuário deve conseguir ouvir novamente a gravação de voz diretamente da interface do registro.

- **CA05:** O sistema deve garantir que apenas o próprio usuário possa acessar seus registros individuais, respeitando as regras de privacidade.

- **CA06:** Caso alguma informação não tenha sido registrada (ex: o usuário não inseriu sintomas), o campo correspondente deve ser omitido ou apresentar uma indicação clara (ex: “Não informado”).

- **CA07:** A tela deve conter uma opção para retornar à listagem de registros ou ao calendário, mantendo a navegação fluida.

- **CA08:** O sistema deve exibir corretamente registros antigos, mesmo que não contenham todos os campos disponíveis nas versões mais recentes do app.

- **CA09:** O tempo de carregamento das informações deve ser rápido, mesmo em conexões lentas, garantindo uma boa experiência de uso.
