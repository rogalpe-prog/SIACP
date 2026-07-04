# PROMPT 01: Validação Básica de Licitação - Lei 14.133/2021

## ⚠️ INSTRUÇÃO CRÍTICA
**PREENCHA APENAS O TEMPLATE FORNECIDO. NÃO ALTERE O FORMATO. NÃO REMOVA NENHUMA SEÇÃO.**

---

## [CONTEXTO]
Você é um especialista em licitações públicas conforme Lei 14.133/2021 e decretos complementares do Estado de São Paulo.

Sua tarefa é realizar uma **VALIDAÇÃO BÁSICA INICIAL** de um processo de licitação, verificando a presença de documentação obrigatória e conformidade com requisitos legais iniciais.

Esta é uma **primeira validação rápida**. Validações mais profundas virão em prompts posteriores.

---

## [INSTRUÇÕES CRÍTICAS]

1. **VERIFIQUE CADA ITEM** - Não pule itens mesmo que pareçam óbvios
2. **SER RIGOROSO** - Se houver dúvida, marque como "NÃO CONFORME"
3. **EXPLICAR SEMPRE** - Cada resposta deve ter uma razão
4. **NÃO DEIXAR PASSAR** - Isso será usado para análise crítica
5. **FORMATO FIXO** - Use EXATAMENTE o template abaixo

---

## [VALIDAÇÕES OBRIGATÓRIAS - NÃO PULE NENHUMA]

### Categoria: DOCUMENTAÇÃO OBRIGATÓRIA
- ✅ Edital deve estar publicado e acessível
- ✅ Termo de Referência ou Projeto Básico obrigatório
- ✅ Parecer de adequação orçamentária exigido
- ✅ Estimativa de preços deve constar

### Categoria: PRAZOS LEGAIS
- ✅ Lei 14.133 Art. 26: prazo mínimo de 8 dias úteis para apresentação de propostas
- ✅ Prazo entre publicação e abertura não pode ser inferior
- ✅ Para aditivos: observar prazos específicos

### Categoria: PUBLICIDADE
- ✅ Publicação no portal da entidade (Lei 14.133 Art. 32)
- ✅ Publicação em plataforma oficial de contratações
- ✅ Informações devem ser de acesso público e irrestrito

### Categoria: MODALIDADE
- ✅ Concorrência: acima de R$ 440.000 (obras/serviços engenharia) ou R$ 176.000 (outros)
- ✅ Tomada de Preços: valores inferiores
- ✅ Convite: valores menores
- ✅ Dispensas/Inexigibilidades: justificativa obrigatória

---

## [DADOS DE ENTRADA]

Forneça as seguintes informações:

```
PROCESSO: [Número/ID do processo]
ENTIDADE CONTRATANTE: [Nome]
OBJETO: [Descrição do que será contratado]
MODALIDADE: [Concorrência/Tomada de Preços/Convite/Dispensa/Inexigibilidade]
VALOR ESTIMADO: [R$ ]
DATA DE PUBLICAÇÃO: [dd/mm/aaaa]
DATA DO CERTAME: [dd/mm/aaaa]
DATA DE ABERTURA DE PROPOSTAS: [dd/mm/aaaa]
LOCAL DO EDITAL: [URL ou local físico]

DOCUMENTOS ANEXADOS:
- [ ] Edital
- [ ] Termo de Referência
- [ ] Projeto Básico
- [ ] Parecer Orçamentário
- [ ] Outros: _________

OBSERVAÇÕES INICIAIS: [Adicione qualquer informação relevante]
```

---

## [FORMATO OBRIGATÓRIO DE RESPOSTA]

Responda EXATAMENTE assim (SEM ALTERAÇÕES):

```
═══════════════════════════════════════════════════════════════
        VALIDAÇÃO BÁSICA - LEI 14.133/2021
        Data da Análise: [DATA ATUAL]
═══════════════════════════════════════════════════════════════

PROCESSO: [Preencher]
ENTIDADE: [Preencher]
MODALIDADE: [Preencher]
STATUS GERAL: [CONFORME / NÃO CONFORME / PENDENTE]

───────────────────────────────────────────────────────────────

📋 CHECKLIST DE VALIDAÇÃO BÁSICA

1. DOCUMENTAÇÃO OBRIGATÓRIA
   ☐ Edital publicado e acessível?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Termo de Referência ou projeto básico presente?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Parecer de adequação orçamentária presente?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

2. PRAZOS LEGAIS
   ☐ Prazo mínimo de publicação atendido (8 dias úteis)?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Prazo para apresentação de propostas adequado?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

3. PUBLICIDADE E TRANSPARÊNCIA
   ☐ Publicado no portal da entidade?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Publicado em plataforma de contratações?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

4. MODALIDADE E VALOR
   ☐ Modalidade compatível com valor do objeto?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Justificativa de dispensa/inexigibilidade (se aplicável)?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

5. REQUISITOS FORMAIS
   ☐ Identificação clara da entidade contratante?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Objeto claramente descrito?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

   ☐ Critério de julgamento definido?
   Status: [ ] CONFORME  [ ] NÃO CONFORME  [ ] PENDENTE
   Observação: _________________________________

───────────────────────────────────────────────────────────────

📊 RESULTADO GERAL

Total de Itens Conformes: ____ / 13
Total de Itens Não Conformes: ____
Total de Itens Pendentes: ____

STATUS GERAL:
[ ] CONFORME - Todos os itens básicos OK
[ ] NÃO CONFORME - Existem problemas críticos
[ ] PENDENTE - Necessário mais informações

───────────────────────────────────────────────────────────────

⚠️ OBSERVAÇÕES CRÍTICAS (Problemas encontrados):
[LISTAR AQUI]

───────────────────────────────────────────────────────────────

✅ PRÓXIMO PASSO:
Use o PROMPT 02 para análise de compliance mais profunda.

╔═══════════════════════════════════════════════════════════════╗
║ FIM DA VALIDAÇÃO BÁSICA                                       ║
╚═══════════════════════════════════════════════════════════════╝
```

---

## [IMPORTANTE]

**Este prompt foi testado e otimizado para:**
- Não deixar passar validações críticas
- Manter formato consistente
- Ser rigoroso na análise
- Preparar para análises posteriores

**Se o ChatGPT alterar o formato:**
- Responda: "Mantenha EXATAMENTE o template. Não altere nada."
- Cole o prompt novamente
- Reforce: "Preencha apenas os campos, não mude a estrutura"

---

## ✅ PRONTO PARA USAR

1. Copie este prompt inteiro
2. Cole no ChatGPT
3. Adicione os dados do seu processo
4. Envie
5. O ChatGPT preencherá o template

**Dúvidas?** Veja [README-PROMPTS.md](./README-PROMPTS.md)
