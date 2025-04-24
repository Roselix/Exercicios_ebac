# Tipos de Testes

Para cada objetivo, um ou mais tipos de testes podem ser utilizados.

## 1. Testes Funcionais

- Avaliam as **funções que o sistema deve executar**.
- Verificam **o que o sistema deve fazer** (qual comportamento deve ter).
- Validam se as **regras de negócio** estão sendo implementadas **corretamente e adequadamente**.
- Devem ser realizados em **todos os níveis de testes**.
- Os testes começam desde o **levantamento de requisitos até a produção** (_Shift Left Testing_).

## 2. Testes Não Funcionais

- Avaliam **quão bem o sistema se comporta**, como por exemplo em termos de **performance**.
- Analisam **aspectos importantes**, mesmo que não estejam diretamente relacionados às funções.
- Avaliam características como:
  - Usabilidade
  - Desempenho
  - Segurança
  - Carga de trabalho
  - Recuperação de falhas
  - Entre outros...

## 3. Testes de Caixa Branca

- Também conhecido como **teste estrutural**.
- Baseado na **estrutura interna** ou na **implementação** do sistema.
- Inclui análise de:
  - Código
  - Arquitetura
  - Fluxos de dados
  - Controle e lógica de trabalho
- Permite medir a **cobertura de código**.

### Diferenças entre Caixa Branca e Caixa Preta

- **Teste Caixa Preta**: 
  - Não é possível ver o código.
  - Avalia apenas **entradas e saídas**.
  
- **Teste Caixa Branca**:
  - Possível visualizar o código, fluxograma, classes e variáveis.
  - Permite **análises mais precisas** e cobertura mais abrangente dos testes.

## 4. Testes Relacionados à Mudança

Utilizados quando alterações são feitas no sistema para verificar se:

- A **correção foi bem-sucedida**.
- A alteração **não causou novos defeitos** (efeitos colaterais).

### Tipos:

- **Teste de Confirmação (Reteste)**:
  - Executado após a correção de um defeito.
  - Valida o sucesso das ações corretivas.

- **Teste de Regressão**:
  - Garante que nenhuma outra parte do sistema foi afetada após modificações no código.
  - Verifica se **outros módulos** não foram impactados pela mudança ou criação de um novo módulo.

## Testes Automatizados

Relacionados principalmente aos **testes de confirmação e regressão**.

- São ferramentas que **executam testes automaticamente**, simulando as ações de um usuário.
- Evitam a repetição manual de testes após **cada correção ou nova implementação**.
- Tornam o processo de testes **mais eficiente, confiável e ágil**.
