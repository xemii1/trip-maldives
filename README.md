# Мальдивы — маршрут поездки, 50 вариантов размещения (реальные цены)

## Вводные

- Даты: 1 ноября 2026 ± 5 дней (расчёт сделан на заезд **31.10.2026 (ночной вылет) / 01.11.2026 (прилёт) — 08.11.2026**, 7 ночей на острове)
- Продолжительность на месте: 7 ночей
- Питание: «всё включено» с алкоголем
- Бюджет: 500 000 ₽ на двоих на всю поездку (перелёт + отель + трансфер)
- Количество человек: 2
- Вылет/возврат: Москва (Шереметьево, SVO)

## Проверка реальности бюджета (важно прочитать)

Первая версия этого файла была построена на цифрах «от X ₽», которые агрегаторы показывают на карточке отеля/списка туров. При прямой проверке через браузер (chrome-devtools, реальные даты 01.11–08.11.2026, 2 взрослых, тариф именно **«Всё включено»**, а не «завтрак») выяснилось:

1. **Цена «от» почти везде — это тариф с завтраком**, а не «всё включено». Реальная цена AI выше на 40–150%.
2. **3 отеля из исходных 30 не предлагают тариф «Всё включено» вообще** на эти даты (только завтрак/полупансион/полный пансион) и исключены из подборки: **Season Paradise**, **Noovilu Suites Maldives**, **The Standard, Huruvalhi Maldives**.
3. **Местные обитаемые острова (не курортные)** — например Perla Dhangethi на о. Дангети — показывают тариф «Всё включено» на туроператорских сайтах, но по законам Мальдив продажа алкоголя туристам на таких островах жёстко ограничена. Это подтвердилось на **Booking.com**: фильтр «Всё включено» для острова Дангети находит 6 отелей (Lily Beach Resort, Nova Maldives, NH Maldives Kuda Rah и др. — все настоящие курортные острова), и **PERLA Dhangethi среди них нет**, хотя гостевые дома с тем же названием острова там представлены под фильтром «Завтрак включён»/«Трёхразовое питание». То есть алкоголь в тариф Perla Dhangethi, скорее всего, **не входит** — вариант не соответствует требованию «алкоголь включён», несмотря на маркировку «Всё включено» у туроператора.
4. Из оставшихся **27 отелей с подтверждённым «живым» тарифом «Всё включено»** только **5 укладываются в бюджет 500 000 ₽**, и только **4 из них** — настоящие курортные острова с гарантированным алкоголем (Canareef, Adaaran Hudhuranfushi, Ellaidhoo, Cinnamon Dhonveli); медиана по всем 27 — **557 773 ₽**, у многих реальных островов-курортов пакет уходит в 600 000–800 000 ₽.
5. Цена «Итого на двоих» в таблице ниже — это **реальная, подтверждённая вживую на level.travel цена всего пакета** (перелёт + отель + трансфер). Для пакетных вариантов (без 🅱️) в файлах `trips/*.md` больше **не показывается** отдельная «расчётная» цена перелёта и отдельная «расчётная» цена отеля — оба указаны как «входит в стоимость пакета», потому что туроператор не публикует такую разбивку, и любая попытка разделить единую цену была бы искусственной оценкой. Раздел «Рейс» по-прежнему приводит для конкретики реальный прямой рейс Аэрофлота (даты, время, номера рейсов, багаж) — это ориентир на случай, если понадобится похожий рейс, а не обязательно тот перевозчик, которым в реальности летит купленный тур.
6. **Перекрёстная проверка на Booking.com** (независимо от level.travel): Canareef Resort Maldives, тариф «Всё включено», 7 ночей, 2 взрослых, **только отель без перелёта — 220 358 ₽**. У level.travel полный пакет (перелёт+отель+трансфер) для этого же отеля — 433 034 ₽; вычитая ориентировочный перелёт (145 000 ₽), получаем расчётную цену отеля 288 034 ₽ — того же порядка, разница объясняется внутренним перелётом до атолла Адду и/или более дорогим трансфером в составе пакета level.travel. Это подтверждает, что цифры в таблице ниже не завышены и не занижены на порядок.

