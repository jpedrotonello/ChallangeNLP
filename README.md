# Desafio Processamento de Linguagem Natural

Para este desafio, foi criada uma máquina preditiva capaz de classificar mensagens de SMS para decidir se a mensagem deve ser bloqueada ou não.
O modelo preditivo usado atingiu uma acurácia de 98,8%, tendo a seguinte matriz de confusão:
<br>
| 268 | 2   |
|-----|-----|
| 12  | 918 |

Falsos positivos (FP): 2 <br>
Falsos negativos (FN): 12 <br>
Verdadeiros positivos (VP): 268 <br>
Verdadeiros negativos (VN): 918 <br>

Estes números foram obtidos através dos dados do arquivo train_data.csv. Este arquivo possui 6000 mensagens com a devida classificação ("ok" ou "bloqued"). <br>
Destes 6000 registros, 80% deles foram separados para treino e 20% para o teste da máquina preditiva, obtendo-se uma acurácia de 98,8%. <br>
O mesmo modelo de máquina preditiva foi treinado com os 6000 registros do arquivo train_data.csv para ser aplicado nos registros do arquivo validation_data.csv. Não podemos ter um resultado de acurácia para os registros do arquivo de validação, pois as mensagens não foram previamente classificadas, impossibilitando uma predição supervisionada.
