# Educational-stats

Education stats - онлайн-сервис для получения статистики успеваемости студентов.

Стек технологий: Python, FastAPI, PostgreSQL, React.js

Функционал API:
 - GET /students: Получить список всех студентов.
 - GET /students/{student_id}: Получить информацию о конкретном студенте.
 - POST /students: Добавить нового студента.
 - PUT /students/{student_id}: Обновить информацию о студенте.
 - DELETE /students/{student_id}: Удалить студента.



Задачи и сроки реализации:
 - Сбор и анализ информации. (1 неделя) (✓)
 - Разработка базы данных для хранения информации о студентах, их оценках и предметах. (3 недели) (Processing)
 - Написание API для взаимодействия с базой данных и вычисления рейтинга успеваемости. (4 недели) (X)
 - Создание интерфейса для ввода данных и просмотра отчетности. (3 недели) (X) 
 - Тестирование. (2 неделя) (X)


Правила работы в репозитории:
- не изменять ветку main, во избежание путаницы с работающей версией проекта
- подробно расписывать commit'ы чтобы сразу было понятно что было изменено в проекте

Для управления репозиторием в рамках проекта была выбрана стратегия GitHub Flow. Этот выбор обусловлен простотой и понятностью модели работы с репозиторием на GitHub. При использовании данной стратегии существует только одна основная ветка проекта (обычно называемая "main") и вспомогательные ветки, в которых я могу разрабатывать различные модули и функциональность, а затем интегрировать изменения с помощью pull request'ов. 
