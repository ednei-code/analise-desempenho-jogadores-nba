# Análise Estatística e Inferencial do Desempenho de Atletas da NBA

## 📊 Visão Geral
Este projeto realiza uma análise abrangente dos dados de jogadores da NBA, utilizando métodos estatísticos descritivos e inferenciais para compreender os fatores que influenciam o desempenho atlético nas quadras. Através de técnicas avançadas de inferência estatística, validamos hipóteses e extraímos conclusões significativas sobre o universo do basquete profissional americano.

## 🎯 Objetivo do Projeto
Explorar e analisar os dados dos jogadores da NBA para entender melhor os fatores que influenciam o desempenho e as características dos atletas, utilizando técnicas de inferência estatística para validar hipóteses e tirar conclusões robustas.

## ❓ Perguntas de Pesquisa
Esta análise busca responder às seguintes questões:

* Como se distribuem as variáveis demográficas (idade, altura, peso) e estatísticas de desempenho (pontos, rebotes, assistências)?
* Quais correlações significativas existem entre características físicas e métricas de desempenho?
* De que forma o desempenho dos jogadores evoluiu ao longo das temporadas?
* Quais franquias da NBA apresentam jogadores com métricas de performance superiores?
* Como a posição no draft da NBA se relaciona com o desempenho futuro do atleta?
* Existe alguma relação entre origem geográfica e performance nas quadras?
* Como os testes estatísticos e intervalos de confiança confirmam ou refutam nossas observações iniciais?

## 🔬 Metodologia
Esta análise foi conduzida utilizando a linguagem de programação **Python**, com foco em métodos de estatística descritiva e inferencial. As seguintes técnicas estatísticas foram aplicadas:

* **Análise Descritiva:** Utilizamos medidas de tendência central (média, mediana), dispersão (desvio padrão, variância) e visualizações (histogramas, box plots, scatter plots) para caracterizar as distribuições dos dados.

* **Teste de Mann-Whitney U:** Aplicado para comparar distribuições de amostras independentes e identificar diferenças estatisticamente significativas entre grupos (ex: comparação entre jogadores de diferentes rodadas do draft).

* **Correlação de Pearson:** Implementada para quantificar a força e direção das relações lineares entre variáveis contínuas (ex: relação entre altura e capacidade de rebote).

* **Correlação de Spearman:** Utilizada para avaliar relações monotônicas entre variáveis, oferecendo maior robustez contra outliers e captando relações não-lineares importantes.

## 📚 Fonte de Dados
O conjunto de dados utilizado contém mais de duas décadas de informações sobre jogadores da NBA, abrangendo:
- Variáveis demográficas (idade, altura, peso, local de nascimento)
- Detalhes biográficos (franquia, ano e posição no draft)
- Estatísticas de performance (jogos disputados, médias de pontos, rebotes, assistências, etc.)

Os dados foram obtidos da plataforma **Kaggle** e passaram por processos de limpeza e normalização antes da análise.

## 📁 Estrutura do Projeto
O projeto está organizado em dois Jupyter Notebooks principais:

1. **`analise_descritiva.ipynb`:** Contém toda a análise estatística descritiva, incluindo visualizações e resumos numéricos das principais variáveis.

2. **`analise_inferencial.ipynb`:** Apresenta a análise estatística inferencial, com testes de hipóteses e análises de correlação para validar conclusões e responder às perguntas de pesquisa.

## 🚀 Como Executar

### Pré-requisitos
- Python 3.8+
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scipy, statsmodels

### Instalação
```bash
# Clone este repositório
git clone https://github.com/seu-usuario/nba-player-analysis.git

# Acesse o diretório do projeto
cd nba-player-analysis

# Instale as dependências
pip install -r requirements.txt

# Execute os notebooks via Jupyter
jupyter notebook
```

## 🔮 Resultados Principais
Os resultados detalhados podem ser encontrados nos notebooks, mas algumas descobertas notáveis incluem:
- Correlações significativas entre altura e eficiência de rebote
- Evolução temporal nas médias de arremessos de três pontos
- Diferenças estatisticamente significativas no desempenho entre jogadores de diferentes posições de draft

## 👨‍💻 Autor
**Ednei Vicente** - Cientista de Dados
* E-mail: [ednei.adgpo@gmail.com](mailto:ednei.adgpo@gmail.com)
* LinkedIn: [Ednei Cunha Vicente](https://www.linkedin.com/in/ednei-cunha-vicente-551b64187/)

## 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
