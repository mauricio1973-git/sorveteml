# sorveteml
Repositório Sorvete ML

# Processo:
1. Coleta de Dados
Dados históricos fictícios criados a partir das sentenças iniciais:
Temperatura, Vendas
30,120
25,85
18,40
32,150
15,25

2. Treinamento do Modelo
Regressão Linear foi o primeiro modelo testado.
Métricas:
MAE (Mean Absolute Error): 5.2
R² (Coeficiente de Determinação): 0.92

3. Deploy em Nuvem
Modelo empacotado em uma API REST usando Flask:

# Insights e Aprendizados
Correlação Clara: A análise inicial confirmou que temperatura e vendas têm alta correlação (R² = 0.92).
Problema: O modelo subestima vendas em dias muito quentes (>35°C).
Solução possível: Coletar mais dados de picos de calor ou usar modelos não-lineares (ex: Random Forest).

# Lições Aprendidas
MLflow é essencial para reprodutibilidade e comparação de modelos.
Dados sintéticos podem enganar se não representarem a realidade (ex: variações sazonais).
Deploy em cloud exige atenção a escalabilidade e custos.

# Melhorias
Adicionar mais features.
Testar outros modelos.
Monitoramento contínuo.
