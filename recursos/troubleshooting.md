# 🔧 Troubleshooting - Soluções para Problemas

## 🚨 Problemas Comuns

### ❌ Problema 1: "ChatGPT Não Está Respondendo"

**Sintomas:**
- ChatGPT congela
- Resposta demora muito
- "Erro de processamento"

**Causas:**
- Prompt muito longo
- Dados malformatados
- Limite de tokens excedido

**Soluções:**

1️⃣ **Tente novamente em outro chat:**
```
- Crie uma nova conversa
- Cole o prompt novamente
- Adicione dados
- Envie
```

2️⃣ **Reduza a quantidade de dados:**
```
- Em vez de todo o edital, forneça resumo
- Copie apenas trechos relevantes
- Seja mais direto
```

3️⃣ **Divida em etapas:**
```
Não faça:
"Analise tudo isso"

Faça:
"Analise apenas o Termo de Referência"
[depois]
"Agora analise o Edital"
```

---

### ❌ Problema 2: "ChatGPT Alterou o Formato"

**Sintomas:**
- Resposta não segue o template
- Campos reorganizados
- Formatação diferente

**Causas:**
- Você modificou o prompt
- Prompt foi resumido
- Instrução não foi clara

**Soluções:**

1️⃣ **Copie o prompt ORIGINAL novamente:**
```
- Abra o arquivo .md do prompt
- Clique em "Raw"
- Ctrl + A → Ctrl + C
- Cole novamente no ChatGPT
```

2️⃣ **Reforce a instrução:**
```
Envie ao ChatGPT:

"Você DEVE usar EXATAMENTE este template. 
Não altere nada. Apenas preencha os campos.
Aqui está o template:

[COLE O TEMPLATE]

Agora, preencha com os dados que vou fornecer."
```

3️⃣ **Se persistir, crie novo chat:**
```
- Às vezes o histórico confunde ChatGPT
- Comece uma nova conversa
- Cole o prompt original
- Seja rigoroso nas instruções
```

---

### ❌ Problema 3: "Resposta Muito Vaga ou Superficial"

**Sintomas:**
- Análise não é completa
- Validações foram puladas
- Respostas muito curtas

**Causas:**
- ChatGPT pode estar "preguiçoso"
- Dados insuficientes
- Instrução ambígua

**Soluções:**

1️⃣ **Reforce o rigor:**
```
Envie ao ChatGPT:

"Esta é uma análise LEGAL de licitação.
Deve ser MUITO rigorosa.
Não deixe passar NADA.
Se tiver dúvida, marque como NÃO CONFORME.
Justifique CADA resposta."
```

2️⃣ **Solicite mais detalhes:**
```
"Seja mais específico em cada ponto.
Cite artigos da lei.
Justifique cada avaliação.
Não seja genérico."
```

3️⃣ **Use prompt mais detalhado:**
```
Se usar PROMPT 01 e resultado for vago:
→ Use PROMPT 02 (Checklist Compliance)
→ Mais detalhado
→ Melhor estrutura
```

---

### ❌ Problema 4: "Erro na Análise/Contradição"

**Sintomas:**
- ChatGPT contradiz a si mesmo
- Análise está incorreta
- Aplicou regra errada

**Causas:**
- Dados confusos ou contraditórios
- ChatGPT interpretou errado
- Lei foi mal citada

**Soluções:**

1️⃣ **Revise os dados:**
```
Você forneceu dados conflitantes?
Exemplo:
- Disse modalidade é "Convite"
- Mas valor é R$ 500.000

Corrija ANTES de enviar novamente
```

2️⃣ **Questione o ChatGPT:**
```
"Você disse X, mas depois disse Y.
Isso está correto?
Qual é a resposta correta?"
```

3️⃣ **Forneça referência:**
```
"De acordo com Lei 14.133 Art. 6:
[COLAR ARTIGO]

Sua análise está alinhada com isso?"
```

---

### ❌ Problema 5: "ChatGPT Não Encontra Informação"

**Sintomas:**
- "Não tenho essa informação"
- "Não consigo verificar"
- "Preciso de mais dados"

**Causas:**
- Você não forneceu informação
- Informação não estava clara
- ChatGPT não conseguiu localizar

**Soluções:**

1️⃣ **Forneça o documento completo:**
```
Em vez de:
"Qual é a modalidade?"

Faça:
"Modalidade: Concorrência"
ou
"Aqui está o edital: [COLAR]"
```

2️⃣ **Seja explícito:**
```
Não deixe implícito.
Sempre diga:
- Data de publicação
- Data de abertura
- Valor estimado
- etc.
```

