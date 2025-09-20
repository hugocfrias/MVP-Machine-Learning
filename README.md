# MVP-Machine-Learning

O Conjunto de Dados de 'Mental Health and Lifestyle Habits Dataset (2019-2024)' é uma coleção abrangente de dados que visa compreender como diversos fatores de estilo de vida afetam o bem-estar mental. Esta base de dados captura aspectos como rotinas de exercícios, hábitos alimentares, padrões de sono, níveis de estresse e interações sociais, além de informações demográficas.

O objetivo é identificar 'níveis de stress e bem-estar' de acordo com hábitos do cotidiano.

Podemos segregar os diferentes níveis de stress e bem-estar de acordo com as aferições de horas de sono, horas de trabalho e horas em telas diários, por exemplo?

Há algum padrão facilmente de ser identificado apenas com uma análise gráfica?

De maneira empírica, pela natureza dos atributos do dataset original, creio que há relação entre alguns desses atributos (exemplos: horas de sono vs horas trabalhadas / horas de sono vs horas de tela).

Atributos do Dataset O dataset 'Mental Health Lifestyle' possui 3000 instâncias, de maneira balanceada em relação aos atributos categóricos (Países, Gêneros, Tipo de Dieta etc). No total, possui 12 atributos:

---

>**1. Country:** País do respondente (Australia, Brazil, Canada, Germany, India, Japan, USA) Age: Idade do respondente (Anos);

>**2. Gender:** Identidade de gênero do respondente (Female, Male, Other) 

>**3. Exercise Level:** Nível de exercício físico do respondente (High, Low, Moderate) 

>**4. Diet Type:** Classificação da dieta do respondente (Balanced, Junk Food, Keto, Vegan, Vegetarian)

>**5. Sleep Hours:** Horas de sono diária do respondente (Horas)

>**6. Stress Level:** Nível de stress do respondente (High, Low, Moderate)

>**7. Mental Health Condition:** Condição de saúde mental do respondente (Anxiety, Bipolar, Depression, None, PTSD)

>**8. Work Hours per Week:** Horas de trabalho diária do respondente (Horas)

>**9. Screen Time per Day:** Tempo de tela diária do respondente (Horas)

>**10. Social Interaction Score:** Pontuação de interação Social do respondente (Escala 1-10)

>**11. Happiness Score:** Pontuação de Felicidade do respondente (Escala 1-10)

---

Temos um problema foi identificado como do tipo de **classificação supervisionada**. De acordo com os atributos numéricos (horas de sono, horas trabalhadas, idade, score de felididade etc), o objetivo é a previsão dos '**níveis de stress**' e  bem-estar' dos indivíduos.
