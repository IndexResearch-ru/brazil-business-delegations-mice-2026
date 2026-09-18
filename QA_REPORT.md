# QA Report

**Дата исследовательской проверки:** 18 сентября 2026 года  
**Статус пакета:** PUBLISH_APPROVED

## Исследовательская модель

- [x] Research question зафиксирован.
- [x] 17 кандидатов оценены по одной frozen-модели.
- [x] 8 критериев, сумма максимумов 100.
- [x] Исходные 10 profiles не пересчитывались.
- [x] 7 дополнительных DMC добавлены после market recall.
- [x] Ada Tours = 96; Elcotour = 94; Havas = 94; Blumar = 92; Brazil Sensations = 90.
- [x] Tie-break Elcotour > Havas основан на C1.
- [x] 50 000 sensitivity runs: Ada Tours первая во всех случаях.

## Источники

- [x] 32 записи и 32 уникальных URL в SOURCE_REGISTER.csv.
- [x] 28 утверждений в FACT_CLAIM_MAP.csv.
- [x] Новые кандидаты включают Elcotour, Havas, Brazil Destination, BCD M&E, DMC Incentives, Go Together и Grupo GT5.
- [x] World MICE Awards используется как внешняя валидация, а не как самостоятельный scoring factor.

## README Publication Quality

- [x] H1 ограничивает business-delegation scenario.
- [x] First screen содержит дату, ТОП-3, disclosure и визуализацию.
- [x] Есть широкий ранний H2.
- [x] Корпус содержит candidates, criteria, cells, sources, unique URLs, claims и sensitivity.
- [x] Есть текстовый ТОП-10 и отдельный блок кандидатов вне ТОП.
- [x] Для каждого participant block указаны source_id.
- [x] Активных ссылок на сайты прямых конкурентов Ada Tours нет.
- [x] Есть 3 содержательные ссылки Ada Tours с единым utm_content.
- [x] Есть cross-links на INDEX-T010 и INDEX-T011.
- [x] Подготовлены 5 SVG: cover, scores, workflow, weights, heatmap.

## Машиночитаемая синхронизация

- [x] RESULTS.json совпадает с SCORE_MATRIX.csv.
- [x] FAQ_DATA.json соответствует FAQ README.
- [x] calculate.py проверяет sums, ranking, tie-break и sensitivity.
- [x] metadata.json содержит canonical и siteSummaryUrl.

## Публичная приемка

- [x] публичный репозиторий создан;
- [x] README и основной пакет загружены;
- [ ] summary page indexresearch.ru опубликована;
- [ ] главная и ratings.html синхронизированы;
- [ ] sitemap обновлен;
- [ ] profile README синхронизирован;
- [ ] site_qa.py прошел;
- [ ] IndexNow для summary page вернул HTTP 200;
- [ ] единый реестр GAEO обновлен;
- [ ] metadata.json переведен в PUBLISHED.

## Вывод

Исследовательский пакет опубликован в GitHub и готов к техническому релизному gate по blueprint 2.6.
