# Анализ изменения стоимости медицинского обслуживания

### Подходы и инструменты

**Предобработка данных**: `python`, `pandas`, `numpy`. Обработка данных, дубликаты, пропуски, названия столбцов, категоризация, декомпозиция, `feature_generation`.

**EDA**: `matplolib`, `seaborn`: `histogram`, `boxplot`, `scatterplot`, `pie_chart`, `heatmap`, `категоризация`, `chi2_contingency`, `pingouin`, `statsmodels.formula`.

**Описание данных**
* record_id- уникальный идентификатор строки данных
* service_date - дата оказания медицинской услуги
* service_name - наименование медицинской услуги
* service_number - количество услуг
* service_amount - сумма выплат (стоимость оказанных услуг в рублях)
* insured - уникальный идентификатор пациента
* sex_id - пол пациента
* age_for_service_date - возраст пациента