3️⃣ **Crie contexto:**
```
Antes de fazer perguntas, contextualize:
"Este é um processo de licitação
conforme Lei 14.133/2021,
realizado pela Prefeitura de X.
Aqui estão os dados: [...]"
```

---

### ❌ Problema 6: "Prompt Não Existe ou Está Errado"

**Sintomas:**
- Prompt está quebrado
- Arquivo não abre
- Template está com erro

**Causas:**
- Arquivo deletado
- Erro na criação
- Você modificou acidentalmente

**Soluções:**

1️⃣ **Verifique a pasta correta:**
```
Prompts estão em:
/prompts/01-validacao-basica.md
/prompts/02-checklist-compliance.md
/prompts/03-analise-conformidade.md
/prompts/04-gerar-relatorio.md
```

2️⃣ **Abra no GitHub:**
```
- Acesse: https://github.com/rogalpe-prog/SIACP
- Vá até pasta /prompts/
- Clique no arquivo
- Clique em "Raw"
- Ctrl + A → Ctrl + C
```

3️⃣ **Reporte o problema:**
```
Se o arquivo estiver errado:
1. Abra uma Issue: https://github.com/rogalpe-prog/SIACP/issues
2. Descreva o problema
3. Anexe screenshot
4. Envie
```

---

### ❌ Problema 7: "Dados do Processo Incompletos"

**Sintomas:**
- Faltam documentos
- Informações vagas
- Datas confusas

**Causas:**
- Processo está realmente incompleto
- Você não coletou tudo
- Entidade não publicou

**Soluções:**

1️⃣ **Marque como PENDENTE:**
```
Na resposta do ChatGPT:
Status: PENDENTE

Motivo: Informação não disponível
Necessário: [LISTAR]
```

2️⃣ **Obtenha as informações:**
```
- Contate a entidade
- Peça documentos faltantes
- Aguarde publicação
- Depois refaça análise
```

3️⃣ **Analise com o que tem:**
```
Use PROMPT 01 (Validação Básica)
Status: PARCIALMENTE CONFORME
Observação: "Análise pendente de [...]"
```

---

### ❌ Problema 8: "Não Entendo a Resposta"

**Sintomas:**
- Resposta muito técnica
- Termos jurídicos confusos
- Não sabe o que fazer

**Causas:**
- Você é novo no assunto
- Explicação muito profunda
- Precisa de contexto

**Soluções:**

1️⃣ **Consulte a documentação:**
```
Leia:
- Lei-14133-2021.md (explica lei)
- validacoes-criticas.md (explica validações)
- README-PROMPTS.md (explica prompts)
```

2️⃣ **Peça explicação simples:**
```
"Explique isso em linguagem simples:
[COPIAR RESPOSTA DO CHATGPT]"
```

3️⃣ **Procure exemplos:**
```
Na pasta /exemplos/ há casos resolvidos.
Veja como funciona na prática.
```

---

## ✅ Checklist de Verificação

Antes de reportar um problema, verifique:

- [ ] Copiei o prompt INTEIRO (sem resumir)?
- [ ] Adicionei TODOS os dados pedidos?
- [ ] Tenho acesso à internet?
- [ ] O ChatGPT está carregando?
- [ ] Já tentei em outro navegador?
- [ ] Já tentei em novo chat?
- [ ] Revisei os dados que enviei?
- [ ] Consultei a documentação?

---

## 📞 Quando Reportar uma Issue

**Reporte se:**
- ✅ Um prompt está quebrado
- ✅ Documentação tem erro
- ✅ Encontrou bug real
- ✅ Quer sugerir melhoria

**Não reporte para:**
- ❌ Ajuda em usar ChatGPT (veja FAQ)
- ❌ Dúvidas sobre Lei 14.133 (veja Lei-14133-2021.md)
- ❌ Perguntas sobre seu processo específico

---

## 🔗 Link para Reportar

**GitHub Issues:**
https://github.com/rogalpe-prog/SIACP/issues

**Forneça:**
1. Título descritivo
2. Descrição do problema
3. Passos para reproduzir
4. Screenshot (se aplicável)
5. Que prompt/arquivo está envolvido

---

## 💡 FAQ Rápido

**P: ChatGPT está muito lento**
R: Normal para prompts longos. Aguarde ou divida em partes.

**P: Posso modificar o prompt?**
R: Sim, mas mantenha estrutura. Não altere o template.

**P: Qual prompt usar?**
R: 01 → 02 → 03 → 04 (nesta ordem)

**P: Posso usar em outro LLM?**
R: Sim, mas ChatGPT é recomendado.

**P: Como compartilho resultados?**
R: Copie resposta → Salve em arquivo → Compartilhe.

---

**Última Atualização:** Julho 2026