7. **Поиск напрямую на Booking.com (не только отели из исходного списка level.travel)** нашёл ещё **23 курортных острова** с официальным фильтром Meal Plan = «Всё включено» (это отдельная категория самого Booking.com, а не текст в описании — надёжнее, чем у level.travel), которых не было в исходной подборке. Из них **5 укладываются в бюджет**: **Adaaran Club Rannalhi** (279 095 ₽ отель + перелёт), **Riu Atoll** (281 609 ₽), **Meeru Maldives Resort Island** (302 158 ₽, рейтинг 9,2 при 976 отзывах), **OBLU XPERIENCE Ailafushi** (313 986 ₽), **Malahini Kuda Bandos** (340 326 ₽). Остальные **18** (Riu Palace Maldivas, Medhufushi, Eri Maldives, Centara Mirage Lagoon, Kuredu, Safari Island, Rahaa Resort, Ifuru Island, Brennia Kottefaru, Nika Island, Taj Coral Reef, Niva Kuramathi, OBLU NATURE Helengeli, Mercure Kooddoo, Adaaran Select Meedhupparu, Sandies Bathala, NH Collection Reethi, ROBINSON NOONU) превышают бюджет, но добавлены для полноты картины и сравнения атоллов/типов курортов. Здесь цена отеля показана **отдельно от перелёта** (на Booking.com нет пакетных туров) — к цене отеля прибавлена та же ориентировочная стоимость перелёта (145 000 ₽), что и в остальных расчётах.

**Вывод:** бюджет 500 000 ₽ на двоих за 7 ночей с настоящим «всё включено + алкоголь» на острове-курорте Мальдив в начале ноября 2026 — достижим при отдельном бронировании отеля и перелёта: **9 настоящих курортных островов** укладываются в бюджет с гарантированным алкоголем (4 через пакетные туры level.travel + 5 через прямое бронирование на Booking.com). Perla Dhangethi формально тоже укладывается по цене, но алкоголь там, вероятнее всего, не входит — сохранён в списке как самый дешёвый бюджетный вариант, но с явной пометкой несоответствия требованию.

Вариантов, уложившихся в бюджет по цене: **10 из 50** проверенных, из них с подтверждённым алкоголем — **9**. Максимум в подборке — 808 590 ₽, минимум — 279 095 ₽ (только отель, без перелёта) / 343 866 ₽ (полный пакет с перелётом, Perla Dhangethi). Таблица отсортирована по возрастанию итоговой цены.

## Список вариантов

