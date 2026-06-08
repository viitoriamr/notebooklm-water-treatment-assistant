# Troubleshooting e Lições Aprendidas

Durante o desenvolvimento do NotebookLM foram identificadas algumas limitações e oportunidades de melhoria na elaboração dos prompts.

## Caso 1 - Pergunta Genérica

### Prompt Inicial

```text
Como reduzir turbidez?
```

### Problema

A resposta gerada foi ampla e pouco aplicável a situações reais de operação.

### Ajuste Realizado

```text
Considerando uma ETA convencional composta por coagulação, floculação, decantação e filtração, quais fatores podem provocar aumento de turbidez na saída dos filtros?
```

### Resultado

A resposta tornou-se mais específica, apresentando causas operacionais e sugestões de investigação.

---

## Caso 2 - Consulta Legal

### Prompt Inicial

```text
Qual o limite de DBO?
```

### Problema

A pergunta não informava o contexto da legislação.

### Ajuste Realizado

```text
Quais são os critérios relacionados à DBO para lançamento de efluentes?
```

### Resultado

A IA apresentou respostas mais precisas e alinhadas à norma de lançamento de efluentes.

---

## Caso 3 - Água Desmineralizada

### Prompt Inicial

```text
Por que a condutividade aumentou?
```

### Problema

Faltavam informações para interpretação.

### Ajuste Realizado

```text
A condutividade da água desmineralizada aumentou de 0,2 µS/cm para 3,0 µS/cm após o leito misto. Quais são as possíveis causas?
```

### Resultado

A IA apresentou hipóteses relacionadas ao leito misto e ao esgotamento das resinas e falhas de regeneração.

---

# Principais Aprendizados

- Prompts específicos geram respostas mais precisas.
- Informar o contexto operacional melhora significativamente a qualidade das respostas.
- Descrever sintomas, valores e condições de processo permite análises mais completas.
