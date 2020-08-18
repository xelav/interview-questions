# Data Science Interview Questions

## Statistics

- Матожидание, дисперсия суммы случайных величин и случайной величины с коэффициентом
- ЦПТ, закон больших чисел
- Правило трёх сигм
- Распределения с тяжелыми хвостами. Примеры, и в чем их проблема?
- Как подсчитать матожидание выборки от распределения с тяжелыми хвостами?
- Какие статистические тесты знаешь? Их предположения
- Отличие параметрических тестов от непараметрических

https://www.healthknowledge.org.uk/public-health-textbook/research-methods/1b-statistical-methods/parametric-nonparametric-tests#:~:text=Parametric%20tests%20are%20those%20that,used%20for%20non%2DNormal%20variables


- Ошибки первого и второго рода
- Что такое p-value?
- Предположения линейной модели
- Теорема Байеса. Примеры, когда она важна
- R statisic
- If we will add a random noise feature to a linear model will R statistic on train improve? 
- Ковариация. Как связана независимость двух случайных величин и нулеввая ковариация?
- Корреляция. Пирсон и Спирмен. V-коэффициент Краммера
- Как подсчитать связь категориальной переменной и непрервыной?
- Чему будет равна ковариция случайных величин X и X^2?
- Дисперсия суммы двух зависимых величин

## Data Science

- Алгоритмы классификации и регрессии
- В каких случаях можно использовать линейные алгоритмы?
- Почему бутстрап-алгоритмы настолько хороши?
- Метрики качества
- Про AUC ROC. Преимущества, как строится, в чем смысл.
- Что такое бутстрапинг
- Почему ансамблирование работает? Bias-Variance tradoff
- Переобучается ли RandomForest с ростом количества деревьев?
- Как уменьшить корреляцию алгоритмов?
- Валидация, зачем и как
- Алгоритмы кластеризации
- Методы регуляризации (в нейронных сетях и обычных алгоритмов)
- Прикол L1 регуляризации и её объяснение
- Техники визуализации данных
- Техники генерации фичей
- Мешает ли линейным моделям корреляция признаков? Методы обучения линейных моделей. Проблемы точного решения и их решения
- Отличие mean и average
- Как строится ROC кривая. Что означают её оси
- Постановка задачи линейной регрессии и основные предположения. Функция потерь и методы оптимизации
- Логистическая регрессия
- Можем ли использовать ММП для регрессии и среднеквадратичную ошибку для логистической регрессии?
- Решающие деревья
- SVM. Kernel Trick
- Bayesian vs frequentist probability interpretations
- Методы обработки категориальных переменных
- EM Algorithm. Gaussian Mixture Model
- K-Means
- KNN
- PCA
- SVD
- ExtraTrees
- Hyper parameters search
- Time serires data. (S)ARIMA
- Фильтры с временными рядами
- Как выявить нелинейную зависимость между двумя выборками. Тест хи-квадрат и Колмогорова-Смирнова

## Neurokeks

- Backpropogation. Chain rule
- Optimizers
- Activation functions
- Dataset augmentation
- Initialization
- Batcnorm layer. Why it works. Train and validation
- Dropout layer. Why it works. Train and validation
- If we will decrese input size of simple CNN network (without linear layers) by two times, how will change number of trainable params? What if there is linear layers?
- Task of language modeling
- Classic NLP tasks when using recurrent neural models
- Attention, Transformers
- BERT. What it accepts as input and what is its outputs
- CNN networks. Typical architecture
- Network finetuning for CNN networks
- Residual connections in CV models
- Can we apply Dropout layers for CNN networks?
- Нейросеть с двумя линейными "широкими" слоями способна аппроксимировать любую гладкую функцию. Почему мы используем вместо широких глубокие сети?
- Vanishing and exploding gradients