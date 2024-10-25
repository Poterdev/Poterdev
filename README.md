# Análise de Monitoramento de Máquinas

## 📊 Visão Geral
Este projeto implementa uma análise abrangente de dados de desempenho de máquinas, focando na identificação e visualização de variáveis-chave que impactam falhas mecânicas. A análise inclui visualização de pressão hidráulica, vibrações, temperatura do spindle e forças de corte para otimizar operações e prevenir falhas.

## 🔍 Principais Funcionalidades
- Visualização avançada de dados usando Seaborn e Matplotlib
- Análise estatística de parâmetros críticos da máquina
- Análise de correlação entre variáveis operacionais
- Análise de frequência de falhas por máquina
- Recomendações abrangentes para melhoria de processo

## 📈 Principais Visualizações
1. **Análise de Variáveis Críticas**
   - Boxplot da distribuição da Pressão Hidráulica
   - Gráfico de dispersão da correlação entre Vibração da Ferramenta e do Spindle
   - Gráfico de densidade da Temperatura do Spindle
   - Gráfico de dispersão da Força de Corte vs Pressão Hidráulica

2. **Análise de Falhas**
   - Gráfico de barras de frequência de falhas por máquina
   - Mapa de calor de correlação entre variáveis significativas

## 🛠️ Dependências
- pandas
- seaborn
- matplotlib
- numpy

## 📋 Variáveis Monitoradas
- Pressão Hidráulica (bar)
- Vibração da Ferramenta e do Spindle (µm)
- Temperatura do Mancal do Spindle (°C)
- Força de Corte (kN)

## 💡 Recomendações de Melhoria

### 1. Sistema de Monitoramento Prioritário
- Foco no monitoramento da pressão hidráulica e vibrações
- Estabelecimento de limites de controle baseados nas distribuições observadas
- Implementação de alertas precoces

### 2. Manutenção Preventiva
- Utilização da temperatura do spindle como indicador principal
- Monitoramento de tendências de vibração
- Estabelecimento de intervalos de manutenção baseados nos padrões observados

### 3. Otimização de Processo
- Ajuste da força de corte e pressão hidráulica
- Manutenção da operação dentro das faixas ideais identificadas
- Implementação de controles mais rigorosos nas máquinas com maior frequência de falhas

## 📊 Análise Estatística
O projeto inclui análise estatística detalhada das variáveis principais, incluindo:
- Cálculos de média e desvio padrão
- Análise de distribuição
- Estudos de correlação entre parâmetros operacionais

## 🤔 Análises Adicionais
Para análises adicionais ou aspectos específicos dos dados, estarei implementando com o decorrer do tempo para gerar mais conteudos, o tratamento de outlier e seus impactos, tratamento de dados nulos e engenharia de recursos.
Outra analise que conseguimos é conseguir por metodo de clusterização, as zonas de configuração segura, da pressão hidráulica e configurações de corte.
