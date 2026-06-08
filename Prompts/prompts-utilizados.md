# 📖 Engenharia de Prompts Utilizada

Durante a construção do NotebookLM, foram realizados diversos testes para avaliar a capacidade da IA de interpretar parâmetros de qualidade da água, relacionar variáveis operacionais e consultar informações presentes nas fontes selecionadas.

## Prompt 1 - Relação entre parâmetros

### Prompt

```text
Explique a relação entre pH, alcalinidade e eficiência da coagulação em estações de tratamento de água.
```

### Objetivo

Compreender como diferentes parâmetros físico-químicos influenciam a eficiência do tratamento.

### Resultado

A IA explicou a importância da alcalinidade para garantir a estabilidade do pH e da influência do pH sobre a coagulação.

---

## Prompt 2 - Diagnóstico Operacional

### Prompt

```text
A turbidez da água filtrada aumentou repentinamente. Quais podem ser as causas mais prováveis?
```

### Objetivo

Avaliar a capacidade da IA de auxiliar na identificação de desvios operacionais.

### Resultado

Foram sugeridas hipóteses relacionadas à saturação dos filtros, problemas na coagulação e floculação, arraste de flocos, alteração na qualidade da água bruta, falhas operacionais dos filtros, problemas na retrolavagem, entre outros.

---

## Prompt 3 - Água Desmineralizada

### Prompt

```text
O aumento da condutividade em água desmineralizada pode indicar quais problemas operacionais?
```

### Objetivo

Testar o conhecimento da IA sobre sistemas de troca iônica e osmose reversa.

### Resultado

A IA relacionou corretamente o aumento da condutividade à exaustão de resinas, falhas de regeneração e passagem de sais dissolvidos, além de sugerir também problemas na osmose reversa, como incrustação e ensujamento da membrana.

---

## Prompt 4 - Legislação

### Prompt

```text
Quais são os limites de pH estabelecidos pela legislação brasileira para lançamento de efluentes?
```

### Objetivo

Verificar a capacidade de consulta às normas ambientais presentes na base de conhecimento.

### Resultado

A IA localizou corretamente a informação na Resolução CONAMA 430/2011, listando a faixa ideal desse parâmetro.

---

## Prompt 5 - Comparação de Indicadores

### Prompt

```text
Compare ORP e residual de cloro e explique como interpretar os resultados em conjunto.

```

### Objetivo

Avaliar a capacidade da IA de relacionar indicadores.

### Resultado

A IA explicou a correlação entre ORP e residual de cloro, auxiliando na interpretação dos resultados.
