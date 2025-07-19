# RNF07 – Privacidade e Consentimento

## Descrição  
A aplicação deve garantir que todo compartilhamento de informações com terceiros, como psicólogos, seja feito apenas com consentimento informado do usuário, podendo ser revogado a qualquer momento, conforme os princípios da LGPD (Lei Geral de Proteção de Dados).

## Justificativa  
Respeitar a privacidade e o consentimento do usuário é um requisito legal e ético fundamental, garantindo transparência e controle sobre os dados pessoais.

A possibilidade de revogação do consentimento assegura a conformidade com a LGPD e fortalece a confiança do usuário na aplicação.

## Critérios de Aceitação  
- **CA01:** O sistema deve registrar o consentimento informado antes de compartilhar dados.  
- **CA02:** O usuário deve poder revogar o consentimento a qualquer momento.  
- **CA03:** Compartilhamento sem consentimento não deve ocorrer sob nenhuma circunstância.

## Observações Técnicas  
- Implementar logs detalhados de consentimento e compartilhamento.  
- Desenvolver interfaces claras para gestão de consentimento pelo usuário.  
- Garantir criptografia e proteção dos dados compartilhados.
