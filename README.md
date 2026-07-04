# SIACP - Sistema Inteligente de Análise de Contratações Públicas

## 📋 Descrição

Sistema de auditoria inteligente para análise de processos de licitações conforme a **Lei 14.133/2021** (Lei de Licitações e Contratos Administrativos) e decretos complementares do Estado de São Paulo.

### Objetivo
Automatizar a análise de processos de licitações, garantindo compliance total com a legislação e identificando inconsistências que possam deixar passar validações críticas.

---

## 🎯 Características Principais

✅ **Análise Estruturada** - Checklist completo de validações obrigatórias  
✅ **Prompts Otimizados** - Instruções precisas para evitar falhas de análise  
✅ **Templates Fixos** - Formato consistente que não se altera em iterações  
✅ **Separação de Responsabilidades** - Validação desacoplada da formatação  
✅ **Documentação Completa** - Guias, exemplos e referências legais  
✅ **Versionamento** - Histórico de todas as mudanças e melhorias  

---

## 📁 Estrutura do Projeto

```
SIACP/

README.md

SIACP-CORE/
    00-CONSTITUICAO.md
    01-METODOLOGIA.md
    02-FLUXO.md
    03-REGRAS.md
    04-RESTITUICAO.md
    05-CERTIFICACAO.md

SIACP-BASE/
    Lei14133.md
    Decretos-SP.md
    Jurisprudencia-TCU.md
    Jurisprudencia-TCESP.md
    Pareceres-CJPM.md
    PGE-SP.md
    Compras-SP.md
    CADTERC.md

SIACP-MISSOES/
    01-Bens-Comuns.md
    02-Servicos-Comuns.md
    03-Obras-Engenharia.md
    04-Outsourcing.md
    05-Contratacao-Direta.md
    06-SRP.md
    07-Credenciamento.md
    08-Gestao-Contratual.md
    09-Planejamento.md

SIACP-TEMPLATES/
    template-checklist.json
    template-analise.json
    template-restituicao.md
    template-certificacao.md

SIACP-EXEMPLOS/

SIACP-CHANGELOG/

## 🚀 Como Usar

### 1️⃣ **Começar Rápido**
Leia o [GUIA-RAPIDO.md](./GUIA-RAPIDO.md) para instruções passo a passo.

### 2️⃣ **Copiar um Prompt**
- Abra a pasta `prompts/`
- Copie o conteúdo do prompt desejado
- Cole no ChatGPT
- Siga as instruções do prompt

### 3️⃣ **Usar Templates**
- Abra a pasta `templates/`
- Use o template apropriado para sua análise
- O ChatGPT deve preencher o template, sem alterações

### 4️⃣ **Consultar Documentação**
- Veja `docs/` para referências legais
- Veja `exemplos/` para ver como funciona

---

## 📚 Conteúdo Principal

| Arquivo | Descrição |
|---------|-----------|
| [Prompts](./prompts/README-PROMPTS.md) | Instruções otimizadas para análise |
| [Templates](./templates/) | Estruturas fixas para respostas |
| [Documentação Legal](./docs/Lei-14133-2021.md) | Referência da Lei 14.133 |
| [Exemplos](./exemplos/) | Casos de uso reais |

---

## 🔍 O Que Este Sistema Faz

### ✅ Validações Realizadas:

- **Conformidade Legal** - Atende Lei 14.133/2021?
- **Documentação** - Todos os documentos obrigatórios presentes?
- **Prazos** - Prazos legais foram respeitados?
- **Transparência** - Processo foi transparente?
- **Igualdade** - Todos os licitantes foram tratados igualmente?
- **Publicidade** - Divulgação adequada?
- **Regulamentação** - Segue decretos complementares de SP?

---

## 💡 Diferencial

🎯 **Prompts otimizados** que forçam o ChatGPT a:
- Não deixar passar validações críticas
- Manter formato consistente
- Separar análise de formatação
- Usar checklists estruturados

---

## 📞 Como Contribuir

Encontrou um erro? Quer melhorar um prompt? 

1. Abra uma [Issue](../../issues)
2. Ou faça um [Pull Request](../../pulls)

---

## 📄 Licença

Este projeto é de código aberto e pode ser usado livremente.

---

## 🎓 Referências

- [Lei 14.133/2021 - Lei de Licitações e Contratos](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14133.htm)
- [Decretos Complementares - São Paulo](https://www.saopaulo.sp.gov.br)

---

**Versão:** 1.0  
**Última atualização:** Julho 2026  
**Autor:** rogalpe-prog
