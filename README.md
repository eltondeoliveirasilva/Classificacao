# Classificacao

O que é classificação em Machine Learning?

Classificação é a tarefa de identificar a qual categoria ou classe uma amostra pertence, com base nos dados de entrada e características disponíveis. É um dos principais problemas abordados em aprendizado de máquina supervisionado.

Em problemas de classificação, os dados de entrada são divididos em dois grupos:


Dados de treinamento: usados para treinar o modelo de Machine Learning, identificando padrões que mapeiam os dados de entrada para as categorias desejadas.

Dados de teste: usados para testar o modelo treinado, avaliando sua capacidade de generalização para dados nunca vistos antes.


O objetivo é desenvolver um modelo que seja capaz de receber novos dados de entrada e corretamente prever a qual classe eles pertencem, entre um conjunto pré-definido de classes.

Alguns exemplos de problemas de classificação incluem:


Identificar se um e-mail é spam ou não
Diagnosticar se um paciente tem uma certa doença com base nos sintomas
Reconhecer dígitos manuscritos (0 a 9) em imagens
Classificar transações bancárias como fraude ou não fraude
Identificar o idioma em que um texto está escrito
Etiquetar o conteúdo de uma imagem (cachorro, gato, pássaro etc)

A seguir, veremos com mais detalhes os principais algoritmos de classificação e como eles funcionam.

Principais algoritmos de classificação

Existem vários algoritmos de Machine Learning que podem ser usados para classificação. Os mais populares incluem:

Árvores de Decisão

Árvores de decisão funcionam dividindo recursivamente o espaço de dados em regiões com o maior grau de homogeneidade possíveis. Cada divisão gera um nó da árvore, e em cada nó é tomada uma decisão para dividir o espaço.

As árvores de decisão são fáceis de entender e visualizar, trabalham bem com dados categóricos e numéricos, e realizam embeddings de features automaticamente. Por outro lado, podem facilmente overfittar se não forem controladas.

árvore de decisão

Alguns algoritmos populares de árvores de decisão incluem ID3, C4.5 e CART.

Naive Bayes

O Naive Bayes é baseado no Teorema de Bayes e assume que as features são independentes entre si. Isso simplifica os cálculos, permitindo construir classificadores muito rápidos que trabalham bem em problemas do mundo real.

O algoritmo calcula as probabilidades de uma amostra pertencer a cada classe e faz a predição considerando a classe com maior probabilidade. Funciona bem com datasets pequenos e é fácil de interpretar.

Máquinas de Vetor de Suporte (SVM)

SVM é um algoritmo que constrói um hiperplano para separar as classes no espaço de dados. O objetivo é definir uma margem máxima entre as classes, o que torna o classificador robusto para separar novos dados.

As SVM trabalham bem com datasets complexos e podem lidar com milhares de features sem overfitting. Por outro lado, o tempo de treinamento pode ser alto para datasets grandes.

svm

Redes Neurais

As redes neurais artificiais tentam simular o funcionamento do cérebro humano, compostas por camadas de neurônios interconectados que enviam sinais uns aos outros.

Elas aprendem a partir de grandes quantidades de dados, extraindo padrões complexos neles. Destacam-se em problemas como visão computacional e processamento de linguagem natural.

rede neural

Random Forest

O Random Forest constrói uma floresta de árvores de decisão, treinando cada uma com uma amostragem aleatória dos dados. Na predição, o resultado é dado pela votação das árvores individuais.

Essa abordagem corrige problemas como overfitting e também produz classificadores muito robustos e precisos. É um dos algoritmos mais populares atualmente.

Avaliação de modelos de classificação

Para avaliar a qualidade de um modelo de classificação, existem algumas métricas comumente utilizadas, como:

Acurácia: proporção de predições corretas em relação ao total.

Precisão: proporção de predições positivas corretas em relação a todas as predições positivas.

Revocação: proporção de predições positivas corretas em relação ao total de casos positivos.

Curva ROC: demonstra o equilíbrio entre a taxa de verdadeiros positivos e falsos positivos em diversos limiares.

Matriz de confusão: tabela com o desempenho do classificador para cada classe.

Analisar essas métricas é fundamental para identificar possíveis problemas no modelo, como overfitting, e entender onde ele precisa melhorar.

Além disso, as curvas de aprendizado, que mostram a evolução da acurácia durante o treinamento, também são úteis para diagnosticar overfitting ou subajuste.

Casos de uso da classificação

A classificação tem aplicações em praticamente todos os setores e áreas que lidam com grandes volumes de dados. Alguns casos de uso incluem:

Detecção de fraudes: classificar transações como fraudulentas ou legítimas com base no comportamento do usuário.

Diagnóstico médico: com base nos sintomas e exames, prever a probabilidade do paciente ter uma certa doença.

Filtragem de spam: classificar e-mails como spam ou não spam automaticamente.

Recomendação de produtos: com base no histórico e perfil do usuário, sugerir produtos que ele deve gostar.

Análise de sentimentos: classificar a polaridade de textos (positivo, negativo, neutro).

Reconhecimento facial: identificar e distinguir rostos humanos em imagens e vídeos.

Classificação de objetos: identificar e categorizar objetos presentes em imagens.

Essas são apenas algumas das muitas aplicações da classificação na ciência de dados hoje.
