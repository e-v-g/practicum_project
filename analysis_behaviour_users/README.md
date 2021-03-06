**Анализ поведения пользователей мобильного приложения**

Для проведения анализа имеется лог данных:
- название события;
- уникальный идентификатор пользователя;
- время события;
- номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

Цель проекта: определить по результатам A/A/B-теста, какой шрифт лучше использовать в приложении

В процессе выполнения проекта выполнила: предобработку данных, определила порядок, в котором проходят событий, построила воронку событий, исследовала путь пользователей до совершения покупки, сформулировала гипотезы (H0, H1) и рассчитала статистическую значимость между долями пользователей, совершающих событие, сначала для группы А1 и А 2, затем и для группы В. Так как было проведено много проверок, появилась вероятность возникновения ошибки первого рода, для снижения вероятности я применила метод Шидака. По результатам исследования сформулировала общий вывод с рекомендациями.

Использовала инструменты: Python, pandas, numpy, matplotlib, scipy.stats, math, plotly, statsmodels.
