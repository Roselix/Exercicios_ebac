# Níveis de Testes: Quando Testar

Também chamados de **estágios de testes**, definem **o momento mais apropriado** para a execução de determinados testes.

---

## 1. Testes de Componentes

- Testam **componentes individuais** do software.
- Também chamados de **Testes de Unidade**.
- Realizados pelo **próprio desenvolvedor**.
- Testam a **menor unidade do sistema**, geralmente um método.
- **Feedback rápido**.

### O teste deve responder:
- O que estou testando?
- O que o método deveria fazer?
- Qual o seu retorno atual?
- O que eu espero que ele retorne?

---

## 2. Testes de Integração

- Testam a **integração das unidades** já testadas individualmente.
- Realizados de forma **incremental**, incluindo os módulos um por um até cobrir todos os casos.
- Normalmente realizados por **desenvolvedores não envolvidos** na construção dos módulos ou pela equipe de testes.
- Verificam a integração com **banco de dados**, **APIs** e outros componentes.

---

## 3. Testes de Sistema

- Também conhecidos como **testes funcionais**.
- Aplicados pela **equipe de testes**.
- Verificam o sistema **como um todo**, usando técnicas funcionais para gerar os casos de teste.
- Executados em **ambientes controlados**, similares ao ambiente do cliente.
- Fornecem **parâmetros de aprovação** para liberar o sistema.
- Responde à pergunta:  
  > **"Os recursos do sistema estão funcionando corretamente?"**

---

## 4. Testes de Aceitação

- Realizados pelos **usuários finais** da aplicação.
- Executados **antes da liberação em produção**.
- Avaliam se a solução atende aos **objetivos de negócio**.

### Categorias:
- **Teste Alfa**:
  - Executado em **ambiente controlado**.
- **Teste Beta**:
  - Usuário executa os testes em um ambiente mais **realista e livre**.

---

## Tipos de Testes de Aceitação

### Testes Exploratórios

- Executados por **qualquer membro do time** (devs, PO, designers, etc.).
- Realizados de forma **dinâmica**, sem documentação formal.
- Baseados no **conhecimento prévio** e experiência dos testadores.

### Quando usar:
- Projeto com **prazo apertado**.
- **Documentação desatualizada**.
- Como **complemento a testes planejados**.

### Estilos:
- **Estilo Livre (Ad-hoc)**:  
  O sistema é testado **sem diretrizes rígidas**, de forma improvisada.

> Enquanto você foca nos testes planejados, o time pode contribuir com os testes exploratórios.