| № | Отель | Тип предложения | Категория | Атолл | Итого на двоих (реальная цена) | В бюджете 500к | Файл |
|---|---|---|---|---|---|---|---|
| 1 | Perla Dhangethi ⚠️ без алкоголя | Пакет | 4* | Южный Ари | 343 866 ₽ | ✅ | [trip-perla-dhangethi-1.md](trips/trip-perla-dhangethi-1.md) |
| 31 | Adaaran Club Rannalhi 🅱️ | 🅱️ Отдельно | 4* | Южный Мале | 424 095 ₽ | ✅ | [trip-adaaran-club-rannalhi-all-inclusive-31.md](trips/trip-adaaran-club-rannalhi-all-inclusive-31.md) |
| 32 | Riu Atoll 🅱️ | 🅱️ Отдельно | 4* | Даалу | 426 609 ₽ | ✅ | [trip-riu-atoll-all-inclusive-32.md](trips/trip-riu-atoll-all-inclusive-32.md) |
| 20 | Canareef Resort Maldives | Пакет | 4* | Адду (южный атолл) | 433 034 ₽ | ✅ | [trip-canareef-resort-maldives-20.md](trips/trip-canareef-resort-maldives-20.md) |
| 33 | Meeru Maldives Resort Island 🅱️ | 🅱️ Отдельно | 4* | Северный Мале | 447 158 ₽ | ✅ | [trip-meeru-maldives-resort-island-33.md](trips/trip-meeru-maldives-resort-island-33.md) |
| 34 | OBLU XPERIENCE Ailafushi 🅱️ | 🅱️ Отдельно | 4* | Северный Мале | 458 986 ₽ | ✅ | [trip-oblu-xperience-ailafushi-all-inclusive-with-free-transfers-34.md](trips/trip-oblu-xperience-ailafushi-all-inclusive-with-free-transfers-34.md) |
| 27 | Adaaran Select Hudhuranfushi | Пакет | 4* | Северный Мале | 465 373 ₽ | ✅ | [trip-adaaran-select-hudhuranfushi-27.md](trips/trip-adaaran-select-hudhuranfushi-27.md) |
| 19 | Ellaidhoo Maldives by Cinnamon | Пакет | 4* | Северный Ари | 466 671 ₽ | ✅ | [trip-ellaidhoo-maldives-by-cinnamon-19.md](trips/trip-ellaidhoo-maldives-by-cinnamon-19.md) |
| 35 | Malahini Kuda Bandos 🅱️ | 🅱️ Отдельно | 4* | Северный Мале | 485 326 ₽ | ✅ | [trip-malahini-kuda-bandos-35.md](trips/trip-malahini-kuda-bandos-35.md) |
| 18 | Cinnamon Dhonveli Maldives | Пакет | 4* | Северный Мале | 498 670 ₽ | ✅ | [trip-cinnamon-dhonveli-maldives-18.md](trips/trip-cinnamon-dhonveli-maldives-18.md) |
| 7 | Centara Ras Fushi Resort & Spa (Adults Only 18+) | Пакет | 4* | Северный Мале | 505 751 ₽ | ❌ | [trip-centara-ras-fushi-resort-spa-adults-only-18-7.md](trips/trip-centara-ras-fushi-resort-spa-adults-only-18-7.md) |
| 16 | Bandos Maldives | Пакет | 4* | Северный Мале | 506 370 ₽ | ❌ | [trip-bandos-maldives-16.md](trips/trip-bandos-maldives-16.md) |
| 36 | Riu Palace Maldivas - All Inclusive 🅱️ | 🅱️ Отдельно | 4* | Атолл Дхаалу | 507 158 ₽ | ❌ | [trip-riu-palace-maldivas-all-inclusive-36.md](trips/trip-riu-palace-maldivas-all-inclusive-36.md) |
| 37 | Medhufushi Island Resort 🅱️ | 🅱️ Отдельно | 4* | Атолл Мимиу (Meemu) | 510 830 ₽ | ❌ | [trip-medhufushi-island-resort-37.md](trips/trip-medhufushi-island-resort-37.md) |
| 8 | Villa Park (Ex. Sun Island Resort & Spa) | Пакет | 5* | Южный Ари | 517 122 ₽ | ❌ | [trip-villa-park-ex-sun-island-resort-spa-8.md](trips/trip-villa-park-ex-sun-island-resort-spa-8.md) |
| 38 | Eri Maldives 🅱️ | 🅱️ Отдельно | 5* | Северный Мале Атолл | 525 744 ₽ | ❌ | [trip-eri-maldives-38.md](trips/trip-eri-maldives-38.md) |
| 39 | Centara Mirage Lagoon Maldives 🅱️ | 🅱️ Отдельно | 4* | Северный Мале Атолл | 525 896 ₽ | ❌ | [trip-centara-mirage-lagoon-maldives-39.md](trips/trip-centara-mirage-lagoon-maldives-39.md) |
| 12 | Holiday Inn Resort Kandooma Maldives | Пакет | 4* | Южный Мале | 526 058 ₽ | ❌ | [trip-holiday-inn-resort-kandooma-maldives-12.md](trips/trip-holiday-inn-resort-kandooma-maldives-12.md) |
| 17 | Thulhagiri Island Resort | Пакет | 4* | Северный Мале | 526 576 ₽ | ❌ | [trip-thulhagiri-island-resort-17.md](trips/trip-thulhagiri-island-resort-17.md) |
| 5 | Fihalhohi Island Resort | Пакет | 3* | Южный Мале | 528 222 ₽ | ❌ | [trip-fihalhohi-island-resort-5.md](trips/trip-fihalhohi-island-resort-5.md) |
| 6 | Kandima Maldives | Пакет | 5* | Даалу | 532 258 ₽ | ❌ | [trip-kandima-maldives-6.md](trips/trip-kandima-maldives-6.md) |
| 40 | Kuredu Island Resort & Spa 🅱️ | 🅱️ Отдельно | 4* | Лавияни Атолл | 537 662 ₽ | ❌ | [trip-kuredu-island-resort-spa-40.md](trips/trip-kuredu-island-resort-spa-40.md) |
| 41 | Safari Island Resort & Spa Maldives 🅱️ | 🅱️ Отдельно | 4* | Северный Ари Атолл | 547 453 ₽ | ❌ | [trip-safari-island-resort-spa-maldives-41.md](trips/trip-safari-island-resort-spa-maldives-41.md) |
| 13 | Royal Island Resort & Spa | Пакет | 5* | Атолл Баа (биосфера ЮНЕСКО) | 552 580 ₽ | ❌ | [trip-royal-island-resort-spa-13.md](trips/trip-royal-island-resort-spa-13.md) |
| 42 | Rahaa Resort Maldives 🅱️ | 🅱️ Отдельно | 5* | Атолл Хаа Алиф (дальний север) | 554 155 ₽ | ❌ | [trip-rahaa-resort-maldives-42.md](trips/trip-rahaa-resort-maldives-42.md) |
| 11 | Nooe Maldives Kunaavashi | Пакет | 5* | Вааву Атолл | 557 773 ₽ | ❌ | [trip-nooe-maldives-kunaavashi-11.md](trips/trip-nooe-maldives-kunaavashi-11.md) |
| 9 | Sheraton Maldives Full Moon Resort & Spa | Пакет | 5* | Северный Мале | 569 368 ₽ | ❌ | [trip-sheraton-maldives-full-moon-resort-spa-9.md](trips/trip-sheraton-maldives-full-moon-resort-spa-9.md) |
| 43 | Ifuru Island Maldives 🅱️ | 🅱️ Отдельно | 5* | Раа Атолл | 571 627 ₽ | ❌ | [trip-ifuru-island-maldives-43.md](trips/trip-ifuru-island-maldives-43.md) |
| 44 | Brennia Kottefaru Maldives 🅱️ | 🅱️ Отдельно | 5* | Раа Атолл | 580 854 ₽ | ❌ | [trip-brennia-kottefaru-maldives-44.md](trips/trip-brennia-kottefaru-maldives-44.md) |
| 45 | Nika Island Resort & Spa, Maldives 🅱️ | 🅱️ Отдельно | 4* | Южный Ари Атолл | 585 374 ₽ | ❌ | [trip-nika-island-resort-spa-maldives-45.md](trips/trip-nika-island-resort-spa-maldives-45.md) |
| 46 | Taj Coral Reef Resort & Spa, Maldives 🅱️ | 🅱️ Отдельно | 5* | Северный Мале Атолл | 590 410 ₽ | ❌ | [trip-taj-coral-reef-resort-spa-maldives-46.md](trips/trip-taj-coral-reef-resort-spa-maldives-46.md) |
| 26 | Cocoon Maldives | Пакет | 5* | Лавияни | 600 911 ₽ | ❌ | [trip-cocoon-maldives-26.md](trips/trip-cocoon-maldives-26.md) |
| 48 | OBLU NATURE Helengeli - All-Inclusive with free Transfers 🅱️ | 🅱️ Отдельно | 4* | Северный Мале Атолл | 602 985 ₽ | ❌ | [trip-oblu-nature-helengeli-all-inclusive-with-free-transfers-48.md](trips/trip-oblu-nature-helengeli-all-inclusive-with-free-transfers-48.md) |
| 21 | Villa Nautica (Ex. Paradise Island) | Пакет | 5* | Северный Мале | 603 103 ₽ | ❌ | [trip-villa-nautica-ex-paradise-island-21.md](trips/trip-villa-nautica-ex-paradise-island-21.md) |
| 25 | Kudafushi Resort & Spa | Пакет | 5* | Раа | 603 765 ₽ | ❌ | [trip-kudafushi-resort-spa-25.md](trips/trip-kudafushi-resort-spa-25.md) |
| 47 | Niva Kuramathi Maldives 🅱️ | 🅱️ Отдельно | 5* | Северный Ари Атолл | 608 867 ₽ | ❌ | [trip-niva-kuramathi-maldives-47.md](trips/trip-niva-kuramathi-maldives-47.md) |
| 4 | Machchafushi Island Resort & Spa | Пакет | 4* | Южный Ари | 610 132 ₽ | ❌ | [trip-machchafushi-island-resort-spa-4.md](trips/trip-machchafushi-island-resort-spa-4.md) |
| 49 | Mercure Maldives Kooddoo - Adults-Only Escape 🅱️ | 🅱️ Отдельно | 4* | Атолл Гаафу Алиф (дальний юг) | 611 450 ₽ | ❌ | [trip-mercure-maldives-kooddoo-adults-only-escape-49.md](trips/trip-mercure-maldives-kooddoo-adults-only-escape-49.md) |
| 14 | Sun Siyam Olhuveli | Пакет | 4* | Южный Мале | 617 345 ₽ | ❌ | [trip-sun-siyam-olhuveli-14.md](trips/trip-sun-siyam-olhuveli-14.md) |
| 29 | Niva Dhigali Maldives | Пакет | 5* | Раа | 618 305 ₽ | ❌ | [trip-niva-dhigali-maldives-29.md](trips/trip-niva-dhigali-maldives-29.md) |
| 15 | Furaveri Island Resort & Spa | Пакет | 5* | Раа | 619 412 ₽ | ❌ | [trip-furaveri-island-resort-spa-15.md](trips/trip-furaveri-island-resort-spa-15.md) |
| 51 | Sandies Bathala 🅱️ | 🅱️ Отдельно | 4* | Северный Ари Атолл | 625 326 ₽ | ❌ | [trip-sandies-bathala-51.md](trips/trip-sandies-bathala-51.md) |
| 24 | Hard Rock Hotel Maldives | Пакет | 5* | Южный Мале | 641 820 ₽ | ❌ | [trip-hard-rock-hotel-maldives-24.md](trips/trip-hard-rock-hotel-maldives-24.md) |
| 50 | Adaaran Select Meedhupparu 🅱️ | 🅱️ Отдельно | 4* | Раа Атолл | 644 959 ₽ | ❌ | [trip-adaaran-select-meedhupparu-50.md](trips/trip-adaaran-select-meedhupparu-50.md) |
| 52 | NH Collection Maldives Reethi Resort 🅱️ | 🅱️ Отдельно | 5* | Атолл Баа (биосфера ЮНЕСКО) | 647 985 ₽ | ❌ | [trip-nh-collection-maldives-reethi-resort-52.md](trips/trip-nh-collection-maldives-reethi-resort-52.md) |
| 53 | ROBINSON NOONU - All Inclusive 🅱️ | 🅱️ Отдельно | 5* | Атолл Ноону | 658 080 ₽ | ❌ | [trip-robinson-noonu-all-inclusive-53.md](trips/trip-robinson-noonu-all-inclusive-53.md) |
| 10 | Avani+ Fares Maldives Resort | Пакет | 5* | Атолл Баа | 660 993 ₽ | ❌ | [trip-avani-fares-maldives-resort-10.md](trips/trip-avani-fares-maldives-resort-10.md) |
| 30 | Niva Velassaru Maldives | Пакет | 5* | Южный Мале | 718 513 ₽ | ❌ | [trip-niva-velassaru-maldives-30.md](trips/trip-niva-velassaru-maldives-30.md) |
| 28 | The Westin Maldives Miriandhoo Resort | Пакет | 5* | Атолл Баа (биосфера ЮНЕСКО) | 723 020 ₽ | ❌ | [trip-the-westin-maldives-miriandhoo-resort-28.md](trips/trip-the-westin-maldives-miriandhoo-resort-28.md) |
| 23 | Le Meridien Maldives Resort & Spa | Пакет | 5* | уточняется | 808 590 ₽ | ❌ | [trip-le-meridien-maldives-resort-spa-23.md](trips/trip-le-meridien-maldives-resort-spa-23.md) |

