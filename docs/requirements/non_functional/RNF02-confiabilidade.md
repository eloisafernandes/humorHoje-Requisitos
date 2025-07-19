# RNF02 – Confiabilidade

## Descrição  
O aplicativo deve permitir o registro de humor em modo offline. Deve ser implementado backup diário dos dados dos usuários para recuperação em caso de falha.

## Justificativa  
Garantir a possibilidade de registro offline assegura que o usuário possa registrar seu humor mesmo sem conexão com a internet, aumentando a confiabilidade e usabilidade do sistema.

A implementação de backups diários protege os dados dos usuários contra perdas, assegurando a integridade e a recuperação das informações em caso de falhas técnicas.

## Critérios de Aceitação  
- **CA01:** O sistema deve permitir o registro de humor completo em modo offline, sincronizando os dados automaticamente quando a conexão for restabelecida.  
- **CA02:** Deve existir um processo automatizado de backup diário dos dados dos usuários.  
- **CA03:** O sistema deve garantir a restauração dos dados a partir dos backups em caso de falha.

## Observações Técnicas  
- Recomenda-se o uso de armazenamento local (ex.: SQLite, IndexedDB) para registros offline.  
- O processo de sincronização deve tratar conflitos de dados de forma segura e transparente.  
- O backup deve ser armazenado em local seguro, com criptografia e acesso controlado.
