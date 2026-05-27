# CT002 - Cadastro com e-mail já existente

**Objetivo:** Validar se o sistema impede o registro de um usuário com e-mail já cadastrado.
**Pré-condição:** Estar na página de cadastro. (https://www.automationpratice.com.br/register)

### Passos:
1. Inserir nome completo.
 "Vinicius Rodrigues"

2. Inserir um e-mail que já possui cadastro no sistema.
 "vinicius.rodrigues@example.com"

3. Inserir uma senha válida.
"12345678"
4. Clicar no botão "Cadastrar".

### Resultado Esperado:
- O sistema não deve permitir a criação da conta.
- O sistema deve exibir uma mensagem de erro ou alerta informando que o e-mail já está em uso.

---
**Status:** [ ] Pendente | [] Aprovado | [✓] Reprovado

**Evidência:** Mesmo com dados válidos, o sistema permitiu o cadastro com um e-mail já existente, isso indica uma falha na validação de unicidade do e-mail. (Bug identificado e precisa ser corrigido para evitar registros duplicados).