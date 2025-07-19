# RNF02 – Desempenho

## Descrição  
A geração de gráficos mensais não deve levar mais de 3 segundos e a abertura da tela de histórico não deve levar mais de 2 segundos, mesmo com 3 anos de registros diários de um usuário.

## Justificativa  
Este requisito assegura que o sistema mantenha uma performance adequada e uma experiência de usuário fluida, mesmo com grande volume de dados acumulados.

A rápida resposta do sistema é fundamental para a satisfação do usuário e a eficácia na análise de seu histórico emocional.

## Critérios de Aceitação  
- **CA01:** A geração dos gráficos mensais deve ocorrer em até 3 segundos, independentemente do volume de dados.  
- **CA02:** A abertura da tela de histórico deve ocorrer em até 2 segundos, mesmo com 3 anos de registros diários.  
- **CA03:** O sistema deve monitorar e reportar eventuais degradações de performance que ultrapassem os tempos estabelecidos.

## Observações Técnicas  
- Recomenda-se a implementação de mecanismos de cache para dados agregados.  
- O uso de técnicas de otimização de consultas e indexação no banco de dados é obrigatório.  
- A arquitetura deve suportar processamento assíncrono para geração de gráficos, minimizando impactos na interface do usuário.
