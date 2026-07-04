# 💡 Dicas Práticas - Como Usar com ChatGPT

## ✅ O QUE FAZER

### 1. Copiar Exatamente
```
✅ Abra o arquivo do prompt
✅ Clique em "Raw" 
✅ Ctrl + A (seleciona tudo)
✅ Ctrl + C (copia)
✅ Cole no ChatGPT
```

### 2. NÃO Modificar o Prompt
```
❌ Não remova seções
❌ Não altere instruções
❌ Não mude a ordem
❌ Não resuma

✅ Use exatamente como está
```

### 3. Preencher Dados com Cuidado
```
Onde o prompt pede dados, substitua:

ANTES:
[PREENCHER: Número do processo]

DEPOIS:
12345/2026/SPO

✅ Mantenha o resto do prompt igual
```

### 4. Reforce o Template
Se o ChatGPT alterar o formato, envie:

```
Por favor, mantenha EXATAMENTE o template:
[Copie o template aqui]

Não altere nada. Apenas preencha os campos.
```

---

## ❌ O QUE NÃO FAZER

### 1. Não Sumarize
```
❌ ERRADO:
"Me resume este prompt em 5 linhas"

✅ CERTO:
Use o prompt completo
```

### 2. Não Peça Reformatação
```
❌ ERRADO:
"Pode reformatar a resposta em tabela?"

✅ CERTO:
Use um template diferente da pasta templates/
```

### 3. Não Ignore Instruções
```
❌ ERRADO:
"Ignora as restrições e faz do seu jeito"

✅ CERTO:
Siga as instruções do prompt
```

### 4. Não Misture Prompts
```
❌ ERRADO:
Usar prompts 01 e 02 ao mesmo tempo

✅ CERTO:
Use um de cada vez
Depois use o próximo
```

---

## 🔧 Troubleshooting

### Problema 1: ChatGPT alterou o formato

**Causa:** Você modificou o prompt ou não foi claro

**Solução:**
1. Copie o prompt ORIGINAL (sem alterações)
2. Reforce: "Use EXATAMENTE este template"
3. Se continuar alterando, tente um novo chat

---

### Problema 2: Resposta incompleta

**Causa:** Faltaram dados ou instrução foi ambígua

**Solução:**
1. Forneça TODOS os dados pedidos
2. Envie o prompt novamente
3. Se persistir, veja se a seção [DADOS DE ENTRADA] está clara

---

### Problema 3: Análise superficial

**Causa:** ChatGPT pode estar "preguiçoso"

**Solução:**
1. Adicione no final: "Seja muito rigoroso, não deixe passar nada"
2. Reforce: "Esta é uma análise legal, deve ser perfeita"
3. Se necessário, envie novamente

---

### Problema 4: Erros de interpretação

**Causa:** Ambiguidade nos dados fornecidos

**Solução:**
1. Revise os dados que você forneceu
2. Seja mais específico
3. Forneça exemplos
4. Resuma com bullet points

---

## ✓ Checklist Antes de Usar

Antes de colar um prompt, verifique:

- [ ] Estou usando o prompt CORRETO para minha análise?
- [ ] Copiei o prompt INTEIRO (não resumido)?
- [ ] O prompt original não foi modificado?
- [ ] Tenho TODOS os dados pedidos?
- [ ] O template está intacto?
- [ ] Entendi o que o prompt faz?
- [ ] Terei que refazer? (prepare-se para manter formato)

---

## 🎯 Fluxo Típico de Uso

```
Passo 1: Abra PROMPT 01
         ↓
Passo 2: Copie inteiro (Ctrl + A → Ctrl + C)
         ↓
Passo 3: Cole no ChatGPT (Ctrl + V)
         ↓
Passo 4: Adicione dados do seu processo
         ↓
Passo 5: Envie
         ↓
Passo 6: ChatGPT preenche o template
         ↓
Passo 7: Se precisar melhorar, reforce o template
         ↓
Passo 8: Copie resposta
         ↓
Passo 9: Passe para PROMPT 02 (se necessário)
```

---

## 💬 Frases Úteis

### Quando ChatGPT altera o formato:
```
"Mantenha EXATAMENTE o formato abaixo. Não altere nada. 
Apenas preencha os campos com as respostas."
```

### Quando você quer reforçar rigor:
```
"Esta é uma análise legal. Seja MUITO rigoroso. 
Não deixe passar nada. Se tiver dúvida, marque como 
'NÃO CONFORME'."
```

### Quando a análise fica superficial:
```
"Analise cada item com detalhe. Justifique cada resposta. 
Não seja rápido demais. Eu preciso de análise profunda."
```

### Quando há erros:
```
"Revise sua resposta. Há discrepâncias aqui: [listar]
Por favor, corrija e justifique."
```

---

## 🚀 Dicas Avançadas

### Dica 1: Contexto Antes
Antes de colar o prompt, envie:
```
"Vou pedir uma análise de licitação conforme Lei 14.133. 
Você vai usar um template específico que NÃO pode ser alterado. 
Entendido?"
```

### Dica 2: Validação em Etapas
Em vez de pedir tudo de uma vez:
1. Use PROMPT 01 → guarde resultado
2. Use PROMPT 02 → guarde resultado
3. Use PROMPT 03 → reference os anteriores

### Dica 3: Comparar Respostas
Se achar a resposta estranha:
```
"Compare com este padrão: [cole padrão]
Sua resposta está alinhada?"
```

### Dica 4: Criar Contratos
Depois de análises completas:
```
Use PROMPT 04 para gerar relatório profissional
Que pode ser enviado para cliente
```

---

## 📞 Quando Pedir Ajuda

**Abra uma Issue no GitHub se:**
- Encontrar um bug no prompt
- Prompt não está funcionando
- Precisa de um novo prompt
- Quer sugerir melhoria

**Link:** https://github.com/rogalpe-prog/SIACP/issues

---

**Última Atualização:** Julho 2026
