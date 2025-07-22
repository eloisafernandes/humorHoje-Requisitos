# RF03 – Adicionar Sentimento/Humor

## Descrição  
O sistema DEVE permitir que o usuário adicione livremente sentimentos. Um sentimento deve ter, no mínimo, um nome ou um emoji associado a ele, e pode ter ambos ao mesmo tempo. Não há restrições quanto à unicidade de nomes ou emojis, sendo possível a repetição de ambos sem limitações.

## Origem  
Analogia (aplicativos semelhantes, como o Daylio).

## Prioridade  
Alta

## Status  
Elaborado

## Justificativa  
Permitir que o usuário adicione seus próprios sentimentos ou humores torna o aplicativo mais flexível e pessoal. Essa funcionalidade respeita a diversidade de experiências emocionais e amplia as possibilidades de expressão além das opções predefinidas.

Ao não impor restrições à unicidade de nomes ou emojis, o sistema prioriza a liberdade de registro, evitando frustrações ou limitações artificiais na experiência do usuário.  
Esse nível de personalização favorece o engajamento contínuo e contribui para que o usuário se sinta acolhido e representado ao longo do uso do aplicativo.

## Critérios de Aceitação

- **CA01:** O sistema deve permitir que o usuário adicione manualmente um novo sentimento ou humor.

- **CA02:** Cada novo sentimento deve conter:  
  - Um nome (ex: “ansioso”);  
  - Um emoji (ex: 😴).

- **CA03:** O sistema deve impor as seguintes regras de unicidade:  
  - **Não é permitido** adicionar sentimentos com nomes iguais a outros já existentes para o mesmo usuário;  
  - **É permitido** repetir emojis já utilizados.

- **CA04:** O sistema deve armazenar corretamente os sentimentos adicionados e disponibilizá-los para seleção em registros futuros.

- **CA05:** O sistema deve validar que os campos foram preenchidos antes de permitir o salvamento.

- **CA06:** O sistema deve exibir uma mensagem de confirmação após a adição bem-sucedida do novo sentimento (ex: “Sentimento adicionado com sucesso”).

- **CA07:** Os sentimentos adicionados devem ser exclusivos do usuário que os criou, não interferindo na experiência de outros usuários.


 **Acesse o Caso de Uso 03 - Adicionar Sentimento Humor:**  
[📄 Visualizar imagem](https://drive.google.com/drive/folders/1EX_Y-lNCC3ZgQuc3HMN-vqBjEOEOc6jk)
