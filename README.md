"# Projeto de Testes Manuais – Automation Practice

Este projeto foi desenvolvido para demonstrar minha capacidade de realizar testes manuais de ponta a ponta em uma aplicação web de e-commerce, identificar falhas de usabilidade e validação, e registrar evidências com clareza e profissionalismo.

## Objetivo do projeto

O principal objetivo foi validar o fluxo real de uso do site Automation Practice, simulando a jornada de um cliente desde o cadastro até a finalização da compra, além de analisar o comportamento do sistema em cenários de sucesso e falha.

Este trabalho é uma boa representação de como um profissional de QA pensa: observando regras de negócio, testando cenários críticos, validando comportamento esperado e registrando problemas de forma objetiva.

---

## O que foi testado

Os cenários foram organizados em arquivos dentro da pasta test-cases e cobrem os principais pontos do fluxo da aplicação:

1. Cadastro de usuário
2. Login na plataforma
3. Adição de produtos ao carrinho
4. Finalização da compra
5. Uso da wishlist

---

## Fluxo principal validado

### 1. Cadastro
- Teste de cadastro com sucesso
- Teste de cadastro com e-mail já existente

### 2. Login
- Teste de login com credenciais válidas
- Teste de login com credenciais inválidas

### 3. Carrinho e compra
- Adição de produto ao carrinho
- Finalização da compra com preenchimento de dados de entrega e pagamento

### 4. Wishlist
- Adição de produto à lista de desejos

---

## Onde deu o bug

Durante a execução dos testes manuais, foram identificadas duas falhas importantes:

### Bug 1 – Cadastro com e-mail já existente
Local: test-cases/cadastro/cadastro_negativo.md

Problema encontrado:
- O sistema permitiu o cadastro mesmo com um e-mail que já estava registrado.

Impacto:
- Isso pode gerar cadastros duplicados, comprometer a integridade dos dados e prejudicar a experiência do usuário.

### Bug 2 – Login com credenciais inválidas
Local: test-cases/login/login_negativo.md

Problema encontrado:
- O sistema não bloqueou o acesso quando foram informadas credenciais incorretas.

Impacto:
- Isso representa uma falha de validação e pode comprometer a segurança da aplicação.

---

## Resultados obtidos

- Cenários aprovados: 5
- Problemas identificados: 2
- Perfil de validação demonstrado: fluxo funcional, validação de regras de negócio, análise de falhas e documentação de testes

---

## Por que este projeto é importante

Este projeto demonstra minhas habilidades em:

- Pensamento analítico
- Testes manuais de software
- Identificação de bugs e falhas de validação
- Documentação clara de cenários e evidências
- Compreensão do ciclo de QA em uma aplicação real

É uma excelente base para mostrar, em entrevistas e no LinkedIn, que eu já tenho prática em testar sistemas com foco em qualidade, usabilidade e confiabilidade.

---

## Estrutura do repositório

- test-cases/ → cenários de teste manuais organizados por funcionalidade
- evidencias/ → espaço destinado às evidências e registros do projeto

---

## Conclusão

Este projeto reflete uma abordagem profissional de qualidade de software, com foco em testes manuais, rastreio de defeitos e comunicação clara dos resultados. Ele é um ótimo exemplo do tipo de trabalho que pode ser apresentado para recrutadores e equipes de produto.
" 
