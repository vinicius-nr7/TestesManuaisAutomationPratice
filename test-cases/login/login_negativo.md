# CT004 - Login com credenciais inválidas

**Objetivo:** Validar o comportamento do sistema com credenciais incorretas.
**Pré-condição:** Estar na página de login.(https://www.automationpratice.com.br/login)

### Passos:
1. Inserir um e-mail ou senha incorretos.
   - E-mail: "vinicius.rodrigues@example.com"
   - Senha: "87654321"
2. Clicar no botão "Login".

### Resultado Esperado:
- O sistema deve exibir a mensagem de erro: "E-mail ou senha inválidos".

**Evidência:** Mesmo com dados inválidos, o sistema não impediu o login, indicando uma falha na validação das credenciais. (Bug identificado e precisa ser corrigido para garantir a segurança do acesso).

---
**Status:** [ ] Pendente | [ ] Aprovado | [ ✓ ] Reprovado