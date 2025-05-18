# Задание 3

## Roadmap

[Roadmap](./Roadmap.png)

## Технический радар «Будущее 2.0»

| Квадрант   | Технологии и методологии                                                                                                                              |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Adopt**  | • Apache Kafka (EventBus)<br>• Delta Lake (Lakehouse)<br>• DBT / Spark (CDC-пайплайны)<br>• Kubernetes (контейнеризация)<br>• Agile / DevOps          |
| **Trial**  | • Dremio / AtScale (семантический слой)<br>• GraphQL API<br>• React / Vue (портал)<br>• Data Catalog (краткое тестирование)<br>• Domain-Driven Design |
| **Assess** | • Apache Pulsar (альтернатива Kafka)<br>• Apache Iceberg (альтернатива Delta Lake)<br>• Great Expectations (качество данных)<br>• MLOps-платформы     |
| **Hold**   | • PowerBuilder (frontend-legacy)<br>• SQL Server 2008 (монолитный DWH)<br>• Apache Camel (старый ESB)<br>• Waterfall (классический СКС)               |

### Обоснование

1. **Adopt**

   - Kafka и Delta Lake уже доказали эффективность для реального времени и масштабируемого хранения.<br>
   - DBT/Spark позволяют управлять CDC-конвейерами декларативно.<br>
   - Kubernetes обеспечит гибкое масштабирование.<br>
   - Agile/DevOps ускорят delivery.

2. **Trial**

   - Семантические движки (Dremio, AtScale) нужны для единой модели данных — тестируем в одном домене.<br>
   - GraphQL и современный frontend дадут гибкость портала.<br>
   - Data Catalog помогут автоматизировать поиск метаданных.<br>
   - DDD упорядочит границы доменов.

3. **Assess**

   - Pulsar и Iceberg могут дать дополнительные возможности, но на данный момент стоит оценить риски.<br>
   - Great Expectations и MLOps пригодятся для повышения качества и управления AI-pipeline.

4. **Hold**
   - Legacy-технологии (PowerBuilder, SQL 2008, Camel) сохраняются только до полного перехода.<br>
   - Waterfall не подходит под быстро меняющиеся условия — переходим на гибкие методологии.