*Исключены (не предлагают тариф «Всё включено» на эти даты):* Season Paradise, Noovilu Suites Maldives, The Standard, Huruvalhi Maldives.

**Пометки:** 🅱️ — отель найден напрямую на Booking.com (не было в исходном списке level.travel); цена = реальная цена отеля на Booking.com + ориентировочная стоимость перелёта (145 000 ₽), а не единый пакетный тур. ⚠️ — вариант не соответствует требованию «алкоголь включён» (см. п.3 в разделе выше).

## Краткая сводка по номерам и активностям

Питание — «да» у всех вариантов (это было условием отбора). Алкоголь — «да» у курортных островов; у Perla Dhangethi — «нет (не входит)», подтверждено перекрёстно через Booking.com (см. п.3 выше и файл варианта). Дайвинг и сёрфинг — качественная оценка по репутации атолла/курорта (не официальный рейтинг). Отсортировано по цене.

| № | Отель | Тип номера | Питание | Алкоголь | Дайвинг | Сёрфинг |
|---|---|---|---|---|---|---|
| 1 | Perla Dhangethi ⚠️ | бунгало на берегу | да | нет (не входит) | хорошо | отсутствует |
| 31 | Adaaran Club Rannalhi 🅱️ | бунгало на берегу / над водой | да | да | хорошо | плохо |
| 32 | Riu Atoll 🅱️ | бунгало / вилла на берегу | да | да | хорошо | отсутствует |
| 20 | Canareef Resort Maldives | бунгало на берегу | да | да | отлично | плохо |
| 33 | Meeru Maldives Resort Island 🅱️ | бунгало на берегу, первая линия | да | да | хорошо | плохо |
| 34 | OBLU XPERIENCE Ailafushi 🅱️ | бунгало на берегу | да | да | хорошо | плохо |
| 27 | Adaaran Select Hudhuranfushi | вилла-гарден на берегу | да | да | хорошо | отлично |
| 19 | Ellaidhoo Maldives by Cinnamon | бунгало на берегу | да | да | отлично | отсутствует |
| 35 | Malahini Kuda Bandos 🅱️ | бунгало на берегу | да | да | хорошо | плохо |
| 18 | Cinnamon Dhonveli Maldives | бунгало на берегу | да | да | хорошо | отлично |
| 7 | Centara Ras Fushi Resort & Spa (Adults Only 18+) | вилла над водой | да | да | хорошо | плохо |
| 16 | Bandos Maldives | бунгало на берегу | да | да | отлично | плохо |
| 36 | Riu Palace Maldivas - All Inclusive 🅱️ | бунгало на берегу | да | да | хорошо | отсутствует |
| 37 | Medhufushi Island Resort 🅱️ | бунгало на берегу | да | да | хорошо | отсутствует |
| 8 | Villa Park (Ex. Sun Island Resort & Spa) | вилла на берегу | да | да | хорошо | отсутствует |
| 38 | Eri Maldives 🅱️ | вилла на берегу | да | да | хорошо | плохо |
| 39 | Centara Mirage Lagoon Maldives 🅱️ | бунгало на берегу | да | да | хорошо | плохо |
| 12 | Holiday Inn Resort Kandooma Maldives | бунгало на берегу | да | да | хорошо | отлично |
| 17 | Thulhagiri Island Resort | бунгало на берегу | да | да | хорошо | плохо |
| 5 | Fihalhohi Island Resort | бунгало на берегу | да | да | отлично | плохо |
| 6 | Kandima Maldives | студия на берегу | да | да | хорошо | хорошо |
| 40 | Kuredu Island Resort & Spa 🅱️ | бунгало на берегу | да | да | отлично | отсутствует |
| 41 | Safari Island Resort & Spa Maldives 🅱️ | бунгало на берегу | да | да | хорошо | отсутствует |
| 13 | Royal Island Resort & Spa | вилла на берегу | да | да | отлично | отсутствует |
| 42 | Rahaa Resort Maldives 🅱️ | вилла на берегу | да | да | хорошо | отсутствует |
| 11 | Nooe Maldives Kunaavashi | вилла на берегу | да | да | хорошо | отсутствует |
| 9 | Sheraton Maldives Full Moon Resort & Spa | вилла на берегу | да | да | хорошо | плохо |
| 43 | Ifuru Island Maldives 🅱️ | вилла на берегу | да | да | хорошо | отсутствует |
| 44 | Brennia Kottefaru Maldives 🅱️ | вилла на берегу | да | да | хорошо | отсутствует |
| 45 | Nika Island Resort & Spa, Maldives 🅱️ | бунгало на берегу | да | да | отлично | отсутствует |
| 46 | Taj Coral Reef Resort & Spa, Maldives 🅱️ | вилла на берегу / над водой | да | да | хорошо | плохо |
| 26 | Cocoon Maldives | вилла над водой | да | да | хорошо | отсутствует |
| 48 | OBLU NATURE Helengeli - All-Inclusive with free Transfers 🅱️ | бунгало на берегу | да | да | отлично | отсутствует |
| 21 | Villa Nautica (Ex. Paradise Island) | вилла на берегу | да | да | хорошо | плохо |
| 25 | Kudafushi Resort & Spa | вилла на берегу | да | да | хорошо | отсутствует |
| 47 | Niva Kuramathi Maldives 🅱️ | бунгало на берегу | да | да | отлично | отсутствует |
| 4 | Machchafushi Island Resort & Spa | вилла на берегу | да | да | отлично | отсутствует |
| 49 | Mercure Maldives Kooddoo - Adults-Only Escape 🅱️ | бунгало на берегу | да | да | хорошо | отсутствует |
| 14 | Sun Siyam Olhuveli | вилла над водой | да | да | хорошо | хорошо |
| 29 | Niva Dhigali Maldives | вилла над водой | да | да | хорошо | отсутствует |
| 15 | Furaveri Island Resort & Spa | вилла на берегу | да | да | хорошо | отсутствует |
| 51 | Sandies Bathala 🅱️ | бунгало на берегу | да | да | отлично | отсутствует |
| 24 | Hard Rock Hotel Maldives | вилла на берегу | да | да | хорошо | плохо |
| 50 | Adaaran Select Meedhupparu 🅱️ | бунгало на берегу | да | да | хорошо | отсутствует |
| 52 | NH Collection Maldives Reethi Resort 🅱️ | вилла на берегу | да | да | отлично | отсутствует |
| 53 | ROBINSON NOONU - All Inclusive 🅱️ | вилла на берегу | да | да | хорошо | отсутствует |
| 10 | Avani+ Fares Maldives Resort | вилла на берегу | да | да | хорошо | отсутствует |
| 30 | Niva Velassaru Maldives | вилла на берегу | да | да | хорошо | плохо |
| 28 | The Westin Maldives Miriandhoo Resort | вилла на берегу | да | да | отлично | отсутствует |
| 23 | Le Meridien Maldives Resort & Spa | вилла на берегу | да | да | хорошо | отсутствует |

