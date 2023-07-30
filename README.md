# music_genre_prediction_ydx

Музыкальный стриминговый сервис "МиФаСоль" расширяет работу с новыми артистами и музыкантами, в связи с чем возникла задача -- правильно классифицировать новые музыкальные треки, чтобы улучшить работу рекомендательной системы. Для этого подготовлен датасет, в котором собраны некоторые характеристики музыкальных произведений и их жанры. Задача -- разработать модель, позволяющую классифицировать музыкальные произведения по жанрам.

Наилучший результат показал ансамбль из XGBoostClassifier, обученных в режиме one-vs-all. При этом точность детектирования большинства классов наблюдалась достаточно низкая - порядка 0.17-0.4.

Для дальнейшего развития представляется полезным использовать исходные данные треков для более детального их анализа с помощью, например, рекуррентных нейронных сетей.

При необходимости путь к папке с данными нужно заменить на ./data