# Миграции FanRuan в SiglaVision

Независимая коллекция примеров переноса отчётов из галереи FanRuan в SiglaVision. Здесь можно будет скачать пакет для ручного импорта и сравнить внешний вид исходного отчёта и перенесённой версии.

## Каталог отчётов

В таблице указана последняя версия пакета для каждого отчёта. История версий доступна на странице [Releases](https://github.com/korvin-studio-public/sigla-gallery-migrations/releases).

| Отчёт | Оригинал | Версия пакета | Версия SiglaVision | ZIP | PDF оригинала | PDF в Sigla | Статус |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Manufacturing Supply Chain Dashboard | [FineBI Gallery](https://gallery.fanruan.com/manufacturing-supply-chain-executive-dashboard) | 0.2.12 | 2.0.7 | [ZIP](https://github.com/korvin-studio-public/sigla-gallery-migrations/releases/download/manufacturing-supply-chain-v0.2.12/manufacturing-supply-chain-v0.2.12.zip) | - | [PDF](https://github.com/korvin-studio-public/sigla-gallery-migrations/releases/download/manufacturing-supply-chain-v0.2.12/sigla-result.pdf) | Подготовлен |

Для каждой версии отчёта предусмотрен отдельный релиз с нативным ZIP. PDF показывают внешний вид оригинала и результата в SiglaVision. Они публикуются при наличии и могут появиться позже.

## Как импортировать отчёт

1. Откройте релиз нужной версии отчёта.
2. Прочитайте инструкцию, требования к зависимостям и результаты проверок. В описании релиза также будут указаны версия SiglaVision, условия совместимости пакета, его SHA-256 и список изменений.
3. Скачайте нативный ZIP из раздела Assets и импортируйте его вручную в SiglaVision по инструкции. Для импорта используйте только этот ZIP. Архив GitHub `Source code (zip)` содержит файлы репозитория.

## Статусы пакетов

- **Подготовлен** - ZIP готов к ручному импорту, подтверждение импорта ещё ожидается.
- **Проверен после импорта** - импортировали конкретный ZIP и проверили данные, расчёты, взаимодействия, сохранение и повторное открытие отчёта. Подробности приведены в релизе.
