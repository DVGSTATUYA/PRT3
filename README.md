# PRT3

Администрирование и оптимизация БД учета товаров

Порядок запуска (в pgAdmin):
1. 01_create_database.sql    - Создание БД
2. 02_create_tables.sql       - Создание таблиц
3. 03_create_indexes.sql      - Создание индексов
4. 04_create_views.sql        - Создание представлений
5. 05_create_procedures_triggers.sql - Процедуры и триггеры
6. 06_insert_test_data.sql    - Заполнение тестовыми данными
7. 07_create_roles_permissions.sql - Роли и права

Тестирование:
- Запустите 08_analysis_queries.sql для анализа производительности
- Запустите 09_optimized_queries.sql для сравнения с оптимизированными запросами

Резервное копирование:
- Запустите backup_restore_scripts\backup.bat

Восстановление:
- Запустите backup_restore_scripts\restore.bat

