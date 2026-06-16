# Skill: Monitoramento de Mercado de Grãos

Esta skill capacita a Aurora a monitorar e analisar continuamente o mercado de grãos, com foco em soja e milho, tanto no cenário nacional (Brasil) quanto internacional. Ela utilizará fontes de informação confiáveis para manter seu conhecimento atualizado e fornecer insights proativos a Arthur Emanuel Forster e à Comércio de Cereais Forster LTDA.

## 🎯 Objetivo

Manter a Aurora sempre atualizada sobre:
- Cotações de soja e milho (bolsas nacionais e internacionais).
- Notícias e análises de mercado (oferta, demanda, clima, geopolítica).
- Políticas de exportação e importação do Brasil.
- Fatores que impactam os preços e a logística de grãos.

## ⚙️ Mecanismo de Funcionamento

A Aurora executará as seguintes ações de forma periódica ou sob demanda:

1. **Coleta de Dados:**
   - Acessar portais de notícias agrícolas (e.g., Notícias Agrícolas, Reuters, Bloomberg Commodities).
   - Consultar relatórios de instituições como Embrapa, CNA Brasil, IPEA.
   - Monitorar cotações em bolsas de commodities (CBOT, B3).
   - Buscar dados de órgãos governamentais sobre exportação/importação.

2. **Análise e Síntese:**
   - Processar as informações coletadas para identificar tendências, anomalias e eventos significativos.
   - Correlacionar dados de clima, política e economia com o movimento dos preços.
   - Gerar resumos executivos e alertas sobre mudanças importantes no mercado.

3. **Atualização da Base de Conhecimento:**
   - Integrar novas informações e insights ao seu módulo de memória persistente, refinando o documento `docs/market_intelligence/brazilian_grain_market.md` ou criando novos documentos de análise.

4. **Comunicação Proativa:**
   - Notificar Arthur Emanuel Forster sobre eventos críticos, oportunidades ou riscos identificados no mercado de grãos.
   - Responder a perguntas específicas sobre o mercado, fornecendo dados e análises embasadas.

## 🛠️ Ferramentas Utilizadas (Internas do Hermes Agent)

- **Web Search:** Para buscar notícias e artigos atualizados.
- **Webpage Extract:** Para extrair conteúdo textual de páginas relevantes.
- **Memory System:** Para armazenar e recuperar informações de longo prazo.
- **Context Files:** Para referenciar documentos como `docs/market_intelligence/brazilian_grain_market.md`.

## ⏰ Frequência de Execução

- **Padrão:** Diariamente, no início do dia útil, para um panorama geral.
- **Sob Demanda:** Acionada por Arthur para análises específicas ou em resposta a eventos de alta volatilidade.

## ⚠️ Considerações

- A Aurora priorizará fontes de informação confiáveis e verificadas.
- A interpretação dos dados será sempre contextualizada com os objetivos da Comércio de Cereais Forster LTDA.

---
*Skill desenvolvida por Manus AI, sob a supervisão de Arthur Emanuel Forster (Notty0001).*
