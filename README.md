# Quiz Relâmpago — Vibe Coding

**Equipa 5 · Assignment 5 — Spec-Driven vs Vibe Coding** · Metodologias de Desenvolvimento de Software

Um quiz de escolha múltipla com temporizador por pergunta, construído em **Vibe Coding**: o código foi gerado pelo prompt direto e iterativo a um agente de IA (Claude), **sem especificação, plano nem lista de tarefas**.

Este repositório é uma das duas condições de uma experiência crossover. A outra condição, os Flashcards de Estudo em Spec-Driven Development, está em [`mds-a5-equipa5-flashcards-spec`](https://github.com/UTILIZADOR/mds-a5-equipa5-flashcards-spec). A análise comparativa está em [`mds-a5-equipa5-relatorio`](https://github.com/UTILIZADOR/mds-a5-equipa5-relatorio).

## Demo

- **Netlify:** 

## Método

> Prompt, correr, corrigir, repetir.

- Agente de IA: Claude
- Sem spec, sem plano e sem lista de tarefas, por definição da condição
- Orçamento de tempo: 3 h no máximo
- Todos os prompts ficam registados em [`PROMPTS.md`](PROMPTS.md), com a hora e o resultado de cada um
- Há um commit por cada iteração relevante, e o histórico serve de evidência do processo

## Executar localmente

É um site estático e não precisa de build. Abram o `index.html` no browser ou sirvam a pasta:

```bash
npx serve .
```

## Deploy

Netlify, sem comando de build, com a raiz do repositório como pasta de publicação.
