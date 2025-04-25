# Técnicas de Teste: Como Testar?

---

## ✨ O que são?

As **técnicas de teste** ajudam a planejar *como* testar um sistema, com o objetivo de encontrar defeitos de forma eficiente, considerando o tipo de teste e o contexto do projeto.

---

## 📜 Os Sete Princípios dos Testes

1. **O teste mostra a presença de defeitos, não sua ausência**
   - Testar revela problemas, mas não garante que não existam mais.

2. **Testes exaustivos são impossíveis**
   - Não dá pra testar *tudo*, então priorizamos os testes mais relevantes.

3. **Testar cedo economiza tempo e dinheiro**
   - Detectar problemas no início é muito mais barato do que no final.

4. **Defeitos se agrupam**
   - Os bugs costumam se concentrar em áreas específicas do sistema.

5. **O paradoxo do pesticida**
   - Testes repetitivos perdem a eficácia com o tempo. É preciso variar.

6. **O teste depende do contexto**
   - A estratégia muda conforme o tipo de software, público e objetivos.

7. **Ausência de erros é uma ilusão**
   - Um sistema sem bugs pode ainda assim não atender às necessidades.

---

## ❓ Qual técnica usar?

A escolha depende de fatores como:

- Complexidade do sistema  
- Contratos com o cliente  
- Documentação disponível  
- Níveis e tipos de risco  
- Habilidades e conhecimento do QA  
- Ferramentas disponíveis  
- Tempo e orçamento  
- Modelo de trabalho adotado  
- Tipo de defeitos esperados  

---

## 🧠 Técnicas Baseadas em Caixa Branca

Analisam o **código-fonte, lógica e fluxograma** da aplicação.

- **Cobertura de instrução**
- **Cobertura de decisão**
- **Análise de fluxo de dados**

> Acesso à estrutura interna do sistema.

---

## 🎯 Técnicas Baseadas em Caixa Preta

Focam em **entradas e saídas**, sem olhar para o código.

- **Particionamento de Equivalência**
- **Análise de Valor Limite**
- **Tabela de Decisão**
- **Transição de Estado**
- **Baseado em Casos de Uso**

> Simulam a visão do usuário final.

---

## 🔍 Técnicas Baseadas em Experiência

Utilizam o **conhecimento e percepção do testador**:

- **Teste Exploratório**
- **Baseado em Checklist**
- **Suposição de Erros Comuns**

> Usadas quando há pouca documentação ou tempo reduzido.

---

## 🧪 Conclusão

Cada técnica tem seu valor e deve ser escolhida de acordo com o contexto do projeto. Misturar abordagens geralmente resulta em testes mais eficazes e completos.
