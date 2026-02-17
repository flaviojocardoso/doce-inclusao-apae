# 🍰 Doce Inclusão - Gestão Culinária e Custos (MVP)

O **Doce Inclusão** é um Web App desenvolvido sob medida para o projeto culinário da **APAE de Gravataí/RS**. A ferramenta digitaliza o processo de planejamento alimentar, transformando controles manuais em um sistema automatizado de cálculos e logística.

---

### 🚀 O Problema vs. A Solução

* **Desafio:** A instituição lidava com a dificuldade de calcular insumos para receitas que variavam conforme o número de alunos, além de enfrentar a flutuação constante de preços nos supermercados.
* **Solução:** Desenvolvi uma arquitetura onde o custo dos insumos é centralizado. Ao atualizar o preço de um ingrediente, o custo de todas as receitas vinculadas é recalculado automaticamente, gerando uma lista de compras exata para o dia da aula.

---

### 🛠️ Diferenciais Técnicos

* **Arquitetura de Dados:** Separação lógica entre "Insumos" (base de custos) e "Receitas" (composição técnica), permitindo escalabilidade.
* **Cálculos Dinâmicos:** Algoritmos que realizam conversão de unidades (kg/g, l/ml) para garantir precisão no custo final por aluno.
* **Offline First & PWA:** Utilização de `localStorage` para persistência de dados local, permitindo o uso sem internet dentro da cozinha, além de ser instalável como um aplicativo nativo.
* **UX Inclusiva:** Interface limpa com aba de ajuda dedicada para facilitar a adoção tecnológica pelos colaboradores da instituição.

---

### 💻 Tecnologias Utilizadas

* **JavaScript (Vanilla ES6+):** Lógica de negócios e manipulação de estado.
* **HTML5 & CSS3:** Design responsivo focado em dispositivos móveis.
* **PWA Manifest:** Suporte para instalação em Android e iOS.

---

### 📊 Impacto Gerado
Este projeto demonstra minha capacidade de realizar o **levantamento de requisitos** com clientes reais, prototipar uma solução focada em **experiência do usuário (UX)** e entregar um produto funcional que gera economia de tempo e recursos.

---
*"Mais do que código, uma ferramenta de impacto social e inclusão."*
