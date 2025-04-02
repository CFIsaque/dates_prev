# 📌Algoritmo de previsão de sucesso em encontros
## 📖Descrição
Este projeto é um algoritmo de classificação supervisionada utilizando Árvore de Decisão para prever a probabilidade de uma pessoa ter um date bem-sucedido com base em seu histórico de conversas e encontros.

## 🚀 Tecnologias Utilizadas
🔹Python

🔹Numpy

🔹Pandas 

🔹Scikit-Learn

## 📊  Como o algoritmo funciona?
O modelo é treinado com um conjunto de dados que contém informações sobre conversas passadas e se esses contatos resultaram em encontros - e caso resultou - se o encontro foi bom ou ruim. Ele aprende a identificar padrões e a classificar novos casos com base em características específicas. Utilizei um modelo de Árvore de Decisão, que divide os dados em ramificações com base em perguntas sobre as features, classificando o resultado final em uma das três categorias de destino.

Em resumo:

🔹O algoritmo analisa os dados históricos de dates.

🔹 Ele aprende os padrões que levam a um date bom, ruim ou inexistente.

🔹 Ao ser apresentado um novo perfil, ele retorna a probabilidade de cada categoria.

## 🏷️ Features e Target
O modelo utiliza quatro variáveis/características para a previsão:

🔹 Confiança (Nível de autoconfiança da pessoa, de 1 a 10)

🔹 Senso de humor (Capacidade de fazer o outro rir, de 1 a 10)

🔹 Comunicação (Qualidade das interações por mensagem, de 1 a 10)

🔹 Gostos (Afinidade de gostos pessoais, de 1 a 10)

Para a saída, o modelo classifica a situação em três possíveis resultados:

🔹 Sem date – A interação não resultou em um encontro.

🔹 Date ruim – O date aconteceu, mas foi uma experiência negativa.

🔹 Date ótimo – O date aconteceu e foi um sucesso.
#
## 📸 Imagens
### árvore de decisão do modelo treinado
![image](https://github.com/user-attachments/assets/22221dd9-9fc1-449a-8918-2b7df34379eb)
### Output com novo conjunto de dados de três pessoas diferentes
![image](https://github.com/user-attachments/assets/f2bc11a2-038d-49ee-8519-0943c983554f)
#
## 🔍 Aprendizados e Insights
📌 O modelo conseguiu prever os resultados dos encontros com base em padrões comportamentais.

📌  A árvore de decisão não apenas confirma padrões óbvios, mas também revela relações inesperadas. Nesse caso, mesmo que confiança e afinidade por gostos sejam considerados fatores positivos, a análise mostrou que quando confiança > 6.5 e afinidade < 4.5, a probabilidade de um date ruim é alta.

📌 Próximos passos: Expansão do conjunto de dados e implementar técnicas avançadas de feature engineering.

