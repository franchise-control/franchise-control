# Franchise Control

Платформа управления франчайзинговой сетью. Реестр точек и договоров, расчёт
роялти по восьми схемам, сбор отчётов о выручке от франчайзи, документы из 1С и
ЭДО, проверки качества точек по чек-листам.

Здесь мы выкладываем то, что вынесли из платформы и что полезно само по себе, —
под MIT, без оговорок и без регистрации.

## Открытые библиотеки

| Пакет | О чём |
| --- | --- |
| [royalty-calc](https://github.com/franchise-control/royalty-calc) | Расчёт роялти: восемь схем из договоров коммерческой концессии, точная арифметика на целых копейках и точных дробях, объяснение расчёта построчно |
| [revenue-report](https://github.com/franchise-control/revenue-report) | Отчёт франчайзи о выручке: разбор периода и денежных сумм в том виде, в котором их присылают, проверка со списком всех ошибок сразу, разбор CSV-выгрузки |

Обе — TypeScript, строгий режим, без зависимостей, покрытие выше 98 %, CI на
Node 18, 20 и 22. Стыкуются друг с другом одной строкой: `revenue-report`
приводит присланное к пригодному виду, `royalty-calc` по нему считает.

Обе лежат и на российской площадке — [GitVerse](https://gitverse.ru/franchise-control):
[royalty-calc](https://gitverse.ru/franchise-control/royalty-calc),
[revenue-report](https://gitverse.ru/franchise-control/revenue-report). Код
тот же, вплоть до хеша коммита. Домен github.com в России не заблокирован, но
доступность к нему плавает, и зеркало решает это без VPN.

## Почему мы это открываем

Расчёт роялти — не конкурентное преимущество. Преимущество в том, что вокруг
него: кабинет франчайзи, документооборот, проверки, сроки. А вот на арифметике
ошибаются все, и ошибка вылезает в акте, который подписывают две стороны.
Библиотека, которую читают и проверяют посторонние, ошибается реже закрытой.

Если вы нашли схему расчёта, которой у нас нет, или формат выгрузки, который мы
не поняли, — заводите issue с примером. Живой случай из чужой практики полезнее
звезды.

## Полезное без оплаты

- [Калькулятор роялти](https://franchise-control.pro/calculator) — восемь схем
  в браузере, без регистрации
- [Чек-лист проверки договора коммерческой
  концессии](https://franchise-control.pro/materialy/chek-list-dogovora) — PDF
- [Регламент сбора отчётов о
  выручке](https://franchise-control.pro/materialy/reglament-otchyotov) — PDF
- [Восемь схем роялти: формулы, примеры, подводные
  камни](https://franchise-control.pro/materialy/kalkulyator-royalti) — PDF
- [Блог](https://franchise-control.pro/blog) — практика управления сетью,
  договор концессии, сбор отчётов

## О платформе

- [Управление франшизами](https://franchise-control.pro/upravlenie-franshizoy)
- [Платформа контроля франшиз](https://franchise-control.pro/kontrol-franshiz)
- [Учёт и расчёт роялти](https://franchise-control.pro/uchyot-royalti)
- [О продукте](https://franchise-control.pro/o-produkte) — кто делает, из чего
  состоит и чего платформа намеренно не делает

## Связь

[franchise-control.pro](https://franchise-control.pro) ·
[info@franchise-control.pro](mailto:info@franchise-control.pro) ·
[телеграм](https://t.me/franchisecontrol) ·
[контакты и реквизиты](https://franchise-control.pro/kontakty)

Разработчик платформы — ООО «МИР ПРОДАЖ», ИНН 4802015048.
