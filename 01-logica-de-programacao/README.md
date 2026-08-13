# 💻 Lógica de Programação

> **Lógica de Programação Descomplica VNT 4.0**

Este diretório reúne os exercícios e atividades desenvolvidos ao longo do curso de **Lógica de Programação**, como parte da Trilha de Front-End do Descomplica VNT 4.0.

O principal objetivo deste repositório é registrar o processo de **aprendizado, prática e evolução** durante as aulas, desde os primeiros exercícios de lógica até a construção do projeto final.

---

## 🎯 Sobre o curso

Este curso representa o primeiro contato da trilha com os fundamentos necessários para começar a desenvolver aplicações para a Web.

Os exercícios foram desenvolvidos inicialmente **conforme as propostas apresentadas durante as aulas**, com foco em compreender os conceitos e praticar a lógica de programação.

Após concluir os exercícios, também realizei **pequenas melhorias e adaptações por iniciativa própria**, buscando praticar um pouco além do que foi solicitado e compreender melhor o funcionamento do código.

> 💡 Como são exercícios introdutórios, as melhorias realizadas são simples e têm principalmente o objetivo de **reforçar o aprendizado e a prática dos conceitos apresentados em aula**.

---

## 📚 Estrutura do curso

```text
📁 Lógica de Programação
│
├── 📂 Módulo 01
├── 📂 Módulo 02
├── 📂 Módulo 03
├── 📂 Módulo 04
├── 📂 Módulo 05
├── 📂 Módulo 06
├── 📂 Módulo 07
│
└── 📂 Projeto Final
```

### 🧩 Módulos 01 a 07

Contêm os exercícios desenvolvidos durante as aulas e atividades propostas ao longo do curso.

A organização por módulos permite acompanhar de forma mais clara a evolução dos conteúdos e dos conhecimentos adquiridos.

### 🚀 Projeto Final

O projeto final está organizado em uma pasta própria, separado dos exercícios dos módulos, permitindo uma apresentação mais clara do resultado desenvolvido ao final do curso.

---

## 🛠️ Tecnologias

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

* **HTML5** — estrutura das páginas e exercícios.
* **JavaScript Vanilla** — desenvolvimento da lógica e interação com o usuário.
* **Git/GitHub** — versionamento e organização dos estudos.

---

## 🧠 Principais aprendizados

Durante o curso foram trabalhados conceitos fundamentais de lógica de programação e JavaScript, entre eles:

* 📌 Variáveis e constantes;
* 📥 Entrada e saída de dados;
* ➕ Operadores aritméticos, relacionais e lógicos;
* 🔀 Estruturas condicionais;
* 🔁 Estruturas de repetição;
* ⚙️ Funções;
* 📦 Manipulação e tratamento de dados;
* 🔎 Validação de informações;
* 🧩 Organização da lógica de um programa;
* 🌐 Integração entre HTML e JavaScript;
* 💻 Desenvolvimento de pequenos programas utilizando JavaScript.

---

## 💡 Um pouco além do exercício

Uma parte importante deste repositório é justamente registrar não apenas a resolução dos exercícios, mas também a **experimentação após a resolução**.

Depois de concluir algumas atividades, foram realizadas pequenas alterações para testar possibilidades diferentes e compreender melhor o comportamento do código.

Por exemplo, um exercício simples de entrada de dados pode começar com:

```javascript
const nome = prompt("Informe seu nome:");
console.log(nome);
```

E, durante a prática, receber pequenas melhorias:

```javascript
const nome = prompt("Informe seu nome:") || "Desconhecido";

document.getElementById("resultado").innerText =
  `Olá, ${nome}!`;
```

São alterações simples, mas ajudam a transformar o exercício em uma oportunidade de **experimentar, testar e aprender**.

---

## 🧪 Exemplo de exercício

Um dos exercícios trabalha entrada de dados, conversão de valores e validação:

```javascript
const name = prompt("Informe o seu nome:") || "Desconhecido";

const age = Number(
  prompt("Informe a sua idade:")
);

const city =
  prompt("Informe a cidade onde mora:") ||
  "Não informada";

const validAge =
  !isNaN(age) && age > 0 ? age : 0;

const message = `Nome: ${name}
Idade: ${validAge}
Cidade: ${city}`;

document.getElementById("resultado").innerText = message;
```

Esse tipo de exercício permite praticar conceitos básicos como:

```text
Entrada de dados
      ↓
Conversão
      ↓
Validação
      ↓
Processamento
      ↓
Exibição do resultado
```

---

## 📈 Evolução durante os estudos

A proposta deste repositório não é apresentar apenas códigos prontos, mas também **registrar uma etapa importante da minha evolução na programação**.

Os primeiros exercícios possuem uma abordagem mais simples e direta, enquanto as pequenas melhorias realizadas posteriormente representam momentos de experimentação e aprofundamento dos conceitos.

A ideia é que este repositório também sirva como um registro do ponto de partida da minha jornada no desenvolvimento Front-End.

> **Aprender programação também é testar, errar, modificar, comparar e tentar novamente.**

---

## 🎓 Lógica de Programação

Este curso faz parte da **Trilha de Front-End da Residência Descomplica VNT 4.0**, sendo uma das primeiras etapas da formação.

O conteúdo desenvolvido aqui serve como base para os próximos cursos e projetos da trilha, principalmente para a evolução dos conhecimentos em desenvolvimento Web.

---

## 👩‍💻 Sobre este repositório

Este repositório possui caráter **educacional**, reunindo atividades realizadas durante o processo de formação.

Os códigos apresentados representam exercícios de aprendizado e experimentação, desenvolvidos com o objetivo de construir uma base sólida em lógica de programação e JavaScript.

---

### 🌱 Em constante evolução

Este é apenas o começo.

Cada exercício representa uma pequena etapa na construção de conhecimentos que serão utilizados nos próximos projetos da trilha de Front-End.

**Do primeiro `console.log()` aos próximos projetos. 🚀**

---
