# Технический радар "Будущее 2.0"

| Категория                  | Технология/Методология          | Статус | Обоснование                                    |
|----------------------------|---------------------------------|--------|------------------------------------------------|
| **Платформы данных**       | Data Lake (S3/MinIO)            | Adopt  | Необходимо для хранения больших объемов данных |
|                            | Modern DWH (Snowflake/BigQuery) | Adopt  | Замена устаревшего SQL Server 2008             |
|                            | Apache Kafka/Pulsar             | Adopt  | Потоковая обработка данных в реальном времени  |
|                            | Apache Airflow/Dagster          | Adopt  | Оркестрация ETL процессов                      |
| **API и интеграции**       | API Gateway (Kong/Nginx)        | Adopt  | Единая точка входа для всех API                |
|                            | RESTful APIs                    | Adopt  | Стандартизация интерфейсов                     |
|                            | Event-driven architecture       | Trial  | Асинхронная обработка между доменами           |
|                            | GraphQL                         | Trial  | Гибкие запросы для аналитики                   |
| **Инфраструктура**         | Kubernetes                      | Adopt  | Контейнеризация и оркестрация                  |
|                            | Docker                          | Adopt  | Упаковка приложений                            |
|                            | Infrastructure as Code          | Trial  | Автоматизация развертывания                    |
|                            | Service Mesh (Istio)            | Trial  | Управление микросервисами                      |
| **Разработка**             | Microservices                   | Adopt  | Доменная архитектура                           |
|                            | Domain-driven design            | Adopt  | Методология разделения на домены               |
|                            | CI/CD                           | Adopt  | Автоматизация развертывания                    |
|                            | Test automation                 | Trial  | Повышение качества                             |
| **Аналитика и BI**         | Self-service BI                 | Adopt  | Витрина данных для пользователей               |
|                            | Real-time analytics             | Trial  | Аналитика в реальном времени                   |
|                            | Machine Learning Platform       | Trial  | Развитие ИИ-сервисов                           |
| **Языки программирования** | Python                          | Adopt  | ИИ, аналитика, ETL                             |
|                            | Golang                          | Adopt  | Микросервисы, высокая производительность       |
|                            | Java                            | Adopt  | Корпоративные приложения                       |
|                            | SQL                             | Adopt  | Работа с данными                               |
| **Устаревшие технологии**  | SQL Server 2008                 | Hold   | Постепенная миграция                           |
|                            | Power Builder                   | Hold   | Замена на современные интерфейсы               |
|                            | Apache Camel (текущая версия)   | Hold   | Замена на современную платформу интеграций     |
|                            | Monolithic DWH                  | Hold   | Разделение на домены                           |