# 📋 Templates - Modelos Estruturados

## O Que São Templates?

São **modelos prontos** em formato estruturado (JSON, Markdown) que você pode:
- ✅ Copiar e colar
- ✅ Preencher com dados
- ✅ Usar com ChatGPT
- ✅ Adaptar conforme necessário

---

## 📁 Templates Disponíveis

### 1. **template-checklist.json**
**Formato:** JSON estruturado
**Uso:** Checklist de compliance completo
**Campos:** 30+ validações organizadas por seção

**Quando usar:**
- Análise profunda de licitação
- Auditoria formal
- Documentação legal
- Resultado com múltiplas seções

**Estrutura:**
```json
{
  "metadata": { },
  "resumo_executivo": { },
  "secoes": {
    "documentacao": [ ],
    "prazos": [ ],
    "publicidade": [ ],
    "modalidade": [ ],
    "conflitos": [ ],
    "edital": [ ],
    "julgamento": [ ]
  },
  "problemas_encontrados": [ ],
  "recomendacoes": [ ],
  "conclusao": { }
}
```

---

### 2. **template-analise.json**
**Formato:** JSON estruturado
**Uso:** Análise técnica e jurídica
**Campos:** Justificativas detalhadas

**Quando usar:**
- Análise com fundamentação legal
- Relatório técnico
- Decisão justificada
- Parecer formal

**Estrutura:**
```json
{
  "identificacao": { },
  "analise_tecnica": [ ],
  "analise_juridica": [ ],
  "conclusao": { }
}
```

---

### 3. **template-relatorio.md**
**Formato:** Markdown
**Uso:** Relatório executivo formatado
**Campos:** Resumo, conclusão, recomendações

**Quando usar:**
- Comunicação com stakeholders
- Relatório gerencial
- Sumário executivo
- Apresentação

**Estrutura:**
```markdown
# Relatório de Análise
## 1. Resumo Executivo
## 2. Constatações
## 3. Conclusão
## 4. Recomendações
## 5. Anexos
```

---

## 🚀 Como Usar um Template

### Passo 1: Copie o Template
```bash
1. Abra o arquivo (.json ou .md)
2. Clique em "Raw" (se no GitHub)
3. Ctrl + A (seleciona tudo)
4. Ctrl + C (copia)
```

### Passo 2: Abra um Editor
```bash
Opções:
- Notepad (Windows)
- TextEdit (Mac)
- VS Code (qualquer SO)
- Google Docs
- Word
```

### Passo 3: Cole o Template
```bash
1. Abra novo arquivo no editor
2. Ctrl + V (cola)
3. Salve como: [processo]-checklist.json
```

### Passo 4: Preencha os Dados
```bash
Substitua:
[PREENCHIMENTO OBRIGATÓRIO] → seus dados
[PREENCHER] → informações relevantes
```

### Passo 5: Use com ChatGPT
```bash
1. Copie o template preenchido
2. Cole no ChatGPT
3. Diga: "Preencha este template com análise de [...]"
4. Aguarde resultado
```

---

## 📝 Exemplo de Preenchimento

### ANTES (Template vazio):
```json
{
  "metadata": {
    "processo_id": "[PREENCHIMENTO OBRIGATÓRIO]",
    "entidade": "[PREENCHIMENTO OBRIGATÓRIO]",
    "objeto": "[PREENCHIMENTO OBRIGATÓRIO]"
  }
}
```

### DEPOIS (Preenchido):
```json
{
  "metadata": {
    "processo_id": "12345/2026/SPO",
    "entidade": "Prefeitura Municipal de São Paulo",
    "objeto": "Fornecimento de material de expediente"
  }
}
```

---

## 🔄 Fluxo de Uso Recomendado

```
1. Use PROMPT 01 (Validação Básica)
   ↓
2. Preencha template-checklist.json
   ↓
3. Use PROMPT 02 (Análise Detalhada)
   ↓
4. Copie para template-analise.json
   ↓
5. Use PROMPT 03 (Conformidade)
   ↓
6. Gere template-relatorio.md
   ↓
7. Compartilhe com stakeholders
```

---

## 💾 Salvando Resultados

### Opção 1: Arquivo Local
```bash
1. Preencha o template
2. Salve no seu computador
3. Guarde em pasta organizadora
4. Nome: [processo]-[tipo]-[data].json
```

### Opção 2: Nuvem
```bash
Google Drive:
- Crie pasta para cada licitação
- Salve templates lá
- Compartilhe com time

OneDrive:
- Sincronize com seu PC
- Acesse de qualquer dispositivo
```

### Opção 3: GitHub
```bash
Se quiser versionar:
1. Crie um fork do SIACP
2. Crie branch: dados-reais
3. Commit templates preenchidos
4. Mantenha histórico
```

---

## 🎯 Dicas Importantes

✅ **Use Templates Estruturados**
- Mantém formato consistente
- Fácil comparação entre análises
- Documentação clara

✅ **Preencha TODOS os campos**
- Não deixe em branco
- Se não aplica, escreva "N/A"
- Se desconhece, escreva "PENDENTE"

✅ **Mantenha Original Intacto**
- Não modifique o template base
- Crie cópia para cada análise
- Preserve estrutura

✅ **Valide Antes de Compartilhar**
- Revise dados
- Verifique formatting
- Teste abertura em diferentes programas

---

## 🔍 Validando o Template

Antes de usar, verifique:

- [ ] JSON é válido (teste em jsonlint.com)
- [ ] Markdown sem erros de sintaxe
- [ ] Todos os campos principais existem
- [ ] Indentação está correta
- [ ] Aspas estão balanceadas

---

## 🛠️ Editando Templates

**Se quiser modificar um template:**

1. ✅ Adicione novos campos (estrutura permitida)
2. ✅ Reorganize seções (mantenha lógica)
3. ✅ Customize para seu caso
4. ❌ Não remova campos críticos
5. ❌ Não altere nomes de seções principais

---

## 📊 Conversão Entre Formatos

### JSON → Markdown
```bash
1. Copie dados do JSON
2. Cole em template-relatorio.md
3. Formate como bullet points
4. Adjust títulos
```

### Markdown → JSON
```bash
1. Copie dados do Markdown
2. Cole em template-checklist.json
3. Organize por seções
4. Valide estrutura JSON
```

---

## 🔗 Ferramentas Úteis

**Para editar JSON:**
- VS Code (recomendado)
- Sublime Text
- Notepad++
- Online: jsoncrack.com

**Para validar JSON:**
- jsonlint.com
- jsonformatter.org

**Para editar Markdown:**
- VS Code
- Typora
- StackEdit (online)

**Para converter formatos:**
- Pandoc (CLI)
- CloudConvert (online)

---

## 📞 Suporte

**Dúvidas sobre templates?**

1. Consulte README-PROMPTS.md
2. Veja exemplo em /exemplos/
3. Abra Issue no GitHub
4. Leia Lei-14133-2021.md

---

**Última Atualização:** Julho 2026
