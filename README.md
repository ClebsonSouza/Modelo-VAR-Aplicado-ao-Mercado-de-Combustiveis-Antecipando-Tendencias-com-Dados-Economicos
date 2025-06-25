# Modelo-VAR-Aplicado-ao-Mercado-de-Combustiveis-Antecipando-Tendencias-com-Dados-Economicos

## 📊 Resumo Objetivo do Projeto

Este projeto aplica o modelo VAR (Vector Autoregressive) para analisar e prever o comportamento do preço médio semanal da gasolina comum na cidade de João Pessoa entre 2020 e 2024.

Foram utilizadas três séries temporais semanais com valores nominais (todos na mesma base do Real Brasileiro):

Preço da Gasolina (João Pessoa – fonte: ANP)

Cotação do Dólar (USD/BRL) — fonte: Investing.com

Cotação do Petróleo Brent (futuros) — fonte: Investing.com

###❓ Problema de Negócio

Como antecipar aumentos no preço da gasolina para melhorar a gestão de estoque e repasse de preços em redes de postos de combustíveis em João Pessoa?

### ✅ Solução Prática com Base no Modelo

O modelo VAR mostrou que o preço do petróleo Brent é o principal fator causal que afeta diretamente o preço da gasolina.

A cotação do dólar teve influência fraca e inconsistente sobre a gasolina.

A resposta ao impulso confirmou que choques no Brent geram efeitos positivos no preço da gasolina nos períodos subsequentes.

### 💡 Aplicação Estratégica

Implementar um sistema de monitoramento semanal do Brent, alimentando o modelo VAR para prever o preço da gasolina com até 2 a 3 semanas de antecedência.

Com base nas previsões, redes de postos podem:

Ajustar os níveis de estoque estrategicamente

Planejar políticas de repasse de preços ao consumidor

Minimizar perdas causadas por atrasos nos reajustes
