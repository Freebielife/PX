# Not Pixel Observatory

## О проекте / токене

Not Pixel in-game utility token.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-25):

- <https://tonapi.io/v2/jettons/EQB420yQsZobGcy0VYDfSKHpG2QQlw-j1f_tPu1J488I__PX>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Первичный снимок собран по данным TonAPI и GeckoTerminal 25 ноября 2026 года. История обменов загружается постепенно; её полнота отражается в статусах разделов.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
GitHub Actions настроен на обновление каждые 30 минут (17 и 47 минут каждого часа UTC). Фактический плановый запуск ещё не подтверждён.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Подключение к общему Cloudflare-планировщику не выполнено: действующий реестр и права доступа не подтверждены. Публикация в TON Storage выполняется отдельно. Секретов в HTML нет.

## Оформление

Логотип: https://static.notpx.app/px_logo.png (метаданные данного контракта).
Флаг: TONecoFlags №038, выбран пользователем.
Канал проекта: https://t.me/notpixel_channel (ссылка из метаданных контракта).

## Покрытие данных

Лента проверяет прямые обмены PX/TON на STON.fi и DeDust. Остальные найденные пары показаны в пулах; их сделки не включаются в ленту. Подтверждённые источники заморозки и стейкинга не настроены.
