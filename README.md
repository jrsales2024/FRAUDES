# FRAUDES
DETECÇÃO DE FRAUDES
Conclusão da Comparação:

O modelo Random Forest demonstrou um desempenho muito superior em termos de Precisão e F1-Score para a classe de fraude (Classe 1). Enquanto a Regressão Logística teve um recall muito maior, sua precisão extremamente baixa (0,07) fez com que a maioria das variações de fraude fossem, na verdade, transações legítimas, gerando muitos alertas falsos. O Random Forest consegue um bom recall (0,83) com uma precisão muito mais alta (0,84), resultando em um F1-Score muito mais robusto (0,83 vs 0,14).



Além disso, o Random Forest alcançou uma Acurácia perfeita (1,00) e um AUC mais alto (0,97), estabelecendo uma melhor capacidade geral de distinção entre as classes.



Embora o Random Forest tenha mais falsos positivos (16 vs 9) e falsos negativos (17 vs 9) em termos absolutos nesta execução específica com a nova divisão, sua capacidade geral de balancear resultados e recall é visivelmente melhor, como demonstrado pelo F1-Score e AUC.



Concluí a comparação entre os modelos de Regressão Logística e Random Forest. O Random Forest demonstrou um desempenho significativamente melhor na detecção de fraudes após a engenharia de recursos e o rebalanceamento dos dados.
