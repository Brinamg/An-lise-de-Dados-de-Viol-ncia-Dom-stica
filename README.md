# Análise de Dados do Ligue 180 (2014)

## Introdução

Este repositório apresenta uma análise abrangente dos dados de violência doméstica registrados pelo serviço Ligue 180 durante o ano de 2014. A violência doméstica é um problema crítico e persistente, que afeta milhões de pessoas em todo o mundo, independentemente de gênero, classe social ou localização geográfica. Com a crescente digitalização de dados, tornou-se possível aplicar técnicas avançadas de aprendizado de máquina para identificar padrões ocultos e gerar insights que podem informar políticas públicas mais eficazes e direcionadas.

O objetivo deste estudo é utilizar algoritmos de machine learning para explorar o conjunto de dados de denúncias, a fim de compreender melhor as dinâmicas subjacentes à violência doméstica no Brasil. A análise visa não apenas identificar padrões nos dados históricos, mas também contribuir para a criação de ferramentas preditivas que possam ser usadas na prevenção e mitigação de novos casos.

## Justificativa

A violência doméstica continua a ser um dos maiores desafios sociais, com impactos profundos e duradouros nas vítimas, suas famílias e a sociedade em geral. Em 2014, o Ligue 180, um serviço crucial de suporte às vítimas no Brasil, recebeu um grande volume de denúncias, refletindo tanto a prevalência do problema quanto a necessidade urgente de respostas efetivas.

A análise detalhada desses dados é de suma importância para várias razões:

1. **Identificação de Padrões:** Entender as características dos casos registrados pode revelar fatores de risco e padrões recorrentes que não são visíveis a olho nu, mas que podem ser cruciais para a intervenção precoce.

2. **Apoio à Formulação de Políticas:** Políticas públicas informadas por dados têm maior potencial de eficácia. Ao identificar tendências e clusters de violência, é possível direcionar recursos e esforços de maneira mais estratégica, aumentando a eficiência das ações governamentais e de organizações não governamentais.

3. **Conscientização e Prevenção:** A análise dos dados pode também fornecer insights valiosos para campanhas de conscientização, ajudando a educar a população sobre os sinais de alerta e as formas de prevenção da violência doméstica.

4. **Inovação Tecnológica:** Aplicar técnicas de machine learning a dados sociais representa um avanço significativo na maneira como abordamos problemas complexos. Essa inovação não só melhora a precisão das análises, mas também abre caminho para o desenvolvimento de soluções preditivas que podem salvar vidas.

Diante da gravidade do problema e da potencial contribuição que uma análise bem conduzida pode oferecer, este estudo se justifica pela necessidade de aprofundar o conhecimento sobre a violência doméstica e fornecer subsídios para ações que visem sua erradicação.

## Fundamentação Teórica

Este estudo se baseia em conceitos fundamentais de aprendizado de máquina e análise de dados, bem como na literatura existente sobre violência doméstica e a utilização de dados para políticas públicas.

- **Aprendizado de Máquina (Machine Learning):** Utiliza-se uma série de algoritmos, incluindo Árvores de Decisão, KMeans, Redes Neurais e Regressão Logística, que permitem a construção de modelos preditivos e a identificação de padrões nos dados. Esses algoritmos são selecionados com base em sua capacidade de lidar com dados não balanceados e complexos, características comuns em conjuntos de dados de violência doméstica.

- **Violência Doméstica:** A literatura aponta que a violência doméstica é multifacetada, com diversas variáveis socioculturais e econômicas influenciando sua ocorrência. Estudos anteriores demonstram que a análise de grandes volumes de dados, como os do Ligue 180, pode revelar padrões ocultos que não são evidentes em análises tradicionais.

- **Políticas Públicas:** A fundamentação teórica também aborda o uso de dados para informar e melhorar as políticas públicas. A capacidade de prever ocorrências de violência com precisão pode auxiliar na alocação de recursos e na criação de campanhas preventivas mais eficazes.

## Metodologia

A análise foi realizada utilizando diversas técnicas de machine learning, incluindo:

- **Árvore de Decisão (Decision Tree):** Utilizada para criar um modelo preditivo que classifica os casos de violência com base em variáveis específicas.
- **KMeans:** Aplicado para identificar clusters nos dados, agrupando registros com características similares.
- **Redes Neurais:** Usadas para capturar padrões mais complexos nos dados e melhorar a precisão das previsões.
- **Regressão Logística (Logistic Regression):** Implementada para prever a probabilidade de ocorrência de determinados tipos de violência com base nas características do caso.

Os dados foram pré-processados para lidar com valores ausentes e inconsistências, e as variáveis foram selecionadas com base em sua relevância para os modelos. A avaliação dos modelos foi feita utilizando métricas como acurácia, precisão, recall e F1-score.

## Resultados

A análise dos dados de violência doméstica utilizando diferentes modelos de machine learning revelou insights valiosos:

- **Árvore de Decisão:** Identificou as variáveis mais influentes, como idade da vítima, relação com o agressor, e tipo de violência, fornecendo um modelo claro e interpretável que pode ser usado para formular políticas de intervenção direcionadas.

- **KMeans (Clustering):** Revelou a existência de clusters específicos de casos, permitindo a identificação de perfis de risco e o direcionamento de recursos para as áreas mais vulneráveis.

- **Redes Neurais:** Ofereceu a maior precisão na previsão de novos casos, capturando padrões complexos entre as variáveis. Embora menos interpretável, este modelo pode ser crucial para previsões detalhadas.

- **Regressão Logística:** Forneceu um modelo estatisticamente sólido que calcula a probabilidade de ocorrência de diferentes tipos de violência, facilitando a priorização de casos de alto risco.

Comparando os modelos, a **Árvore de Decisão** e a **Regressão Logística** se destacaram pela interpretabilidade, sendo úteis para a comunicação com formuladores de políticas. Já as **Redes Neurais** se destacaram em precisão, sendo mais adequadas para aplicações onde a exatidão é crítica. O **KMeans** foi essencial para segmentar o público-alvo de intervenções, facilitando a personalização das políticas públicas.

Esses insights podem ajudar a direcionar ações específicas para prevenir e combater a violência doméstica, além de orientar futuras pesquisas e intervenções na área.

## Contribuições

Contribuições são bem-vindas! Se você tem interesse em aprimorar esta análise ou aplicar novas técnicas de machine learning, fique à vontade para enviar um pull request ou abrir uma issue.

