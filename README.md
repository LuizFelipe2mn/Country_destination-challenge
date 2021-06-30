# Country_destination-challenge

O objetivo do exercicio é predizer para que país o usuário do serviço fará sua primeira viagem. Esse label está contido na coluna ‘country_destination’. Trata-se de um problema de classifiação multi-classe. Os possíveis valores são: - NDF - US - FR - IT correspondentes a quatro possibilidades do usuário.
As outras colunas contém features do usuário, que podem ser tanto categoricas quanto numéricas.

A avaliação será feita com duas metricas:

logloss: http://scikit-learn.org/stable/modules/generated/sklearn.metrics.log_loss.html

A submissão contem um csv, contendo as probabilidades de cada label com a seguinte convenção: {'NDF': 0, 'US': 1, 'FR': 2, 'IT': 3}
