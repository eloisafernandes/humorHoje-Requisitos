# RNF04 – Segurança

## Descrição  
O sistema deve garantir que todas as informações do usuário, incluindo anotações, histórico de humor e dados de perfil, sejam armazenadas de forma criptografada no dispositivo local.  

Toda a comunicação entre dispositivos (ex: entre psicólogo e paciente) deve ser realizada por meio de protocolos seguros como TLS 1.2 ou superior.

## Justificativa  
A proteção dos dados pessoais e sensíveis dos usuários é fundamental para assegurar a privacidade, evitar vazamentos e cumprir com legislações aplicáveis.

O uso de criptografia local e comunicação segura fortalece a confiança dos usuários no sistema e previne acessos não autorizados.

## Critérios de Aceitação  
- **CA01:** Dados armazenados localmente devem estar criptografados com algoritmos reconhecidos e seguros.  
- **CA02:** Toda comunicação entre dispositivos deve utilizar protocolos seguros (TLS 1.2 ou superior).  
- **CA03:** O sistema deve rejeitar conexões inseguras e notificar falhas de segurança.

## Observações Técnicas  
- Recomenda-se o uso de criptografia AES-256 para armazenamento local.  
- Para comunicação, utilizar TLS 1.2+ com certificados válidos e práticas seguras de handshake.  
- Implementar mecanismos para monitorar e registrar tentativas de acesso não autorizado.

👉 [Ver RNF04 – Segurança no Grafo NFR](https://drive.google.com/file/d/116588AFrYBHpNhVAQ5aezO3UyFu2rY_2/view?usp=sharing)