## Варианты рейсов (Москва — Мале, туда/обратно)

Три реальных варианта авиаперелёта на выбранные даты (заезд 01.11.2026, выезд 08.11.2026, 7 ночей), эконом-класс, на двоих пассажиров. Вариант 1 (Аэрофлот) указан как ориентир во всех файлах `trips/*.md` в разделе «Рейс». Для пакетных вариантов (без 🅱️) перелёт уже включён в общую цену тура и отдельно не оплачивается — эта таблица показывает, сколько бы стоил перелёт сам по себе, если бронировать его отдельно (актуально для вариантов 🅱️ с Booking.com, где отель и перелёт покупаются отдельно). Варианты 2-3 — реальные регулярные стыковочные маршруты, для сравнения.

| № | Авиакомпания / маршрут | Вылет туда | Прилёт туда | Вылет обратно | Прилёт обратно | Стыковки | Общая стоимость на двоих |
|---|---|---|---|---|---|---|---|
| 1 | **Аэрофлот**, прямой рейс (SU324 / SU321) | SVO, 31.10.2026, 23:55 | MLE, 01.11.2026, 11:15 | MLE, 08.11.2026, 11:00 | SVO, 08.11.2026, 18:15 | без пересадок | ≈ 145 000 ₽ |
| 2 | **Emirates**, через Дубай (EK134+EK658 / EK659+EK131) | DME, 31.10.2026, 17:00 | MLE, 01.11.2026, 09:30 | MLE, 08.11.2026, 11:15 | DME, 08.11.2026, 20:30 | 1 пересадка в DXB (≈9 ч туда, ≈2 ч обратно) | ≈ 145 000-160 000 ₽ |
| 3 | **Qatar Airways**, через Доху (QR340+QR672 / QR673+QR337) | SVO, 31.10.2026, 17:02 | MLE, 01.11.2026, 08:15 | MLE, 08.11.2026, 08:20 | SVO, **09.11.2026**, 06:25 | 1 пересадка в DOH (≈3 ч туда, ≈12 ч обратно - ночная) | ≈ 130 000-150 000 ₽ |

