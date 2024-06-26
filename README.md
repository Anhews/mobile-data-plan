# Mobile-data-plan
Рекомендация тарифов

**Цель:** построение системы, способной проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра» (для оператора мобильной связи) 

**Описание данных:** данные о поведении клиентов, которые уже перешли на тарифы «Смарт» или «Ультра» (из проекта курса «Статистический анализ данных»). 

Известно (информация о поведении одного пользователя за месяц):
- `сalls` — количество звонков,
- `minutes` — суммарная длительность звонков в минутах,
- `messages` — количество sms-сообщений,
- `mb_used` — израсходованный интернет-трафик в Мб,
- `is_ultra` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

**Этапы:**
- Изучение данных файла. 
- Разделение исходных данных на обучающую, валидационную и тестовую выборки.
- Исследование качества разных моделей, меняя гиперпараметры.
- Проверка качества модели на тестовой выборке.
- Проверка модели на вменяемость.
