# 📌 Planejamento de Renda Passiva

Este repositório contém o projeto **Planejamento de Renda Passiva**, estruturado para documentar e versionar estratégias de investimento periódico com foco em geração de renda passiva.  
O objetivo é oferecer uma visão executiva, quantitativa e prática sobre como construir patrimônio ao longo de 6 anos (Jan/2025 – Jan/2031), integrando análises, métricas e projeções visuais.

---

## 🎯 Objetivos
- Elaborar um plano estruturado de renda passiva.  
- Definir alocação trimestral de investimentos em FIIs, ações de dividendos, Tesouro IPCA/SELIC e LCI/LCA.  
- Estimar renda passiva por trimestre e patrimônio acumulado ao final do período.  
- Apresentar riscos principais e estratégias de mitigação.  
- Integrar métricas financeiras (Dividend Yield, ROE, Vacância, Duration, Liquidez, Volatilidade).  

---

## 📂 Estrutura do Projeto
O conteúdo segue **4 etapas sequenciais**:

1. **Sumário Executivo**  
   - Alocação proposta  
   - Renda passiva estimada por trimestre  
   - Principais riscos e mitigação  

2. **Tabelas por Classe de Ativo**  
   - Top 10 ativos por classe  
   - Score calculado com fórmula e pesos  
   - Justificativa breve (méritos e riscos)  

3. **Gráficos e Projeções**  
   - FIIs/Ações: histórico de dividendos, distribuição mensal, preço vs média anual  
   - Tesouro: curva de juros, sensibilidade a variação de 100 bps  
   - LCI/LCA: taxa vs prazo, cenários conservador/base/otimista  

4. **Notas Metodológicas**  
   - Fórmulas, pesos, fontes e observações em tabela consolidada  

---

## 📊 Critérios de Seleção
- Exclusão de ativos com baixa liquidez (FIIs < R$ 500k/dia, Ações < R$ 1M/dia).  
- Limite de concentração: máx. 10% por ativo e 30% por setor.  
- Ajuste de dividendos por eventos societários.  
- Separação de dividendos extraordinários.  

---

## 🧮 Score Composto
Exemplo de fórmula aplicada:

**FIIs**  


\[
Score\_{FII} = (DY\_{5anos} \cdot 0,30) + (Consistência \cdot 0,20) + (Vacância \cdot 0,15) + (P/VP \cdot 0,15) + (Liquidez \cdot 0,10) + (Volatilidade \cdot 0,10)
\]



**Ações**  


\[
Score\_{Ação} = (Dividend Yield \cdot 0,25) + (Payout Ratio \cdot 0,15) + (CAGR\_{5anos} \cdot 0,20) + (ROE \cdot 0,20) + (Dívida Líquida/EBITDA \cdot 0,10) + (Liquidez \cdot 0,10)
\]



---

## 📈 Resultado Esperado
- Relatório executivo modular e robusto.  
- Patrimônio acumulado ao final de **Jan/2031**, com distribuição percentual por classe de ativo.  
- Resumo executivo final em até 150 palavras, destacando patrimônio total, concentração e riscos principais.  

---

## 📌 Público-Alvo
Investidores individuais e gestores que buscam estruturar planos de renda passiva com clareza, métricas objetivas e visão de longo prazo.

---

## 📑 Licença
Este projeto está sob a licença [MIT](LICENSE).  
Sinta-se livre para usar, adaptar e compartilhar, mantendo os créditos.

---