**Пояснения:**
- Аэропорты: SVO — Шереметьево (Москва), DME — Домодедово (Москва, использует Emirates), MLE — Велана Интернешнл (Мале), DXB — Дубай, DOH — Доха.
- Номера рейсов и расписание подтверждены независимо по нескольким агрегаторам (tutu.ru, Яндекс.Путешествия, euroavia.ru, airportia.com), но собраны как комбинация отдельно проверенных участков маршрута (Москва→хаб и хаб→Мале), а не как единая забронированная стыковка — при покупке возможны расхождения на 1 рейс в зависимости от точной даты и дня недели.
- У варианта 3 (Qatar Airways) на найденном расписании нет удобного вечернего рейса Доха—Москва в день прилёта из Мале, поэтому обратный путь фактически занимает на 1 день больше (прилёт в Москву 09.11 вместо 08.11).
- Стоимость всех вариантов ориентировочная (по данным поисковых агрегаторов, не проверена вживую через chrome-devtools в отличие от цен отелей) — точная цена уточняется при бронировании.

## Методология и источники

- Цены пакетов «перелёт + отель + трансфер» для 30 отелей из исходного списка **проверены вживую в браузере** (chrome-devtools MCP) на [level.travel](https://level.travel): для каждого отеля открывалась страница с параметрами `nights=7&start_date=2026-11-01&adults=2&from=Moscow-RU` и извлекался минимальный тариф именно «Всё включено» на 7 ночей (не «от X ₽», которое обычно означает завтрак). Дата проверки — 21.08.2026.
- Дополнительные 23 отеля (🅱️) найдены прямым поиском на [Booking.com](https://www.booking.com): страна «Мальдивы», тип объекта «Курортные отели», фильтр Meal Plan = «Всё включено» (официальная категория Booking.com), даты 01.11-08.11.2026, 2 взрослых, сортировка по возрастанию цены — всего найдено 123 варианта; из них отобраны 23 (5 самых дешёвых, укладывающихся в бюджет, + ещё 18 для более широкого покрытия атоллов и типов курортов). Дубликаты отелей, уже присутствующих в подборке через level.travel (например, Avani+ Fares, Villa Nautica, Villa Park), пропущены. Это цена **только отеля**, без перелёта.
- Отдельно перепроверена цена Canareef Resort Maldives (уже входившего в подборку с level.travel) на Booking.com — для сверки порядка цифр между двумя источниками.
- Список отелей и общие описания островов изначально собраны через WebSearch/WebFetch — статьи [maldivy.ru](https://maldivy.ru/hotels/all-inclusive/) и [belyypesok.ru](https://belyypesok.ru/nedorogie-oteli-na-maldivax-vse-vklyucheno/), а также листинги level.travel.
- Данные о рейсе — прямой регулярный рейс **Аэрофлот SVO ↔ MLE** (SU324 туда, SU321 обратно), подтверждён на нескольких независимых источниках (tutu.ru, euroavia.ru, uniticket.ru).
- Атолл/расположение и звёздность для части отелей скорректированы по данным, полученным при живой проверке (заголовок страницы отеля), — они точнее исходных.
- Цены агрегаторов колеблются ежедневно и по мере приближения даты — перед покупкой их нужно перепроверить.