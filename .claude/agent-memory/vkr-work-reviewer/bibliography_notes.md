---
name: Список литературы ВКР — состав и пометки
description: Номера источников, их содержание и пометки о добавлении новых источников
metadata:
  type: project
---

Файл: bibliography.md (47 источников по состоянию на 30.05.2026 после переработки §1.3 — удалены 4 нерелевантных, добавлены 8 новых).

## Раздел II. Книги и научные статьи (источники 1–10)

1. Егиазарян М.С. — Анализ существующих приложений по ведению семейного бюджета (КиберЛенинка, 2020). §1.1.
2. Gavrila L. — алгоритм клиринга финансовых обязательств (arXiv, 2020). §1.1, §1.6, введение.
3. Girdhar G. — Design and Development of Expense App (IEEE, 2024). Введение, §1.1.
4. Kleppmann M. — Designing Data-Intensive Applications (O'Reilly, 2017). §1.4, §1.5.
5. Martin R.C. — Clean Architecture (Prentice Hall, 2017). §1.4, введение.
6. Pătcaş C. — The Debts' Clearing Problem (arXiv, 2011). §1.1, §1.6, введение.
7. Rahmatulloh A. — Event-Driven Architecture (IEEE, 2022). §1.3, §1.4, §1.5.
8. Tezuysal A. — Database Design with PostgreSQL and MySQL (Packt, 2024). §1.3, §1.5.
9. Tragura S.J.C. — Building Python Microservices with FastAPI (Packt, 2022). §1.3.3.
10. Yurochkin D.E. — Development of an Application for Expense Accounting (IEEE, 2021). НЕ ИСПОЛЬЗУЕТСЯ в главах 1.x (резерв для глав 2/3).

## Раздел III. Интернет-источники (источники 11–29)

11. Docker Documentation — §1.3, §1.4, введение.
12. FastAPI Documentation — §1.3, §1.5.
13. Mohan K.M. — Algorithm Behind Splitwise's Debt Simplification (Medium) — §1.2, §1.6. Medium-источник.
14. React Documentation — §1.3.
15. PostgreSQL 16 Documentation — §1.3, §1.5.
16. RabbitMQ Documentation — §1.3, §1.4.
17. Splitwise — §1.1, §1.2, введение.
18. Tricount — §1.2, введение.
19. Splid — §1.2.
20. Дзен-мани — §1.2.
21. CoinKeeper — §1.2.
22. Nginx Documentation — §1.3, §1.4.
23. Alembic Documentation — §1.3, §1.5.
24. Zustand Documentation — §1.3.
25. SQLAlchemy Documentation — §1.3, §1.5.
26. OpenAPI Specification — §1.3, §1.5.
27. РБК/ДомРФ — аренда жилья — §1.1, введение.
28. НАФИ — семейный отдых молодёжи — §1.1, введение.
29. НАФИ — мобильные приложения россиян — §1.1, введение.

## Раздел IV. Книги и стандарты (30–47)

30. Newman S. — Building Microservices (O'Reilly, 2021). §1.3.3 (через композитную ссылку [7, 30]).
31. IETF Idempotency-Key Internet-Draft — §1.5.4.
32. RFC 7519 JWT — §1.4.2, §1.5.
33. OWASP Password Storage Cheat Sheet — §1.5, Argon2.
34. React Router Documentation — §1.3.
35. TanStack Query Documentation — §1.3.
36. Vite Documentation — §1.3.
37. Settle Up (Step Up Labs) — §1.2.
38. Т-Банк — функция «Разделить» — §1.2.
39. Сбербанк/Рамблер — совместный сбор — §1.2.
40. Splitwise Engineering Blog — §1.3.1 (Ruby on Rails, cacheable).
41. Splitwise GitHub (open-source repos) — §1.3.1 (super_diff, RSpec).
42. Prospeo / Splitwise Technology Stack — §1.3.1 (фронт-стек, AWS — частичное подтверждение).
43. Vávra D. — mdevCoinExchange Medium — §1.3.1 (Angular + Firebase шаблон той же команды).
44. Procházka F. — FCM Medium — §1.3.1 (Settle Up + web-push через FCM).
45. egregors/zenmoney-backup GitHub — §1.3.2 (Дзен-мани REST API, OAuth, JSON-экспорт).
46. Sviridov A. — личный блог mrlokans.work — §1.3.2 (API-импорт vs SMS-парсинг для Дзен-мани).
47. mk-manishkumar/coinkeeper GitHub — §1.3.2, §1.3.3 (open-source expense tracker, React+TS+Express).

## Изменения за переработку §1.3 (30.05.2026)

- УДАЛЕНЫ 4 нерелевантных источника старого §1.3: Django docs, Express docs (как docs), Vue docs, Apache Kafka docs.
- ДОБАВЛЕНЫ 8 источников (40–47) для архитектурного анализа аналогов.
- Перенумерация 29→25, 30→26, ..., 43→39 для смещения номеров после удаления.
- ИТОГО: 47 источников.

## Открытые методические замечания

- [10] Yurochkin не используется в главах 1.x. Решение: оставить как резерв для глав 2/3.
- [13] Mohan (Medium), [43] Vávra (Medium), [44] Procházka (Medium), [46] Sviridov (личный блог) — категория источников «отраслевые публикации», приемлемость для академической ВКР рекомендуется уточнить у руководителя.
- [42] Prospeo — справочный агрегатор стека; URL подтверждает Redux/Bootstrap/Ruby, но НЕ подтверждает React и AWS в открыто доступной части страницы. Может потребоваться дополнительное подтверждение.
- [43] Vávra — статья про mdevCoinExchange (не про Settle Up), используется как косвенное подтверждение шаблона Angular+Firebase для той же команды (Step Up Labs).

**Why:** Список литературы — единственный источник истины для ссылок [N] в тексте.
**How to apply:** Перед проверкой любого раздела — свериться с актуальным bibliography.md. При работе над Главами 2/3 — добавлять источники для pytest, Hypothesis, Locust, certbot.
