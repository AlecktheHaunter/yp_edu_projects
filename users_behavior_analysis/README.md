# Исследование поведения пользователей интернет-магазина

## Цели и задачи проекта

**Результат проекта:**
Оценена корректность проведения А/В теста и сделан статистически обоснованный вывод о влиянии измененных шрифтов на воронку продаж.

В процессе анализа выполнено:
- проведена предобработка данных,
- построена воронка продаж,
- выполнен статистический анализ различий групп в А/А/В тесте.

**Описание исходных данных**: 
файл с логами, содержащий следующие данные:
- название события;
- id пользователя;
- время события;
- отнесение события к одной из групп A/A/B: коды 246, 247, 248 соответственно.

**Цель проекта** - изучить поведение пользователей он-лайн магазина по продаже продуктов питания, изучить воронку продаж.

**Задачи проекта:**
- изучить воронку продаж;
- исследовать влияние изменения шрифтов в приложении на поведение пользователей с помощью исследования результатов A/A/B экспертименты.

**Теги:**

предобработка данных, EDA, событийная аналитика, продуктовые метрики, статистический тест, визуализация данных.


## Библиотеки

import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import math
import seaborn as sns
import scipy.stats as st
import warnings
import os
from statistics import median