# Apresentação Pessoal em JavaScript

Exercício de lógica em JavaScript puro que captura dados do usuário (nome, idade e cidade) via `prompt()`, valida as entradas e exibe o resultado sem manipulação do DOM.

## Sobre o projeto

A proposta inicial era simples coletar informações do usuário e exibi-las na tela. A partir daí, o exercício foi evoluído para incluir

- Validação de entrada valores vazios ou cancelados recebem um padrão (`Desconhecido`, `Não informada`), e idades inválidas (`NaN` ou negativas) são tratadas como `0`.
- Boas práticas de declaração uso de `const` para valores que não mudam, evitando reatribuições acidentais.
- Template literals para montar a mensagem final de forma legível.
- Exibição sem DOM por escolha, o resultado é mostrado via `alert()` e `console.log()`, mantendo o foco na lógica em vez de manipulação de elementos HTML.

## Tecnologias

- HTML5
- JavaScript (Vanilla)

## Como executar

1. Baixe ou clone este repositório.
2. Abra o arquivo `.html` em qualquer navegador.
3. Responda aos prompts solicitados (nome, idade e cidade).
4. O resultado será exibido em um alerta e também registrado no console do navegador (F12 → Console).

## Aprendizados

Este exercício reforça conceitos fundamentais de JavaScript captura de entrada do usuário, tratamento de valores inválidosausentes, uso correto de `const``let`, template literals e exibição de resultados por meio de lógica pura (`alert``console.log`).