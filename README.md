# nails_msk
# Анализ демографических данных подписчиков ВК для маникюрных салонов в Москве
## Цель исследования  
Анализ демографических характеристик подписчиков сообществ ВК, посвящённых маникюрным салонам и мастерам в Москве, с целью выявления целевой аудитории для потенциального запуска рекламы.  

## Задачи  
1. **Анализ гендерного состава подписчиков** – определить, насколько значительную долю составляют мужчины и есть ли среди них потенциальный спрос на услуги маникюра.  
2. **Возрастной анализ мужчин** – построить гистограмму возрастного распределения среди подписчиков-мужчин.  
3. **Возрастной анализ женщин** – построить гистограмму возрастного распределения среди подписчиц-женщин.  
4. **Географический анализ** – определить долю подписчиков из Москвы и других городов (по доступным данным).  
5. **Выборка целевой аудитории для интервью** – отфильтровать женщин среднего возраста из Москвы, чтобы затем по ID пригласить их на интервью.  


## Структура проекта
1. **Загрузка и подготовка данных**: Скачивание данных с ВКонтакте, их очистка и преобразование в пригодный для анализа формат.
2. **Разведочный анализ данных**: Оценка типов данных, проверка пропусков и анализ первых шагов.
3. **Визуализация**: Построение графиков и диаграмм для анализа возрастных категорий и географического положения.
4. **Фильтрация**: Отбор подписчиков для дальнейшего анализа.

## Используемые библиотеки
- `pandas` — для обработки и анализа данных
- `matplotlib` — для визуализации данных
- `vk_api` — для взаимодействия с API ВКонтакте

## Файлы в репозитории
- **vk_group_members.csv** — исходные данные с информацией о подписчиках.
- **vk_group_members_cleaned.csv** — очищенные и обработанные данные.
- **nails_msk.ipynb** — Jupyter Notebook с полным анализом и визуализациями.

### Итоги исследования: Демография подписчиков московских маникюрных салонов в ВК

**Задачи и результаты:**

1. **Анализ по полу:**  
   Женщины составляют 84% подписчиков, что подтверждает высокую заинтересованность женской аудитории в услугах маникюрных салонов.

2. **Анализ по возрасту мужчин:**  
   Мужчин среди подписчиков намного меньше (475), что говорит о низком уровне заинтересованности мужчин в услугах маникюра. Гистограмма показала, что мужчины, если они есть, в основном относятся к возрастным категориям до 35 лет.

3. **Анализ по возрасту женщин:**  
   Женщины, как основная аудитория, распределяются по различным возрастным группам. Это демонстрирует разнообразие возрастных предпочтений в салонах красоты и маникюра. Гистограмма показала, что большинство подписчиц моложе 40 лет.

4. **Анализ по географии (Москва/Не Москва):**  
   Большее количество подписчиков находится в Москве, однако и подписчики из других регионов тоже составляют значительную часть аудитории. Это может быть полезно для рекламных кампаний, направленных на привлечение пользователей из разных городов.

5. **Фильтрация женщин для интервью:**  
   Были отобраны женщины, для проведения с ними качественного интервью. С помощью датасетов получилось отобрать идеальных представителей целевой аудитории.
   
**Общий вывод:**  
Большинство подписчиков - женщины в возрасте до 35 лет, преимущественно из Москвы. Мужчины составляют лишь небольшую часть подписчиков, что подтверждает, что маникюрные салоны и услуги маникюра ориентированы в первую очередь на женскую аудиторию.
