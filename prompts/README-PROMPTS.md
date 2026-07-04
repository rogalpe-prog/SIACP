# 📋 Guia de Prompts - SIACP

## O Que São Estes Prompts?

São instruções **otimizadas** para o ChatGPT que:
- ✅ Forçam análises completas
- ✅ Evitam que validações sejam puladas
- ✅ Mantêm formato consistente
- ✅ Separam análise de formatação

---

## 📝 Prompts Disponíveis

### 1️⃣ **01-validacao-basica.md**
**Quando usar:** Primeira análise rápida
**Saída:** Checklist básico de conformidade
**Tempo:** 2-3 minutos
**Foco:** Validações obrigatórias Lei 14.133

### 2️⃣ **02-checklist-compliance.md**
**Quando usar:** Análise estruturada completa
**Saída:** Checklist detalhado em JSON
**Tempo:** 5-7 minutos
**Foco:** Todos os critérios de compliance

### 3️⃣ **03-analise-conformidade.md**
**Quando usar:** Análise profunda e justificada
**Saída:** Análise com justificativas
**Tempo:** 10-15 minutos
**Foco:** Razões de cada validação

### 4️⃣ **04-gerar-relatorio.md**
**Quando usar:** Após análise completa
**Saída:** Relatório executivo formatado
**Tempo:** 3-5 minutos
**Foco:** Resumo para stakeholders

---

## 🎯 Fluxo Recomendado

```
1. Use 01-validacao-basica.md
   ↓
2. Se passou, use 02-checklist-compliance.md
   ↓
3. Se passou, use 03-analise-conformidade.md
   ↓
4. Finalize com 04-gerar-relatorio.md
```

---

## ⚙️ Como Usar Cada Prompt

### Passo 1: Copie o Prompt Completo
```bash
1. Abra o arquivo .md
2. Ctrl + A (selecionar tudo)
3. Ctrl + C (copiar)
```

### Passo 2: Cole no ChatGPT
```bash
1. Acesse https://chatgpt.com
2. Crie uma nova conversa
3. Ctrl + V (colar)
4. Pressione Enter
```

### Passo 3: Aguarde a Confirmação
O ChatGPT vai responder algo como:
> "Entendi. Estou pronto para analisar o processo de licitação conforme a Lei 14.133..."

### Passo 4: Forneça os Dados
Cole o conteúdo da licitação que quer analisar.

### Passo 5: Revise o Resultado
Verifique se:
- ✅ Todas as validações foram executadas
- ✅ O formato está correto
- ✅ Nenhum campo está vazio

---

## ⚠️ Problemas Comuns

### ❌ ChatGPT Alterou o Formato
**Solução:**
1. Copie novamente o template da pasta `templates/`
2. Diga: "Use EXATAMENTE este template, não altere nada"
3. Cole o template
4. Depois forneça os dados

### ❌ ChatGPT Pulou uma Validação
**Solução:**
1. Vá para `docs/validacoes-criticas.md`
2. Copie a validação que foi pulada
3. Diga ao ChatGPT: "Você pulou esta validação: [cole aqui]"
4. Peça para refazer

### ❌ Resultado Muito Vago
**Solução:**
1. Use um prompt mais detalhado (02, 03 ou 04)
2. Ou peça para o ChatGPT: "Seja mais específico em cada ponto"

---

## 💡 Dicas Importantes

✅ **Sempre comece com o Prompt 1** - Validação básica primeiro
✅ **Use templates estruturados** - Não deixe o ChatGPT improvisar
✅ **Revise cada resultado** - Checklist completo após cada análise
✅ **Salve as análises** - Guarde em arquivo para histórico
✅ **Se tiver dúvida, consulte docs/** - Lei 14.133 está documentada

---

## 🔗 Próximos Passos

1. Leia [GUIA-RAPIDO.md](../GUIA-RAPIDO.md)
2. Comece com o Prompt 01
3. Consulte [exemplos/](../exemplos/) se tiver dúvidas
4. Veja [docs/validacoes-criticas.md](../docs/validacoes-criticas.md) para referência
