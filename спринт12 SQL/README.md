***Викишоп

Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

Постройте модель со значением метрики качества F1 не меньше 0.75.

Лемматизация (WordNetLemmatizer), tf-idf, LogisticRegression, KNeighborsClassifier, LGBMClassifier.

Лучшие результаты показала модель LogisticRegression f1= 0.7373612823674477 с параметрами: C= 1 ; max_iter = 10 ; class_weight = balanced. KNeighborsClassifier лучший результат F1: 0.2848114598693912. LGBMClassifier F1= 0.6148771235362032.